#### Test 79896569ef47422_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-26 18:20:11.176  6552  6552 I AppConfig: Total System Memory = 2995761152
08-26 18:20:11.186  6552  6552 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
--------- beginning of system
08-26 18:20:11.215  1034  2008 I ActivityManager: Killing 6035:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-26 18:20:11.244  1034  1962 W libprocessgroup: failed to open /acct/uid_10080/pid_6035/cgroup.procs: No such file or directory
08-26 18:20:11.245  1998  1998 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-26 18:20:11.245  1998  1998 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-26 18:20:11.248  1998  1998 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-26 18:20:11.271  6410  6410 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-26 18:20:11.277  6410  6410 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-26 18:20:11.340  1034  1926 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6580 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 18:20:11.593  6580  6580 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-26 18:20:11.685  6580  6580 D LgDataFeature: LgDataFeature() Constructor: none
08-26 18:20:11.685  6580  6580 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 18:20:11.747  6580  6580 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-26 18:20:11.762   325   431 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-26 18:20:11.762  3294  6616 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-26 18:20:11.772  6580  6580 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 18:20:11.773  6580  6580 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 18:20:11.790  6580  6580 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 18:20:11.790  6580  6580 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-26 18:20:11.804  1034  1926 I ActivityManager: Killing 5448:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-26 18:20:11.871  1034  2035 W libprocessgroup: failed to open /acct/uid_10085/pid_5448/cgroup.procs: No such file or directory
08-26 18:20:11.898  5016  6618 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-26 18:20:11.923  3427  3443 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-26 18:20:11.954  1034  2008 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6619 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 18:20:11.959  3427  3443 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1f5a9b4d on behalf of 6580
08-26 18:20:11.977  1034  1727 V SIM_STK : Menu title from STK is T-Mobile
08-26 18:20:11.990  6580  6580 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-26 18:20:12.001  6580  6580 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-26 18:20:12.104  1819  1836 I art     : Explicit concurrent mark sweep GC freed 30645(1918KB) AllocSpace objects, 12(192KB) LOS objects, 51% free, 29MB/61MB, paused 1.532ms total 49.089ms
08-26 18:20:12.121  6619  6619 D DocsApplication: Installing DEX configuration.
08-26 18:20:12.140  5016  6618 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 242 ms] updated apps [took 242 ms] 
08-26 18:20:12.143  6619  6619 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-26 18:20:12.145  6619  6619 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{35d157a7 com.google.android.apps.docs}
08-26 18:20:12.157  6619  6619 D TAG     : onCreate()
08-26 18:20:12.172  6619  6619 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-26 18:20:12.247  6647  6647 D AndroidRuntime: 
08-26 18:20:12.247  6647  6647 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 18:20:12.250  6647  6647 D AndroidRuntime: CheckJNI is OFF
08-26 18:20:12.420  6647  6647 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 18:20:12.425  1034  1926 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 18:20:12.434  1944  2940 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-26 18:20:12.436  1034  1926 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-26 18:20:12.438  1034  1926 D ActivityManager: setTaskToReturnTo : TaskRecord{1a44eb5b #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 18:20:12.438  1034  1926 D ActivityManager: setTaskToReturnTo : TaskRecord{1a44eb5b #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 18:20:12.439  1034  1926 D WindowStateEx: AppWindowTokenEx init.. 
08-26 18:20:12.439   335   366 E GBMv2   : DFP En is all cleared set to be enabled
08-26 18:20:12.474  1034  1926 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6669 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 18:20:12.476  6647  6647 D AndroidRuntime: Shutting down VM
08-26 18:20:12.534  1944  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-26 18:20:12.534  1944  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{47c92d3 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 18:20:12.535  1944  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-26 18:20:12.535  1944  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3ff8fe10 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 18:20:12.583  6669  6669 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-26 18:20:12.650  6669  6669 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-26 18:20:12.668  6669  6669 I LibraryLoader: Loading: webviewchromium
08-26 18:20:12.671  6669  6669 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3585-3588)
08-26 18:20:12.671  6669  6669 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 18:20:12.686  6669  6669 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {380b1ef9}
08-26 18:20:12.687  6669  6669 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 18:20:12.688  6669  6669 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 18:20:12.698  6669  6669 I BrowserStartupController: Initializing chromium process, renderers=0
08-26 18:20:12.699  6669  6669 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 18:20:12.710   312  2172 V AudioPolicyService: registerClient() client 0xb1030ee0, uid 10118
,08-26 18:20:12.710  6669  6669 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 18:20:12.711  6669  6669 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-26 18:20:12.712  6669  6669 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-26 18:20:12.714  1034  1110 D BluetoothManagerService: Message: 20
08-26 18:20:12.714  1034  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e57f50d:true
08-26 18:20:12.728  6669  6669 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 18:20:12.728  6669  6669 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 18:20:12.728  6669  6669 I Adreno-EGL: Build Date: 12/12/14 금
08-26 18:20:12.728  6669  6669 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 18:20:12.728  6669  6669 I Adreno-EGL: Remote Branch: 
08-26 18:20:12.728  6669  6669 I Adreno-EGL: Local Patches: 
08-26 18:20:12.728  6669  6669 I Adreno-EGL: Reconstruct Branch: 
,08-26 18:20:12.809  6669  6698 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-26 18:20:12.818  6669  6669 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-26 18:20:12.838  6669  6669 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 18:20:12.844  6669  6669 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 18:20:12.847  6669  6669 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-26 18:20:12.850  6669  6669 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-26 18:20:12.850  6669  6669 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-26 18:20:12.866  6669  6669 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-26 18:20:12.872  6669  6669 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 18:20:12.872  6669  6669 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 18:20:12.904  6669  6710 D OpenGLRenderer: Render dirty regions requested: true
08-26 18:20:12.904  6669  6710 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 18:20:12.909  6669  6710 D OpenGLRenderer: Enabling debug mode 0
,08-26 18:20:12.920  6669  6669 D Atlas   : Validating map...
,08-26 18:20:12.924  1034  1907 D SplitWindow: check instance of lgWin Window{2fd1741f u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 18:20:12.943  6669  6708 D LgDataFeature: LgDataFeature() Constructor: none
08-26 18:20:12.943  6669  6708 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 18:20:13.011  1034  1111 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +478ms (total +572ms)
08-26 18:20:13.012  1034  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{12701ff8 u0 com.test.thalitest/.MainActivity t6} time:103929
,08-26 18:20:13.021  6669  6669 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@353ca61c time:103939
08-26 18:20:13.134  6669  6669 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-26 18:20:13.134  6669  6669 I chromium: 
,08-26 18:20:13.140  1819  5205 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-26 18:20:13.144  6669  6669 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-26 18:20:13.182  6669  6708 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-26 18:20:13.182  6669  6708 I chromium: 
08-26 18:20:13.186  1819  5205 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,08-26 18:20:13.240  1819  5205 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-26 18:20:13.282  6669  6725 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,08-26 18:20:13.296  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 18:20:13.296  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 18:20:13.296  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 18:20:13.296  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 18:20:13.296  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 18:20:13.296  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3101d020 added. We now have 1 listener(s)
08-26 18:20:13.301  1034  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:13.304  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-26 18:20:13.305  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 18:20:13.307  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:13.307  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 18:20:13.315  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 18:20:13.315  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 18:20:13.315  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 18:20:13.315  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-26 18:20:13.315  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 18:20:13.315  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 18:20:13.315  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 18:20:13.315  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 18:20:13.315  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 18:20:13.315  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 18:20:13.315  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 18:20:13.315  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 18:20:13.315  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 18:20:13.315  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 18:20:13.315  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c3ce7f added. We now have 1 listener(s)
08-26 18:20:13.315  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:13.322  1034  1544 D WifiService: New client listening to asynchronous messages
,08-26 18:20:13.331  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 18:20:13.331  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 18:20:13.332  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 18:20:13.332  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 18:20:13.333  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 18:20:13.339  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:13.339  1034  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:13.340  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-26 18:20:13.355  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-26 18:20:13.356  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:13.356  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:13.356  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:13.356  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:13.356  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:13.356  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:13.356  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:13.356  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:13.356  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 18:20:13.356  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 18:20:13.360  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:13.362  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:13.364  6669  6725 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 18:20:13.403  6669  6669 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 18:20:13.495  6619  6619 D LgDataFeature: LgDataFeature() Constructor: none
08-26 18:20:13.495  6619  6619 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 18:20:13.633  6619  6619 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-26 18:20:13.659  1034  1907 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6743 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-26 18:20:13.745  6743  6743 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-26 18:20:13.759  6743  6743 I LockScreenSettings: New app installed broadcast received ..
,08-26 18:20:13.762  6743  6743 I LockScreenSettings: Number of installed packages  1
,08-26 18:20:13.855   335   368 E GBMv2   : DFP En is all cleared set to be enabled
08-26 18:20:13.855   335   368 E GBMv2   : Set value is all cleared set the max
08-26 18:20:13.855   335   368 I GBMv2   : DFP Enabled. Ignore VFP set
,08-26 18:20:13.870  1034  1990 I art     : Explicit concurrent mark sweep GC freed 28651(1351KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.342ms total 89.337ms
,08-26 18:20:13.914  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
,08-26 18:20:13.979  1034  1893 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6766 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 18:20:13.980  1034  1893 I ActivityManager: Killing 5582:com.lge.bnr/1000 (adj 15): empty #17
,08-26 18:20:14.009   339   339 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 453us total 29.943ms
,08-26 18:20:14.031   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 21.113ms
,08-26 18:20:14.049   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 357us total 16.735ms
,08-26 18:20:14.081  1034  2053 W libprocessgroup: failed to open /acct/uid_1000/pid_5582/cgroup.procs: No such file or directory
08-26 18:20:14.130  6766  6766 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-26 18:20:14.130  6766  6766 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-26 18:20:14.201  1034  1908 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6785 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 18:20:14.205  1034  1908 I ActivityManager: Killing 6090:com.google.android.gm/u0a64 (adj 15): empty #17
08-26 18:20:14.314  1034  1962 W libprocessgroup: failed to open /acct/uid_10064/pid_6090/cgroup.procs: No such file or directory
,08-26 18:20:14.352  6669  6729 W jxcore-log: Initializing JXcore engine
08-26 18:20:14.352  6669  6729 W jxcore-log: JXcore engine is ready
,08-26 18:20:14.377  6729  6729 W Thread-781: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7546]" dev="sockfs" ino=7546 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-26 18:20:14.377  6729  6729 W Thread-781: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2864 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-26 18:20:14.377  6729  6729 W Thread-781: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9043]" dev="sockfs" ino=9043 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-26 18:20:14.377  6729  6729 W Thread-781: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-26 18:20:14.377  6729  6729 W Thread-781: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32389]" dev="sockfs" ino=32389 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-26 18:20:14.396  6785  6785 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-26 18:20:14.401  6669  6729 W jxcore-log: Starting JXcore engine
08-26 18:20:14.420  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,08-26 18:20:14.421  6785  6785 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 18:20:14.456  1034  1727 I ActivityManager: Killing 5889:com.google.android.talk/u0a72 (adj 15): empty #17
,08-26 18:20:14.556  1034  1956 W libprocessgroup: failed to open /acct/uid_10072/pid_5889/cgroup.procs: No such file or directory
,08-26 18:20:14.575  6669  6729 W jxcore-log: Platform android
08-26 18:20:14.575  6669  6729 W jxcore-log: 
08-26 18:20:14.575  6669  6729 W jxcore-log: Process ARCH arm
08-26 18:20:14.575  6669  6729 W jxcore-log: 
,08-26 18:20:14.914  6669  6729 I jxcore-log: JXcore Cordova bridge is ready!
08-26 18:20:14.914  6669  6729 I jxcore-log: 
,08-26 18:20:14.914  6669  6729 W jxcore-log: JXcore engine is started
,08-26 18:20:14.927  6669  6725 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-26 18:20:14.933  6669  6669 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 18:20:17.564  6619  6619 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-26 18:20:17.566  1034  2053 I ActivityManager: Killing 5707:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-26 18:20:17.595  5687  5687 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-26 18:20:17.595  5687  5687 W System.err: android.os.DeadObjectException
08-26 18:20:17.595  5687  5687 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 18:20:17.595  5687  5687 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 18:20:17.596  5687  5687 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 18:20:17.596  5687  5687 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 18:20:17.596  5687  5687 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 18:20:17.596  5687  5687 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 18:20:17.596  5687  5687 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 18:20:17.596  5687  5687 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 18:20:17.596  5687  5687 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 18:20:17.596  5687  5687 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 18:20:17.596  5687  5687 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:17.596  5687  5687 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:17.596  5687  5687 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 18:20:17.596  5687  5687 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 18:20:17.596  5687  5687 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 18:20:17.596  5687  5687 W System.err: android.os.DeadObjectException
08-26 18:20:17.597  5687  5687 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 18:20:17.597  5687  5687 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 18:20:17.597  5687  5687 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 18:20:17.597  5687  5687 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 18:20:17.597  5687  5687 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 18:20:17.597  5687  5687 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 18:20:17.597  5687  5687 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 18:20:17.597  5687  5687 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 18:20:17.597  5687  5687 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 18:20:17.597  5687  5687 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 18:20:17.597  5687  5687 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:17.597  5687  5687 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:17.597  5687  5687 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 18:20:17.597  5687  5687 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 18:20:17.597  5687  5687 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 18:20:17.597  5687  5687 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-26 18:20:17.836  1034  1893 W libprocessgroup: failed to open /acct/uid_1000/pid_5707/cgroup.procs: No such file or directory
08-26 18:20:17.837  1034  1893 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-26 18:20:17.847  5687  5687 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 18:20:17.848  5687  5687 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 18:20:17.897  1034  1050 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6827 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 18:20:17.897  5687  5687 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 18:20:17.965  6827  6827 D UEI.SmartControl: Quickset Services start...
08-26 18:20:17.967  6827  6827 I UEI.SmartControl: Manufacture = LGE
08-26 18:20:17.967  6827  6827 D UEI.SmartControl: Id = LGNevo
08-26 18:20:17.968  6827  6827 D UEI.SmartControl: File observer start...
08-26 18:20:17.968  6827  6827 E UEI.SmartControl: IR Port is disabled: false
08-26 18:20:17.969  6827  6827 D UEI.SmartControl: Starting file observer...
08-26 18:20:17.969  6827  6827 D UEI.SmartControl: Extracting JNI libs...
08-26 18:20:17.969  6827  6827 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-26 18:20:18.053  6827  6827 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-26 18:20:18.053  6827  6827 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 18:20:18.053  6827  6827 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 18:20:18.090  6827  6827 I UEI.SmartControl: --- Selecting new region: 6
08-26 18:20:18.092  6827  6827 I UEI.SmartControl: Model = LG-D855
,08-26 18:20:18.095  6827  6827 D UEI.SmartControl: QS Service created
08-26 18:20:18.111  6827  6827 I UEI.SmartControl: Service initServices...
,08-26 18:20:18.117  6827  6827 D UEI.SmartControl: QS start get config
08-26 18:20:18.161  6827  6827 D UEI.SmartControl: Loading JNI Libs...
,08-26 18:20:18.522  6827  6827 I UEI.SmartControl: Supports setup maps: true
,08-26 18:20:18.539  6827  6827 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 18:20:18.539  6827  6827 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 18:20:18.539  6827  6827 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 18:20:18.539  6827  6827 I UEI.SmartControl: ### init IR Blaster...
,08-26 18:20:18.556  6827  6827 D serial_port: Configuring serial port
08-26 18:20:18.560  6827  6827 E UEI.SmartControl: UEIBLaster setting for 616
08-26 18:20:18.560  6827  6827 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 18:20:18.560  6827  6827 I UEI.SmartControl: configuring settings for MAXQ616
08-26 18:20:18.560  6827  6827 I UEI.SmartControl: Get version...
,08-26 18:20:18.574  6619  6730 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-26 18:20:18.576  6827  6847 D UEI.SmartControl: serial port data available: 21
08-26 18:20:18.604  6827  6827 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 18:20:18.604  6827  6827 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 18:20:18.604  6827  6827 I UEI.SmartControl: QS saving settings...
08-26 18:20:18.605  6827  6827 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 18:20:18.618  6827  6847 D UEI.SmartControl: serial port data available: 4
,08-26 18:20:18.652  6827  6827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 18:20:18.657  6827  6850 I UEI.SmartControl: Device manager: loading config....
08-26 18:20:18.658  6827  6850 D UEI.SmartControl: ----------- loading internal config...
08-26 18:20:18.669  6827  6827 E UEI.SmartControl: Services init done
,08-26 18:20:18.673  6827  6827 D UEI.SmartControl: QS Service init finished
08-26 18:20:18.673  6827  6827 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 18:20:18.674  6827  6827 D UEI.SmartControl: QS Service version code: 201091
08-26 18:20:18.674  6827  6827 D UEI.SmartControl: Service requested: Control
08-26 18:20:18.678  6827  6850 E UEI.SmartControl: Loading SETTINGS...
08-26 18:20:18.680  6827  6827 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 18:20:18.681  1034  2035 I ActivityManager: Killing 5687:com.lge.qremote/u0a112 (adj 15): empty #17
,08-26 18:20:18.687  6827  6850 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 18:20:18.705  6827  6849 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 18:20:18.705  6827  6849 D UEI.SmartControl: -----service ready thread exits
,08-26 18:20:18.796  1034  1907 W libprocessgroup: failed to open /acct/uid_10112/pid_5687/cgroup.procs: No such file or directory
,08-26 18:20:18.804  6827  6827 D UEI.SmartControl: Internal service binding...
,08-26 18:20:20.518  2799  2799 I MusicWidget: mDelayedStopHandler : unbind
,08-26 18:20:20.527  2176  2176 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-26 18:20:20.528  2176  2176 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-26 18:20:20.528  2176  2176 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-26 18:20:20.533  2176  2176 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-26 18:20:20.533  2176  2176 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-26 18:20:20.534  2176  2176 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-26 18:20:20.537  2176  2176 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-26 18:20:20.538  2176  2176 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,08-26 18:20:20.543  1034  1656 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1d18b2eecom.lge.music.MediaPlaybackService$5@3c1ce38f
08-26 18:20:20.544  2176  2176 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-26 18:20:20.544  2176  2176 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 18:20:20.545  2176  2176 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 18:20:20.546  2176  2176 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 18:20:20.547  2176  2176 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@b55b1b5
08-26 18:20:20.547  2176  2176 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 18:20:20.548  2176  2176 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-26 18:20:20.548  2176  2176 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 18:20:20.549  2176  2176 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-26 18:20:20.549  2176  2176 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-26 18:20:20.549  2176  2176 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 18:20:20.550  2176  2176 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 18:20:20.550  2176  2176 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 18:20:20.551  2176  2176 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-26 18:20:20.553  2176  2176 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 18:20:20.554  2176  2176 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-26 18:20:20.556  2176  2176 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-26 18:20:20.556  2176  2176 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-26 18:20:20.556  2176  2176 V MediaPlayer[Native]: reset
,08-26 18:20:20.563  2176  2176 V MediaPlayer[Native]: setListener
08-26 18:20:20.563  2176  2176 V MediaPlayer[Native]: disconnect
08-26 18:20:20.563  2176  2176 V MediaPlayer[Native]: destructor
,08-26 18:20:20.564   312  1383 V AudioFlinger: releasing 18 from 2176 for -1
08-26 18:20:20.564   312  1383 V AudioFlinger:  decremented refcount to 0
08-26 18:20:20.564   312  1383 V AudioFlinger: purging stale effects
08-26 18:20:20.565  2176  2176 V MediaPlayer[Native]: disconnect
08-26 18:20:20.566  2176  2176 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-26 18:20:20.568  2176  2176 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-26 18:20:20.568  2176  2176 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-26 18:20:20.569  2176  2176 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-26 18:20:20.569  2176  2176 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-26 18:20:20.569  2176  2176 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-26 18:20:20.570  2176  2176 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 893167132
08-26 18:20:20.570  2176  2176 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 893167132
08-26 18:20:20.583  2176  2176 I SmartShareClient: [SmartShareManagerClient] terminate service: 2176/MediaPlaybackService/330417987
08-26 18:20:20.586  2176  2176 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-26 18:20:20.586  2176  2176 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3b177225
,08-26 18:20:20.589  2176  2176 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-26 18:20:20.590  2176  2176 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-26 18:20:20.590  2176  2176 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-26 18:20:20.591  2176  2176 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-26 18:20:20.592  1034  1956 I ActivityManager: Killing 5622:com.android.calendar/u0a13 (adj 15): empty #17
08-26 18:20:20.594  2176  2176 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29998
08-26 18:20:20.676  1034  1051 W libprocessgroup: failed to open /acct/uid_10013/pid_5622/cgroup.procs: No such file or directory
,08-26 18:20:23.666  6827  6851 D UEI.SmartControl: Internal timer expired: 1
08-26 18:20:23.666  6827  6851 D UEI.SmartControl: unbind internal service
,08-26 18:20:23.679  6827  6827 D UEI.SmartControl: Service.onUnbind: IControl
08-26 18:20:23.680  6827  6827 D UEI.SmartControl: Service.onDestroy
08-26 18:20:23.681  6827  6827 D UEI.SmartControl: Lock is in USE false
08-26 18:20:23.681  6827  6827 D UEI.SmartControl: unbind internal service
08-26 18:20:23.681  6827  6827 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@b55b1b5
08-26 18:20:23.692  6827  6827 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-26 18:20:23.692  6827  6827 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-26 18:20:23.692  6827  6827 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-26 18:20:23.692  6827  6827 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-26 18:20:23.692  6827  6827 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-26 18:20:23.693  6827  6827 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-26 18:20:23.693  6827  6827 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-26 18:20:23.693  6827  6827 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-26 18:20:23.693  6827  6827 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:23.693  6827  6827 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 18:20:23.693  6827  6827 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 18:20:23.693  6827  6827 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:23.693  6827  6827 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:23.693  6827  6827 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 18:20:23.693  6827  6827 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 18:20:23.693  6827  6827 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@b55b1b5
,08-26 18:20:23.698  6827  6827 D serial_port: close(fd = 25)
08-26 18:20:23.701  6827  6827 I UEI.SmartControl: Serial port is closed.
08-26 18:20:23.701  6827  6827 I UEI.SmartControl: Serial port is closed.
08-26 18:20:23.701  6827  6827 D UEI.SmartControl: Blaster closed
08-26 18:20:23.702  6827  6827 D UEI.SmartControl: Shut down QS...
08-26 18:20:23.702  6827  6827 D UEI.SmartControl: Stopping QS lib
08-26 18:20:23.702  6827  6827 D UEI.SmartControl: QS lib stop result = true
08-26 18:20:23.702  6827  6827 D UEI.SmartControl: Stopped QS lib
08-26 18:20:23.703  6827  6827 D UEI.SmartControl: Stopped file observer...
08-26 18:20:23.703  6827  6827 D UEI.SmartControl: QS shutdown complete
08-26 18:20:25.371  1034  1091 I ActivityManager: Waited long enough for: ServiceRecord{2c9c326 u0 com.google.android.gms/.wearable.service.WearableService}
,08-26 18:20:27.670  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 18:20:27.670  6669  6729 I jxcore-log: 
,08-26 18:20:27.676  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 18:20:27.676  6669  6729 I jxcore-log: 
08-26 18:20:27.681  6669  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:27.681  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:27.681  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:27.681  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:27.681  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:27.681  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:27.681  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:27.681  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:27.684  6669  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:27.687  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 18:20:27.687  6669  6729 I jxcore-log: 
08-26 18:20:27.690  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 18:20:27.690  6669  6729 I jxcore-log: 
,08-26 18:20:28.663  6669  6729 D executeNativeTests: Running unit tests
,08-26 18:20:28.798  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:28.798  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 added. We now have 2 listener(s)
,08-26 18:20:28.801  1034  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:28.804  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 18:20:28.804  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:28.804  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:28.804  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:28.804  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 added. We now have 2 listener(s)
08-26 18:20:28.804  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:28.805  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 18:20:28.808  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:28.812  6669  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:28.812  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:28.812  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:28.812  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:28.812  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:28.812  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:28.812  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:28.812  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 18:20:28.819  6669  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:28.819  6669  6729 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 18:20:28.821  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:28.823  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:28.826  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 18:20:28.829  6669  6729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 18:20:28.829  6669  6729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 18:20:28.831  6669  6729 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-26 18:20:28.832  6669  6729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 18:20:28.832  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 18:20:28.832  6669  6729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 18:20:28.832  6669  6729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 18:20:28.833  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:28.836  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:28.836  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:28.837  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:28.837  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.837  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:28.837  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:28.838  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 removed from the list
08-26 18:20:28.838  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:28.838  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 removed from the list
08-26 18:20:28.838  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:28.838  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:28.841  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.841  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:28.842  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:28.843  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:28.843  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:28.843  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:28.847  6669  6729 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 18:20:28.848  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:28.848  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:28.848  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:28.849  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:28.849  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.849  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:28.849  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:28.849  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:28.849  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:28.849  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:28.849  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.849  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:28.849  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.850  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:28.854  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:28.854  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:28.854  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:28.854  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:28.861  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 18:20:28.861  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 18:20:28.861  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 18:20:28.861  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 18:20:28.861  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 18:20:28.861  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 18:20:28.861  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 18:20:28.861  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 18:20:28.861  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 18:20:28.861  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 18:20:28.861  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 18:20:28.862  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 18:20:28.862  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 18:20:28.862  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 18:20:28.862  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 18:20:28.862  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 18:20:28.862  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 18:20:28.862  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 18:20:28.862  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 18:20:28.862  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 18:20:28.862  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 18:20:28.862  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 18:20:28.862  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-26 18:20:28.866  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 18:20:28.866  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 18:20:28.866  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 18:20:28.866  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 18:20:28.866  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 18:20:28.866  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 18:20:28.866  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 18:20:28.866  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 18:20:28.866  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:28.867  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:28.867  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:28.867  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:28.867  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.867  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:28.867  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:28.867  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:28.867  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:28.867  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:28.867  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.868  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:28.868  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.868  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:28.869  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:28.869  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:28.869  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:28.869  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:28.870  6669  6729 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 18:20:28.873  6669  6729 I org.thaliproject.p2p.btconn,ectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:28.876  6669  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:28.876  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:28.876  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:28.876  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:28.876  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:28.876  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:28.876  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:28.876  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 18:20:28.881  6669  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:28.881  6669  6729 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 18:20:28.883  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:28.885  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:28.885  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:28.885  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 18:20:28.886  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 18:20:28.886  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:28.886  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 18:20:28.890  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 18:20:28.892  1034  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:28.899  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 18:20:28.905  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 18:20:28.909  6669  6729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 18:20:28.911  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 18:20:28.912  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:28.914  6669  6729 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 18:20:28.914  6669  6729 I io.jxcore.node.ConnectionHelper: start: OK
08-26 18:20:28.918  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:28.918  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:28.918  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 18:20:28.920  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:28.921  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.921  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:28.921  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:28.921  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:28.921  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:28.921  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:28.921  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:28.922  6669  6729 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 18:20:28.925  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:28.928  6669  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:28.928  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:28.928  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:28.928  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:28.928  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:28.928  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:28.928  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:28.928  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:28.930  6669  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:28.930  6669  6729 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 18:20:28.934  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:28.935  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:28.936  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:28.936  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 18:20:28.936  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 18:20:28.936  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:28.936  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 18:20:28.940  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 18:20:28.941  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 18:20:28.944  6669  6729 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 18:20:28.945  6669  6729 I io.jxcore.node.ConnectionHelper: start: OK
08-26 18:20:28.946  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:28.946  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:28.946  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:28.947  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:28.947  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.947  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:28.947  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:28.947  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:28.947  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:28.947  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:28.947  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:28.948  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.948  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:28.949  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:28.949  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:28.951  6669  6729 D BluetoothLeScanner: could not find callback wrapper
08-26 18:20:28.951  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:28.951  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:28.951  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:28.952  6669  6729 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 18:20:28.954  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 18:20:28.960  6669  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:28.960  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:28.960  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:28.960  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:28.960  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:28.960  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:28.960  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:28.960  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:28.962  6669  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:28.962  6669  6729 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 18:20:28.968  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:28.972  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:28.972  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:28.972  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 18:20:28.973  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 18:20:28.973  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:28.973  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 18:20:28.984  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 18:20:28.985  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 18:20:28.987  6669  6729 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 18:20:28.988  6669  6729 I io.jxcore.node.ConnectionHelper: start: OK
08-26 18:20:28.988  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:28.988  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:28.988  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:28.989  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:28.989  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:28.989  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:28.990  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:28.990  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.990  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:28.990  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:28.990  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:28.990  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:28.990  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:28.990  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:28.991  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.991  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:28.992  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:28.992  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:28.992  6669  6729 D BluetoothLeScanner: could not find callback wrapper
08-26 18:20:28.992  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:28.992  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:28.993  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:28.993  6669  6729 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 18:20:28.994  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:28.994  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:28.994  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, s,kipping...
08-26 18:20:28.994  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:28.994  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.994  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:28.995  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:28.995  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:28.995  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:28.995  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:28.995  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.995  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:28.995  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:28.995  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:28.996  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:28.996  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:29.001  6669  6729 D BluetoothLeScanner: could not find callback wrapper
08-26 18:20:29.001  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:29.001  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.001  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.003  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 18:20:29.003  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:29.003  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:29.003  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:29.003  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.003  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.003  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.003  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.003  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.003  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.003  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:29.003  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.003  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.003  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.003  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.004  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:29.004  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:29.005  6669  6729 D BluetoothLeScanner: could not find callback wrapper
08-26 18:20:29.005  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:29.005  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.005  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.006  6669  6729 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 18:20:29.006  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:29.006  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:29.006  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:29.006  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.007  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.007  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.007  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.007  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.007  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.007  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:29.007  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.007  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.007  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.007  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.008  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:29.008  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:29.008  6669  6729 D BluetoothLeScanner: could not find callback wrapper
08-26 18:20:29.008  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:29.008  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.008  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.009  6669  6729 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 18:20:29.009  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:29.009  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:29.009  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:29.010  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.010  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.010  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.010  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.010  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.010  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.010  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:29.010  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.010  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.010  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.010  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.012  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:29.012  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:29.013  6669  6729 D BluetoothLeScanner: could not find callback wrapper
08-26 18:20:29.013  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:29.013  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.013  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.014  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 18:20:29.014  6669  6729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 18:20:29.014  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 18:20:29.014  6669  6729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 18:20:29.014  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 18:20:29.014  6669  6729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 18:20:29.015  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:29.015  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:29.015  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:29.016  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.016  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.016  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.016  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.016  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.016  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.016  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:29.016  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.016  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.016  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.016  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.018  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:29.018  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:29.018  6669  6729 D BluetoothLeScanner: could not find callback wrapper
,08-26 18:20:29.018  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:29.018  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.018  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.019  6669  6729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 18:20:29.019  6669  6729 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 18:20:29.020  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 18:20:29.023  6669  6729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 18:20:29.024  6669  6729 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 18:20:29.024  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 18:20:29.024  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 18:20:29.024  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 18:20:29.025  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 18:20:29.026  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 18:20:29.027  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 18:20:29.027  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 18:20:29.027  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 18:20:29.027  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 18:20:29.027  6669  6729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 18:20:29.027  6669  6729 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 18:20:29.027  6669  6729 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 18:20:29.028  6669  6729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 18:20:29.028  6669  6729 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 18:20:29.028  6669  6729 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 18:20:29.028  6669  6729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 18:20:29.028  6669  6729 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 18:20:29.028  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 18:20:29.030  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 18:20:29.032  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 18:20:29.032  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 18:20:29.033  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 18:20:29.033  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 18:20:29.033  6669  6729 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 18:20:29.033  6669  6729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 18:20:29.033  6669  6729 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 18:20:29.034  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:29.034  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:29.034  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:29.035  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.035  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.035  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.035  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 18:20:29.035  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.035  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.035  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.036  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:29.036  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.036  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.036  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.036  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.037  6669  6894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 845)
08-26 18:20:29.039  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:29.039  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:29.040  6669  6729 D BluetoothLeScanner: could not find callback wrapper
08-26 18:20:29.040  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:29.040  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.040  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.045  6669  6729 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 18:20:29.045  6669  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 845
08-26 18:20:29.046  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:29.046  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:29.046  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:29.046  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.046  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.046  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.046  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.046  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.046  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.046  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:29.046  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.046  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.046  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.046  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.047  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:29.047  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:29.048  6669  6729 D BluetoothLeScanner: could not find callback wrapper
08-26 18:20:29.048  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:29.048  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.048  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.049  6669  6729 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 18:20:29.050  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:29.050  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:29.050  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:29.050  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.051  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.051  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.051  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.051  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.051  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.051  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:29.051  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.051  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.051  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list, - probably already removed
08-26 18:20:29.051  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.052  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:29.052  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:29.055  6669  6729 D BluetoothLeScanner: could not find callback wrapper
08-26 18:20:29.055  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:29.055  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.055  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.056  6669  6729 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 18:20:29.056  6669  6729 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 18:20:29.057  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 18:20:29.057  6669  6729 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 18:20:29.057  6669  6729 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 18:20:29.057  6669  6729 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 18:20:29.057  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 18:20:29.057  6669  6729 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 18:20:29.057  6669  6729 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 18:20:29.057  6669  6729 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 18:20:29.057  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 18:20:29.057  6669  6729 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 18:20:29.058  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:29.058  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:29.058  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:29.063  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.063  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.063  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.063  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.063  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.063  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.063  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:29.063  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.063  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.064  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.064  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.072  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:29.072  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:29.082  6669  6729 D BluetoothLeScanner: could not find callback wrapper
08-26 18:20:29.082  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:29.082  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.082  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.083  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.083  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.083  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.083  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.083  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.083  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.083  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:29.083  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.083  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.083  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.083  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.083  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.083  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.083  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.083  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.083  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:29.083  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:29.083  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:29.084  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.084  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.084  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.084  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.084  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.084  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.084  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:29.084  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.084  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.084  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.084  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.084  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:29.084  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:29.085  6669  6729 D BluetoothLeScanner: could not find callback wrapper
08-26 18:20:29.085  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:29.085  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.085  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.087  6669  6729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 18:20:29.087  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:29.087  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 18:20:29.088  6669  6729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 18:20:29.088  6669  6729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 18:20:29.088  6669  6669 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 18:20:29.088  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 18:20:29.088  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 18:20:29.089  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.089  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 18:20:29.089  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 18:20:29.090  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 18:20:29.090  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.090  6669  6729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 18:20:29.091  6669  6669 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 18:20:29.091  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.091  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.091  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 18:20:29.091  6669  6729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 18:20:29.091  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 18:20:29.092  6669  6900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 18:20:29.092  6669  6900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 18:20:29.093  6669  6669 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 18:20:29.102  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 18:20:29.104  6669  6729 D BluetoothLeScanner: could not find callback wrapper
08-26 18:20:29.104  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:29.104  6669  6729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 18:20:29.104  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.104  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.112  6669  6729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 18:20:29.113  6669  6669 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 18:20:29.113  6669  6669 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 18:20:29.113  6669  6669 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 18:20:29.113  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.113  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 18:20:29.113  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:29.113  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:29.113  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.114  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 18:20:29.114  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.114  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.114  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 18:20:29.114  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
,08-26 18:20:29.114  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:29.114  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.114  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.114  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.114  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.114  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:29.114  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:29.115  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.115  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.115  6669  6729 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 18:20:29.116  6669  6729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 18:20:29.116  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 18:20:29.116  6669  6729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 18:20:29.116  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:29.116  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:29.116  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:29.117  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.117  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.117  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.117  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.117  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.117  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.117  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:29.117  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.117  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.117  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.117  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.118  6669  6729 I org.,thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:29.118  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:29.118  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.118  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.119  1034  1990 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:29.119  1034  2053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:29.120  1034  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:29.121  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:29.121  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:29.121  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:29.121  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.121  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.121  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.121  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.121  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 18:20:29.121  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.121  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:29.121  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.121  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.121  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.121  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.122  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 18:20:29.122  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:29.122  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.122  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list,
08-26 18:20:29.123  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:29.123  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:29.123  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:29.123  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:29.123  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 18:20:29.123  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:29.123  6669  6729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ba05ef0 not in the list
08-26 18:20:29.123  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.123  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
08-26 18:20:29.123  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:29.123  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 18:20:29.123  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.123  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:29.123  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:29.124  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:29.124  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:29.124  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:29.124  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd5bc69 not in the list
,08-26 18:20:29.125  6669  6729 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 18:20:29.125  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-26 18:20:29.125  6669  6729 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 18:20:29.125  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 18:20:29.125  6669  6729 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 18:20:29.126  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 18:20:29.127  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 18:20:29.127  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 18:20:29.128  6669  6729 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 18:20:29.128  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 18:20:29.128  6669  6729 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 18:20:29.128  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 18:20:29.128  6669  6729 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 18:20:29.128  6669  6729 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 18:20:29.128  6669  6729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 18:20:29.129  6669  6729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 18:20:29.129  6669  6729 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 18:20:29.129  6669  6729 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 18:20:29.129  6669  6729 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 18:20:29.129  6669  6729 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 18:20:29.130  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:29.130  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ec965c6 added. We now have 2 listener(s)
08-26 18:20:29.130  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:29.131  6669  6729 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 18:20:29.132  1034  2008 D WifiServiceImplEx: setWifiEnabled: true pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 18:20:29.133  1034  2008 D WifiService: setWifiEnabled: true pid=6669, uid=10118
08-26 18:20:29.133  1034  2008 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 18:20:29.135  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:29.135  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15e6d987 added. We now have 3 listener(s)
08-26 18:20:29.135  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:29.138  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load,: Already loaded
08-26 18:20:29.138  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2efbf0b4 added. We now have 4 listener(s)
08-26 18:20:29.138  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:29.140  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:29.140  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23d484dd added. We now have 5 listener(s)
08-26 18:20:29.140  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:29.142  1034  2008 D WifiServiceImplEx: setWifiEnabled: false pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 18:20:29.142  1034  2008 D WifiService: setWifiEnabled: false pid=6669, uid=10118
08-26 18:20:29.142  1034  2008 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 18:20:29.152  6669  6894 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-26 18:20:29.152  6669  6894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 18:20:29.152  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 18:20:29.153  4274  4405 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:29.153  4274  4448 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
08-26 18:20:29.153  4274  4405 D LGBluetoothServiceAdapter: [BTUI] connectSocket FD=84 mFd=82
08-26 18:20:29.153  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 18:20:29.153  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 18:20:29.154  1034  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 18:20:29.155  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 18:20:29.155  1034  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 18:20:29.155  1034  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 18:20:29.155  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 18:20:29.155  1034  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 18:20:29.155  1034  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 18:20:29.155  1034  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 18:20:29.156  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:29.156  1034  1050 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2eb1d4ef mBinding = false
08-26 18:20:29.156  1034  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 18:20:29.156  1034  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 18:20:29.164  1034  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-26 18:20:29.164  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 18:20:29.164  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:29.164  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:29.164  2764  2764 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 18:20:29.167  1034  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 18:20:29.167  1034  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 18:20:29.167  1034  1539 D WifiNative-wlan0: SET ps 1: returned true
08-26 18:20:29.168  1034  2871 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:29.173   307   889 D CommandListener: Clearing all IP addresses on wlan0
08-26 18:20:29.173  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 18:20:29.173  1034  1110 D BluetoothManagerService: Message: 2
08-26 18:20:29.174  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 18:20:29.174  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 18:20:29.174  1034  1110 D BluetoothManagerService: Sending off request.
08-26 18:20:29.175  4274  4294 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-26 18:20:29.177  4274  4348 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 18:20:29.177  4274  4348 D BluetoothAdapterProperties: Setting state to 13
08-26 18:20:29.177  4274  4348 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 18:20:29.178  4274  4348 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 18:20:29.178  4274  4348 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 18:20:29.179  4274  4351 D BluetoothAdapterProperties: Scan Mode:20
08-26 18:20:29.179  4274  4348 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 18:20:29.180  4274  4661 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 18:20:29.180  4274  4661 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 18:20:29.180  4274  4661 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 18:20:29.180  4274  4661 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 18:20:29.180  4274  4661 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 18:20:29.180  4274  4661 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 18:20:29.180  4274  4661 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 18:20:29.180  4274  4661 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 18:20:29.181  4274  4662 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 18:20:29.181  4274  4719 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 18:20:29.181  4274  4720 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 18:20:29.182  6669  6894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 845)
08-26 18:20:29.182  4274  4723 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 18:20:29.183  4274  4348 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 18:20:29.184  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 18:20:29.184  4274  4448 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 18:20:29.184  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 18:20:29.185  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 18:20:29.185  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 18:20:29.185  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 18:20:29.185  4274  4448 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 18:20:29.185  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 18:20:29.185  4274  4448 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 18:20:29.185  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 18:20:29.185  4274  4448 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 18:20:29.185  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 18:20:29.185  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 18:20:29.185  4274  4448 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 18:20:29.203  6669  6669 W org.thaliproject.p2p.btcon,nectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:29.203  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:29.203  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:29.203  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:29.203  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:29.203  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:29.203  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:29.203  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:29.203  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 18:20:29.214  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:29.214  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 18:20:29.225  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 18:20:29.225  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-26 18:20:29.226  1034  1110 D BluetoothManagerService: Message: 60
08-26 18:20:29.226  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 18:20:29.226  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 18:20:29.233  1034  1051 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-26 18:20:29.233  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:29.233  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 18:20:29.233  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 18:20:29.233  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:29.233  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-26 18:20:29.236  1034  1091 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6905 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-26 18:20:29.239  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:29.239  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:29.240  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 18:20:29.241  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 18:20:29.241  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:29.243  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:29.245  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:29.246  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:29.246  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 18:20:29.247  4274  4274 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:29.247  4274  4274 D BluetoothMapService: STATE_TURNING_OFF
08-26 18:20:29.248  4274  4274 V BluetoothMapService: Handler(): got msg=4
08-26 18:20:29.248  4274  4274 D BluetoothMapService: MAP Service closeService in
08-26 18:20:29.248  4274  4274 D BluetoothMapMasInstance: MAP Service shutdown
08-26 18:20:29.248  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:29.248  4274  4274 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 18:20:29.248  4274  4274 V BluetoothMapService: MAP Service closeService out
08-26 18:20:29.248  4274  4274 V BtOppService: Receiver DISABLED_ACTION 
08-26 18:20:29.249  4274  4274 I BtOppRfcommListener: stopping Accept Thread
08-26 18:20:29.249  4274  4274 V BtOppRfcommListener: close mBtServerSocket
08-26 18:20:29.249  4274  4274 V BtOppRfcommListener: waiting for thread to terminate
08-26 18:20:29.249  4274  4719 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 18:20:29.250  4274  4274 V BtOppRfcommListener: done waiting for thread to terminate
08-26 18:20:29.251  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:29.251  6669  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:29.251  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:29.251  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:29.251  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:29.251  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:29.251  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:29.251  6669  6729, V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:29.251  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:29.252  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:29.252  6669  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:29.252  6669  6729 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 18:20:29.253  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:29.254  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:29.256  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:29.256  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:29.256  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:29.256  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:29.256  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:29.256  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:29.256  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:29.256  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:29.256  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:29.256  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:29.257  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:29.258  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:29.264  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-26 18:20:29.277  1034  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 18:20:29.277  1034  1545 D DSQN    : disableDataServiceNotify
08-26 18:20:29.277  1034  1545 D DSQN    : stop dsqn bin
08-26 18:20:29.277   307  6930 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 18:20:29.278  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-26 18:20:29.278  1034  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-26 18:20:29.284  1034  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 18:20:29.286  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:29.286  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:29.286  1034  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-26 18:20:29.292  1034  1091 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6932 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 18:20:29.293  1603  2082 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 18:20:29.294  1034  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 18:20:29.294  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:29.294  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:29.294  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 18:20:29.294  1034  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 18:20:29.294  1034  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 18:20:29.295  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 18:20:29.295  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 18:20:29.295  1034  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:29.295  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 18:20:29.295  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:29.295  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:29.295  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 18:20:29.295  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:29.295  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:29.296  1034  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@22c6183f
08-26 18:20:29.296  1034  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:29.296  1034  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:29.296  1034  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:29.296  1034  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:29.296  1034  1,539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:29.296  1034  1538 D LGWifiP2pService: P2pDisablingState
08-26 18:20:29.296  1034  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:29.296  1034  1538 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:29.297  1034  1538 D LGWifiP2pService: p2p socket connection lost
08-26 18:20:29.297  1034  1538 D LGWifiP2pService: P2pDisabledState
08-26 18:20:29.297  1034  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:29.297  1034  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 18:20:29.297  4274  4274 V BtOppService: onDestroy
08-26 18:20:29.298  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:29.298  1034  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:29.298  1034  1545 D NetworkManagementService: Removing idletimer
08-26 18:20:29.299  1034  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 18:20:29.299  1034  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:29.299  1034  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:29.299  1034  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 18:20:29.299  1855  1855 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:29.299  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:29.299  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 18:20:29.299  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 18:20:29.300  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 18:20:29.300  1034  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:29.300  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 18:20:29.300  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 18:20:29.300  1034  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:29.300  1034  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 18:20:29.300  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 18:20:29.300  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-26 18:20:29.300  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 18:20:29.300  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 18:20:29.300  1034  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 18:20:29.300  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 18:20:29.300  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 18:20:29.300  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 18:20:29.301  1034  1537 V NetworkPolicy: [LG_RESTRICTE,D] !!!isConnected  type  :1
08-26 18:20:29.301  2764  2764 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 18:20:29.301  1034  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:29.301  1034  1538 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:29.301  1034  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:29.301  1034  1558 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:29.301  4274  4274 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 18:20:29.302  1034  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 18:20:29.302  1034  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 18:20:29.302  1034  1539 D WifiNative-wlan0: SET ps 1: returned true
08-26 18:20:29.303   307   889 D CommandListener: Clearing all IP addresses on wlan0
08-26 18:20:29.303  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 18:20:29.303  1944  1944 D WfdsService: WifiP2pState is changed : false
08-26 18:20:29.303  1944  2286 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 18:20:29.303  1944  2286 D WfdsService: Set the WFDS Monitor: false
08-26 18:20:29.304  1944  2286 D WfdsMonitor: WFDS Monitor is stopped
08-26 18:20:29.304  1944  2286 D WfdsService: STATE : WfdsDisabledState - enter
08-26 18:20:29.304  1944  2288 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 18:20:29.304  1944  2790 D CtrlSupplicant: Received on exit socket, terminate
08-26 18:20:29.304  1944  2790 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 18:20:29.304  1944  2790 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 18:20:29.304  1944  2790 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 18:20:29.304  1944  2286 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 18:20:29.306  1034  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 18:20:29.306  1034  1539 D WifiNative-p2p0: TERMINATE: returned true
08-26 18:20:29.306  1034  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 18:20:29.306  1034  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 18:20:29.306  1034  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 18:20:29.307  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 18:20:29.308  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:29.308  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:29.308  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 18:20:29.309  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 18:20:29.311  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:29.311  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:29.311  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:29.311  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:29.311  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:29.311  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:29.311  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:29.311  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:29.311  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:29.312  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:29.312  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:29.313  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:29.313  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:29.313  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:29.313  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:29.313  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:29.313  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:29.313  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:29.313  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:29.313  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:29.313  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 18:20:29.314  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:29.314  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 18:20:29.314  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:29.314  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:29.321  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:29.321  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:29.323  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 18:20:29.347  6932  6932 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 18:20:29.347  6932  6932 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-26 18:20:29.348  6932  6932 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 18:20:29.348  6932  6932 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-26 18:20:29.349  6932  6932 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 18:20:29.349  6932  6932 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 18:20:29.366  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 18:20:29.366  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:29.367  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:29.378  1034  2871 D DhcpStateMachine: StoppedState
,08-26 18:20:29.378  1034  2871 D DhcpStateMachine: StoppedState{ when=-76ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:29.379  1034  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 18:20:29.379  1034  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 18:20:29.380  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 18:20:29.380  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:29.381  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:29.381  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 18:20:29.381  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:29.382  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:29.382  6905  6905 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 18:20:29.383  6905  6905 W LG Account v2.2: No ProfileInfo entries
08-26 18:20:29.383  6905  6905 I LG Account v2.2: isEnabled: false
08-26 18:20:29.383  6905  6905 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 18:20:29.383  6905  6905 I Feature : [Lifetracker]Country: EU
08-26 18:20:29.383  6905  6905 I Feature : [Lifetracker]Operator: OPEN
08-26 18:20:29.383  6905  6905 I Feature : [Lifetracker]Ranking support: false
08-26 18:20:29.384  6905  6905 I Feature : [Lifetracker]Comfort support: false
08-26 18:20:29.384  6905  6905 I Feature : [Lifetracker]Accessory: true
08-26 18:20:29.384  6905  6905 I Feature : [Lifetracker]Health device: true
08-26 18:20:29.384  6905  6905 I Feature : [Lifetracker]Extra Pedometer: false
08-26 18:20:29.384  6905  6905 I Feature : [Lifetracker]Blood glucose device: false
08-26 18:20:29.384  6905  6905 I Feature : [Lifetracker]Device Number: 3
08-26 18:20:29.386  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:29.393  2764  2764 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 18:20:29.393  2764  2764 I wpa_supplicant: monitor socket send errors count : 1
08-26 18:20:29.393  2764  2764 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1944-2\x00 that cannot receive messages
,08-26 18:20:29.394  1034  2787 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,08-26 18:20:29.394  1034  2787 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 18:20:29.399  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:29.431  1034  1656 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6952 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 18:20:29.432  1034  1656 I ActivityManager: Killing 6140:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-26 18:20:29.435  6932  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 18:20:29.489  2764  2764 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 18:20:29.490  1034  2787 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 18:20:29.490  1034  2787 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 18:20:29.490  1034  2787 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 18:20:29.490  1034  2787 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 18:20:29.490  1034  1110 D Tethering: InitialState.processMessage what=4
08-26 18:20:29.491  1034  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 18:20:29.491  1034  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=120396
08-26 18:20:29.491  1034  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=120396
08-26 18:20:29.492  2764  2764 W wpa_supplicant: USIM:  scard_deinit function
08-26 18:20:29.492  1034  2008 W libprocessgroup: failed to open /acct/uid_10014/pid_6140/cgroup.procs: No such file or directory
08-26 18:20:29.495  1034  2787 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 18:20:29.495  1034  2787 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 18:20:29.497  1034  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=120402  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 18:20:29.499  1034  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=120404  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 18:20:29.507  4274  4274 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 18:20:29.508  4274  4274 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:29.508  4274  4274 V BluetoothPbapReceiver: ***********state = 13
08-26 18:20:29.510  1034  1110 D BluetoothManagerService: Message: 20
08-26 18:20:29.510  4274  4274 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 18:20:29.511  1034  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16d87201:true
,08-26 18:20:29.513  1034  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:29.513  1034  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:29.513  4274  4274 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:29.514  4274  4274 V BluetoothPbapService: state: 13
08-26 18:20:29.514  4274  4274 V BluetoothPbapService: Pbap Service closeService in
08-26 18:20:29.516  4274  4274 V BluetoothPbapService: successfully stopped pbap service
08-26 18:20:29.516  4274  4274 V BluetoothPbapService: Pbap Service closeService out
08-26 18:20:29.517  4274  4274 V BluetoothPbapService: Pbap Service onDestroy
08-26 18:20:29.517  4274  4274 V BluetoothPbapService: Pbap Service closeService in
08-26 18:20:29.517  4274  4274 V BluetoothPbapService: Pbap Service closeService out
08-26 18:20:29.517  4274  4274 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 18:20:29.520  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 18:20:29.532  1034  1110 D BluetoothManagerService: Message: 30
,08-26 18:20:29.538  1034  1110 D BluetoothManagerService: Message: 30
08-26 18:20:29.540  6932  6932 D LocalBluetoothProfileManager: Adding local MAP profile
08-26 18:20:29.542  6932  6932 D BluetoothMap: Create BluetoothMap proxy object
08-26 18:20:29.543  1034  1110 D BluetoothManagerService: Message: 30
08-26 18:20:29.547  1034  1110 D BluetoothManagerService: Message: 30
,08-26 18:20:29.549  6932  6932 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-26 18:20:29.550  6932  6932 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-26 18:20:29.563  6952  6952 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-26 18:20:29.567  6932  6932 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-26 18:20:29.570  6932  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-26 18:20:29.577  6952  6952 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-26 18:20:29.578  6952  6952 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 18:20:29.580  1034  2008 I ActivityManager: Killing 6267:com.android.defcontainer/u0a4 (adj 15): empty #17
08-26 18:20:29.604  2764  2764 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 18:20:29.604  1034  2787 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 18:20:29.604  1034  2787 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 18:20:29.604  1034  2787 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-26 18:20:29.607  1034  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-26 18:20:29.613  6669  6669 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-26 18:20:29.615  1034  1962 W libprocessgroup: failed to open /acct/uid_10004/pid_6267/cgroup.procs: No such file or directory
08-26 18:20:29.615  6932  6932 D DockEventReceiver: finishStartingService: stopping service
08-26 18:20:29.626  6932  6932 D BluetoothInputDevice: Proxy object connected
08-26 18:20:29.627  6932  6932 D HidProfile: Bluetooth service connected
,08-26 18:20:29.629  6932  6932 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 18:20:29.630  6932  6932 D PanProfile: Bluetooth service connected
08-26 18:20:29.631  6932  6932 D BluetoothMap: Proxy object connected
08-26 18:20:29.632  6932  6932 D MapProfile: Bluetooth service connected
08-26 18:20:29.632  6932  6932 D BluetoothMap: getConnectedDevices()
08-26 18:20:29.633  6932  6932 D BluetoothMap: Bluetooth is Not enabled
08-26 18:20:29.633  6932  6932 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 18:20:29.647  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:29.689  6932  6932 D LgDataFeature: LgDataFeature() Constructor: none
08-26 18:20:29.689  6932  6932 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 18:20:29.708  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:29.714  1944  1944 D WfdsService: Supplicant Connection state is changed : false
08-26 18:20:29.714  1944  2286 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 18:20:29.715  1944  2286 D WfdsService: Set the WFDS Monitor: false
08-26 18:20:29.715  1944  2286 D WfdsMonitor: WFDS Monitor is stopped
08-26 18:20:29.715  1034  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 18:20:29.715  1034  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 18:20:29.715  1034  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 18:20:29.715  1034  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 18:20:29.718  6932  6932 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 18:20:29.719  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 18:20:29.719  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:29.722  2479  2479 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:29.727  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:29.728  6932  6932 D BluetoothPermissionRequest: onReceive
08-26 18:20:29.729  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:29.730  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 18:20:29.730  1034  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 18:20:29.730  1034  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 18:20:29.735  6932  6932 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 18:20:29.745  1034  1926 I ActivityManager: Killing 6461:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-26 18:20:29.745  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 18:20:29.766  4274  4274 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-26 18:20:29.766  4274  4274 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 18:20:29.767  4274  4274 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-26 18:20:29.770  1034  1893 W libprocessgroup: failed to open /acct/uid_10008/pid_6461/cgroup.procs: No such file or directory
08-26 18:20:29.780  4274  4274 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:29.780  4274  4274 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 18:20:29.781  4274  4274 V BluetoothFtpService: Ftp Service onStartCommand
08-26 18:20:29.781  4274  4274 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:29.782  4274  4274 V BluetoothFtpService: Ftp Service closeService
08-26 18:20:29.782  4274  4274 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 18:20:29.855  1034  1926 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6980 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-26 18:20:29.859  4274  4274 V BluetoothFtpService: successfully stopped ftp service
08-26 18:20:29.860  4274  4274 V BluetoothFtpService: Ftp Service onDestroy
08-26 18:20:29.860  4274  4274 V BluetoothFtpService: Ftp Service closeService
08-26 18:20:29.862  4274  4274 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 18:20:29.862  4274  4274 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 18:20:29.862  4274  4274 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 18:20:29.862  4274  4274 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:29.862  4274  4274 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 18:20:29.862  4274  4274 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 18:20:29.864  4274  4274 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:29.864  4274  4274 V BluetoothSapService: state: 13
08-26 18:20:29.864  4274  4274 V BluetoothSapService: Stopping SAP server process
08-26 18:20:29.865  4274  4274 V BluetoothSapService: Sap Service closeSapService in
08-26 18:20:29.865  4274  4274 V BluetoothSapService: Close listen Socket : 
08-26 18:20:29.865  4274  4274 V BluetoothSapService: Close rfcomm Socket : 
08-26 18:20:29.865  4274  4274 V BluetoothSapService: Close sapd  Socket : 
,08-26 18:20:29.920  1034  1990 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6997 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 18:20:29.921  4274  4274 V BluetoothSapService: Sap Service closeSapService out
08-26 18:20:29.921  4274  4274 V BluetoothSapService: Sap Service onDestroy
08-26 18:20:29.921  4274  4274 V BluetoothSapService: Sap Service closeSapService in
08-26 18:20:29.921  4274  4274 V BluetoothSapService: Close listen Socket : 
08-26 18:20:29.922  4274  4274 V BluetoothSapService: Close rfcomm Socket : 
08-26 18:20:29.922  4274  4274 V BluetoothSapService: Close sapd  Socket : 
08-26 18:20:29.931  4274  4274 V BluetoothSapService: Sap Service closeSapService out
08-26 18:20:29.957  6980  6980 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 18:20:29.982  6980  6980 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-26 18:20:29.984  6997  6997 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 18:20:30.001  1034  1576 I ActivityManager: Killing 6499:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-26 18:20:30.011  6980  6980 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-26 18:20:30.011  6980  6980 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 18:20:30.012  6980  6980 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 18:20:30.012  6980  6980 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 18:20:30.012  6980  6980 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-26 18:20:30.014  6980  6980 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-26 18:20:30.017  6980  6980 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 18:20:30.035  1034  1956 W libprocessgroup: failed to open /acct/uid_10011/pid_6499/cgroup.procs: No such file or directory
,08-26 18:20:30.045  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 18:20:30.048  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:30.064  6980  6980 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 18:20:30.066  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:30.066  6980  6980 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 18:20:30.069  6980  6980 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 18:20:30.071  6952  6952 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 18:20:30.071  6952  6952 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 18:20:30.071  6952  6952 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 18:20:30.077  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:30.088  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:30.097  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:30.097  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:30.099  6980  6980 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 18:20:30.103  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 18:20:30.107  6952  6952 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 18:20:30.107  6952  6952 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 18:20:30.107  6952  6952 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 18:20:30.111  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:30.123  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:30.137  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:30.138  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 18:20:30.140  6980  6980 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 18:20:30.188  4274  4351 D bt_hci_bdroid: cleanup
08-26 18:20:30.188  4274  4450 I bt_lpm  : LPM is already off!!!
,08-26 18:20:30.189  4274  4632 I bt_userial_mct: exiting userial_read_thread
08-26 18:20:30.189  4274  4632 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 18:20:30.190  4274  4448 W bt-btif : ag scb idx 1 not allocated
08-26 18:20:30.190  4274  4448 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 18:20:30.190  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 18:20:30.190  4274  4448 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 18:20:30.191  4274  4448 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 18:20:30.191  4274  4448 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 18:20:30.192  4274  4351 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 18:20:30.192  4274  4450 I bt_vendor: hw_epilog_process
08-26 18:20:30.193  4274  4351 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 18:20:30.193  4274  4351 D bt_userial_mct: userial_close
08-26 18:20:30.193  4274  4351 E bt_userial_mct: pthread_join() FAILED result:3
08-26 18:20:30.193  4274  4351 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 18:20:30.193  1034  1926 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7017 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-26 18:20:30.314  6952  6952 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 18:20:30.318  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:30.320  4274  4351 D bt_hci_bdroid: set_power 0
08-26 18:20:30.320  4274  4351 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 18:20:30.320  4274  4351 I bt_vendor: bluetooth satus is on
08-26 18:20:30.321  4274  4351 I bt_vendor: bt-vendor : resetting BT status
08-26 18:20:30.321  4274  4351 I bt_vendor: Starting hciattach daemon
08-26 18:20:30.321  4274  4351 I bt_vendor: try to set false
08-26 18:20:30.323  4274  4351 I bt_vendor: Starting hciattach daemon
08-26 18:20:30.323  4274  4351 I bt_vendor: try to set false
08-26 18:20:30.324  4274  4351 I bt_vendor: cleanup
08-26 18:20:30.325  4274  4448 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 18:20:30.325  4274  4351 I GKI_LINUX: GKI_exit_task 0 done
08-26 18:20:30.325  4274  4351 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 18:20:30.326  4274  4348 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-26 18:20:30.329  4274  4274 D HeadsetService: Received stop request...Stopping profile...
08-26 18:20:30.330  4274  4274 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 18:20:30.330  4274  4274 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 18:20:30.330  4274  4274 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc23e3e
08-26 18:20:30.331  4274  4388 D HeadsetStateMachine: Exit Disconnected: -1
08-26 18:20:30.331  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-26 18:20:30.331  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 18:20:30.332  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-26 18:20:30.332  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-26 18:20:30.332  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-26 18:20:30.333  4274  4274 D A2dpService: Received stop request...Stopping profile...
08-26 18:20:30.334  4274  4435 D A2dpStateMachine: Exit Disconnected: -1
08-26 18:20:30.335  4274  4274 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 18:20:30.336  4274  4274 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 18:20:30.336  4274  4274 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 18:20:30.336  4274  4274 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc23e3e
08-26 18:20:30.336  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:30.337  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-26 18:20:30.337  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 18:20:30.338  4274  4274 D HeadsetStateMachine: Unbinding service...
08-26 18:20:30.343  4274  4274 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 18:20:30.343  4274  4274 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 18:20:30.343  4274  4274 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 18:20:30.343  4274  4274 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 18:20:30.344  4274  4274 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 18:20:30.344  4274  4274 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 18:20:30.344  4274  4274 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 18:20:30.344  4274  4348 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 18:20:30.344  4274  4274 D HidService: Received stop request...Stopping profile...
08-26 18:20:30.344  4274  4274 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc23e3e
,08-26 18:20:30.349  6932  6932 D BluetoothInputDevice: Proxy object disconnected
08-26 18:20:30.349  6932  6932 D HidProfile: Bluetooth service disconnected
08-26 18:20:30.349  4274  4274 D HealthService: Received stop request...Stopping profile...
08-26 18:20:30.349  4274  4274 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc23e3e
08-26 18:20:30.352  4274  4274 D PanService: Received stop request...Stopping profile...
08-26 18:20:30.352  4274  4274 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc23e3e
08-26 18:20:30.353  6932  6932 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 18:20:30.353  6932  6932 D PanProfile: Bluetooth service disconnected
08-26 18:20:30.353  4274  4274 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 18:20:30.354  4274  4274 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 18:20:30.354  4274  4274 D BtGatt.GattService: stop()
08-26 18:20:30.354  4274  4274 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 18:20:30.355  4274  4274 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc23e3e
08-26 18:20:30.358  4274  4274 I BluetoothA2dpServiceJni: cleanupNative
08-26 18:20:30.358  4274  4436 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 18:20:30.358  4274  4274 I GKI_LINUX: GKI_exit_task 2 done
,08-26 18:20:30.358  4274  4274 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 18:20:30.359  4274  4274 D BluetoothMapService: Received stop request...Stopping profile...
08-26 18:20:30.359  4274  4274 D BluetoothMapService: stop()
08-26 18:20:30.359  4274  4274 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 18:20:30.359  4274  4274 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 18:20:30.360  7017  7040 W FormManager: Network not available. Please check & try again.
08-26 18:20:30.360  4274  4274 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc23e3e
08-26 18:20:30.361  6932  6932 D BluetoothMap: Proxy object disconnected
08-26 18:20:30.361  6932  6932 D MapProfile: Bluetooth service disconnected
08-26 18:20:30.361  4274  4274 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 18:20:30.361  4274  4274 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 18:20:30.362  4274  4274 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 18:20:30.362  4274  4274 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 18:20:30.362  4274  4274 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 18:20:30.362  4274  4274 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 18:20:30.362  4274  4274 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 18:20:30.363  4274  4274 V BluetoothMapService: Handler(): got msg=4
08-26 18:20:30.363  4274  4274 D BluetoothMapService: MAP Service closeService in
08-26 18:20:30.363  4274  4274 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 18:20:30.363  4274  4274 V BluetoothMapService: MAP Service closeService out
08-26 18:20:30.363  4274  4274 D BluetoothMapService: cleanup()
08-26 18:20:30.363  4274  4274 D BluetoothMapService: MAP Service closeService in
08-26 18:20:30.363  4274  4274 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 18:20:30.363  4274  4274 V BluetoothMapService: MAP Service closeService out
08-26 18:20:30.364  4274  4348 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 18:20:30.364  4274  4348 D BluetoothAdapterProperties: Setting state to 10
08-26 18:20:30.364  4274  4348 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 18:20:30.364  1034  1110 D BluetoothManagerService: Message: 60
08-26 18:20:30.364  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 18:20:30.364  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-26 18:20:30.365  4274  4348 I BluetoothAdapterState: Entering OffState
08-26 18:20:30.365  6932  6948 D BluetoothPan: onBluetoothStateChange on: false
08-26 18:20:30.366  1034  1110 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 18:20:30.366  1034  1110 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 18:20:30.366  1855  3502 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 18:20:30.370  6932  6948 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 18:20:30.371  6932  6947 D BluetoothMap: onBluetoothStateChange: up=false
08-26 18:20:30.372  1855  3501 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 18:20:30.372  1855  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 18:20:30.374  6932  6948 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 18:20:30.375  1034  1110 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 18:20:30.375  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 18:20:30.378  1034  1110 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 18:20:30.378  1034  1110 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 18:20:30.378  1034  1110 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2eb1d4ef mBinding = false
08-26 18:20:30.378  7017  7041 V FormManager: Network unavailable.
08-26 18:20:30.378  1034  1110 D BluetoothManagerService: Sending unbind request.
08-26 18:20:30.380  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 18:20:30.383  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:30.384  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:30.384  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:30.384  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 18:20:30.386  1944  2104 D LGBluetoothAPIService: Message: 2
08-26 18:20:30.386  1944  2104 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2acd3d09 mBinding = false
08-26 18:20:30.387  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 18:20:30.388  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 18:20:30.388  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 18:20:30.388  6932  6932 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 18:20:30.388  4274  4351 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 18:20:30.388  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 18:20:30.389  1603  1603 D BluetoothAdapter: 399480497: getState() :  mService = null. Returning STATE_OFF
08-26 18:20:30.389  4274  4274 I GKI_LINUX: GKI_exit_task 1 done
08-26 18:20:30.389  4274  4274 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 18:20:30.389  1603  1603 D BluetoothAdapter: 399480497: getState() :  mService = null. Returning STATE_OFF
08-26 18:20:30.389  4274  4274 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 18:20:30.389  4274  4274 I art     : --- WEIRD: removing null entry 246
08-26 18:20:30.389  4274  4274 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-26 18:20:30.389  4274  4274 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 18:20:30.390  1944  2104 D LGBluetoothAPIService: Sending unbind request.
08-26 18:20:30.390  4274  4274 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 18:20:30.393  4274  4274 I art     : System.exit called, status: 0
08-26 18:20:30.393  4274  4274 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 18:20:30.401  7017  7041 V FormManager: Network unavailable.
,08-26 18:20:30.402  6932  6932 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 18:20:30.403  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 18:20:30.403  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 18:20:30.403  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 18:20:30.403  6932  6932 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 18:20:30.403  6932  6932 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 18:20:30.404  6932  6932 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 18:20:30.406  6932  6932 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 18:20:30.406  6932  6932 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 18:20:30.408  6932  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 18:20:30.414   312  2172 V AudioFlinger: 4274 died, releasing its sessions
08-26 18:20:30.414   312  2172 V AudioFlinger:  pid 1855 @ 0
08-26 18:20:30.414   312  2172 V AudioFlinger:  pid 3203 @ 1
08-26 18:20:30.414   312  2172 V AudioFlinger:  pid 3203 @ 2
,08-26 18:20:30.417  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 18:20:30.417  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 18:20:30.419  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 18:20:30.463  1034  1908 I ActivityManager: Process com.android.bluetooth (pid 4274) has died
,08-26 18:20:30.463  1034  1908 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-26 18:20:30.473  6932  6932 D DockEventReceiver: finishStartingService: stopping service
08-26 18:20:30.474  6932  6932 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 18:20:30.479  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 18:20:30.481  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 18:20:30.491  1034  1907 I ActivityManager: Killing 5952:com.android.contacts/u0a19 (adj 15): empty #17
,08-26 18:20:30.503  4752  7051 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 18:20:30.503  4752  7053 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 18:20:30.508  4752  7053 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 18:20:30.598  1034  1051 W libprocessgroup: failed to open /acct/uid_10019/pid_5952/cgroup.procs: No such file or directory
,08-26 18:20:30.607  2176  2176 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19986
08-26 18:20:30.643  6952  6952 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 18:20:30.643  6952  6952 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 18:20:30.643  6952  6952 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 18:20:30.646  7017  7056 W FormManager: Network not available. Please check & try again.
08-26 18:20:30.660  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 18:20:30.667  7017  7057 V FormManager: Network unavailable.
,08-26 18:20:30.676  7017  7057 V FormManager: Network unavailable.
08-26 18:20:30.677  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:30.678  6932  6932 D BluetoothPermissionRequest: onReceive
08-26 18:20:30.684  6932  6932 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-26 18:20:30.686  6932  6932 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 18:20:30.693  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 18:20:30.763  1034  1990 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7058 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 18:20:30.803  6980  6980 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-26 18:20:30.805  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 18:20:30.806  6980  6980 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-26 18:20:30.834  7058  7058 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 18:20:30.835  7058  7058 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 18:20:30.835  7058  7058 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-26 18:20:30.836  7058  7058 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 18:20:30.856  7058  7058 D BluetoothAdapterApp: Loading JNI Library
,08-26 18:20:30.865  6980  6980 D LgDataFeature: LgDataFeature() Constructor: none
08-26 18:20:30.865  6980  6980 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 18:20:30.875  6980  6980 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-26 18:20:30.878  6980  6980 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 18:20:30.878  6980  6980 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-26 18:20:30.878  6980  6980 V SoundPool: doLoad: loading sample sampleID=1
08-26 18:20:30.878  6980  6980 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 18:20:30.883  6827  6827 D UEI.SmartControl: QS Service created
08-26 18:20:30.886  6980  7077 V SoundPool: Start decode
08-26 18:20:30.886  6980  7077 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 18:20:30.887   312  1383 V MediaPlayerService: decode(22, 10857164, 17813)
08-26 18:20:30.887   312  1383 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 18:20:30.888   312  1383 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 18:20:30.888   312  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 18:20:30.888   312  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 18:20:30.888   312  1383 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 18:20:30.888   312  1383 V MediaPlayerService: player type = 3
08-26 18:20:30.888   312  1383 V AwesomePlayer: AwesomePlayer create()
08-26 18:20:30.889   312  1383 V AwesomePlayer: reset_l() 
08-26 18:20:30.889   312  1383 V AwesomePlayer: cancelPlayerEvents
08-26 18:20:30.889   312  1383 V AwesomePlayer: setAudioSink() 
08-26 18:20:30.889   312  1383 V AwesomePlayer: reset_l() 
08-26 18:20:30.889   312  1383 V AudioCache: notify(0xb5474480, 8, 0, 0)
08-26 18:20:30.889   312  1383 V AudioCache: ignored
08-26 18:20:30.889   312  1383 V AwesomePlayer: cancelPlayerEvents
08-26 18:20:30.889   312  1383 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
,08-26 18:20:30.890   312  1383 V AwesomePlayer: setDataSource_l dataSource
08-26 18:20:30.890   312  1383 V LGParserOSAL: SniffLGParser start
08-26 18:20:30.890   312  1383 V LGParserOSAL: MainType:5, SubType=0
08-26 18:20:30.890   312  1383 V LGParserOSAL: #### check Mime : application/ogg
08-26 18:20:30.890   312  1383 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 18:20:30.890   312  1383 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 18:20:30.894  7058  7058 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@35d157a7 Instance Count = 1
08-26 18:20:30.896  6980  6980 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 18:20:30.899  7058  7058 D BluetoothAdapterApp: onCreate
08-26 18:20:30.899  6980  6980 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-26 18:20:30.900  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 18:20:30.922  6980  6980 V LGMDMManager: Create singleton instance
08-26 18:20:30.922  7058  7058 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 18:20:30.922  7058  7058 D ProfileConfigQcom: Adding HeadsetService
08-26 18:20:30.923  7058  7058 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 18:20:30.923  7058  7058 D ProfileConfigQcom: Adding A2dpService
08-26 18:20:30.923  7058  7058 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 18:20:30.923  7058  7058 D ProfileConfigQcom: Adding HidService
08-26 18:20:30.923  7058  7058 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 18:20:30.924  7058  7058 D ProfileConfigQcom: Adding HealthService
08-26 18:20:30.924  7058  7058 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 18:20:30.925  7058  7058 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 18:20:30.925  7058  7058 D ProfileConfigQcom: Adding PanService
08-26 18:20:30.925  6827  6827 I UEI.SmartControl: Service initServices...
08-26 18:20:30.925  7058  7058 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 18:20:30.925  7058  7058 D ProfileConfigQcom: Adding GattService
08-26 18:20:30.925  6827  6827 D UEI.SmartControl: QS start get config
08-26 18:20:30.926  7058  7058 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 18:20:30.926  7058  7058 D ProfileConfigQcom: Adding BluetoothMapService
08-26 18:20:30.926  7058  7058 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 18:20:30.928  7058  7058 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 18:20:30.932  6932  6932 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-26 18:20:30.934  7058  7058 V LGMDMManagerInternal: Create singleton instance
08-26 18:20:30.946   312  1383 V LGParserOSAL: supported mime: application/ogg
08-26 18:20:30.946   312  1383 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 18:20:30.946   312  1383 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 18:20:30.946   312  1383 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 18:20:30.946   312  1383 V AwesomePlayer: AudioTrack Setting
08-26 18:20:30.946   312  1383 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 18:20:30.946   312  1383 V AwesomePlayer: setAudioSource() 
08-26 18:20:30.946   312  1383 V MediaPlayerService: prepare
08-26 18:20:30.946   312  1383 V AwesomePlayer: prepareAsync_l() 
08-26 18:20:30.946   312  1383 V MediaPlayerService: wait for prepare
08-26 18:20:30.946   312  7079 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 18:20:30.946   312  7079 V AwesomePlayer: initAudioDecoder() 
08-26 18:20:30.946   312  7079 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 18:20:30.946   312  7079 V AudioSystem: isOffloadSupported()
08-26 18:20:30.946   312  7079 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 18:20:30.946   312  7079 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 18:20:30.947   312  7079 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 18:20:30.947   312  7079 V AwesomePlayer: getUseOffload() = 0 
08-26 18:20:30.947   312  7079 V OMXCodec: OMXCodec::Create
08-26 18:20:30.947   312  7079 V OMXCodec: findMatchingCodecs()
08-26 18:20:30.947   312  7079 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 18:20:30.947   312  7079 V OMXCodec: matchingCodecs.size()=1
08-26 18:20:30.947   312  7079 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-26 18:20:30.951   312  7079 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 18:20:30.951   312  7079 V LGCodecAdapter: LG Codec Adapter start
08-26 18:20:30.951   312  7079 V OMXCodec: OMXCodec Createtor
08-26 18:20:30.951   312  7079 V OMXCodec: setComponentRole
08-26 18:20:30.951   312  7079 V OMXCodec: configureCodec protected=0
08-26 18:20:30.951   312  7079 V LGCodecAdapter: called getLGCodecSpecificData
08-26 18:20:30.951   312  7079 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 18:20:30.951   312  7079 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 18:20:30.951   312  7079 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 18:20:30.951   312  7079 V LGCodecOSAL: Not support LGCodec
08-26 18:20:30.951   312  7079 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 18:20:30.951   312  7079 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 18:20:30.951   312  7079 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 18:20:30.951   312  7079 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 18:20:30.951   312  7079 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 18:20:30.951   312  7079 V AudioSystem: isOffloadSupported()
08-26 18:20:30.951   312  7079 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 18:20:30.951   312  7079 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 18:20:30.951   312  7079 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 18:20:30.951   312  7079 V OMXCodec: init()
08-26 18:20:30.951   312  7079 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 18:20:30.951   312  7079 V OMXCodec: allocateBuffers
08-26 18:20:30.951   312  7079 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 18:20:30.951   312  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 18:20:30.952   312  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-26 18:20:30.952   312  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-26 18:20:30.952   312  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-26 18:20:30.952   312  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-26 18:20:30.952   312  7079 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 18:20:30.952   312  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 18:20:30.952   312  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-26 18:20:30.952   312  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-26 18:20:30.952   312  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-26 18:20:30.952   312  7079 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-26 18:20:30.952   312  7079 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 18:20:30.960   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 18:20:30.960   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 18:20:30.960   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 18:20:30.960   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 18:20:30.960   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 18:20:30.960   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
08-26 18:20:30.960   312  7079 V OMXCodec: init() mAsyncCompletion wait free! 
08-26 18:20:30.960   312  7079 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 18:20:30.960   312  7079 V AudioCache: notify(0xb5474480, 5, 0, 0)
08-26 18:20:30.960   312  7079 V AudioCache: ignored
08-26 18:20:30.960   312  7079 V AudioCache: notify(0xb5474480, 1, 0, 0)
08-26 18:20:30.960   312  7079 V AudioCache: prepared
08-26 18:20:30.960   312  1383 V AudioCache: wait - success
08-26 18:20:30.960   312  1383 V MediaPlayerService: start
08-26 18:20:30.960   312  1383 V AwesomePlayer: play_l() 
08-26 18:20:30.960   312  1383 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 18:20:30.960   312  1383 V AwesomePlayer: createAudioPlayer_l
08-26 18:20:30.960   312  1383 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 18:20:30.960   312  1383 V AwesomePlayer: startAudioPlayer_l() 
08-26 18:20:30.960   312  1383 D AudioPlayer: start of Playback, useOffload 0
08-26 18:20:30.960   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,08-26 18:20:30.960   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 18:20:30.964   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 18:20:30.964   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 18:20:30.964   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 18:20:30.964   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 18:20:30.964   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 18:20:30.964   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 18:20:30.964   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
,08-26 18:20:30.964   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-26 18:20:30.964   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-26 18:20:30.964   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 18:20:30.964   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
08-26 18:20:30.964   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 18:20:30.964   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
08-26 18:20:30.965   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 18:20:30.965   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 18:20:30.965   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 18:20:30.965   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 18:20:30.965   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-26 18:20:30.965   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-26 18:20:30.965   312  7081 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 18:20:30.965   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 18:20:30.965   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-26 18:20:30.965   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-26 18:20:30.965   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-26 18:20:30.965   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on output port
08-26 18:20:30.970   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 18:20:30.970   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 18:20:30.972   312  1383 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 18:20:30.972   312  1383 V AudioCache: notify(0xb5474480, 6, 0, 0)
08-26 18:20:30.972   312  1383 V AudioCache: ignored
08-26 18:20:30.973   312  1383 V MediaPlayerService: wait for playback complete
08-26 18:20:30.973   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.973   312  7082 V AudioCache: memcpy(0xaf0f9000, 0xb16f0000, 4096)
08-26 18:20:30.975   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.975   312  7082 V AudioCache: memcpy(0xaf0fa000, 0xb16f0000, 4096)
08-26 18:20:30.975   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.975   312  7082 V AudioCache: memcpy(0xaf0fb000, 0xb16f0000, 4096)
08-26 18:20:30.978   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.978   312  7082 V AudioCache: memcpy(0xaf0fc000, 0xb16f0000, 4096)
08-26 18:20:30.978   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.978   312  7082 V AudioCache: memcpy(0xaf0fd000, 0xb16f0000, 4096)
08-26 18:20:30.978   312  7082 V AudioCache: write(0xb16f0000, 4096)
,08-26 18:20:30.978   312  7082 V AudioCache: memcpy(0xaf0fe000, 0xb16f0000, 4096)
08-26 18:20:30.978   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.978   312  7082 V AudioCache: memcpy(0xaf0ff000, 0xb16f0000, 4096)
08-26 18:20:30.979   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.979   312  7082 V AudioCache: memcpy(0xaf100000, 0xb16f0000, 4096)
08-26 18:20:30.980   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.980   312  7082 V AudioCache: memcpy(0xaf101000, 0xb16f0000, 4096)
08-26 18:20:30.981   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.981   312  7082 V AudioCache: memcpy(0xaf102000, 0xb16f0000, 4096)
08-26 18:20:30.982   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.982   312  7082 V AudioCache: memcpy(0xaf103000, 0xb16f0000, 4096)
08-26 18:20:30.983   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.983   312  7082 V AudioCache: memcpy(0xaf104000, 0xb16f0000, 4096)
08-26 18:20:30.984   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.984   312  7082 V AudioCache: memcpy(0xaf105000, 0xb16f0000, 4096)
08-26 18:20:30.984   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.984   312  7082 V AudioCache: memcpy(0xaf106000, 0xb16f0000, 4096)
08-26 18:20:30.985   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.985   312  7082 V AudioCache: memcpy(0xaf107000, 0xb16f0000, 4096)
08-26 18:20:30.986   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.986   312  7082 V AudioCache: memcpy(0xaf108000, 0xb16f0000, 4096)
08-26 18:20:30.986   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.986   312  7082 V AudioCache: memcpy(0xaf109000, 0xb16f0000, 4096)
08-26 18:20:30.987   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.987   312  7082 V AudioCache: memcpy(0xaf10a000, 0xb16f0000, 4096)
08-26 18:20:30.988   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.988   312  7082 V AudioCache: memcpy(0xaf10b000, 0xb16f0000, 4096)
08-26 18:20:30.988   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.988   312  7082 V AudioCache: memcpy(0xaf10c000, 0xb16f0000, 4096)
08-26 18:20:30.989   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.989   312  7082 V AudioCache: memcpy(0xaf10d000, 0xb16f0000, 4096)
08-26 18:20:30.990   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.990   312  7082 V AudioCache: memcpy(0xaf10e000, 0xb16f0000, 4096)
08-26 18:20:30.990   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.990   312  7082 V AudioCache: memcpy(0xaf10f000, 0xb16f0000, 4096)
08-26 18:20:30.991   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.991   312  7082 V AudioCache: memcpy(0xaf110000, 0xb16f0000, 4096)
08-26 18:20:30.992   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.992   312  7082 V AudioCache: memcpy(0xaf111000, 0xb16f0000, 4096)
08-26 18:20:30.993   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.993   312  7082 V AudioCache: memcpy(0xaf112000, 0xb16f0000, 4096)
08-26 18:20:30.993   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.993   312  7082 V AudioCache: memcpy(0xaf113000, 0xb16f0000, 4096)
08-26 18:20:30.994   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.994   312  7082 V AudioCache: memcpy(0xaf114000, 0xb16f0000, 4096)
08-26 18:20:30.995   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.995   312  7082 V AudioCache: memcpy(0xaf115000, 0xb16f0000, 4096)
08-26 18:20:30.995   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.995   312  7082 V AudioCache: memcpy(0xaf116000, 0xb16f0000, 4096)
08-26 18:20:30.996   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.996   312  7082 V AudioCache: memcpy(0xaf117000, 0xb16f0000, 4096)
08-26 18:20:30.997   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.997   312  7082 V AudioCache: memcpy(0xaf118000, 0xb16f0000, 4096)
08-26 18:20:30.998   312  7082 V Au,dioCache: write(0xb16f0000, 4096)
08-26 18:20:30.998   312  7082 V AudioCache: memcpy(0xaf119000, 0xb16f0000, 4096)
08-26 18:20:30.998   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.998   312  7082 V AudioCache: memcpy(0xaf11a000, 0xb16f0000, 4096)
08-26 18:20:30.999   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:30.999   312  7082 V AudioCache: memcpy(0xaf11b000, 0xb16f0000, 4096)
08-26 18:20:31.000   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:31.000   312  7082 V AudioCache: memcpy(0xaf11c000, 0xb16f0000, 4096)
08-26 18:20:31.000   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:31.000   312  7082 V AudioCache: memcpy(0xaf11d000, 0xb16f0000, 4096)
08-26 18:20:31.001   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:31.001   312  7082 V AudioCache: memcpy(0xaf11e000, 0xb16f0000, 4096)
08-26 18:20:31.002   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:31.002   312  7082 V AudioCache: memcpy(0xaf11f000, 0xb16f0000, 4096)
08-26 18:20:31.003   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:31.003   312  7082 V AudioCache: memcpy(0xaf120000, 0xb16f0000, 4096)
08-26 18:20:31.004   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:31.004   312  7082 V AudioCache: memcpy(0xaf121000, 0xb16f0000, 4096)
08-26 18:20:31.004   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:31.004   312  7082 V AudioCache: memcpy(0xaf122000, 0xb16f0000, 4096)
08-26 18:20:31.005   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:31.005   312  7082 V AudioCache: memcpy(0xaf123000, 0xb16f0000, 4096)
08-26 18:20:31.006   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:31.006   312  7082 V AudioCache: memcpy(0xaf124000, 0xb16f0000, 4096)
08-26 18:20:31.007   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:31.007   312  7082 V AudioCache: memcpy(0xaf125000, 0xb16f0000, 4096)
08-26 18:20:31.007   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:31.007   312  7082 V AudioCache: memcpy(0xaf126000, 0xb16f0000, 4096)
08-26 18:20:31.008   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:31.008   312  7082 V AudioCache: memcpy(0xaf127000, 0xb16f0000, 4096)
08-26 18:20:31.008   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:31.009   312  7082 V AudioCache: memcpy(0xaf128000, 0xb16f0000, 4096)
08-26 18:20:31.009   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:31.009   312  7082 V AudioCache: memcpy(0xaf129000, 0xb16f0000, 4096)
08-26 18:20:31.010   312  7082 V AudioCache: write(0xb16f0000, 4096)
08-26 18:20:31.010   312  7082 V AudioCache: memcpy(0xaf12a000, 0xb16f0000, 4096)
08-26 18:20:31.010   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-26 18:20:31.010   312  7082 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 18:20:31.010   312  7082 V AwesomePlayer: postAudioEOS() 
08-26 18:20:31.010   312  7082 V AudioCache: write(0xb16f0000, 280)
08-26 18:20:31.010   312  7082 V AudioCache: memcpy(0xaf12b000, 0xb16f0000, 280)
,08-26 18:20:31.012   312  7079 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 18:20:31.012   312  7079 V AwesomePlayer: onStreamDone
08-26 18:20:31.012   312  7079 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 18:20:31.012   312  7079 V AudioCache: notify(0xb5474480, 2, 0, 0)
08-26 18:20:31.012   312  7079 V AudioCache: playback complete
08-26 18:20:31.012   312  7079 V AwesomePlayer: pause_l() 
08-26 18:20:31.012   312  7079 V AudioCache: notify(0xb5474480, 7, 0, 0)
08-26 18:20:31.012   312  7079 V AudioCache: ignored
08-26 18:20:31.012   312  7079 V AwesomePlayer: cancelPlayerEvents
08-26 18:20:31.012   312  7079 D AudioPlayer: Pause Playback at 1068125
08-26 18:20:31.013   312  1383 V AudioCache: wait - success
08-26 18:20:31.013   312  1383 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 18:20:31.013   312  1383 V AwesomePlayer: reset_l() 
08-26 18:20:31.013   312  1383 V AudioCache: notify(0xb5474480, 8, 0, 0)
08-26 18:20:31.013   312  1383 V AudioCache: ignored
08-26 18:20:31.013   312  1383 V AwesomePlayer: cancelPlayerEvents
08-26 18:20:31.013   312  1383 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-26 18:20:31.013   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 18:20:31.013   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 18:20:31.013   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 18:20:31.013   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 18:20:31.014  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:31.018   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 18:20:31.019  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 1
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 18:20:31.019   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-26 18:20:31.019   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCo,mpletion wait free!!
08-26 18:20:31.019   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 18:20:31.020   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 18:20:31.020   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 18:20:31.020  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 18:20:31.020   312  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 18:20:31.020   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 18:20:31.020   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 18:20:31.020   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 18:20:31.020  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 18:20:31.021   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-26 18:20:31.021   312  1383 D AudioPlayer: AudioPlayer releasing audio source
08-26 18:20:31.021   312  1383 D AudioPlayer: AudioPlayer done releasing audio source
08-26 18:20:31.021   312  1383 V AwesomePlayer: reset_l() 
08-26 18:20:31.021   312  1383 V AwesomePlayer: cancelPlayerEvents
08-26 18:20:31.021   312  1383 V AwesomePlayer: ~AwesomePlayer call
08-26 18:20:31.021  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:31.021  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 18:20:31.022   312  1383 V AwesomePlayer: reset_l() 
08-26 18:20:31.022   312  1383 V AwesomePlayer: cancelPlayerEvents
08-26 18:20:31.022  6980  7077 V SoundPool: close(31)
08-26 18:20:31.022  6980  7077 V SoundPool: pointer = 0x9fe89000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 18:20:31.023  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 18:20:31.024  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-26 18:20:31.026  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3458
,08-26 18:20:31.028  6997  6997 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-26 18:20:31.217  6827  6827 I UEI.SmartControl: Supports setup maps: true
,08-26 18:20:31.220  6827  6827 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 18:20:31.220  6827  6827 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 18:20:31.220  6827  6827 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 18:20:31.220  6827  6827 I UEI.SmartControl: ### init IR Blaster...
08-26 18:20:31.224  6827  6827 D serial_port: Configuring serial port
08-26 18:20:31.224  6827  6827 E UEI.SmartControl: UEIBLaster setting for 616
08-26 18:20:31.224  6827  6827 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 18:20:31.224  6827  6827 I UEI.SmartControl: configuring settings for MAXQ616
08-26 18:20:31.224  6827  6827 I UEI.SmartControl: Get version...
08-26 18:20:31.243  6827  7084 D UEI.SmartControl: serial port data available: 21
,08-26 18:20:31.269  6827  6827 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-26 18:20:31.270  6827  6827 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 18:20:31.270  6827  6827 I UEI.SmartControl: QS saving settings...
08-26 18:20:31.272  6827  6827 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 18:20:31.288  6827  7084 D UEI.SmartControl: serial port data available: 4
,08-26 18:20:31.321  6827  7090 I UEI.SmartControl: Device manager: loading config....
,08-26 18:20:31.323  6827  7090 D UEI.SmartControl: ----------- loading internal config...
08-26 18:20:31.323  6827  6827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 18:20:31.327  6827  6827 E UEI.SmartControl: Services init done
08-26 18:20:31.327  6827  6827 D UEI.SmartControl: QS Service init finished
08-26 18:20:31.330  6827  6827 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 18:20:31.330  6827  6827 D UEI.SmartControl: QS Service version code: 201091
08-26 18:20:31.331  6827  6827 D UEI.SmartControl: Service requested: Control
08-26 18:20:31.338  6827  7090 E UEI.SmartControl: Loading SETTINGS...
,08-26 18:20:31.342  6827  6827 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-26 18:20:31.347  6827  6827 D UEI.SmartControl: Internal service binding...
08-26 18:20:31.350  6980  6980 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-26 18:20:31.362  6827  6843 I UEI.SmartControl: ------ IControl API: 11
08-26 18:20:31.362  6827  6843 D UEI.SmartControl: File observer start...
08-26 18:20:31.363  6827  6843 E UEI.SmartControl: IR Port is disabled: false
08-26 18:20:31.363  6827  7090 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 18:20:31.364  6827  6843 D UEI.SmartControl: Starting file observer...
08-26 18:20:31.366  6827  6843 I UEI.SmartControl: Registering callback...
08-26 18:20:31.367  6827  6842 I UEI.SmartControl: ------ IControl API: 19
08-26 18:20:31.368  6827  6842 I UEI.SmartControl: Registering Services Ready callback...
,08-26 18:20:31.379  6827  7089 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 18:20:31.379  6827  7089 D UEI.SmartControl: -----service ready thread exits
08-26 18:20:31.381  6980  6995 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-26 18:20:31.383  6980  7075 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 18:20:31.383  6980  7075 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 18:20:31.384  6980  6980 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 18:20:31.384  6980  6980 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-26 18:20:31.385  6827  6843 I UEI.SmartControl: ------ IControl API: 8
08-26 18:20:31.386  6980  6980 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 18:20:31.387  6980  6980 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 18:20:31.387  6980  6980 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 18:20:31.387  6980  6980 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-26 18:20:31.388  6980  6980 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 18:20:31.389  6980  6980 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-26 18:20:31.391  6980  6980 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-26 18:20:31.394  6980  6980 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-26 18:20:31.396  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-26 18:20:31.398  6980  6980 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 18:20:31.398  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 18:20:31.399  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 18:20:31.400  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-26 18:20:31.401  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-26 18:20:31.402  6980  6980 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472228431401]
08-26 18:20:31.405  6980  6980 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-26 18:20:31.407  1034  1962 I ActivityManager: Killing 6552:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-26 18:20:31.431  6980  7095 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-26 18:20:31.463  1034  1962 I ActivityManager: Killing 6523:com.lge.email/u0a23 (adj 15): empty #18
,08-26 18:20:31.495  1034  1050 W libprocessgroup: failed to open /acct/uid_10027/pid_6552/cgroup.procs: No such file or directory
,08-26 18:20:31.498  1034  1656 W libprocessgroup: failed to open /acct/uid_10023/pid_6523/cgroup.procs: No such file or directory
08-26 18:20:31.504  6980  6980 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-26 18:20:31.506  6980  6980 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 18:20:31.507  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-26 18:20:31.508  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-26 18:20:31.509  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-26 18:20:31.510  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-26 18:20:31.511  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-26 18:20:31.522  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-26 18:20:32.257  1034  1990 D WifiServiceImplEx: setWifiEnabled: true pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-26 18:20:32.258  1034  1990 D WifiService: setWifiEnabled: true pid=6669, uid=10118
,08-26 18:20:32.259  1034  1990 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 18:20:32.289  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 18:20:32.290  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 18:20:32.290  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 18:20:32.291  1034  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-26 18:20:32.291  1034  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-26 18:20:32.292  1034  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-26 18:20:32.292  1034  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 18:20:32.292  1034  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 18:20:32.292  1034  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 18:20:32.292  1034  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 18:20:32.292  1034  1539 E WifiHW  : unknown target_country: EU , set to default
08-26 18:20:32.292  1034  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 18:20:32.292  1034  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 18:20:32.293  1034  1539 I WifiUtil: gEnableBmps=1
08-26 18:20:32.298  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:32.305  1034  1110 D Tethering: MasterInitialState.processMessage what=3
,08-26 18:20:32.311  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:32.317  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:32.319  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:32.324  1034  1110 D Tethering: MasterInitialState.processMessage what=3
08-26 18:20:32.333  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:32.336  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:32.336  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:32.338  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 18:20:32.347  5843  5843 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 18:20:32.354  6410  6440 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 18:20:32.355  5843  5843 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 18:20:32.383  2140  2140 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:32.421  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:32.459  1034  1962 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7114 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-26 18:20:32.464  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:32.464  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 18:20:32.542  7114  7114 I AppUp4:AppBoxCP: onCreate
,08-26 18:20:32.543  7114  7114 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-26 18:20:32.553  7114  7114 I AppUp4:DB:  setFingerPrint start
08-26 18:20:32.554  7114  7114 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-26 18:20:32.563  7114  7114 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-26 18:20:32.563  7114  7114 I AppUp4:DB:  SDK version = 21
08-26 18:20:32.563  7114  7114 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-26 18:20:32.565  7114  7114 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-26 18:20:32.567  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 18:20:32.567  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:32.569  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 18:20:32.570  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 18:20:32.580  7114  7114 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 18:20:32.622  7114  7114 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 18:20:32.623  7114  7114 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 18:20:32.632  7114  7114 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@380b1ef9
08-26 18:20:32.632  7114  7114 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 18:20:32.632  7114  7114 D AppUp4:CustFacade: isPhone : true
08-26 18:20:32.633  7114  7114 D AppUp4:CustModeStarterReceiver: begin check event
08-26 18:20:32.633  7114  7114 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-26 18:20:32.634  7114  7114 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-26 18:20:32.634  7114  7134 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-26 18:20:32.635  7114  7134 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-26 18:20:32.635  7114  7134 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-26 18:20:32.636  1034  1926 I ActivityManager: Killing 6580:com.android.vending/u0a44 (adj 15): empty #17
,08-26 18:20:32.738  1034  1051 W libprocessgroup: failed to open /acct/uid_10044/pid_6580/cgroup.procs: No such file or directory
,08-26 18:20:32.743  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:32.746  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 18:20:32.751  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 18:20:32.757  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 18:20:32.775  4752  7139 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 18:20:32.783  4752  7140 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:32.783  4752  7140 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 18:20:32.851  1034  2035 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7141 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-26 18:20:32.877   339   339 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 472us total 27.162ms
,08-26 18:20:32.899   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 21.077ms
,08-26 18:20:32.921   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 457us total 20.316ms
,08-26 18:20:32.929  7141  7141 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 18:20:32.930  7141  7141 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 18:20:32.931  7141  7141 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 18:20:32.932  7141  7141 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 18:20:33.022  7141  7141 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-26 18:20:33.038  7141  7141 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-26 18:20:33.065  1034  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 18:20:33.065  1034  1110 D Tethering: InitialState.processMessage what=4
08-26 18:20:33.065  1034  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 18:20:33.070   307   889 D SoftapController: Softap fwReload - Ok
08-26 18:20:33.071  1034  1539 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (772ms)
08-26 18:20:33.074   307   889 D CommandListener: Setting iface cfg
08-26 18:20:33.074   307   889 D CommandListener: Trying to bring down wlan0
08-26 18:20:33.075   307   889 D CommandListener: Clearing all IP addresses on wlan0
08-26 18:20:33.077  1034  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-26 18:20:33.077  7167  7167 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:33.077  7167  7167 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:33.081  1034  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 18:20:33.081  1034  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 18:20:33.081  1034  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 18:20:33.085  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 18:20:33.087  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-26 18:20:33.093  1034  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 18:20:33.093  1034  1539 D WifiMonitor: connecting to supplicant
08-26 18:20:33.103  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:33.105  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:33.112  7167  7167 I wpa_supplicant: Successfully initialized wpa_supplicant
08-26 18:20:33.112  7141  7141 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 18:20:33.114  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 18:20:33.143  7167  7167 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 18:20:33.143  7167  7167 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-26 18:20:33.154  7141  7141 D LgDataFeature: LgDataFeature() Constructor: none
08-26 18:20:33.154  7141  7141 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 18:20:33.245  7167  7167 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 18:20:33.278  7141  7141 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 18:20:33.322  7167  7167 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-26 18:20:33.326  3203  3203 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 18:20:33.326  3203  3203 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:33.326  3203  3203 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 18:20:33.335  7167  7167 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-26 18:20:33.336  1034  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 18:20:33.337  1034  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,08-26 18:20:33.337  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 18:20:33.337  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 18:20:33.337  1034  7180 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 18:20:33.337  1034  7180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 18:20:33.337  1034  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 18:20:33.337  7141  7141 I HubEmail: JNI_OnLoad()
08-26 18:20:33.337  7141  7141 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 18:20:33.337  7141  7141 I HubEmail: registerNatives()
08-26 18:20:33.337  7141  7141 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 18:20:33.337  7141  7141 I HubEmail: registerNativeMethods()
08-26 18:20:33.337  7141  7141 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-26 18:20:33.337  1034  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 18:20:33.338  7141  7141 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-26 18:20:33.338  1034  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:33.338  1034  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:33.339  1034  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 18:20:33.339  1034  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 18:20:33.339  1034  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 18:20:33.339  1034  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 18:20:33.339  1034  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 18:20:33.377  1034  1956 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7182 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-26 18:20:33.379  1034  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 18:20:33.379  1034  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 18:20:33.379  1034  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 18:20:33.380  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:33.380  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:33.380  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:33.380  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:33.380  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 18:20:33.381  1034  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 18:20:33.382  1034  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-26 18:20:33.382  1034  1539 D WifiConfigStore: Loading config and enabling all networks 
08-26 18:20:33.382  1034  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 18:20:33.383  7017  7178 W FormManager: Network not available. Please check & try again.
08-26 18:20:33.384  1034  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 18:20:33.384  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:33.385  1944  1944 D WfdService: Waiting for WifiP2p enabling
08-26 18:20:33.388  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 18:20:33.389  1034  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 18:20:33.390  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 18:20:33.390  1034  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-26 18:20:33.390  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:33.390  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:33.390  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:33.390  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:33.390  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:33.390  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:33.390  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:33.390  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:33.391  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:33.391  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:33.394  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:33.394  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:33.394  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:33.394  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:33.394  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:33.394  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:33.394  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:33.394  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:33.394  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:33.394  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:33.394  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:33.396  7141  7181 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:33.398  7017  7179 V FormManager: Network unavailable.
08-26 18:20:33.399  1034  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 18:20:33.400  1034  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 18:20:33.400  1034  1539 D WifiStateMachine: enableVerboseLogging : level 2
08-26 18:20:33.400  1034  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 18:20:33.401  1034  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 18:20:33.401  1034  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 18:20:33.401  1034  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 18:20:33.401  1034  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 18:20:33.401  7017  7179 V FormManager: Network unavailable.
08-26 18:20:33.401  1034  1539 D WifiNa,tive-wlan0: SET model_name LG-D855: returned true
08-26 18:20:33.401  1034  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,08-26 18:20:33.402  1034  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 18:20:33.402  1034  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 18:20:33.402  1034  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 18:20:33.402  1034  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 18:20:33.403  1034  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 18:20:33.403  1034  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 18:20:33.403  1034  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 18:20:33.404  1944  1944 D WfdsService: Supplicant Connection state is changed : true
08-26 18:20:33.404  1944  2286 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 18:20:33.404  1944  2286 D WfdsService: Set the WFDS Monitor: true
08-26 18:20:33.404  1944  2286 D WfdsMonitor: WfdsMonitorThread create
,08-26 18:20:33.404  1944  2286 D WfdsMonitor: WFDS Monitor is created and started
08-26 18:20:33.404  1034  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 18:20:33.404  1944  2286 D WfdsService: WiFi: Supplicant connection re-established
08-26 18:20:33.404  1034  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 18:20:33.405  1034  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 18:20:33.405  1034  1539 D WifiNative-HAL: Setting external_sim to 1
08-26 18:20:33.405  1034  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 18:20:33.405  1034  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 18:20:33.405  1034  1539 I WifiNative-HAL: startHal
08-26 18:20:33.405  1034  1539 D wifi    : setting scan oui 0xaf68e780
08-26 18:20:33.406  1034  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 18:20:33.406  1034  1539 I WifiNative-HAL: startHal
08-26 18:20:33.406  1034  1539 D wifi    : setting scan oui 0xaf68e780
08-26 18:20:33.406  1034  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 18:20:33.407  1034  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 18:20:33.407  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 18:20:33.407  7167  7167 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 18:20:33.408  1034  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 18:20:33.408  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 18:20:33.408  7167  7167 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 18:20:33.408  1034  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 18:20:33.408  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 18:20:33.408  7167  7167 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 18:20:33.408  1034  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 18:20:33.408  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 18:20:33.409  7167  7167 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 18:20:33.409  1034  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 18:20:33.409  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 18:20:33.409  7167  7167 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 18:20:33.409  1034  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 18:20:33.409  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 18:20:33.409  7167  7167 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 18:20:33.409  1034  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 18:20:33.409  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 18:20:33.410  7167  7167 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 18:20:33.410  1034  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 18:20:33.412  1944  7199 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 18:20:33.412  1944  7199 E CtrlSupplicant: Succeed to open control connection
08-26 18:20:33.412  1034  1539 E WifiNative: : [124,315,492 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 18:20:33.412  1034  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 18:20:33.413  1034  1539 D WifiNative-wlan0: RECONNECT: returned true
08-26 18:20:33.413  1034  1539 D WifiNative-wlan0: doString: [STATUS]
08-26 18:20:33.413  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 18:20:33.413  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 18:20:33.413  1034  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b86,1-ec7a05ef48b4
08-26 18:20:33.413  1034  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 18:20:33.414  1944  7199 E CtrlSupplicant: Succeed to open monitor connection
08-26 18:20:33.414  1034  1539 D WifiNative-wlan0: SET ps 1: returned true
08-26 18:20:33.414  1944  7199 D WfdsMonitor: Supplicant connection established
08-26 18:20:33.415  1944  2286 D WfdsService: Connected to the supplicant for wfds
08-26 18:20:33.415  1034  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.416  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 18:20:33.416  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-26 18:20:33.416  1034  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.416  1034  1557 I WifiNative-HAL: startHal
08-26 18:20:33.416  1034  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.416  1034  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf68e780
08-26 18:20:33.416  1034  1557 D wifi    : failed to get capabilities : -3
08-26 18:20:33.416  1034  1557 E WifiScanningService: could not get scan capabilities
08-26 18:20:33.417   307   889 D CommandListener: Setting iface cfg
08-26 18:20:33.417   307   889 D CommandListener: Trying to bring up p2p0
08-26 18:20:33.417  1034  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 18:20:33.417  1034  1538 D LGWifiP2pService: P2pEnablingState
08-26 18:20:33.417  1034  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.417  1034  1538 D LGWifiP2pService: P2p socket connection successful
08-26 18:20:33.417  1034  1538 D LGWifiP2pService: P2pEnabledState
08-26 18:20:33.418  1034  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 18:20:33.418  1034  1956 I ActivityManager: Killing 6619:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-26 18:20:33.418  1034  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 18:20:33.418  1034  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 18:20:33.419  1034  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 18:20:33.419  1034  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 18:20:33.419  1034  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
,08-26 18:20:33.420  1034  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 18:20:33.420  1034  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 18:20:33.420  7167  7167 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 18:20:33.421  1034  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 18:20:33.421  1034  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 18:20:33.421  1034  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 18:20:33.421  1034  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 18:20:33.421  7167  7167 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 18:20:33.422  1034  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
,08-26 18:20:33.422  1034  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 18:20:33.423  1034  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 18:20:33.423  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 18:20:33.423  7167  7167 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 18:20:33.424  7167  7167 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 18:20:33.424  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 18:20:33.424  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 18:20:33.424  1034  7180 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ,
08-26 18:20:33.424  1034  7180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 18:20:33.424  7167  7167 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 18:20:33.424  7167  7167 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:33.424  1944  7199 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 18:20:33.424  1034  7180 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 18:20:33.424  1034  7180 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-26 18:20:33.425  1034  7180 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:33.425  1034  7180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:33.425  1034  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 18:20:33.425  7167  7167 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:33.425  1034  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 18:20:33.425  1034  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
,08-26 18:20:33.425  1944  7199 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-26 18:20:33.425  1034  7180 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 18:20:33.425  1034  7180 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:33.425  1034  7180 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:33.425  1034  7180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:33.425  1034  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 18:20:33.425  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 18:20:33.426  7167  7167 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
,08-26 18:20:33.426  7167  7167 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 18:20:33.426  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 18:20:33.426  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 18:20:33.426  1034  7180 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 18:20:33.426  1034  7180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 18:20:33.426  1034  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 18:20:33.426  1034  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,08-26 18:20:33.427  1034  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 18:20:33.427  1034  1539 D WifiNative-wlan0: doBoolean: SCAN
08-26 18:20:33.427  1034  1539 D WifiNative-wlan0: SCAN: returned false
08-26 18:20:33.427  1034  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=124332  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 18:20:33.446  1034  1538 D LGWifiP2pService: sending p2p connection changed broadcast
,08-26 18:20:33.446  1034  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 18:20:33.447  1034  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 18:20:33.447  1034  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 18:20:33.447  1034  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-26 18:20:33.447  1034  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 18:20:33.447  1034  1538 D LGWifiP2pService: before postfix = G3
08-26 18:20:33.447  1034  1538 D WifiServerServiceExt: postfix byte check : 2
08-26 18:20:33.447  1034  1538 D LGWifiP2pService: after postfix = G3
08-26 18:20:33.447  1034  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 18:20:33.448  1034  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 18:20:33.448  1034  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 18:20:33.448  1034  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 18:20:33.448  1034  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 18:20:33.449  1034  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 18:20:33.449  1034  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 18:20:33.449  1034  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 18:20:33.449  1034  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-26 18:20:33.449  1034  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 18:20:33.450  1034  1893 W libprocessgroup: failed to open /acct/uid_10061/pid_6619/cgroup.procs: No such file or directory
08-26 18:20:33.450  1034  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=124356  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 18:20:33.451  1034  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 18:20:33.451  1034  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 18:20:33.452  1034  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 18:20:33.452  1034  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 18:20:33.452  1034  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 18:20:33.453  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 18:20:33.453  1944  1944 D WfdsService: WifiP2pState is changed : true
08-26 18:20:33.453  1944  2286 D WfdsService: Receive the WFDS_ENABLE Method
08-26 18:20:33.453  1944  2286 D WfdsService: Set the WFDS Monitor: true
08-26 18:20:33.453  1944  2286 D WfdsService: Connected to the supplicant for wfds
08-26 18:20:33.453  1944  2286 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 18:20:33.453  7167  7167 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 18:20:33.454  1944  2286 D WfdsService: selectPreferredScanChannel [36]
08-26 18:20:33.454  1944  2286 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 18:20:33.454  1944  1944 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 18:20:33.454  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:33.454  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:33.455  1944  1944 D WfdsService: isConnected: false
08-26 18:20:33.455  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:33.456  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.,provider.Settings.Global, returning read-only value.
08-26 18:20:33.456  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:33.456  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 18:20:33.456  1034  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 18:20:33.456  1034  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 18:20:33.456  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:33.456  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 18:20:33.456  1034  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 18:20:33.456  1034  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 18:20:33.457  1034  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 18:20:33.457  1034  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 18:20:33.457  1034  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 18:20:33.457  1034  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 18:20:33.457  1944  1944 I WfdStateTracker: handleP2pThisDeviceChanged
,08-26 18:20:33.460  1944  1944 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 18:20:33.460  1944  1944 D WfdsService: Update P2p Interface State: 3
08-26 18:20:33.468  1034  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 18:20:33.468  1034  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 18:20:33.468  1034  1538 D LGWifiP2pService: InactiveState
08-26 18:20:33.468  1034  1538 D LGWifiP2pService: InactiveState{ when=-44ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,08-26 18:20:33.468  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-44ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.468  1034  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 18:20:33.469  7167  7167 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 18:20:33.469  7167  7167 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 18:20:33.470  1944  7199 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 18:20:33.470  1034  7180 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 18:20:33.470  1034  7180 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 18:20:33.470  1034  7180 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 18:20:33.470  1034  7180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 18:20:33.470  7167  7167 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 18:20:33.470  7167  7167 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:33.470  1944  7199 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 18:20:33.470  1034  7180 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 18:20:33.470  1034  7180 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:33.470  1034  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
,08-26 18:20:33.470  1034  7180 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:33.470  1034  7180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:33.470  1034  1538 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.470  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.470  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.470  7167  7167 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:33.471  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.471  1034  1538 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.471  1944  7199 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 18:20:33.471  1034  7180 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 18:20:33.471  1034  7180 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:33.471  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.471  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.471  1034  7180 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:33.471  1034  7180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:33.471  1034  1538 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.471  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.471  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.471  1034  1538 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.471  1944  2286 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 18:20:33.473  1034  1538 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.473  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.473  1034  1538 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:33.474  1034  1034 E WifiServerServiceExt: No p2p device connected
08-26 18:20:33.501  7182  7182 D LgDataFeature: LgDataFeature() Constructor: none
08-26 18:20:33.501  7182  7182 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 18:20:33.503  7182  7182 D PhoneMonitor: Register our PhoneStateListener
,08-26 18:20:33.512  7182  7182 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 18:20:33.513  7182  7182 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 18:20:33.526  7182  7182 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-26 18:20:33.527  7182  7182 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-26 18:20:33.529  7182  7182 D TelephonyAutoProfiling: [parse] Load xml
,08-26 18:20:33.535  7182  7182 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-26 18:20:33.535  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-26 18:20:33.535  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
,08-26 18:20:33.536  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-26 18:20:33.536  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
,08-26 18:20:33.536  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-26 18:20:33.536  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-26 18:20:33.536  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
,08-26 18:20:33.536  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-26 18:20:33.536  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
,08-26 18:20:33.536  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-26 18:20:33.536  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
,08-26 18:20:33.536  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-26 18:20:33.537  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
,08-26 18:20:33.537  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-26 18:20:33.537  7182  7182 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-26 18:20:33.537  7182  7182 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-26 18:20:33.547  7182  7182 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-26 18:20:33.565  1034  2053 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7203 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 18:20:33.566  1034  2053 I ActivityManager: Killing 6743:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-26 18:20:33.613  1034  1727 W libprocessgroup: failed to open /acct/uid_10080/pid_6743/cgroup.procs: No such file or directory
,08-26 18:20:33.894  1034  2053 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7227 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-26 18:20:33.898  1034  2053 I ActivityManager: Killing 6065:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-26 18:20:33.955  7167  7167 E wpa_supplicant: USIM:  scard_init function
08-26 18:20:33.955  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 18:20:33.955  1034  7180 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 18:20:33.956  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 18:20:33.956  7167  7167 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 18:20:33.956  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-26 18:20:33.956  1034  7180 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-26 18:20:33.958  1034  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-26 18:20:33.959  1034  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-26 18:20:33.959  1034  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-26 18:20:33.959  1034  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-26 18:20:33.960  1034  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 18:20:33.960  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 18:20:33.960  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-26 18:20:33.974  1034  1907 W libprocessgroup: failed to open /acct/uid_10097/pid_6065/cgroup.procs: No such file or directory
,08-26 18:20:33.984  1034  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=124889  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 18:20:33.991  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:33.991  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:33.992  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:33.992  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:33.992  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 18:20:33.993  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:33.993  1034  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=124899  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 18:20:34.009  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.009  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.009  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 18:20:34.013  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:34.013  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-26 18:20:34.014  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:34.014  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 18:20:34.018  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:34.068  7167  7167 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 18:20:34.073  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 18:20:34.073  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 18:20:34.074  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 18:20:34.074  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 18:20:34.074  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 18:20:34.074  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 18:20:34.075  1034  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=124980  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 18:20:34.077  7167  7167 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 18:20:34.077  7167  7167 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 18:20:34.079  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 18:20:34.079  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 18:20:34.079  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 18:20:34.079  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 18:20:34.079  1034  7180 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 18:20:34.079  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 18:20:34.079  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 18:20:34.080  1034  7180 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 18:20:34.081  1034  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=124981  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 18:20:34.081  1034  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124986
08-26 18:20:34.082  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 18:20:34.082  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 18:20:34.083  1034  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124988
08-26 18:20:34.083  1034  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124988
08-26 18:20:34.084  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124989
08-26 18:20:34.084  1034  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124989
08-26 18:20:34.086  1034  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=124991  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-26 18:20:34.109  1034  1656 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7252 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 18:20:34.113  1034  1656 I ActivityManager: Killing 6766:com.lge.eula/1000 (adj 15): empty #17
08-26 18:20:34.184  1034  1110 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 18:20:34.194  1034  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=125099  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 18:20:34.196  1034  2053 W libprocessgroup: failed to open /acct/uid_1000/pid_6766/cgroup.procs: No such file or directory
08-26 18:20:34.196  1034  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=125101  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-26 18:20:34.200  1034  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=125104  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 18:20:34.202  1034  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=125107
08-26 18:20:34.206  1034  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=125111
08-26 18:20:34.209  1034  1539 D WifiNative-wlan0: doString: [STATUS]
,08-26 18:20:34.212  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 18:20:34.212  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 18:20:34.213  1034  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 18:20:34.216  1034  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-26 18:20:34.233  7252  7252 I art     : Almond Protected OAT
,08-26 18:20:34.242  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:34.242  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:34.244  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:34.244  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.245  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.245  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 18:20:34.246  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.246  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.246  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 18:20:34.265  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 18:20:34.265  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:34.267  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:34.268  1034  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 18:20:34.268  1034  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-26 18:20:34.272  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.272  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.272  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 18:20:34.275  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.275  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.275  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 18:20:34.284  1034  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 18:20:34.284  1034  1545 D ConnectivityService: Got NetworkAgent Messenger
08-26 18:20:34.284  1034  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 18:20:34.284  1034  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 18:20:34.284  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 18:20:34.284  1034  1545 D ConnectivityService: NetworkAgent connected
08-26 18:20:34.285  1034  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 18:20:34.285  1034  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-26 18:20:34.288  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:34.288  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:34.289  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:34.291  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:34.291  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:34.293  1034  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 18:20:34.293  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:34.293  1034  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 18:20:34.293  1034  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 18:20:34.293  1034  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 18:20:34.293  1034  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 18:20:34.294  7252  7252 D WeatherApplication: removeAccount
08-26 18:20:34.295  7252  7252 D WeatherApplication: Account.length = 0
08-26 18:20:34.296  7252  7252 E WeatherApplication: OPERATOR:OPEN
08-26 18:20:34.298  1034  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:34.298  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:34.298  1034  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:34.298  1034  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-26 18:20:34.300   307   889 D CommandListener: Setting iface cfg
08-26 18:20:34.300  7252  7252 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:20:34
,08-26 18:20:34.302  7252  7252 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 18:20:34.302  7252  7252 D Weather.Utils: 2 : All the weather widget is gone.
08-26 18:20:34.303  1034  1539 E WifiStateMachine: Start Dhcp Watchdog 2
08-26 18:20:34.303  1034  7273 D DhcpStateMachine: StoppedState
08-26 18:20:34.303  1034  7273 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:34.303  1034  7273 D DhcpStateMachine: WaitBeforeStartState
08-26 18:20:34.303  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:34.303  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 18:20:34.303  1034  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=125208  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 18:20:34.304  1034  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=125209  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 18:20:34.304  7252  7252 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 18:20:34.304  1034  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=125209  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 18:20:34.305  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:34.305  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 18:20:34.307  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:34.307  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 18:20:34.307  1034  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=125212  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 18:20:34.308  1034  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=125213  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 18:20:34.308  1034  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=125213  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 18:20:34.308  7252  7252 D WeatherAncestor: connectivity changed - connection : true
08-26 18:20:34.308  1034  1539 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:34.309  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:34.309  1034  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:34.309  7252  7252 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-26 18:20:34.309  1034  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:34.309  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:34.310  1034  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:34.310  1034  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:78715] from screen [on:0 period:-945348218] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-26 18:20:34.311  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-945348217] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-26 18:20:34.311  1034  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-26 18:20:34.314  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:34.316  1034  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-26 18:20:34.316  1034  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:34.317  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:34.317  1034  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:34.317  1034  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:34.318  7252  7252 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 18:20:34.318  7252  7252 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 18:20:34.318  7252  7252 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-26 18:20:34.318  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:34.318  1034  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:34.318  1034  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 18:20:34.319  1034  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=161,0,0
08-26 18:20:34.319  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=161,0,0
08-26 18:20:34.319  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 18:20:34.320  7167  7167 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 18:20:34.320  1034  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 18:20:34.321  1034  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 18:20:34.321  1034  1539 D WifiNative-wlan0: SET ps 0: returned true
08-26 18:20:34.321  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 18:20:34.321  7167  7167 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 18:20:34.322  1034  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 18:20:34.322  1034  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 18:20:34.322  1034  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 18:20:34.322  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@438d69e target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:34.322  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@438d69e target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:34.322  1034  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 18:20:34.322  1034  7273 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:34.322  1034  7273 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 18:20:34.323   307   889 D CommandListener: Setting iface cfg
08-26 18:20:34.324   307   889 D CommandListener: Trying to bring up wlan0
08-26 18:20:34.325  1034  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 18:20:34.326  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:34.326  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 18:20:34.326  1034  1539 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 18:20:34.326  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 18:20:34.327  1034  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 18:20:34.327  1034  1539 E WifiStateMachine:  DriverStartedState CMD,_STOP_SUPPLICANT_FAILED 1 0
08-26 18:20:34.327  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 18:20:34.328  1034  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 18:20:34.328  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:34.328  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 18:20:34.328  1034  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 18:20:34.329  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:34.329  1034  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:34.329  1034  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:34.330  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:34.330  1034  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:34.331  1034  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 18:20:34.331  1034  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 18:20:34.332  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 18:20:34.332  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 18:20:34.332  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:34.332  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:34.332  7167  7167 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 18:20:34.332  1034  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 18:20:34.333  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 18:20:34.333  7167  7167 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 18:20:34.333  1034  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
,08-26 18:20:34.333  1034  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 18:20:34.348  1034  1539 D WifiNative-wlan0: SET ps 1: returned true
08-26 18:20:34.349  1034  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 18:20:34.349  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 18:20:34.349  1034  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-26 18:20:34.350  1034  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 18:20:34.350  1034  1545 D ConnectivityService: ignoring duplicate network state non-change
08-26 18:20:34.354  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:34.354  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:34.355  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.355  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.355  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 18:20:34.355  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 18:20:34.355  1034  1545 D ConnectivityService: Adding iface wlan0 to network 101
08-26 18:20:34.356  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:34.358  1034  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 18:20:34.359  7252  7252 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 18:20:34.359  7252  7252 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:20:34
,08-26 18:20:34.365  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.365  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.365  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 18:20:34.366  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 18:20:34.368  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 18:20:34.370  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.370  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.370  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 18:20:34.371  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 18:20:34.376  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:34.376  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 18:20:34.378  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.378  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:34.378  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 18:20:34.380  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:34.382  1034  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 18:20:34.382  1034  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-26 18:20:34.383  1034  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-26 18:20:34.383  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:34.383   307   889 E Netd    : netlink response contains error (File exists)
08-26 18:20:34.383  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 18:20:34.384  1034  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-26 18:20:34.384  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:34.384  1034  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 18:20:34.384  1034  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-26 18:20:34.384  1034  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-26 18:20:34.387  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:34.387  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 18:20:34.387  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 18:20:34.414  1034  1576 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7278 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 18:20:34.416  1034  1576 I ActivityManager: Killing 6785:com.lge.bnr/1000 (adj 15): empty #17
08-26 18:20:34.495  1034  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,08-26 18:20:34.496  1034  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 18:20:34.496  1034  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-26 18:20:34.496  1034  1908 W libprocessgroup: failed to open /acct/uid_1000/pid_6785/cgroup.procs: No such file or directory
08-26 18:20:34.496  1034  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 18:20:34.497  1034  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 18:20:34.497  1034  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:34.497  1034  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 18:20:34.498  1034  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:34.498  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:34.498  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
,08-26 18:20:34.498  1034  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
,08-26 18:20:34.498  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler },
08-26 18:20:34.498  1034  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-26 18:20:34.499  1034  1545 D ConnectivityService:    accepting network in place of null
08-26 18:20:34.499  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 18:20:34.499  1034  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:34.500  1034  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:34.500  1034  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 18:20:34.503  1855  1855 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:34.504  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>],
,08-26 18:20:34.506  1034  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,08-26 18:20:34.506  1034  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 18:20:34.507  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 18:20:34.511   307  7296 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-26 18:20:34.534  1034  7273 D DhcpStateMachine: DHCPV4 request on wlan0
,08-26 18:20:34.536  1034  7273 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 18:20:34.536  1034  7273 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-26 18:20:34.543  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 18:20:34.543  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 18:20:34.543  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 18:20:34.543  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 18:20:34.537  7297  7297 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:34.537  7297  7297 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:34.547  1034  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:34.547  1034  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 18:20:34.548  1034  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 18:20:34.554  1034  1545 D ConnectivityService: validation of new default Network = false
08-26 18:20:34.554  1034  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 18:20:34.554  1034  1545 D DSQN    : enableDataServiceNotify 
08-26 18:20:34.554  1034  1545 D DSQN    : start dsqn bin
,08-26 18:20:34.558  1034  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 18:20:34.559  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:34.559  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:34.559  1034  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:34.547  7298  7298 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:34.547  7298  7298 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:34.560  1603  2082 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 18:20:34.563  7297  7297 I dhcpcd  : version 5.5.6 starting
08-26 18:20:34.566  7297  7297 E dhcpcd  : get_duid: m
08-26 18:20:34.566  7297  7297 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 18:20:34.566  7297  7297 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-26 18:20:34.573   307  7296 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-26 18:20:34.579  7298  7298 E DSQN    : DSQN ssw
08-26 18:20:34.581  1034  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-26 18:20:34.605  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 18:20:34.606  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:34.607  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:34.608  1819  7305 I CheckinService: active receiver: enabled
08-26 18:20:34.611   307  7296 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-26 18:20:34.625  1819  7305 I CheckinService: Preparing to send checkin request
08-26 18:20:34.625  1819  7305 I EventLogService: Accumulating logs since 1472228351798
08-26 18:20:34.627  7297  7297 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 18:20:34.627  7297  7297 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 18:20:34.627  7297  7297 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 18:20:34.627  7297  7297 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 18:20:34.628  7297  7297 D dhcpcd  : wlan0: sending REQUEST (xid 0x181e1fef), next in 4.31 seconds
08-26 18:20:34.644   307   888 D LGDataListener: argv[0]=dsqncommand
08-26 18:20:34.644   307   888 D LGDataListener: argv[1]=wlan0
08-26 18:20:34.644   307   888 D LGDataListener: argv[2]=1
08-26 18:20:34.644   307   888 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-26 18:20:34.644  1034  1108 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 18:20:34.645  1034  1108 D DSQN    : start to monitor internet connection
08-26 18:20:34.668  1819  7305 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-26 18:20:34.674  7297  7297 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 18:20:34.684  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 16:20:34 GMT], X-Android-Received-Millis=[1472228434684], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472228434643]}
08-26 18:20:34.684  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 18:20:34.684  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 18:20:34.684   278   370 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 18:20:34.684   278   370 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 18:20:34.684   278   370 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 18:20:34.684  1034  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-26 18:20:34.684  1034  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 18:20:34.685  1034  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 18:20:34.685  1034  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:34.685  1034  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 18:20:34.685  1034  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-26 18:20:34.685  7278  7313 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 18:20:34.685  1034  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 18:20:34.685  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:34.685  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:34.685  1034  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:34.686  1034  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:34.686  1603  2082 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 18:20:34.686  1034  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:34.686  1034  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 18:20:34.686  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 18:20:34.686  1855  1855 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:34.687  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 18:20:34.688   278   370 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 18:20:34.688   278   370 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 18:20:34.688   278   370 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 18,:20:34.688  7278  7313 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-26 18:20:34.692  7297  7297 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 18:20:34.692  7297  7297 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-26 18:20:34.694  7297  7297 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 18:20:34.694  7297  7297 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 18:20:34.694  7297  7297 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 18:20:34.694  7297  7297 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 18:20:34.695  7297  7297 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 18:20:34.695  7297  7297 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 18:20:34.699   278   370 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 18:20:34.699   278   370 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 18:20:34.700   278   370 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 18:20:34.700  7278  7316 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 18:20:34.713   278   370 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 18:20:34.713   278   370 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,08-26 18:20:34.713   278   370 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 18:20:34.713  7278  7316 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-26 18:20:34.716  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 18:20:34.716  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:34.717  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 18:20:34.837  1034  1926 I art     : Explicit concurrent mark sweep GC freed 105119(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/64MB, paused 1.601ms total 147.219ms
,08-26 18:20:34.894  1034  1962 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7351 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-26 18:20:34.936  7351  7351 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-26 18:20:34.936  7351  7351 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-26 18:20:34.943  1034  7273 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-26 18:20:34.944  1034  7273 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 18:20:34.944  1034  7273 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 18:20:34.944  1034  7273 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
,08-26 18:20:34.944  1034  7273 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 18:20:34.944  1034  7273 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 18:20:34.944  1034  7273 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 18:20:34.944  1034  7273 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 18:20:34.945  1034  7273 D DhcpStateMachine: RunningState
08-26 18:20:34.954  7351  7351 I MultiDex: VM with version 2.1.0 has multidex support
08-26 18:20:34.954  7351  7351 I MultiDex: install
08-26 18:20:34.954  7351  7351 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 18:20:34.960  7351  7351 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-26 18:20:34.980  7278  7278 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-26 18:20:35.001  7278  7278 I LibraryLoader: Loading: webviewchromium
,08-26 18:20:35.005  7278  7278 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5918-5922)
,08-26 18:20:35.005  7278  7278 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 18:20:35.015  7278  7278 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {227c0808}
,08-26 18:20:35.020  7278  7278 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 18:20:35.021  7278  7278 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 18:20:35.047  7278  7278 I BrowserStartupController: Initializing chromium process, renderers=0
08-26 18:20:35.048  7278  7278 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 18:20:35.063   312  2172 V AudioPolicyService: registerClient() client 0xb1030e40, uid 10093
,08-26 18:20:35.065  7278  7375 W AudioManagerAndroid: Requires BLUETOOTH permission
08-26 18:20:35.070  7278  7278 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 18:20:35.072  7278  7278 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-26 18:20:35.072  7278  7278 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-26 18:20:35.088  7278  7278 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 18:20:35.088  7278  7278 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 18:20:35.088  7278  7278 I Adreno-EGL: Build Date: 12/12/14 금
08-26 18:20:35.088  7278  7278 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 18:20:35.088  7278  7278 I Adreno-EGL: Remote Branch: 
08-26 18:20:35.088  7278  7278 I Adreno-EGL: Local Patches: 
08-26 18:20:35.088  7278  7278 I Adreno-EGL: Reconstruct Branch: 
,08-26 18:20:35.162  7278  7278 I NSApplication: Starting up...
,08-26 18:20:35.209  1034  2008 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7388 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-26 18:20:35.210  1034  2008 I ActivityManager: Killing 2176:com.lge.music/u0a34 (adj 15): empty #17
,08-26 18:20:35.226   312  1382 V AudioFlinger: 2176 died, releasing its sessions
08-26 18:20:35.226   312  1382 V AudioFlinger:  pid 1855 @ 0
08-26 18:20:35.226   312  1382 V AudioFlinger:  pid 3203 @ 1
,08-26 18:20:35.226   312  1382 V AudioFlinger:  pid 3203 @ 2
08-26 18:20:35.296  7405  7405 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 18:20:35.305  1034  1576 W libprocessgroup: failed to open /acct/uid_10034/pid_2176/cgroup.procs: No such file or directory
,08-26 18:20:35.322  1034  2032 D WifiServiceImplEx: setWifiEnabled: false pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 18:20:35.322  1034  2032 D WifiService: setWifiEnabled: false pid=6669, uid=10118
08-26 18:20:35.322  1034  2032 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 18:20:35.342  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 18:20:35.342  1034  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 18:20:35.342  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-26 18:20:35.342  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 18:20:35.342  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 18:20:35.343  1034  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 18:20:35.343  1034  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 18:20:35.344  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 18:20:35.344  1034  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 18:20:35.344  1034  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 18:20:35.344  1034  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 18:20:35.345  1034  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 18:20:35.345  1034  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 18:20:35.356  1034  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 18:20:35.357  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 18:20:35.357  7167  7167 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 18:20:35.357  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:35.357  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:35.357  1034  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 18:20:35.357  1034  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 18:20:35.358  1034  1539 D WifiNative-wlan0: SET ps 1: returned true
08-26 18:20:35.358   307   889 D CommandListener: Clearing all IP addresses on wlan0
,08-26 18:20:35.361  1034  7273 D DhcpStateMachine: RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:35.363  7388  7388 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 18:20:35.388  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 18:20:35.388  1034  1545 D ConnectivityService: ignoring duplicate network state non-change
08-26 18:20:35.388  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 18:20:35.388  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-26 18:20:35.389  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:35.389  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:35.391  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 18:20:35.392  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:35.393  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:35.393  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:35.393  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 18:20:35.394  1034  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:35.394  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:35.395  1034  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:35.395  1034  1538 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:35.396  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:35.396  1034  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@22c6183f
08-26 18:20:35.396  7405  7405 I dex2oat : dex2oat took 99.179ms (threads: 4)
08-26 18:20:35.396  1034  1538 D LGWifiP2pService: P2pDisablingState
08-26 18:20:35.396  1034  1538 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:35.396  1034  1538 D LGWifiP2pService: p2p socket connection lost
08-26 18:20:35.396  1034  1538 D LGWifiP2pService: P2pDisabledState
08-26 18:20:35.398  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 18:20:35.402  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:35.402  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:35.402  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-26 18:20:35.402  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 18:20:35.405  1034  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:35.405  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-26 18:20:35.405  1034  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:35.406  1034  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:35.407  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:35.407  1034  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:35.407  1034  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 18:20:35.408  1034  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 18:20:35.412  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 18:20:35.413  1034  1538 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:35.413  1034  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:35.413  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 18:20:35.413  7167  7167 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 18:20:35.413  1034  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 18:20:35.413  1034  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 18:20:35.414  1034  1539 D WifiNative-wlan0: SET ps 1: returned true
08-26 18:20:35.414  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:35.414  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:35.417  1944  1944 D WfdsService: WifiP2pState is changed : false
08-26 18:20:35.417  1944  2286 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 18:20:35.417  1944  2286 D WfdsService: Set the WFDS Monitor: false
,08-26 18:20:35.419  7351  7368 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 18:20:35.419  7351  7368 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 18:20:35.419  7351  7368 I Adreno-EGL: Build Date: 12/12/14 금
08-26 18:20:35.419  7351  7368 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 18:20:35.419  7351  7368 I Adreno-EGL: Remote Branch: 
08-26 18:20:35.419  7351  7368 I Adreno-EGL: Local Patches: 
08-26 18:20:35.419  7351  7368 I Adreno-EGL: Reconstruct Branch: 
08-26 18:20:35.421  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:35.421  1944  2286 D WfdsMonitor: WFDS Monitor is stopped
08-26 18:20:35.421  1944  2286 D WfdsService: STATE : WfdsDisabledState - enter
08-26 18:20:35.422  1944  7199 D CtrlSupplicant: Received on exit socket, terminate
08-26 18:20:35.422  1944  7199 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 18:20:35.422  1944  7199 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 18:20:35.422  1944  7199 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 18:20:35.422  1944  2288 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 18:20:35.422  1944  2286 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 18:20:35.432   307   889 D CommandListener: Clearing all IP addresses on wlan0
08-26 18:20:35.432  1034  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 18:20:35.432  1034  1545 D DSQN    : disableDataServiceNotify
08-26 18:20:35.433  1034  1545 D DSQN    : stop dsqn bin
,08-26 18:20:35.434  1034  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 18:20:35.435  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 18:20:35.436  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:35.436  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:35.436  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 18:20:35.436  1034  1539 D WifiNative-p2p0: TERMINATE: returned true
08-26 18:20:35.436  1034  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 18:20:35.436  1034  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 18:20:35.436  1034  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 18:20:35.438  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 18:20:35.438  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 18:20:35.439  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:35.439  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 18:20:35.441  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 18:20:35.441  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:35.441  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:35.441  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:35.441  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:35.441  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:35.441  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:35.441  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:35.441  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:35.441  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:35.441  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:35.441  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:35.441  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:35.442  1034  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-26 18:20:35.442  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:35.442  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:35.442  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:35.442  1034  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:35.442  1034  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 18:20:35.443  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated,State{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:35.443  1603  2082 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 18:20:35.443  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:35.443  1034  7272 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 18:20:35.443  1034  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 18:20:35.443  1034  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 18:20:35.443  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 18:20:35.443  1034  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:35.443  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 18:20:35.444  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:35.444  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:35.444  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:35.444  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:35.444  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:35.444  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:35.444  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:35.444  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:35.444  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:35.444  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:35.444  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:35.444  1034  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 18:20:35.445  1034  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:35.445  1034  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:35.445  1034  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:35.445  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 18:20:35.445  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 18:20:35.445  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 18:20:35.445  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 18:20:35.446  1855  1855 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:35.446  1034  1545 D NetworkManagementService: Removing idletimer
08-26 18:20:35.446  1034  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:35.446  1034  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:35.446  1034  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 18:20:35.447  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 18:20:35.447  1034  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 18:20:35.448  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 18:20:35.448  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 18:20:35.448  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 18:20:35.448  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 18:20:35.450  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 18:20:35.471  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 18:20:35.472  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:35.473  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 18:20:35.487  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 18:20:35.488  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:35.488  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:35.533  7167  7167 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 18:20:35.533  7167  7167 I wpa_supplicant: monitor socket send errors count : 1
08-26 18:20:35.533  7167  7167 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1944-4\x00 that cannot receive messages
,08-26 18:20:35.535  1034  7180 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 18:20:35.535  1034  7180 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 18:20:35.555  7167  7167 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 18:20:35.556  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 18:20:35.556  7167  7167 W wpa_supplicant: USIM:  scard_deinit function
,08-26 18:20:35.559  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 18:20:35.559  1034  7180 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 18:20:35.559  1034  7180 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 18:20:35.559  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 18:20:35.559  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 18:20:35.560  1034  1110 D Tethering: InitialState.processMessage what=4
08-26 18:20:35.560  1034  1545 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-26 18:20:35.560  1034  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 18:20:35.561  1034  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=126466
08-26 18:20:35.561  1034  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=126466
08-26 18:20:35.562  1034  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=126467  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 18:20:35.564  1034  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=126468  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 18:20:35.565  1034  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:35.566  1034  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:35.568  1034  7273 D DhcpStateMachine: StoppedState
08-26 18:20:35.568  1034  7273 D DhcpStateMachine: StoppedState{ when=-155ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:35.569  1034  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 18:20:35.570  1034  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-26 18:20:35.694  7167  7167 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 18:20:35.694  1034  7180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 18:20:35.694  1034  7180 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 18:20:35.694  1034  7180 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 18:20:35.695  1034  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,08-26 18:20:35.715  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-26 18:20:35.719  6410  6440 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 18:20:35.727  2140  2140 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:35.738  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 18:20:35.738  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:35.738  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 18:20:35.738  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 18:20:35.740  7114  7114 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 18:20:35.744  7114  7114 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@380b1ef9
08-26 18:20:35.744  7114  7114 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 18:20:35.744  7114  7114 D AppUp4:CustFacade: isPhone : true
08-26 18:20:35.744  7114  7114 D AppUp4:CustModeStarterReceiver: begin check event
08-26 18:20:35.744  7114  7114 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 18:20:35.747  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:35.747  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 18:20:35.748  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 18:20:35.749  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 18:20:35.754  4752  7427 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 18:20:35.755  7141  7141 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 18:20:35.757  4752  7428 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:35.757  4752  7428 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 18:20:35.770  3203  3203 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 18:20:35.770  3203  3203 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:35.770  3203  3203 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 18:20:35.776  7141  7429 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:35.778  7182  7182 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 18:20:35.778  7182  7182 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 18:20:35.784  7017  7434 W FormManager: Network not available. Please check & try again.
,08-26 18:20:35.789  7252  7252 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:20:35
08-26 18:20:35.790  7252  7252 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 18:20:35.790  7252  7252 D Weather.Utils: 2 : All the weather widget is gone.
08-26 18:20:35.791  7252  7252 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 18:20:35.791  7252  7252 D WeatherAncestor: connectivity changed - connection : true
08-26 18:20:35.791  7017  7436 V FormManager: Network unavailable.
08-26 18:20:35.791  7252  7252 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@c9f949f
08-26 18:20:35.792  7252  7252 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 18:20:35.793  7017  7436 V FormManager: Network unavailable.
08-26 18:20:35.794  7252  7252 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 18:20:35.794  7252  7252 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 18:20:35.794  7252  7252 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 18:20:35.794  7252  7252 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:20:35
08-26 18:20:35.797  1034  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 18:20:35.797  1034  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 18:20:35.797  1034  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 18:20:35.797  1034  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 18:20:35.799  1944  1944 D WfdsService: Supplicant Connection state is changed : false
08-26 18:20:35.799  1944  2286 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 18:20:35.799  1944  2286 D WfdsService: Set the WFDS Monitor: false
08-26 18:20:35.799  1944  2286 D WfdsMonitor: WFDS Monitor is stopped
08-26 18:20:35.800  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:35.801  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 18:20:35.801  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 18:20:35.801  1034  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 18:20:35.801  1034  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 18:20:35.802  2479  2479 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:35.802  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:35.802  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:35.802  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:35.802  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:35.802  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:35.802  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:35.802  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:35.802  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:35.802  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:35.803  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:35.803  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:35.803  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:35.803  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:35.803  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:35.803  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:35.803  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:35.803  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:35.803  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:35.816  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 18:20:35.816  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 18:20:35.816  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 18:20:35.816  6932  6932 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-26 18:20:35.816  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 18:20:35.817  6932  6932 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 18:20:35.818  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 18:20:35.818  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 18:20:35.818  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 18:20:35.818  6932  6932 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 18:20:35.818  6932  6932 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 18:20:35.824  7351  7368 D LgDataFeature: LgDataFeature() Constructor: none
08-26 18:20:35.825  7351  7368 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 18:20:35.826  6952  6952 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 18:20:35.830  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 18:20:35.834  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:35.839  7351  7368 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 18:20:35.839  7351  7368 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 18:20:35.839  7351  7368 I Adreno-EGL: Build Date: 12/12/14 금
08-26 18:20:35.839  7351  7368 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 18:20:35.839  7351  7368 I Adreno-EGL: Remote Branch: 
08-26 18:20:35.839  7351  7368 I Adreno-EGL: Local Patches: 
08-26 18:20:35.839  7351  7368 I Adreno-EGL: Reconstruct Branch: 
08-26 18:20:35.848  6952  6952 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 18:20:35.851  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:35.853  7017  7439 V FormManager: Network unavailable.
08-26 18:20:35.854  7017  7438 W FormManager: Network not available. Please check & try again.
08-26 18:20:35.854  7017  7439 V FormManager: Network unavailable.
08-26 18:20:35.859  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 18:20:35.865  7017  7440 W FormManager: Network not available. Please check & try again.
08-26 18:20:35.868  7017  7441 V FormManager: Network unavailable.
08-26 18:20:35.870  7017  7441 V FormManager: Network unavailable.
08-26 18:20:35.874  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 18:20:35.874  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 18:20:35.875  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 18:20:35.876  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 18:20:35.882  4752  7442 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 18:20:35.884  4752  7443 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 18:20:35.884  4752  7443 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 18:20:35.892  7351  7368 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 18:20:35.892  7351  7368 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 18:20:35.892  7351  7368 I Adreno-EGL: Build Date: 12/12/14 금
08-26 18:20:35.892  7351  7368 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 18:20:35.892  7351  7368 I Adreno-EGL: Remote Branch: 
08-26 18:20:35.892  7351  7368 I Adreno-EGL: Local Patches: 
08-26 18:20:35.892  7351  7368 I Adreno-EGL: Reconstruct Branch: 
,08-26 18:20:35.910  1034  1050 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7444 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 18:20:35.969  7444  7444 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 18:20:35.969  7444  7444 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 18:20:35.973   307  7463 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 18:20:35.973  1034  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 18:20:35.973  1819  7305 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-26 18:20:35.975  7444  7444 V [BNRBootReceiver]: Boot Receiver Return
08-26 18:20:35.976  7444  7444 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 18:20:35.981  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 18:20:35.994  1819  7305 I CheckinService: active receiver: disabled
,08-26 18:20:36.022  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 18:20:36.025  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:36.082  1034  1374 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7465 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 18:20:36.083  1034  1374 V AlarmManager: RTC_WAKEUP set : Alarm{df88529 type 0 when 1472228426794 com.android.vending} when 1472228426794
,08-26 18:20:36.091  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:36.091  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:36.095  6980  6980 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 18:20:36.100  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 18:20:36.104  6932  6932 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 18:20:36.110  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 18:20:36.122  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:36.128  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:36.136  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:36.137  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 18:20:36.138  6980  6980 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 18:20:36.142  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:36.154  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:36.161  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:36.168  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:36.169  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:36.169  6980  6980 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 18:20:36.172  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:36.183  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:36.190  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:36.197  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:36.198  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 18:20:36.198  6980  6980 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 18:20:36.203  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:36.209  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:36.229  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:36.237  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:36.238  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:36.238  6980  6980 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 18:20:36.246  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 18:20:36.258  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:36.265  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:36.276  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:36.277  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:36.277  6980  6980 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 18:20:36.283  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:36.290  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:36.297  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:36.311  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:36.312  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 18:20:36.313  6980  6980 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 18:20:36.321  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:36.323  6827  7091 D UEI.SmartControl: Internal timer expired: 2
08-26 18:20:36.323  6827  7091 D UEI.SmartControl: unbind internal service
08-26 18:20:36.331  7465  7465 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-26 18:20:36.338  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:36.350  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:36.360  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 18:20:36.361  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:36.368  6980  6980 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 18:20:36.374  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 18:20:36.387  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:36.398  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:36.413  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 18:20:36.414  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:36.415  6980  6980 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 18:20:36.422  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:36.433  6827  7085 D serial_port: close(fd = 24)
,08-26 18:20:36.433  6952  6952 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 18:20:36.437  6827  7085 I UEI.SmartControl: Serial port is closed.
08-26 18:20:36.448  1034  1544 D WifiService: New client listening to asynchronous messages
08-26 18:20:36.449  6952  6952 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 18:20:36.455  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:36.462  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:36.466  7465  7465 D LgDataFeature: LgDataFeature() Constructor: none
08-26 18:20:36.467  7465  7465 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 18:20:36.474  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:36.475  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:36.477  6980  6980 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 18:20:36.479  6980  6980 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 18:20:36.480  6980  6980 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 18:20:36.491  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 18:20:36.496  6952  6952 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 18:20:36.498  6952  6952 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 18:20:36.504  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:36.511  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:36.525  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 18:20:36.525  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:36.527  6980  6980 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 18:20:36.528  7465  7465 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-26 18:20:36.529  6980  6980 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 18:20:36.530  6980  6980 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 18:20:36.535  1034  1907 I ActivityManager: Killing 6905:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-26 18:20:36.544  7465  7465 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 18:20:36.545  7465  7465 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 18:20:36.558  7465  7465 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 18:20:36.558  7465  7465 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-26 18:20:36.587  2140  2140 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-26 18:20:36.587  1034  1893 W libprocessgroup: failed to open /acct/uid_10037/pid_6905/cgroup.procs: No such file or directory
,08-26 18:20:36.601  3427  4202 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-26 18:20:36.603  3427  4202 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1f73c602 on behalf of 7465
08-26 18:20:36.606  2140  2140 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-26 18:20:36.607  2140  2140 D c       : Getting all permits...
08-26 18:20:36.607  2140  2140 D a       : Opening database...
08-26 18:20:36.617  2140  2140 D a       : Opening database auth.proximity.permit_store...
08-26 18:20:36.618  7465  7465 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-26 18:20:36.620  2140  2140 D a       : Closing database...
08-26 18:20:36.631  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 18:20:36.634  7465  7465 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-26 18:20:36.636  6952  6952 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 18:20:36.636  6952  6952 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 18:20:36.637  6952  6952 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 18:20:36.639  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:36.643  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 18:20:36.648  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:36.648  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:36.650  6980  6980 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 18:20:36.652  1034  1051 V SIM_STK : Menu title from STK is T-Mobile
08-26 18:20:36.653  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:36.656  6952  6952 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 18:20:36.656  6952  6952 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 18:20:36.656  6952  6952 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 18:20:36.660  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 18:20:36.666  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:36.672  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 18:20:36.672  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:36.673  6980  6980 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 18:20:36.677  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:36.679  6952  6952 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 18:20:36.679  6952  6952 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 18:20:36.679  6952  6952 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 18:20:36.681  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:36.686  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:36.693  6980  6980 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:36.694  6980  6980 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:36.695  6980  6980 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 18:20:36.701  6952  6952 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 18:20:36.705  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 18:20:36.714  7017  7508 W FormManager: Network not available. Please check & try again.
08-26 18:20:36.715  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:36.726  7017  7509 V FormManager: Network unavailable.
,08-26 18:20:36.730  7017  7509 V FormManager: Network unavailable.
08-26 18:20:36.740  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 18:20:36.740  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 18:20:36.743  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 18:20:36.745  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 18:20:36.756  4752  7510 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 18:20:36.759  4752  7511 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 18:20:36.760  4752  7511 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 18:20:36.765  6952  6952 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 18:20:36.766  6952  6952 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 18:20:36.766  6952  6952 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 18:20:36.772  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 18:20:36.776  7017  7513 W FormManager: Network not available. Please check & try again.
08-26 18:20:36.781  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:36.787  7017  7514 V FormManager: Network unavailable.
,08-26 18:20:36.790  7017  7514 V FormManager: Network unavailable.
08-26 18:20:36.806  6980  6980 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-26 18:20:36.807  6980  6980 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3458
08-26 18:20:36.813  2140  2140 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-26 18:20:36.837  4915  7515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-26 18:20:36.897  7465  7465 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-26 18:20:36.900  1034  1656 I ActivityManager: Killing 6997:com.lge.settings.easy/1000 (adj 15): empty #17
08-26 18:20:36.994  1034  1956 W libprocessgroup: failed to open /acct/uid_1000/pid_6997/cgroup.procs: No such file or directory
,08-26 18:20:37.319  1034  1539 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-945345209] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 18:20:37.320  1034  1539 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-945345208] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 18:20:37.550  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:37.558  1034  1110 D Tethering: MasterInitialState.processMessage what=3
08-26 18:20:37.563  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:37.563  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:37.568  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:37.572  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 18:20:37.573  6410  6440 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 18:20:37.584  5843  5843 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 18:20:37.602  2140  2140 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:37.621  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 18:20:37.622  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:37.622  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 18:20:37.622  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-26 18:20:37.626  7114  7114 I AppUp4:CustModeStarterReceiver: onReceive
08-26 18:20:37.630  7114  7114 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@380b1ef9
08-26 18:20:37.630  7114  7114 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 18:20:37.630  7114  7114 D AppUp4:CustFacade: isPhone : true
08-26 18:20:37.630  7114  7114 D AppUp4:CustModeStarterReceiver: begin check event
08-26 18:20:37.631  7114  7114 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 18:20:37.635  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:37.636  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 18:20:37.637  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 18:20:37.643  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 18:20:37.650  7141  7141 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 18:20:37.686  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 18:20:37.690  4752  7550 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:37.690  4752  7550 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 18:20:37.694  7017  7545 W FormManager: Network not available. Please check & try again.
08-26 18:20:37.696  4752  7546 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 18:20:37.699  3203  3203 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 18:20:37.699  3203  3203 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:37.699  3203  3203 I LgeMiscReceiver: networkInfo.isConnected() = true
08-26 18:20:37.699  3203  3203 D PhoneState: setPdpRejectCasuse : false
,08-26 18:20:37.702  7141  7547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 18:20:37.706  7182  7182 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 18:20:37.706  7182  7182 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 18:20:37.707  7017  7548 V FormManager: Network unavailable.
08-26 18:20:37.719  7252  7252 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:20:37
,08-26 18:20:37.722  7252  7252 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-26 18:20:37.722  7252  7252 D Weather.Utils: 2 : All the weather widget is gone.
,08-26 18:20:37.722  7252  7252 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 18:20:37.722  7017  7548 V FormManager: Network unavailable.
08-26 18:20:37.722  7252  7252 D WeatherAncestor: connectivity changed - connection : true
08-26 18:20:37.722  7252  7252 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@c9f949f
08-26 18:20:37.723  7252  7252 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 18:20:37.723  7252  7252 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 18:20:37.723  7252  7252 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 18:20:37.723  7252  7252 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 18:20:37.723  7252  7252 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:20:37
08-26 18:20:38.350  1034  1656 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:38.351  1034  1656 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 18:20:38.375  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 18:20:38.376  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 18:20:38.376  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-26 18:20:38.379  1034  1110 D BluetoothManagerService: Message: 1
08-26 18:20:38.379  1034  1110 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-26 18:20:38.409  1034  1110 D BluetoothManagerService: Message: 20
08-26 18:20:38.409  1034  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11cf73d1:true
,08-26 18:20:38.413  7058  7058 D BluetoothAdapterState: make
08-26 18:20:38.417  7058  7058 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 18:20:38.418  7058  7058 I bluedroid-qcom: init
08-26 18:20:38.419  7058  7565 I BluetoothAdapterState: Entering OffState
08-26 18:20:38.419  7058  7058 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 18:20:38.420  7058  7058 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 18:20:38.420  7058  7058 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 18:20:38.420  7058  7058 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 18:20:38.420  7058  7058 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 18:20:38.422  7058  7058 I bluedroid-qcom: get_profile_interface socket
08-26 18:20:38.422  7058  7058 I bluedroid-qcom: get_profile_interface map_client
,08-26 18:20:38.427  7058  7569 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 18:20:38.429  7058  7569 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 18:20:38.417  7568  7568 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:38.417  7568  7568 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:38.439  7568  7568 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 18:20:38.439  7568  7568 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 18:20:38.439  7568  7568 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-26 18:20:38.445  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:38.446  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 18:20:38.446  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 18:20:38.447  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:38.448  1034  1110 D Tethering: MasterInitialState.processMessage what=3
08-26 18:20:38.450  7568  7568 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 18:20:38.455  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:38.458  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:38.466  7568  7568 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 18:20:38.466  7568  7568 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-26 18:20:38.468  1034  1110 D Tethering: MasterInitialState.processMessage what=3
,08-26 18:20:38.472  7058  7569 D BluetoothAdapterProperties: Name is: G3
08-26 18:20:38.474  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:38.480  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:38.483  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:38.485  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 18:20:38.485  1034  1110 D BluetoothManagerService: Message: 40
08-26 18:20:38.485  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 18:20:38.486  7058  7074 I bluedroid-qcom: config_hci_snoop_log
08-26 18:20:38.487  1034  1110 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 18:20:38.488  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 18:20:38.498  7058  7565 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 18:20:38.498  7058  7565 D BluetoothAdapterProperties: Setting state to 11
08-26 18:20:38.499  7058  7565 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-26 18:20:38.508  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:38.509  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:38.509  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:38.510  7058  7565 I LGBluetoothServiceJni: classInitNative: succeeds
08-26 18:20:38.511  1034  1110 D BluetoothManagerService: Message: 60
08-26 18:20:38.511  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 18:20:38.511  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 18:20:38.515  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:38.518  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 18:20:38.520  6410  6440 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 18:20:38.523  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 18:20:38.529  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:38.531  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:38.537  6932  6932 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-26 18:20:38.544  7058  7565 D BluetoothBondStateMachine: make
08-26 18:20:38.547  5843  5843 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 18:20:38.549  7058  7582 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 18:20:38.549  7058  7565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:38.550  7058  7565 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 18:20:38.550  7058  7565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:38.550  7058  7565 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 18:20:38.550  7058  7565 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 18:20:38.555  7058  7565 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 18:20:38.559  7058  7058 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 18:20:38.559  5843  5843 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 18:20:38.560  7058  7058 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:38.560  7058  7058 V BluetoothPbapReceiver: ***********state = 11
08-26 18:20:38.567  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 18:20:38.567  7058  7058 D HeadsetService: Received start request. Starting profile...
08-26 18:20:38.568  7058  7565 E BluetoothAdapterService: File transfer profiles supported!!
08-26 18:20:38.568  7058  7058 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 18:20:38.568  7058  7058 D LGBluetoothHfpAdapter: Version 1.6
08-26 18:20:38.571  7058  7058 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-26 18:20:38.573  7058  7058 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 18:20:38.574  7058  7058 D HeadsetStateMachine: make
08-26 18:20:38.617  7058  7058 D LgDataFeature: LgDataFeature() Constructor: none
08-26 18:20:38.618  7058  7058 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 18:20:38.618  1034  1907 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7590 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-26 18:20:38.626  7058  7058 D HeadsetStateMachine: max_hf_connections = 1
08-26 18:20:38.626  7058  7058 I bluedroid-qcom: get_profile_interface handsfree
08-26 18:20:38.627  7058  7565 E BluetoothAdapterService: File transfer profiles supported!!
08-26 18:20:38.628  7058  7058 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 18:20:38.629   312  1383 V AudioPolicyService: registerClient() client 0xb1030ea0, uid 1002
08-26 18:20:38.631   312  2172 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 18:20:38.631   312  2172 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 18:20:38.631   312  2172 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 18:20:38.631  7058  7058 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 18:20:38.632   312   312 V AudioFlinger: registerClient() client 0xb55816b8, pid 7058
08-26 18:20:38.632   312  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 18:20:38.632   312  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 18:20:38.633  7058  7581 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 18:20:38.633   312  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-26 18:20:38.633   312  1378 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 18:20:38.633  1603  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 18:20:38.633  3203  3219 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 18:20:38.633  1603  1619 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 18:20:38.633  3203  3219 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 18:20:38.633  1603  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 18:20:38.633  3203  3219 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 18:20:38.633  1603  1619 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 18:20:38.633  3203  3219 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 18:20:38.633  1855  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 18:20:38.633  1855  1870 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 18:20:38.633  1855  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 18:20:38.633  1855  1870 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-26 18:20:38.633  1034  1908 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 18:20:38.634  1034  1908 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 18:20:38.634  7058  7058 V ToneGenerator: Create Track: 0xb4928a80
08-26 18:20:38.634  1034  1908 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 18:20:38.634  7058  7058 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 18:20:38.634  1034  1908 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 18:20:38.634  7058  7058 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 18:20:38.634   312  1382 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 18:20:38.634   312  1382 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 18:20:38.634   312  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 18:20:38.634   312  1382 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 18:20:38.635  7058  7581 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 18:20:38.635  7058  7581 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 18:20:38.635  7058  7581 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 18:20:38.635   312  1383 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 18:20:38.636   312  2172 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 18:20:38.636   312  2172 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 18:20:38.636   312  2172 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 18:20:38.636   312  2172 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 18:20:38.636  7058  7058 V AudioSystem: getLatency() output 2, latency 50
08-26 18:20:38.636  7058  7058 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 18:20:38.636  7058  7058 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 18:20:38.637  7058  7565 E BluetoothAdapterService: File transfer profiles supported!!
08-26 18:20:38.637   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 18:20:38.637   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 18:20:38.637   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 18:20:38.637   312   312 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 18:20:38.637   312   312 V AudioFlinger: createTrack() lSessionId: 22
08-26 18:20:38.638  7058  7058 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 18:20:38.639   312  2175 V AudioFlinger: acquiring 22 from 7058, for 7058
08-26 18:20:38.639   312  2175 V AudioFlinger:  added new entry for 22
08-26 18:20:38.639  7058  7058 V ToneGenerator: ToneGenerator INIT OK, time: 129556
08-26 18:20:38.639  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:38.640  7058  7584 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 18:20:38.640  7058  7584 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 18:20:38.640  7058  7584 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 18:20:38.640  7058  7584 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 18:20:38.641  2140  2140 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:38.643   312  1382 V AudioFlin,ger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7058
08-26 18:20:38.643  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:38.643   312  1382 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 18:20:38.643   312  1382 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 18:20:38.643   312  1382 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 18:20:38.643   312  1382 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 18:20:38.643   312  1382 V voice   : voice_set_parameters: exit with code(0)
08-26 18:20:38.643   312  1382 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 18:20:38.643   312  1382 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 18:20:38.644   312  1382 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 18:20:38.644   312  1382 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 18:20:38.644   312  1382 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 18:20:38.644   312  1382 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 18:20:38.644  7058  7584 V ToneGenerator: ToneGenerator destructor
08-26 18:20:38.644  7058  7584 V ToneGenerator: stopTone
08-26 18:20:38.644  7058  7584 V ToneGenerator: Delete Track: 0xb4928a80
08-26 18:20:38.645  7058  7584 V AudioTrack: ~AudioTrack, releasing session id from 7058 on behalf of 7058
08-26 18:20:38.645   312  1383 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 18:20:38.645   312  1383 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 18:20:38.645   312  1383 V AudioFlinger: PlaybackThread::Track destructor
08-26 18:20:38.645   312  1267 V AudioPolicyService: AudioCommandThread() waking up
08-26 18:20:38.645   312  1383 V AudioFlinger: removeClient_l() pid 7058, calling pid 312
08-26 18:20:38.645   312  1267 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 18:20:38.645   312  1267 V AudioPolicyManager: releaseOutput() 2
08-26 18:20:38.645   312  1267 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 18:20:38.647   312  1382 V AudioFlinger: releasing 22 from 7058 for 7058
08-26 18:20:38.647   312  1382 V AudioFlinger:  decremented refcount to 0
08-26 18:20:38.647  7058  7058 D A2dpService: Received start request. Starting profile...
08-26 18:20:38.648   312  1382 V AudioFlinger: purging stale effects
08-26 18:20:38.648  7058  7058 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 18:20:38.649  7058  7058 V Avrcp   : make
08-26 18:20:38.650  7058  7058 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 18:20:38.650  7058  7058 I bluedroid-qcom: get_profile_interface avrcp
08-26 18:20:38.653  7058  7565 E BluetoothAdapterService: File transfer profiles supported!!
08-26 18:20:38.654  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 18:20:38.654  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:38.654  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 18:20:38.654  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 18:20:38.656  7114  7114 I AppUp4:CustModeStarterReceiver: onReceive
08-26 18:20:38.662  7058  7565 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 18:20:38.663  7058  7058 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 18:20:38.665  7058  7058 E AudioManager: No RCC entry present to update
08-26 18:20:38.665  7058  7058 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 18:20:38.666  7114  7114 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@380b1ef9
08-26 18:20:38.666  7114  7114 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 18:20:38.667  7114  7114 D AppUp4:CustFacade: isPhone : true
08-26 18:20:38.667  7114  7114 D AppUp4:CustModeStarterReceiver: begin check event
08-26 18:20:38.667  7114  7114 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 18:20:38.668  7058  7565 E BluetoothAdapterService: File transfer profiles supported!!
08-26 18:20:38.669  7058  7058 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 18:20:38.670  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 18:20:38.670  7058  7058 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 18:20:38.671  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:38.671  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 18:20:38.673  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 18:20:38.676  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 18:20:38.676  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-26 18:20:38.683  4752  7610 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 18:20:38.685  4752  7611 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:38.685  4752  7611 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 18:20:38.688  7058  7565 V LGMDMManager: Create singleton instance
08-26 18:20:38.690  7058  7565 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 18:20:38.742  7141  7141 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 18:20:38.766  3203  3203 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 18:20:38.766  3203  3203 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:38.768  3203  3203 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 18:20:38.773  7182  7182 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 18:20:38.774  7182  7182 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 18:20:38.774  7141  7613 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:38.786  1034  1908 V SIM_STK : Menu title from STK is T-Mobile
08-26 18:20:38.786  1034  1908 V SIM_STK : Menu title from STK is T-Mobile
,08-26 18:20:38.789  7252  7252 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:20:38
08-26 18:20:38.791  7252  7252 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.,
08-26 18:20:38.791  7252  7252 D Weather.Utils: 2 : All the weather widget is gone.
08-26 18:20:38.792  7252  7252 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 18:20:38.792  7252  7252 D WeatherAncestor: connectivity changed - connection : true
08-26 18:20:38.792  7252  7252 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@c9f949f
08-26 18:20:38.793  7252  7252 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 18:20:38.793  7252  7252 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 18:20:38.793  7252  7252 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 18:20:38.793  7252  7252 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 18:20:38.793  7252  7252 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:20:38
08-26 18:20:38.793  7017  7615 W FormManager: Network not available. Please check & try again.
08-26 18:20:38.801  7017  7616 V FormManager: Network unavailable.
,08-26 18:20:38.810  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 18:20:38.811  6410  6440 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 18:20:38.819  7017  7616 V FormManager: Network unavailable.
,08-26 18:20:38.824  7590  7590 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 18:20:38.824  7590  7590 W LG Account v2.2: No ProfileInfo entries
08-26 18:20:38.825  7590  7590 I LG Account v2.2: isEnabled: false
08-26 18:20:38.825  7590  7590 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 18:20:38.825  7590  7590 I Feature : [Lifetracker]Country: EU
08-26 18:20:38.825  7590  7590 I Feature : [Lifetracker]Operator: OPEN
08-26 18:20:38.825  7590  7590 I Feature : [Lifetracker]Ranking support: false
08-26 18:20:38.825  7590  7590 I Feature : [Lifetracker]Comfort support: false
08-26 18:20:38.825  7590  7590 I Feature : [Lifetracker]Accessory: true
08-26 18:20:38.825  7590  7590 I Feature : [Lifetracker]Health device: true
08-26 18:20:38.825  7590  7590 I Feature : [Lifetracker]Extra Pedometer: false
08-26 18:20:38.825  7590  7590 I Feature : [Lifetracker]Blood glucose device: false
08-26 18:20:38.825  7590  7590 I Feature : [Lifetracker]Device Number: 3
08-26 18:20:38.835  1034  2032 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 18:20:38.836  2140  2140 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:38.837  6932  6932 D BluetoothPermissionRequest: onReceive
,08-26 18:20:38.840  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 18:20:38.841  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 18:20:38.842  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 18:20:38.843  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 18:20:38.843  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 18:20:38.843  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 18:20:38.843  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 18:20:38.843  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 18:20:38.843  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 18:20:38.843  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 18:20:38.843  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 18:20:38.843  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 18:20:38.844  7058  7058 I BluetoothA2dpServiceJni: classInitNative
08-26 18:20:38.844  7058  7058 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 18:20:38.844  7058  7058 D A2dpStateMachine: make
08-26 18:20:38.845  7058  7058 I bluedroid-qcom: get_profile_interface a2dp
08-26 18:20:38.845  7058  7620 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 18:20:38.847  7058  7058 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 18:20:38.847  7058  7058 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-26 18:20:38.847  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 18:20:38.847  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:38.848  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 18:20:38.848  7114  7114 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 18:20:38.848  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:38.848  7058  7058 D HeadsetStateMachine: Proxy object connected
08-26 18:20:38.849  7058  7058 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 18:20:38.849  7114  7114 I AppUp4:CustModeStarterReceiver: onReceive
08-26 18:20:38.850  7058  7619 D A2dpStateMachine: Enter Disconnected: -2
08-26 18:20:38.849  7058  7058 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-26 18:20:38.851  7058  7058 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 18:20:38.852  7114  7114 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@380b1ef9
08-26 18:20:38.852  7114  7114 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 18:20:38.852  7114  7114 D AppUp4:CustFacade: isPhone : true
08-26 18:20:38.852  7114  7114 D AppUp4:CustModeStarterReceiver: begin check event
08-26 18:20:38.853  7114  7114 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 18:20:38.853  7058  7058 D HidService: Received start request. Starting profile...
08-26 18:20:38.853  7058  7058 I bluedroid-qcom: get_profile_interface hidhost
08-26 18:20:38.853  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:38.854  7058  7058 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 18:20:38.854  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:38.855  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 18:20:38.855  7058  7058 D HealthService: Received start request. Starting profile...
08-26 18:20:38.856  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 18:20:38.857  7058  7058 I bluedroid-qcom: get_profile_interface health
08-26 18:20:38.857  7058  7058 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 18:20:38.857  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:38.857  7058  7584 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 18:20:38.858  7058  7584 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 18:20:38.858  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 18:20:38.858  7058  7584 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 18:20:38.861  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 18:20:38.861  7058  7058 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 18:20:38.863  7058  7058 D PanService: Received start request. Starting profile...
08-26 18:20:38.863  7058  7058 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 18:20:38.863  7058  7058 I bluedroid-qcom: get_profile_interface pan
08-26 18:20:38.864  7141  7141 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 18:20:38.867  4752  7624 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 18:20:38.868  7058  7058 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 18:20:38.868  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:38.869  7058  7058 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 18:20:38.873  4752  7627 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:38.873  4752  7627 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 18:20:38.874  7058  7058 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 18:20:38.875  7058  7058 D BtGatt.GattService: Received start request. Starting profile...
08-26 18:20:38.875  7058  7058 D BtGatt.GattService: start()
08-26 18:20:38.875  7058  7058 I bluedroid-qcom: get_profile_interface gatt
08-26 18:20:38.875  7058  7058 D BtGatt.AdvertiseManager: advertise manager created
08-26 18:20:38.878  7141  7628 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:38.882  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:38.884  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:38.884  7058  7058 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 18:20:38.884  3203  3203 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-26 18:20:38.884  3203  3203 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:38.884  3203  3203 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 18:20:38.885  7058  7058 V BluetoothMapService: BluetoothMapBinder()
08-26 18:20:38.885  7058  7058 D BluetoothMapService: Received start request. Starting profile...
08-26 18:20:38.885  7058  7058 D BluetoothMapService: start()
08-26 18:20:38.886  7182  7182 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 18:20:38.886  7182  7182 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 18:20:38.891  7058  7058 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 18:20:38.891  7058  7058 D BluetoothMapEmailAppObserver: createReceiver()
08-26 18:20:38.893  7058  7058 D BluetoothMapEmailAppObserver: initObservers()
08-26 18:20:38.893  7058  7058 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 18:20:38.893  7017  7633 W FormManager: Network not available. Please check & try again.
08-26 18:20:38.899  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:38.899  7252  7252 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:20:38
,08-26 18:20:38.903  7252  7252 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 18:20:38.903  7252  7252 D Weather.Utils: 2 : All the weather widget is gone.
08-26 18:20:38.903  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 18:20:38.904  7252  7252 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 18:20:38.904  7252  7252 D WeatherAncestor: connectivity changed - connection : true
08-26 18:20:38.904  7017  7634 V FormManager: Network unavailable.
08-26 18:20:38.904  7252  7252 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@c9f949f
08-26 18:20:38.905  7252  7252 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 18:20:38.905  7252  7252 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 18:20:38.905  7252  7252 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 18:20:38.905  7252  7252 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 18:20:38.905  7252  7252 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:20:38
08-26 18:20:38.906  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 18:20:38.908  7017  7634 V FormManager: Network unavailable.
08-26 18:20:38.909  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 18:20:38.909  7058  7058 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 18:20:38.911  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 18:20:38.915  7058  7058 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-26 18:20:38.916  7058  7058 V BluetoothMapService: Handler(): got msg=1
08-26 18:20:38.916  7058  7565 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 18:20:38.916  7058  7565 I bluedroid-qcom: enable
08-26 18:20:38.917  7058  7565 I bt_hci_bdroid: init
08-26 18:20:38.917  7058  7565 I bt_vendor: bt-vendor : init
08-26 18:20:38.917  7058  7565 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 18:20:38.917  7058  7565 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 18:20:38.917  7058  7565 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 18:20:38.917  7058  7565 D bt_userial_mct: userial_init
08-26 18:20:38.918  7058  7635 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 18:20:38.918  7058  7565 D bt_hci_bdroid: set_power 1
08-26 18:20:38.918  7058  7565 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 18:20:38.918  7058  7565 I bt_vendor: Starting hciattach daemon
08-26 18:20:38.918  7058  7565 I bt_vendor: try to set true
08-26 18:20:38.919  7058  7635 I bt-btu  : btu_task pending for preload complete event
08-26 18:20:38.919  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:38.907  7638  7638 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:38.907  7638  7638 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:38.922  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 18:20:38.922  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 18:20:38.922  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 18:20:38.922  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:38.922  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 18:20:38.935  7639  7639 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 18:20:38.965  1034  1656 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7643 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 18:20:38.990   339   339 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 480us total 23.771ms
08-26 18:20:39.006  7662  7662 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
08-26 18:20:39.007  7643  7643 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 18:20:39.013  7663  7663 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-26 18:20:39.014   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 22.313ms
08-26 18:20:39.019  1034  1990 I ActivityManager: Killing 7444:com.lge.bnr/1000 (adj 15): empty #17
,08-26 18:20:39.027  7665  7665 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-26 18:20:39.033   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 404us total 18.485ms
,08-26 18:20:39.036  7666  7666 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-26 18:20:39.044  7667  7667 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 18:20:39.055  7668  7668 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-26 18:20:39.063  1034  1656 W libprocessgroup: failed to open /acct/uid_1000/pid_7444/cgroup.procs: No such file or directory
,08-26 18:20:39.076  7670  7670 I libmdmdetect: ESOC framework not supported
08-26 18:20:39.077  7670  7670 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 18:20:39.085  7670  7670 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-26 18:20:39.085  7670  7670 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 18:20:39.085  7670  7670 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 18:20:39.085  7670  7670 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 18:20:39.085  7670  7670 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 18:20:39.085  7670  7670 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 18:20:39.085  7670  7670 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 18:20:39.125  7670  7671 E QC-QMI  : qmi_client [7670] 14: failed to locate client data
08-26 18:20:39.126   479   479 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-26 18:20:39.126   479   479 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-26 18:20:39.173  7672  7672 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 18:20:39.187  7673  7673 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 18:20:39.220  7058  7565 I bt_vendor: bluetooth satus is on
08-26 18:20:39.220  7058  7565 D bt_hci_bdroid: preload
08-26 18:20:39.220  7058  7637 D bt_userial_mct: userial_open(port:0)
08-26 18:20:39.220  7058  7637 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 18:20:39.224  7058  7637 I bt_vendor: Done intiailizing UART
,08-26 18:20:39.225  7058  7637 I bt_vendor: Done intiailizing UART
,08-26 18:20:39.225  7058  7637 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 18:20:39.225  7058  7637 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 18:20:39.226  7058  7635 I bt-btu  : btu_task received preload complete event
08-26 18:20:39.226  7058  7675 D bt_userial_mct: Entering userial_read_thread()
08-26 18:20:39.227  7058  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 18:20:39.227  7058  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 18:20:39.232  7058  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-26 18:20:39.237  7058  7635 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 18:20:39.237  7058  7635 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 18:20:39.237  7058  7635 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
08-26 18:20:39.238  7058  7635 I         : BTE_InitTraceLevels -- TRC_AVDT,
08-26 18:20:39.238  7058  7635 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 18:20:39.238  7058  7635 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 18:20:39.238  7058  7635 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 18:20:39.238  7058  7635 I         : BTE_InitTraceLevels -- TRC_BTM,
08-26 18:20:39.238  7058  7635 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-26 18:20:39.238  7058  7635 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 18:20:39.238  7058  7635 I         : BTE_InitTraceLevels -- TRC_PAN
,08-26 18:20:39.238  7058  7635 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 18:20:39.238  7058  7635 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 18:20:39.238  7058  7635 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 18:20:39.239  7058  7635 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 18:20:39.239  7058  7635 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 18:20:39.285  1034  1091 W ProcessCpuTracker: Skipping unknown process pid 7585
,08-26 18:20:39.286  1034  1091 W ProcessCpuTracker: Skipping unknown process pid 7588
08-26 18:20:39.296  7058  7635 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-26 18:20:39.296  7058  7635 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0195061 
08-26 18:20:39.296  7058  7635 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0195061 
,08-26 18:20:39.310  7058  7569 E bt-btif : Calling BTA_HhEnable
08-26 18:20:39.310  7058  7569 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-26 18:20:39.311  7058  7569 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 18:20:39.311  7058  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-26 18:20:39.311  7058  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 18:20:39.312  7058  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 18:20:39.312  7058  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 18:20:39.312  7058  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 18:20:39.312  7058  7569 D BluetoothAdapterProperties: Name is: G3
08-26 18:20:39.312  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 18:20:39.313  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
,08-26 18:20:39.315  7058  7569 D BluetoothAdapterProperties: Scan Mode:20
08-26 18:20:39.315  7058  7569 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 18:20:39.316  7058  7569 D bt_hci_bdroid: postload
08-26 18:20:39.316  7058  7637 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 18:20:39.316  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:39.317  7058  7635 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 18:20:39.317  7058  7637 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 18:20:39.317  7058  7569 D bte_conf: Device ID record 1 : primary
08-26 18:20:39.317  7058  7569 D bte_conf:   vendorId            = 00c4
08-26 18:20:39.317  7058  7569 D bte_conf:   vendorIdSource      = 0001
08-26 18:20:39.317  7058  7569 D bte_conf:   product             = 13a1
08-26 18:20:39.317  7058  7569 D bte_conf:   version             = 1000
08-26 18:20:39.317  7058  7569 D bte_conf:   clientExecutableURL = 
08-26 18:20:39.317  7058  7569 D bte_conf:   serviceDescription  = 
08-26 18:20:39.317  7058  7569 D bte_conf:   documentationURL    = 
08-26 18:20:39.317  7058  7569 D bte_conf: bte_load_did_conf no section named DID2.
08-26 18:20:39.318  7058  7637 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 18:20:39.318  7058  7637 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 18:20:39.318  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:39.323  7058  7569 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 18:20:39.317  7680  7680 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:39.317  7680  7680 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:39.324  7058  7635 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 18:20:39.324  7058  7635 W bt-smp  : Plain text(LSB ~ MSB) = c3 68 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 18:20:39.324  7058  7635 W bt-smp  : Encrypted text(LSB ~ MSB) = 03 9e 5b 4d 98 aa 03 87 54 c6 e4 22 fc aa 83 d8 
08-26 18:20:39.324  7058  7635 W bt-btm  : Stopping oneshot timer
08-26 18:20:39.325  7058  7637 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 18:20:39.325  7058  7565 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 18:20:39.325  7058  7565 D BluetoothAdapterProperties: ScanMode =  20
08-26 18:20:39.325  7058  7565 D BluetoothAdapterProperties: State =  11
08-26 18:20:39.326  7058  7565 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 18:20:39.326  7058  7565 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 18:20:39.326  7058  7565 D BluetoothAdapterProperties: Setting state to 12
08-26 18:20:39.326  7058  7565 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 18:20:39.327  7058  7569 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 18:20:39.328  7058  7675 E bt_mct  : hci lib postload completed
08-26 18:20:39.331  1034  1110 D BluetoothManagerService: Message: 60
08-26 18:20:39.331  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 18:20:39.331  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-26 18:20:39.331  6932  6947 D BluetoothPan: onBluetoothStateChange on: true
08-26 18:20:39.332  6932  6947 D BluetoothPan: onBluetoothStateChange call bindService
08-26 18:20:39.332  7058  7565 I BluetoothAdapterState: Entering On State
08-26 18:20:39.336  7058  7565 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 18:20:39.336  7058  7565 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 18:20:39.336  7058  7565 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-26 18:20:39.337  1034  1110 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 18:20:39.337  7058  7565 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-26 18:20:39.340  1034  1110 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 18:20:39.341  6932  6932 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 18:20:39.341  6932  6932 D PanProfile: Bluetooth service connected
08-26 18:20:39.342  1855  3501 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 18:20:39.344  1034  1034 D BluetoothHeadset: Proxy object connected
08-26 18:20:39.348  1034  1034 D BluetoothA2dp: Proxy object connected
08-26 18:20:39.351  1855  1855 D BluetoothHeadset: Proxy object connected
08-26 18:20:39.351  7058  7635 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 18:20:39.351  7058  7635 W bt-smp  : Plain text(LSB ~ MSB) = 1b 2f 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-26 18:20:39.351  7058  7635 W bt-smp  : Encrypted text(LSB ~ MSB) = 9a 05 60 21 42 b6 33 09 55 1a 4b d0 2c ed e7 3d 
08-26 18:20:39.351  7058  7635 W bt-btm  : Stopping oneshot timer
08-26 18:20:39.352  6932  6947 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 18:20:39.363  6932  6947 D BluetoothMap: onBluetoothStateChange: up=true
08-26 18:20:39.366  6932  6932 D BluetoothInputDevice: Proxy object connected
08-26 18:20:39.366  6932  6932 D HidProfile: Bluetooth service connected
08-26 18:20:39.370  1855  4393 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 18:20:39.372  6932  6932 D BluetoothMap: Proxy object connected
08-26 18:20:39.372  6932  6932 D MapProfile: Bluetooth service connected
08-26 18:20:39.372  6932  6932 D BluetoothMap: getConnectedDevices()
08-26 18:20:39.374  7058  7074 V BluetoothMapService: getConnectedDevices()
08-26 18:20:39.374  1855  1855 D BluetoothHeadset: Proxy object connected
08-26 18:20:39.375  1855  1871 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 18:20:39.375  7058  7635 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 18:20:39.375  7058  7635 W bt-smp  : Plain text(LSB ~ MSB) = 24 f9 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 18:20:39.375  7058  7635 W bt-smp  : Encrypted text(LSB ~ MSB) = df dc cd 7c dc a3 79 1a e8 a3 df 8c 6b 14 14 d8 
08-26 18:20:39.375  7058  7635 W bt-btm  : Stopping oneshot timer
08-26 18:20:39.382  7058  7565 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-26 18:20:39.393  7058  7635 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 18:20:39.393  7058  7635 W bt-smp  : Plain text(LSB ~ MSB) = 5e 47 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 18:20:39.393  7058  7635 W bt-smp  : Encrypted text(LSB ~ MSB) = bb 52 eb ee 18 38 01 7e 58 28 06 67 a8 7a b1 a4 
08-26 18:20:39.393  7058  7635 W bt-btm  : Stopping oneshot timer
08-26 18:20:39.402  7058  7569 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 18:20:39.403  7058  7569 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-26 18:20:39.410  7686  7686 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 18:20:39.412  7058  7635 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-26 18:20:39.412  7058  7635 W bt-smp  : Plain text(LSB ~ MSB) = 50 0c 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 18:20:39.412  7058  7635 W bt-smp  : Encrypted text(LSB ~ MSB) = 97 12 54 09 94 07 37 dd 3d f7 a2 c2 03 10 01 fe 
08-26 18:20:39.412  7058  7635 W bt-btm  : Stopping oneshot timer
08-26 18:20:39.534  1034  1110 I art     : Explicit concurrent mark sweep GC freed 102081(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.538ms total 157.414ms
08-26 18:20:39.535  1855  1855 D BluetoothHeadset: Proxy object connected
08-26 18:20:39.536  6932  7683 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 18:20:39.542  1034  1110 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 18:20:39.544  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 18:20:39.544  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 18:20:39.545  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:39.546  1944  2104 D LGBluetoothAPIService: Message: 1
08-26 18:20:39.546  1944  2104 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 18:20:39.549  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 18:20:39.553  1034  1110 D BluetoothManagerService: Message: 40
08-26 18:20:39.553  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-26 18:20:39.556  6669  6669 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 18:20:39.560  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:39.560  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:39.560  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:39.560  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:39.560  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:39.560  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:39.560  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:39.560  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:39.562  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:39.563  1944  2104 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-26 18:20:39.565  7058  7058 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:39.566  7058  7058 D BluetoothMapService: STATE_ON
08-26 18:20:39.567  6932  6932 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 18:20:39.567  7058  7058 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 18:20:39.567  7058  7058 D LGBluetoothAPIServer: [BTUI] onBind()
,08-26 18:20:39.569  1944  1944 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 18:20:39.569  1034  1110 D BluetoothManagerService: Message: 30
08-26 18:20:39.569  1944  2104 D LGBluetoothAPIService: Message: 100
08-26 18:20:39.569  1944  2104 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 18:20:39.571  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:39.571  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:39.571  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:39.571  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:39.571  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:39.571  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:39.571  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:39.571  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:39.572  6932  6932 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-26 18:20:39.575  1034  1110 D BluetoothManagerService: Message: 30
08-26 18:20:39.578  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:39.580  6932  6932 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-26 18:20:39.582  6932  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 18:20:39.586  6932  6932 D BluetoothA2dp: Proxy object connected
08-26 18:20:39.586  6932  6932 D A2dpProfile: Bluetooth service connected
08-26 18:20:39.588  6932  6932 D BluetoothHeadset: Proxy object connected
08-26 18:20:39.589  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:39.589  6932  6932 D HeadsetProfile: Bluetooth service connected
08-26 18:20:39.589  7058  7058 V BluetoothPbapService: Pbap Service onCreate
08-26 18:20:39.589  7058  7058 V BluetoothPbapService: Starting PBAP service
08-26 18:20:39.591  7058  7058 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 18:20:39.591  7058  7058 V BluetoothMapService: Handler(): got msg=1
08-26 18:20:39.591  7058  7058 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 18:20:39.592  7058  7058 V BluetoothPbapService: Pbap Service onBind
08-26 18:20:39.593  7058  7695 D BluetoothMapMasInstance: MAS initSocket()
,08-26 18:20:39.593  7058  7058 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:39.593  7058  7058 V BluetoothPbapService: state: 12
08-26 18:20:39.594  7058  7058 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 18:20:39.594  7058  7058 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:39.594  7058  7058 V BluetoothPbapReceiver: ***********state = 12
08-26 18:20:39.595  7058  7695 D BluetoothMapMasInstance:   masId = 00
08-26 18:20:39.595  7058  7695 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 18:20:39.595  7058  7695 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 18:20:39.595  7058  7695 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 18:20:39.595  6932  6932 D DockEventReceiver: finishStartingService: stopping service
08-26 18:20:39.596  6932  6932 D BluetoothPbap: Proxy object connected
08-26 18:20:39.596  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:39.597  6932  6932 D PbapServerProfile: Bluetooth service connected
08-26 18:20:39.598  7058  7695 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 18:20:39.598  7058  7058 V BluetoothPbapService: Handler(): got msg=1
08-26 18:20:39.599  7058  7058 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 18:20:39.600  7058  7697 V BluetoothPbapService: Pbap Service initSocket
08-26 18:20:39.602  1034  2053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:39.603  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 18:20:39.604  7058  7695 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 18:20:39.604  2140  2140 D c       : Getting all permits...
08-26 18:20:39.604  2140  2140 D a       : Opening database...
08-26 18:20:39.604  7058  7695 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 18:20:39.604  7058  7695 D BluetoothMapMasInstance: Accepting socket connection...
08-26 18:20:39.605  7058  7569 D BluetoothAdapterProperties: Scan Mode:21
08-26 18:20:39.606  7058  7569 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-26 18:20:39.608  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:39.609  2140  2140 D a       : Opening database auth.proximity.permit_store...
08-26 18:20:39.609  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:39.610  2140  2140 D a       : Closing database...
08-26 18:20:39.611  7058  7697 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 18:20:39.612  7058  7697 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 18:20:39.612  7058  7697 V BluetoothPbapService: Succeed to create listening socket 
08-26 18:20:39.612  7058  7697 V BluetoothPbapService: Accepting socket connection...
08-26 18:20:39.621  6932  6932 D BluetoothPermissionRequest: onReceive
,08-26 18:20:39.623  6932  6932 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 18:20:39.625  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 18:20:39.629  7058  7058 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 18:20:39.630  7058  7058 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 18:20:39.638  7058  7058 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-26 18:20:39.664  7058  7058 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-26 18:20:39.665  7058  7058 V BtOppService: onCreate
08-26 18:20:39.669  7058  7058 V BluetoothOppNotification: send message
08-26 18:20:39.672  7058  7058 V BtOppService: Starting RfcommListener
08-26 18:20:39.678  7058  7058 D BluetoothOppPreference: Dumping Names:  
08-26 18:20:39.678  7058  7058 D BluetoothOppPreference: {}
08-26 18:20:39.678  7058  7058 D BluetoothOppPreference: Dumping Channels:  
,08-26 18:20:39.678  7058  7058 D BluetoothOppPreference: {}
08-26 18:20:39.682  7058  7058 V BtOppService: onStartCommand
08-26 18:20:39.683  7058  7703 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 18:20:39.688  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:39.689  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 18:20:39.693  7058  7700 V BtOppService: Deleted complete outbound shares, number =  0
,08-26 18:20:39.695  7058  7700 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 18:20:39.696  7058  7058 V BluetoothOppNotification: new notify threadi!
08-26 18:20:39.696  7058  7703 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 18:20:39.696  7058  7700 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 18:20:39.697  7058  7058 V BluetoothOppNotification: send delay message
08-26 18:20:39.699  7058  7705 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 18:20:39.699  7058  7058 V BtOppService: start RfcommListener
08-26 18:20:39.702  7058  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ebc2a68 on behalf of 
08-26 18:20:39.704  7058  7703 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f79ee81 on behalf of 
,08-26 18:20:39.706  7278  7315 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-26 18:20:39.707  7058  7703 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 18:20:39.708  7058  7703 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 18:20:39.708  7058  7705 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@265c0b26 on behalf of 
08-26 18:20:39.710  7058  7703 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25fa8367 on behalf of 
08-26 18:20:39.711  7058  7058 V BtOppService: RfcommListener started
08-26 18:20:39.712  7058  7705 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 18:20:39.712  7058  7058 V BtOppService: ContentObserver received notification
08-26 18:20:39.713  7058  7703 V BluetoothOppNotification: update too frequent, put in queue
08-26 18:20:39.713  7058  7705 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 18:20:39.715  7058  7703 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 18:20:39.715  7058  7705 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@85d8514 on behalf of 
08-26 18:20:39.715  7058  7703 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 18:20:39.716  7058  7705 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 18:20:39.718  7058  7705 V BluetoothOppNotification: outbound notification was removed.
08-26 18:20:39.718  7058  7705 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-26 18:20:39.718  7058  7703 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fd5f1bd on behalf of 
08-26 18:20:39.719  7058  7703 V BluetoothOppNotification: update too frequent, put in queue
,08-26 18:20:39.722  7058  7705 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22edb3b2 on behalf of 
08-26 18:20:39.723  7058  7707 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 18:20:39.724  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:39.724  7058  7703 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 18:20:39.726  7058  7707 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 18:20:39.727  7058  7707 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
,08-26 18:20:39.728  7058  7707 V BtOppRfcommListener: Started RFCOMM listener....
08-26 18:20:39.728  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:39.728  7058  7707 I BtOppRfcommListener: Accept thread started.
08-26 18:20:39.728  7058  7707 V BtOppRfcommListener: Accepting connection...
08-26 18:20:39.728  7058  7058 V BluetoothFtpService: Ftp Service onCreate
08-26 18:20:39.728  7058  7058 I BluetoothFtpService: Ftp Service onCreate
08-26 18:20:39.728  7058  7058 V BluetoothFtpService: Ftp Service onStartCommand
08-26 18:20:39.728  7058  7058 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:39.728  7058  7058 V BluetoothFtpService: Starting Listening on sockets
08-26 18:20:39.729  7058  7058 V BtOppService: ContentObserver received notification
08-26 18:20:39.729  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 18:20:39.729  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 18:20:39.729  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 18:20:39.729  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:39.729  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 18:20:39.730  7058  7058 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 18:20:39.732  7058  7708 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 18:20:39.732  7058  7708 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 18:20:39.733  7058  7705 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 18:20:39.733  7058  7058 V BluetoothFtpService: Handler(): got msg=1
,08-26 18:20:39.735  7058  7058 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 18:20:39.736  7058  7058 V BluetoothFtpService: Ftp Service initSocket
08-26 18:20:39.741  1034  1893 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:39.741  7058  7708 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17de80 on behalf of 
08-26 18:20:39.741  7058  7708 V BluetoothOppNotification: update too frequent, put in queue
08-26 18:20:39.742  7058  7058 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 18:20:39.742  7058  7708 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 18:20:39.742  7058  7705 V BluetoothOppNotification: inbound notification was removed.
08-26 18:20:39.742  7058  7058 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-26 18:20:39.743  7058  7705 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 18:20:39.743  7058  7058 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 18:20:39.745  7058  7705 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26f4ecb9 on behalf of 
,08-26 18:20:39.748  7058  7709 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-26 18:20:39.759  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:39.759  7058  7058 V BluetoothSapService: Sap Service onCreate
08-26 18:20:39.761  7058  7058 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:39.761  7058  7058 V BluetoothSapService: state: 12
,08-26 18:20:39.761  7058  7058 V BluetoothSapService: Starting SAP server process
08-26 18:20:39.757  7710  7710 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:39.764  7058  7058 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 18:20:39.757  7710  7710 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:39.766  7058  7711 V BluetoothSapService: Sap Service initRfcommSocket
08-26 18:20:39.767  1034  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:39.768  7058  7711 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 18:20:39.769  7058  7711 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
,08-26 18:20:39.769  7058  7711 V BluetoothSapService: Succeed to create listening socket 
08-26 18:20:39.769  7058  7711 V BluetoothSapService: Accepting socket connection...
08-26 18:20:39.779  7710  7710 V BT_SAP  : Event pipe created
08-26 18:20:39.780  7710  7710 V BT_SAP  : create_server_socket qcom.sap.server
08-26 18:20:39.780  7710  7710 V BT_SAP  : created socket fd 6
,08-26 18:20:40.401  1034  1538 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 18:20:40.401  1034  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 18:20:40.440  1034  1539 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 18:20:40.442  1034  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 18:20:40.699  7058  7058 V BluetoothOppNotification: new notify threadi!
,08-26 18:20:40.700  7058  7058 V BluetoothOppNotification: send delay message
,08-26 18:20:40.728  1034  1050 I ActivityManager: Killing 7465:com.android.vending/u0a44 (adj 15): empty #17
,08-26 18:20:40.735  7058  7721 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 18:20:40.740  7058  7721 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@386e9b75 on behalf of 
08-26 18:20:40.741  7058  7721 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 18:20:40.743  7058  7721 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-26 18:20:40.747  7058  7721 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2bf4070a on behalf of 
08-26 18:20:40.748  7058  7721 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 18:20:40.753  7058  7721 V BluetoothOppNotification: outbound notification was removed.
08-26 18:20:40.753  7058  7721 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 18:20:40.755  7058  7721 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cc83b7b on behalf of 
08-26 18:20:40.755  7058  7721 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-26 18:20:40.759  7058  7721 V BluetoothOppNotification: inbound notification was removed.
08-26 18:20:40.759  7058  7721 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 18:20:40.762  7058  7721 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f82fd98 on behalf of 
08-26 18:20:40.787  1034  2032 W libprocessgroup: failed to open /acct/uid_10044/pid_7465/cgroup.procs: No such file or directory
,08-26 18:20:40.973  1034  1990 I ActivityManager: Killing 6952:com.lge.sync/1000 (adj 15): empty #17
,08-26 18:20:41.001  1034  1544 D WifiService: Client connection lost with reason: 4
,08-26 18:20:41.013  1034  2053 W libprocessgroup: failed to open /acct/uid_1000/pid_6952/cgroup.procs: No such file or directory
,08-26 18:20:41.397  1034  1656 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 18:20:41.398  1034  1656 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1f31e6ad mBinding = false
,08-26 18:20:41.429  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 18:20:41.429  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 18:20:41.429  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-26 18:20:41.433  1034  1110 D BluetoothManagerService: Message: 2
08-26 18:20:41.434  1034  1110 D BluetoothManagerService: Sending off request.
08-26 18:20:41.434  7058  7073 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 18:20:41.435  7058  7565 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 18:20:41.435  7058  7565 D BluetoothAdapterProperties: Setting state to 13
08-26 18:20:41.435  7058  7565 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 18:20:41.436  7058  7565 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 18:20:41.436  7058  7565 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 18:20:41.438  7058  7569 D BluetoothAdapterProperties: Scan Mode:20
08-26 18:20:41.439  7058  7565 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 18:20:41.441  7058  7695 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 18:20:41.441  7058  7695 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 18:20:41.441  7058  7695 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 18:20:41.441  7058  7695 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 18:20:41.441  7058  7695 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 18:20:41.441  7058  7695 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 18:20:41.441  7058  7695 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 18:20:41.441  7058  7695 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-26 18:20:41.444  7058  7697 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 18:20:41.446  7058  7707 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 18:20:41.446  7058  7709 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 18:20:41.448  7058  7565 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 18:20:41.449  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 18:20:41.449  7058  7635 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 18:20:41.455  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 18:20:41.455  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 18:20:41.455  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 18:20:41.455  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 18:20:41.455  7058  7635 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 18:20:41.455  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 18:20:41.455  7058  7635 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 18:20:41.455  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 18:20:41.455  7058  7635 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 18:20:41.455  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 18:20:41.455  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 18:20:41.456  7058  7635 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-26 18:20:41.466  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:41.466  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:41.466  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:41.466  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:41.466  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:41.466  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:41.466  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:41.466  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:41.466  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:41.468  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:41.468  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:41.475  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:41.475  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:41.475  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:41.475  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:41.475  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:41.475  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:41.475  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:41.475  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:41.475  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:41.476  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:41.476  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:41.477  1034  1110 D BluetoothManagerService: Message: 60
08-26 18:20:41.478  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 18:20:41.479  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 18:20:41.481  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:41.485  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 18:20:41.489  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:41.492  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:41.493  7058  7058 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:41.493  7058  7058 D BluetoothMapService: STATE_TURNING_OFF
08-26 18:20:41.494  7058  7058 V BluetoothMapService: Handler(): got msg=4
08-26 18:20:41.494  7058  7058 D BluetoothMapService: MAP Service closeService in
08-26 18:20:41.494  7058  7058 D BluetoothMapMasInstance: MAP Service shutdown
08-26 18:20:41.494  7058  7058 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 18:20:41.494  7058  7058 V BluetoothMapService: MAP Service closeService out
,08-26 18:20:41.497  7058  7058 V BtOppService: Receiver DISABLED_ACTION 
08-26 18:20:41.497  7058  7058 I BtOppRfcommListener: stopping Accept Thread
08-26 18:20:41.497  7058  7058 V BtOppRfcommListener: close mBtServerSocket
08-26 18:20:41.499  7058  7707 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 18:20:41.499  7058  7058 V BtOppRfcommListener: waiting for thread to terminate
08-26 18:20:41.500  7058  7058 V BtOppRfcommListener: done waiting for thread to terminate
08-26 18:20:41.503  6932  6932 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-26 18:20:41.511  7058  7711 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 18:20:41.517  6932  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 18:20:41.519  7058  7058 V BtOppService: onDestroy
08-26 18:20:41.520  7058  7058 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 18:20:41.525  7058  7058 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 18:20:41.525  7058  7058 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:41.526  7058  7058 V BluetoothPbapReceiver: ***********state = 13
,08-26 18:20:41.529  7058  7058 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 18:20:41.531  7058  7058 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:41.531  7058  7058 V BluetoothPbapService: state: 13
08-26 18:20:41.531  7058  7058 V BluetoothPbapService: Pbap Service closeService in
08-26 18:20:41.534  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 18:20:41.536  7058  7058 V BluetoothPbapService: successfully stopped pbap service
08-26 18:20:41.536  7058  7058 V BluetoothPbapService: Pbap Service closeService out
08-26 18:20:41.536  7058  7058 V BluetoothPbapService: Pbap Service onDestroy
08-26 18:20:41.536  7058  7058 V BluetoothPbapService: Pbap Service closeService in
08-26 18:20:41.536  7058  7058 V BluetoothPbapService: Pbap Service closeService out
08-26 18:20:41.537  7058  7058 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-26 18:20:41.561  6932  6932 D DockEventReceiver: finishStartingService: stopping service
08-26 18:20:41.564  6932  6932 D BluetoothPbap: Proxy object disconnected
,08-26 18:20:41.564  6932  6932 D PbapServerProfile: Bluetooth service disconnected
08-26 18:20:41.570  6932  6932 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 18:20:41.577  6932  6932 D BluetoothPermissionRequest: onReceive
08-26 18:20:41.577  6932  6932 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 18:20:41.582  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 18:20:41.586  7058  7058 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 18:20:41.586  7058  7058 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 18:20:41.587  7058  7058 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-26 18:20:41.592  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:41.592  7058  7058 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 18:20:41.593  7058  7058 V BluetoothFtpService: Ftp Service onStartCommand
08-26 18:20:41.593  7058  7058 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:41.594  7058  7058 V BluetoothFtpService: Ftp Service closeService
08-26 18:20:41.594  7058  7058 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 18:20:41.596  7058  7058 V BluetoothFtpService: successfully stopped ftp service
08-26 18:20:41.596  7058  7058 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 18:20:41.596  7058  7058 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 18:20:41.596  7058  7058 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 18:20:41.596  7058  7058 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:41.596  7058  7058 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 18:20:41.596  7058  7058 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 18:20:41.597  7058  7058 V BluetoothFtpService: Ftp Service onDestroy
08-26 18:20:41.597  7058  7058 V BluetoothFtpService: Ftp Service closeService
08-26 18:20:41.601  7058  7058 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:41.601  7058  7058 V BluetoothSapService: state: 13
08-26 18:20:41.602  7058  7058 V BluetoothSapService: Stopping SAP server process
08-26 18:20:41.602  7058  7058 V BluetoothSapService: Sap Service closeSapService in
08-26 18:20:41.602  7058  7058 V BluetoothSapService: Close listen Socket : 
08-26 18:20:41.603  7058  7058 V BluetoothSapService: Close rfcomm Socket : 
08-26 18:20:41.603  7058  7058 V BluetoothSapService: Close sapd  Socket : 
,08-26 18:20:41.608  7058  7058 V BluetoothSapService: Sap Service closeSapService out
,08-26 18:20:41.608  7058  7058 V BluetoothSapService: Sap Service onDestroy
,08-26 18:20:41.608  7058  7058 V BluetoothSapService: Sap Service closeSapService in
08-26 18:20:41.608  7058  7058 V BluetoothSapService: Close listen Socket : 
,08-26 18:20:41.608  7058  7058 V BluetoothSapService: Close rfcomm Socket : 
08-26 18:20:41.608  7058  7058 V BluetoothSapService: Close sapd  Socket : 
08-26 18:20:41.609  7058  7058 V BluetoothSapService: Sap Service closeSapService out
08-26 18:20:42.356  7058  7569 D bt_hci_bdroid: cleanup
,08-26 18:20:42.366  7058  7637 I bt_lpm  : LPM is already off!!!
08-26 18:20:42.366  7058  7675 I bt_userial_mct: exiting userial_read_thread
08-26 18:20:42.366  7058  7675 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 18:20:42.367  7058  7635 W bt-btif : ag scb idx 1 not allocated
08-26 18:20:42.367  7058  7635 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 18:20:42.367  7058  7635 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 18:20:42.367  7058  7635 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 18:20:42.368  7058  7569 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 18:20:42.368  7058  7637 I bt_vendor: hw_epilog_process
08-26 18:20:42.369  7058  7569 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 18:20:42.369  7058  7569 D bt_userial_mct: userial_close
08-26 18:20:42.369  7058  7569 E bt_userial_mct: pthread_join() FAILED result:3
08-26 18:20:42.369  7058  7569 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 18:20:42.373  7058  7569 D bt_hci_bdroid: set_power 0
08-26 18:20:42.373  7058  7569 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 18:20:42.373  7058  7569 I bt_vendor: bluetooth satus is on
08-26 18:20:42.373  7058  7569 I bt_vendor: bt-vendor : resetting BT status
08-26 18:20:42.373  7058  7569 I bt_vendor: Starting hciattach daemon
08-26 18:20:42.373  7058  7569 I bt_vendor: try to set false
08-26 18:20:42.376  7058  7569 I bt_vendor: Starting hciattach daemon
08-26 18:20:42.376  7058  7569 I bt_vendor: try to set false
,08-26 18:20:42.383  7058  7569 I bt_vendor: cleanup
08-26 18:20:42.384  7058  7635 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 18:20:42.384  7058  7569 I GKI_LINUX: GKI_exit_task 0 done
08-26 18:20:42.384  7058  7569 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 18:20:42.386  7058  7565 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 18:20:42.392  7058  7058 D HeadsetService: Received stop request...Stopping profile...
,08-26 18:20:42.396  7058  7058 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 18:20:42.396  7058  7058 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 18:20:42.396  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:42.396  7058  7584 D HeadsetStateMachine: Exit Disconnected: -1
08-26 18:20:42.400  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-26 18:20:42.400  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-26 18:20:42.400  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-26 18:20:42.402  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-26 18:20:42.402  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 18:20:42.404  7058  7058 D A2dpService: Received stop request...Stopping profile...
,08-26 18:20:42.407  7058  7619 D A2dpStateMachine: Exit Disconnected: -1
08-26 18:20:42.408  7058  7058 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 18:20:42.411  7058  7565 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 18:20:42.411  7058  7058 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 18:20:42.411  7058  7058 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 18:20:42.411  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:42.413  7058  7058 D HidService: Received stop request...Stopping profile...
08-26 18:20:42.413  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:42.417  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-26 18:20:42.417  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 18:20:42.420  7058  7058 D HealthService: Received stop request...Stopping profile...
08-26 18:20:42.421  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:42.423  7058  7058 D HeadsetStateMachine: Unbinding service...
08-26 18:20:42.424  7058  7058 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 18:20:42.424  7058  7058 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 18:20:42.424  7058  7058 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 18:20:42.424  7058  7058 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 18:20:42.424  7058  7058 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 18:20:42.424  7058  7058 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 18:20:42.424  7058  7058 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 18:20:42.425  7058  7058 D PanService: Received stop request...Stopping profile...
08-26 18:20:42.427  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:42.428  7058  7058 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 18:20:42.429  7058  7058 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 18:20:42.429  7058  7058 D BtGatt.GattService: stop()
08-26 18:20:42.429  7058  7058 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 18:20:42.432  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:42.433  7058  7058 D BluetoothMapService: Received stop request...Stopping profile...
08-26 18:20:42.434  7058  7058 D BluetoothMapService: stop()
08-26 18:20:42.434  7058  7058 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 18:20:42.434  7058  7058 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 18:20:42.435  7058  7058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:42.436  7058  7058 I BluetoothA2dpServiceJni: cleanupNative
08-26 18:20:42.436  7058  7620 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 18:20:42.437  7058  7058 I GKI_LINUX: GKI_exit_task 2 done
08-26 18:20:42.437  7058  7058 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 18:20:42.437  7058  7058 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 18:20:42.437  7058  7058 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 18:20:42.437  7058  7058 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 18:20:42.439  7058  7058 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 18:20:42.439  7058  7058 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 18:20:42.439  7058  7058 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 18:20:42.439  7058  7058 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 18:20:42.442  7058  7058 V BluetoothMapService: Handler(): got msg=4
08-26 18:20:42.442  7058  7058 D BluetoothMapService: MAP Service closeService in
08-26 18:20:42.442  7058  7058 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 18:20:42.442  7058  7058 V BluetoothMapService: MAP Service closeService out
,08-26 18:20:42.445  7058  7565 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 18:20:42.445  7058  7565 D BluetoothAdapterProperties: Setting state to 10
08-26 18:20:42.445  7058  7565 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 18:20:42.446  7058  7058 D BluetoothMapService: cleanup()
08-26 18:20:42.446  7058  7058 D BluetoothMapService: MAP Service closeService in
08-26 18:20:42.446  7058  7058 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 18:20:42.446  7058  7058 V BluetoothMapService: MAP Service closeService out
08-26 18:20:42.447  1034  1110 D BluetoothManagerService: Message: 60
08-26 18:20:42.447  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 18:20:42.447  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-26 18:20:42.447  7058  7565 I BluetoothAdapterState: Entering OffState
08-26 18:20:42.448  6932  6948 D BluetoothPan: onBluetoothStateChange on: false
08-26 18:20:42.448  1034  1110 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 18:20:42.448  1034  1110 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 18:20:42.449  1855  1871 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 18:20:42.450  6932  6948 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 18:20:42.451  6932  6948 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 18:20:42.452  6932  6948 D BluetoothMap: onBluetoothStateChange: up=false
08-26 18:20:42.455  1855  3502 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 18:20:42.458  1855  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 18:20:42.458  6932  6947 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 18:20:42.459  6932  6948 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 18:20:42.460  1034  1110 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 18:20:42.460  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 18:20:42.463  1034  1110 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 18:20:42.463  1034  1110 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 18:20:42.464  1034  1110 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1f31e6ad mBinding = false
08-26 18:20:42.465  1034  1110 D BluetoothManagerService: Sending unbind request.
08-26 18:20:42.469  7058  7569 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 18:20:42.471  7058  7058 I GKI_LINUX: GKI_exit_task 1 done
08-26 18:20:42.472  7058  7058 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 18:20:42.472  7058  7058 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 18:20:42.473  7058  7058 I art     : --- WEIRD: removing null entry 248
08-26 18:20:42.473  7058  7058 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-26 18:20:42.473  7058  7058 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 18:20:42.474  7058  7058 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 18:20:42.475  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 18:20:42.480  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 18:20:42.482  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:42.485  1944  2104 D LGBluetoothAPIService: Message: 2
08-26 18:20:42.485  1944  2104 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3ff1eb0e mBinding = false
08-26 18:20:42.485  1944  2104 D LGBluetoothAPIService: Sending unbind request.
08-26 18:20:42.486  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:42.487  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:42.495  6932  6932 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 18:20:42.495  6932  6932 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-26 18:20:42.499  6932  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 18:20:42.510  7058  7058 I art     : System.exit called, status: 0
,08-26 18:20:42.510  7058  7058 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 18:20:42.517  6932  6932 D DockEventReceiver: finishStartingService: stopping service
08-26 18:20:42.519  1603  1603 D BluetoothAdapter: 399480497: getState() :  mService = null. Returning STATE_OFF
08-26 18:20:42.519  1603  1603 D BluetoothAdapter: 399480497: getState() :  mService = null. Returning STATE_OFF
08-26 18:20:42.538   312  1383 V AudioFlinger: 7058 died, releasing its sessions
08-26 18:20:42.538   312  1383 V AudioFlinger:  pid 1855 @ 0
08-26 18:20:42.538   312  1383 V AudioFlinger:  pid 3203 @ 1
08-26 18:20:42.538   312  1383 V AudioFlinger:  pid 3203 @ 2
,08-26 18:20:42.538  6932  6932 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-26 18:20:42.643  1034  1962 I ActivityManager: Process com.android.bluetooth (pid 7058) has died
,08-26 18:20:42.643  1034  1962 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-26 18:20:42.655  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 18:20:42.687  6932  6932 D BluetoothPermissionRequest: onReceive
,08-26 18:20:42.692  6932  6932 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 18:20:42.692  6932  6932 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 18:20:42.696  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 18:20:42.757  1034  1050 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7771 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 18:20:42.840  7771  7771 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 18:20:42.840  7771  7771 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 18:20:42.841  7771  7771 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-26 18:20:42.841  7771  7771 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 18:20:42.862  7771  7771 D BluetoothAdapterApp: Loading JNI Library
,08-26 18:20:42.899  7771  7771 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@35d157a7 Instance Count = 1
,08-26 18:20:42.907  7771  7771 D BluetoothAdapterApp: onCreate
,08-26 18:20:42.946  7771  7771 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 18:20:42.946  7771  7771 D ProfileConfigQcom: Adding HeadsetService
,08-26 18:20:42.947  7771  7771 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-26 18:20:42.947  7771  7771 D ProfileConfigQcom: Adding A2dpService
08-26 18:20:42.948  7771  7771 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 18:20:42.948  7771  7771 D ProfileConfigQcom: Adding HidService
,08-26 18:20:42.949  7771  7771 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 18:20:42.950  7771  7771 D ProfileConfigQcom: Adding HealthService
08-26 18:20:42.950  7771  7771 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 18:20:42.952  7771  7771 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 18:20:42.953  7771  7771 D ProfileConfigQcom: Adding PanService
08-26 18:20:42.953  7771  7771 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 18:20:42.954  7771  7771 D ProfileConfigQcom: Adding GattService
08-26 18:20:42.954  7771  7771 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 18:20:42.955  7771  7771 D ProfileConfigQcom: Adding BluetoothMapService
08-26 18:20:42.956  7771  7771 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 18:20:42.960  7771  7771 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-26 18:20:42.967  6932  6932 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 18:20:42.970  7771  7771 V LGMDMManagerInternal: Create singleton instance
,08-26 18:20:43.068  7771  7771 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:43.074  7771  7771 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-26 18:20:43.074  7771  7771 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 18:20:43.074  7771  7771 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 18:20:43.076  7771  7771 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:43.076  7771  7771 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 18:20:43.089  7643  7643 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-26 18:20:43.094  1034  2008 I ActivityManager: Killing 6827:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-26 18:20:43.124  6980  6980 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-26 18:20:43.125  6980  6980 W System.err: android.os.DeadObjectException
08-26 18:20:43.125  6980  6980 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 18:20:43.125  6980  6980 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 18:20:43.125  6980  6980 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 18:20:43.125  6980  6980 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 18:20:43.125  6980  6980 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 18:20:43.125  6980  6980 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 18:20:43.126  6980  6980 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 18:20:43.126  6980  6980 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 18:20:43.126  6980  6980 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 18:20:43.126  6980  6980 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 18:20:43.126  6980  6980 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:43.126  6980  6980 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:43.126  6980  6980 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 18:20:43.126  6980  6980 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 18:20:43.126  6980  6980 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 18:20:43.127  6980  6980 W System.err: android.os.DeadObjectException
08-26 18:20:43.128  6980  6980 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 18:20:43.128  6980  6980 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 18:20:43.128  6980  6980 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 18:20:43.128  6980  6980 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,08-26 18:20:43.128  6980  6980 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 18:20:43.128  6980  6980 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 18:20:43.128  6980  6980 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 18:20:43.128  6980  6980 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 18:20:43.128  6980  6980 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 18:20:43.128  6980  6980 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 18:20:43.128  6980  6980 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:43.128  6980  6980 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:43.128  6980  6980 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 18:20:43.128  6980  6980 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 18:20:43.128  6980  6980 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 18:20:43.129  6980  6980 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-26 18:20:43.208  1034  1962 W libprocessgroup: failed to open /acct/uid_1000/pid_6827/cgroup.procs: No such file or directory
,08-26 18:20:43.209  1034  1962 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-26 18:20:43.216  6980  6980 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 18:20:43.217  6980  6980 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 18:20:43.311  1034  1051 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7797 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 18:20:43.313  6980  6980 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 18:20:43.393  7797  7797 D UEI.SmartControl: Quickset Services start...
08-26 18:20:43.396  7797  7797 I UEI.SmartControl: Manufacture = LGE
08-26 18:20:43.396  7797  7797 D UEI.SmartControl: Id = LGNevo
08-26 18:20:43.397  7797  7797 D UEI.SmartControl: File observer start...
08-26 18:20:43.398  7797  7797 E UEI.SmartControl: IR Port is disabled: false
08-26 18:20:43.398  7797  7797 D UEI.SmartControl: Starting file observer...
08-26 18:20:43.399  7797  7797 D UEI.SmartControl: Extracting JNI libs...
,08-26 18:20:43.399  7797  7797 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 18:20:43.516  7797  7797 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-26 18:20:43.516  7797  7797 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 18:20:43.516  7797  7797 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 18:20:43.556  7797  7797 I UEI.SmartControl: --- Selecting new region: 6
,08-26 18:20:43.559  7797  7797 I UEI.SmartControl: Model = LG-D855
,08-26 18:20:43.561  7797  7797 D UEI.SmartControl: QS Service created
,08-26 18:20:43.580  7797  7797 I UEI.SmartControl: Service initServices...
,08-26 18:20:43.586  7797  7797 D UEI.SmartControl: QS start get config
,08-26 18:20:43.662  7797  7797 D UEI.SmartControl: Loading JNI Libs...
,08-26 18:20:44.140  7797  7797 I UEI.SmartControl: Supports setup maps: true
,08-26 18:20:44.148  7797  7797 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 18:20:44.148  7797  7797 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-26 18:20:44.148  7797  7797 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 18:20:44.148  7797  7797 I UEI.SmartControl: ### init IR Blaster...
,08-26 18:20:44.154  7797  7797 D serial_port: Configuring serial port
,08-26 18:20:44.162  7797  7797 E UEI.SmartControl: UEIBLaster setting for 616
08-26 18:20:44.162  7797  7797 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 18:20:44.162  7797  7797 I UEI.SmartControl: configuring settings for MAXQ616
08-26 18:20:44.163  7797  7797 I UEI.SmartControl: Get version...
08-26 18:20:44.180  7797  7815 D UEI.SmartControl: serial port data available: 21
,08-26 18:20:44.209  7797  7797 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 18:20:44.209  7797  7797 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 18:20:44.210  7797  7797 I UEI.SmartControl: QS saving settings...
,08-26 18:20:44.217  7797  7797 D UEI.SmartControl: IR Blaster version: 25672567
08-26 18:20:44.235  7797  7815 D UEI.SmartControl: serial port data available: 4
,08-26 18:20:44.275  7797  7818 I UEI.SmartControl: Device manager: loading config....
,08-26 18:20:44.276  7797  7818 D UEI.SmartControl: ----------- loading internal config...
,08-26 18:20:44.281  7797  7797 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 18:20:44.288  7797  7797 E UEI.SmartControl: Services init done
08-26 18:20:44.288  7797  7797 D UEI.SmartControl: QS Service init finished
08-26 18:20:44.293  7797  7797 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 18:20:44.294  7797  7797 D UEI.SmartControl: QS Service version code: 201091
08-26 18:20:44.295  7797  7797 D UEI.SmartControl: Service requested: Control
,08-26 18:20:44.309  7797  7818 E UEI.SmartControl: Loading SETTINGS...
08-26 18:20:44.312  7797  7797 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-26 18:20:44.315  1034  1990 I ActivityManager: Killing 6980:com.lge.qremote/u0a112 (adj 15): empty #17
,08-26 18:20:44.326  7797  7818 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 18:20:44.344  1034  1956 W libprocessgroup: failed to open /acct/uid_10112/pid_6980/cgroup.procs: No such file or directory
08-26 18:20:44.345  7797  7797 D UEI.SmartControl: Internal service binding...
,08-26 18:20:44.356  7797  7817 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-26 18:20:44.356  7797  7817 D UEI.SmartControl: -----service ready thread exits
,08-26 18:20:44.501  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 18:20:44.501  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:44.708  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-26 18:20:44.749  1034  1424 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 18:20:44.781  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 18:20:44.809  1034  1091 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7823 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-26 18:20:44.818  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-26 18:20:44.820  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-26 18:20:44.830  1034  1034 D administrator: Handling package changes for user 0
,08-26 18:20:44.903  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 18:20:44.914  7823  7823 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 18:20:44.971  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-26 18:20:44.971  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 18:20:45.022  7823  7823 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 18:20:45.023  7823  7823 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 18:20:45.046  1034  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 18:20:45.053  1034  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-26 18:20:45.060  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-26 18:20:45.063  2479  2479 V GmsNetworkLocationProvi: DISABLE
,08-26 18:20:45.098  1034  1090 D LocationProviderProxy: applying state to connected service
,08-26 18:20:45.102  2479  2479 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-26 18:20:45.152  7823  7866 I Babel   : MmsConfig: mnc/mcc: 0/0
08-26 18:20:45.153  7823  7866 I Babel   : MmsConfig.loadMmsSettings
,08-26 18:20:45.154  7823  7866 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-26 18:20:45.155  7823  7866 I Babel   : MmsConfig.loadFromDatabase
,08-26 18:20:45.162  7823  7866 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-26 18:20:45.162  7823  7866 I Babel   : MmsConfig.loadFromResources
08-26 18:20:45.163  7823  7866 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-26 18:20:45.164  7823  7866 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-26 18:20:45.186  7823  7823 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 18:20:45.248  7823  7865 W AudioCapabilities: Unsupported mime audio/evrc
08-26 18:20:45.250  7823  7865 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 18:20:45.251  1819  7870 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-26 18:20:45.251  1819  7870 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-26 18:20:45.259  7114  7114 I AppUp4:CustModeStarterReceiver: onReceive
08-26 18:20:45.259  7823  7865 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 18:20:45.266  7114  7114 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@380b1ef9
,08-26 18:20:45.266  7114  7114 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 18:20:45.266  7114  7114 D AppUp4:CustFacade: isPhone : true
08-26 18:20:45.268  7114  7114 D AppUp4:CustModeStarterReceiver: begin check event
08-26 18:20:45.268  7114  7114 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-26 18:20:45.270  1819  5205 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-26 18:20:45.284  7823  7865 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-26 18:20:45.288  7823  7865 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 18:20:45.293  7823  7865 W AudioCapabilities: Unsupported mime audio/evrc
08-26 18:20:45.301  7823  7865 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-26 18:20:45.304  7823  7865 W VideoCapabilities: Unsupported mime video/divx
,08-26 18:20:45.315  7823  7865 W VideoCapabilities: Unsupported mime video/divx311
,08-26 18:20:45.316  1034  1907 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7874 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-26 18:20:45.319  1034  1990 I ActivityManager: Killing 7141:com.lge.email/u0a23 (adj 15): empty #17
08-26 18:20:45.320  7823  7865 W VideoCapabilities: Unsupported mime video/divx4
08-26 18:20:45.328  7823  7865 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 18:20:45.347  7823  7865 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 18:20:45.352  7823  7865 W AudioCapabilities: Unsupported mime audio/eac3
08-26 18:20:45.353  7823  7865 W AudioCapabilities: Unsupported mime audio/ac3
08-26 18:20:45.354  7823  7865 W AudioCapabilities: Unsupported mime audio/g726
08-26 18:20:45.355  7823  7865 W AudioCapabilities: Unsupported mime audio/wma-voice
08-26 18:20:45.355  7823  7865 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-26 18:20:45.356  7823  7865 W AudioCapabilities: Unsupported mime audio/adpcm
08-26 18:20:45.358  7823  7865 W VideoCapabilities: Unsupported mime video/theora
08-26 18:20:45.359  7823  7865 W VideoCapabilities: Unsupported mime video/mjpg
,08-26 18:20:45.393  1034  1962 W libprocessgroup: failed to open /acct/uid_10023/pid_7141/cgroup.procs: No such file or directory
,08-26 18:20:45.424  7874  7874 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 18:20:45.424  7874  7874 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 18:20:45.425  7874  7874 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 18:20:45.426  7874  7874 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-26 18:20:45.427  7874  7874 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 18:20:45.517  7874  7874 I SystemConfig: BUILD Country: EU
08-26 18:20:45.517  7874  7874 I SystemConfig: BUILD Operator: OPEN
,08-26 18:20:45.579  1034  1656 I ActivityManager: Killing 7017:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-26 18:20:45.690  1034  1727 W libprocessgroup: failed to open /acct/uid_10026/pid_7017/cgroup.procs: No such file or directory
,08-26 18:20:45.704  7874  7892 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-26 18:20:45.705  7874  7892 I SystemConfig: existFile = false
08-26 18:20:45.705  7874  7892 I SystemConfig: canReadFile = false
08-26 18:20:45.705  7874  7892 I SystemConfig: systemFeature RCS result false
08-26 18:20:45.706  7874  7892 D SystemConfig: refreshRcsSupport() :false
,08-26 18:20:45.768  1034  1656 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7897 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-26 18:20:45.828  7897  7897 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 18:20:45.828  7897  7897 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 18:20:45.828  7897  7897 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 18:20:45.829  7897  7897 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 18:20:45.928  7897  7897 I AppConfig: Total System Memory = 2995761152
,08-26 18:20:45.939  7897  7897 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-26 18:20:46.030  1034  2035 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7916 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 18:20:46.031  1034  2035 I ActivityManager: Killing 6410:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-26 18:20:46.093  1034  1576 W libprocessgroup: failed to open /acct/uid_1000/pid_6410/cgroup.procs: No such file or directory
,08-26 18:20:46.279  7916  7916 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-26 18:20:46.413  7916  7916 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 18:20:46.414  7916  7916 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 18:20:46.468  7916  7916 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-26 18:20:46.494  7916  7916 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 18:20:46.497  7916  7916 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 18:20:46.514  7916  7916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 18:20:46.515  7916  7916 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-26 18:20:46.534  1034  1050 I ActivityManager: Killing 7182:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-26 18:20:46.567  1034  2035 W libprocessgroup: failed to open /acct/uid_10046/pid_7182/cgroup.procs: No such file or directory
,08-26 18:20:46.601  5016  7958 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-26 18:20:46.639  1034  1727 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7965 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-26 18:20:46.647  3427  3442 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-26 18:20:46.648  3427  3442 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@122c1b13 on behalf of 7916
08-26 18:20:46.678  7916  7916 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-26 18:20:46.704  7916  7916 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-26 18:20:46.720  7965  7965 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-26 18:20:46.736  7965  7965 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-26 18:20:46.736  7965  7965 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-26 18:20:46.736  7965  7965 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,08-26 18:20:46.736  7965  7965 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,08-26 18:20:46.736  7965  7965 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,08-26 18:20:46.736  7965  7965 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-26 18:20:46.755  1034  2053 I ActivityManager: Killing 7203:com.android.chrome/u0a57 (adj 15): empty #17
,08-26 18:20:46.786  1034  1908 W libprocessgroup: failed to open /acct/uid_10057/pid_7203/cgroup.procs: No such file or directory
,08-26 18:20:47.006  1034  2008 V SIM_STK : Menu title from STK is T-Mobile
,08-26 18:20:47.030  5016  7958 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 429 ms] updated apps [took 429 ms] 
,08-26 18:20:47.517  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 18:20:47.517  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2bcd8723 added. We now have 6 listener(s)
08-26 18:20:47.517  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:47.526  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:47.527  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2dc16420 added. We now have 7 listener(s)
08-26 18:20:47.527  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:47.527  6669  6729 I System.out: IsBluetoothEnabled
08-26 18:20:47.528  1034  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:47.529  1034  1956 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-26 18:20:47.529  1034  1110 D BluetoothManagerService: Message: 2
08-26 18:20:47.533  6669  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:47.533  1034  1893 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:47.533  1034  1893 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 18:20:47.554  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-26 18:20:47.554  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 18:20:47.554  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 18:20:47.555  1034  1110 D BluetoothManagerService: Message: 1
08-26 18:20:47.555  1034  1110 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-26 18:20:47.583  1034  1110 D BluetoothManagerService: Message: 20
08-26 18:20:47.584  1034  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10022d4f:true
,08-26 18:20:47.589  7771  7771 D BluetoothAdapterState: make
08-26 18:20:47.594  7771  7771 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 18:20:47.594  7771  7771 I bluedroid-qcom: init
08-26 18:20:47.595  7771  8010 I BluetoothAdapterState: Entering OffState
08-26 18:20:47.596  7771  7771 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 18:20:47.596  7771  7771 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 18:20:47.596  7771  7771 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 18:20:47.596  7771  7771 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 18:20:47.596  7771  7771 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 18:20:47.598  7771  7771 I bluedroid-qcom: get_profile_interface socket
08-26 18:20:47.598  7771  7771 I bluedroid-qcom: get_profile_interface map_client
,08-26 18:20:47.603  7771  8014 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 18:20:47.597  8013  8013 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:47.608  7771  8014 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 18:20:47.597  8013  8013 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:47.618  8013  8013 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 18:20:47.618  8013  8013 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 18:20:47.618  8013  8013 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-26 18:20:47.622  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 18:20:47.623  1034  1110 D BluetoothManagerService: Message: 40
08-26 18:20:47.623  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 18:20:47.624  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 18:20:47.624  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 18:20:47.625  7771  7786 I bluedroid-qcom: config_hci_snoop_log
08-26 18:20:47.626  1034  1110 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 18:20:47.626  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 18:20:47.627  8013  8013 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 18:20:47.634  8013  8013 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 18:20:47.634  8013  8013 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-26 18:20:47.639  7771  8010 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 18:20:47.639  7771  8014 D BluetoothAdapterProperties: Name is: G3
08-26 18:20:47.639  7771  8010 D BluetoothAdapterProperties: Setting state to 11
08-26 18:20:47.640  7771  8010 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 18:20:47.640  1034  1110 D BluetoothManagerService: Message: 60
08-26 18:20:47.640  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 18:20:47.641  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 18:20:47.642  7771  8010 I LGBluetoothServiceJni: classInitNative: succeeds
08-26 18:20:47.646  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:47.649  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 18:20:47.653  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:47.655  6932  6932 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-26 18:20:47.662  7771  7771 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 18:20:47.663  7771  7771 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:47.663  7771  7771 V BluetoothPbapReceiver: ***********state = 11
,08-26 18:20:47.673  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 18:20:47.688  7771  8010 D BluetoothBondStateMachine: make
,08-26 18:20:47.695  7771  8010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:47.696  7771  8010 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 18:20:47.696  7771  8010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:47.696  7771  8010 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 18:20:47.696  7771  8010 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 18:20:47.698  6932  6932 D BluetoothPermissionRequest: onReceive
08-26 18:20:47.701  7771  8015 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 18:20:47.712  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 18:20:47.723  7771  8010 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 18:20:47.729  7771  7771 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:47.731  7771  7771 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 18:20:47.731  7771  7771 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 18:20:47.731  7771  7771 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 18:20:47.731  7771  7771 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:47.732  7771  7771 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 18:20:47.736  7771  8010 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 18:20:47.737  7771  7771 D HeadsetService: Received start request. Starting profile...
08-26 18:20:47.738  7771  7771 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 18:20:47.738  7771  7771 D LGBluetoothHfpAdapter: Version 1.6
08-26 18:20:47.742  7771  7771 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 18:20:47.743  7771  7771 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 18:20:47.743  7771  7771 D HeadsetStateMachine: make
08-26 18:20:47.744  7771  8010 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 18:20:47.750  7771  8010 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 18:20:47.758  7771  8010 E BluetoothAdapterService: File transfer profiles supported!!
08-26 18:20:47.764  7771  8010 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 18:20:47.770  7771  8010 E BluetoothAdapterService: File transfer profiles supported!!
08-26 18:20:47.784  7771  7771 D LgDataFeature: LgDataFeature() Constructor: none
08-26 18:20:47.785  7771  7771 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 18:20:47.785  7771  8010 V LGMDMManager: Create singleton instance
,08-26 18:20:47.787  7771  8010 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 18:20:47.790  7771  7771 D HeadsetStateMachine: max_hf_connections = 1
08-26 18:20:47.790  7771  7771 I bluedroid-qcom: get_profile_interface handsfree
08-26 18:20:47.793  7771  7771 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 18:20:47.793   312  2172 V AudioPolicyService: registerClient() client 0xb57c0d20, uid 1002
08-26 18:20:47.793   312   312 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 18:20:47.794   312   312 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 18:20:47.794   312   312 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 18:20:47.794  7771  7771 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 18:20:47.794   312  1382 V AudioFlinger: registerClient() client 0xb57c9268, pid 7771
08-26 18:20:47.795   312  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 18:20:47.795   312  1378 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 18:20:47.795  7771  7771 V ToneGenerator: Create Track: 0xb4928080
08-26 18:20:47.795  7771  7771 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 18:20:47.795  7771  7771 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 18:20:47.795   312  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 18:20:47.795   312  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 18:20:47.795   312  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 18:20:47.795   312  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 18:20:47.795  1034  1956 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-26 18:20:47.795  7771  7771 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 18:20:47.795  1034  1956 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 18:20:47.795  1603  3421 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 18:20:47.795  1603  3421 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 18:20:47.795  1855  3502 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 18:20:47.795  1855  3502 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 18:20:47.796   312  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 18:20:47.796  7771  7787 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 18:20:47.796   312  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 18:20:47.796  7771  7787 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 18:20:47.796  1034  1990 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 18:20:47.796  1034  1990 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 18:20:47.796  1855  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 18:20:47.796  1855  1870 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 18:20:47.796  1603  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 18:20:47.796  1603  1622 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 18:20:47.796   312  1383 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 18:20:47.796  7771  7787 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 18:20:47.796  7771  7787 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 18:20:47.796   312  2175 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 18:20:47.796   312  2175 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 18:20:47.796   312  2175 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 18:20:47.796   312  2175 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 18:20:47.796  7771  7771 V AudioSystem: getLatency() output 2, latency 50
08-26 18:20:47.796  7771  7771 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 18:20:47.796  7771  7771 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 18:20:47.797   312  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 18:20:47.797   312  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 18:20:47.797   312  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 18:20:47.797   312  2172 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
,08-26 18:20:47.797   312  2172 V AudioFlinger: createTrack() lSessionId: 23
08-26 18:20:47.798  7771  7771 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 18:20:47.798   312  1382 V AudioFlinger: acquiring 23 from 7771, for 7771
08-26 18:20:47.798   312  1382 V AudioFlinger:  added new entry for 23
08-26 18:20:47.798  7771  7771 V ToneGenerator: ToneGenerator INIT OK, time: 138716
08-26 18:20:47.798  7771  7771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:47.799  7771  8031 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 18:20:47.799  7771  8031 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 18:20:47.799  7771  8031 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 18:20:47.800  7771  8031 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 18:20:47.800   312  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7771
08-26 18:20:47.800   312  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
,08-26 18:20:47.800   312  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 18:20:47.801   312  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 18:20:47.801   312  1383 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 18:20:47.801   312  1383 V voice   : voice_set_parameters: exit with code(0)
08-26 18:20:47.801   312  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
,08-26 18:20:47.801   312  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 18:20:47.801   312  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
,08-26 18:20:47.801   312  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 18:20:47.801   312  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 18:20:47.801   312  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 18:20:47.801  7771  8031 V ToneGenerator: ToneGenerator destructor
08-26 18:20:47.801  7771  8031 V ToneGenerator: stopTone
08-26 18:20:47.801  7771  8031 V ToneGenerator: Delete Track: 0xb4928080
08-26 18:20:47.802   312  2175 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 18:20:47.802   312  2175 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 18:20:47.802   312  2175 V AudioFlinger: PlaybackThread::Track destructor
08-26 18:20:47.802   312  1267 V AudioPolicyService: AudioCommandThread() waking up
08-26 18:20:47.802   312  2175 V AudioFlinger: removeClient_l() pid 7771, calling pid 312
08-26 18:20:47.802   312  1267 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 18:20:47.802   312  1267 V AudioPolicyManager: releaseOutput() 2
08-26 18:20:47.802   312  1267 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 18:20:47.802  7771  8031 V AudioTrack: ~AudioTrack, releasing session id from 7771 on behalf of 7771
08-26 18:20:47.803   312  1383 V AudioFlinger: releasing 23 from 7771 for 7771
08-26 18:20:47.803   312  1383 V AudioFlinger:  decremented refcount to 0
08-26 18:20:47.803   312  1383 V AudioFlinger: purging stale effects
08-26 18:20:47.805  3203  3221 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 18:20:47.805  3203  3221 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 18:20:47.805  3203  3221 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 18:20:47.805  3203  3221 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 18:20:47.806  1034  1051 W Process : Unable to open /proc/8034/status
08-26 18:20:47.923  1034  1962 I art     : Explicit concurrent mark sweep GC freed 25614(1213KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.739ms total 126.655ms
,08-26 18:20:47.925  7771  7771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
,08-26 18:20:47.930  7771  7771 D A2dpService: Received start request. Starting profile...
08-26 18:20:47.932  7771  7771 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 18:20:47.934  7771  7771 V Avrcp   : make
08-26 18:20:47.936  7771  7771 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 18:20:47.936  7771  7771 I bluedroid-qcom: get_profile_interface avrcp
08-26 18:20:47.945  7771  7771 V AudioManager: registerRemoteController: size of Media player list: 0
,08-26 18:20:47.947  7771  7771 E AudioManager: No RCC entry present to update
08-26 18:20:47.947  7771  7771 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 18:20:47.952  7771  7771 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 18:20:47.953  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 18:20:47.953  7771  7771 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 18:20:47.959  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-26 18:20:48.118  1034  1727 V SIM_STK : Menu title from STK is T-Mobile
08-26 18:20:48.118  1034  1727 V SIM_STK : Menu title from STK is T-Mobile
,08-26 18:20:48.263  1034  1926 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 18:20:48.278  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-26 18:20:48.284  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-26 18:20:48.284  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 18:20:48.285  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 18:20:48.285  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 18:20:48.285  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 18:20:48.285  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 18:20:48.285  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 18:20:48.285  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 18:20:48.285  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 18:20:48.285  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 18:20:48.286  7771  7771 I BluetoothA2dpServiceJni: classInitNative
08-26 18:20:48.286  7771  7771 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 18:20:48.286  7771  7771 D A2dpStateMachine: make,
08-26 18:20:48.288  7771  7771 I bluedroid-qcom: get_profile_interface a2dp
,08-26 18:20:48.289  7771  8045 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 18:20:48.292  7771  7771 I LGBluetoothA2dpServiceJni: classInitNative: succeeds,
08-26 18:20:48.292  7771  7771 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter],
08-26 18:20:48.293  7771  7771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:48.294  7771  8044 D A2dpStateMachine: Enter Disconnected: -2,
08-26 18:20:48.294  7771  7771 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 18:20:48.297  7771  7771 D HidService: Received start request. Starting profile...
08-26 18:20:48.297  7771  7771 I bluedroid-qcom: get_profile_interface hidhost
,08-26 18:20:48.297  7771  7771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f,
08-26 18:20:48.298  7771  7771 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 18:20:48.300  7771  7771 D HealthService: Received start request. Starting profile...
08-26 18:20:48.302  7771  7771 I bluedroid-qcom: get_profile_interface health
,08-26 18:20:48.303  7771  7771 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 18:20:48.303  7771  7771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
,08-26 18:20:48.304  7771  7771 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 18:20:48.306  7771  7771 D PanService: Received start request. Starting profile...
08-26 18:20:48.307  7771  7771 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 18:20:48.307  7771  7771 I bluedroid-qcom: get_profile_interface pan
08-26 18:20:48.315  7771  7771 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 18:20:48.315  7771  7771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:48.317  7771  7771 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 18:20:48.326  7771  7771 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 18:20:48.327  7771  7771 D BtGatt.GattService: Received start request. Starting profile...
08-26 18:20:48.327  7771  7771 D BtGatt.GattService: start()
08-26 18:20:48.327  7771  7771 I bluedroid-qcom: get_profile_interface gatt
08-26 18:20:48.328  7771  7771 D BtGatt.AdvertiseManager: advertise manager created
08-26 18:20:48.334  7771  7771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:48.335  7771  7771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:48.336  7771  7771 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 18:20:48.337  7771  7771 V BluetoothMapService: BluetoothMapBinder()
08-26 18:20:48.339  7771  7771 D BluetoothMapService: Received start request. Starting profile...
08-26 18:20:48.339  7771  7771 D BluetoothMapService: start()
,08-26 18:20:48.344  7771  7771 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 18:20:48.344  7771  7771 D BluetoothMapEmailAppObserver: createReceiver()
08-26 18:20:48.345  7771  7771 D BluetoothMapEmailAppObserver: initObservers()
08-26 18:20:48.345  7771  7771 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 18:20:48.356  7771  7771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:48.357  7771  7771 D HeadsetStateMachine: Proxy object connected
08-26 18:20:48.358  7771  7771 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 18:20:48.358  7771  7771 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-26 18:20:48.362  7771  8031 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 18:20:48.363  7771  8031 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 18:20:48.363  7771  8031 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 18:20:48.366  7771  7771 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 18:20:48.369  7771  7771 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 18:20:48.373  7771  7771 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 18:20:48.380  7771  7771 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 18:20:48.380  7771  7771 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 18:20:48.383  7771  7771 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 18:20:48.386  7771  7771 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 18:20:48.387  7771  7771 V BluetoothMapService: Handler(): got msg=1
,08-26 18:20:48.388  7771  8010 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 18:20:48.388  7771  8010 I bluedroid-qcom: enable
08-26 18:20:48.388  7771  8010 I bt_hci_bdroid: init
08-26 18:20:48.388  7771  8052 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 18:20:48.388  7771  8052 I bt-btu  : btu_task pending for preload complete event
08-26 18:20:48.391  7771  8010 I bt_vendor: bt-vendor : init
08-26 18:20:48.391  7771  8010 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 18:20:48.391  7771  8010 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 18:20:48.391  7771  8010 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 18:20:48.391  7771  8010 D bt_userial_mct: userial_init
08-26 18:20:48.391  7771  8010 D bt_hci_bdroid: set_power 1
08-26 18:20:48.391  7771  8010 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 18:20:48.391  7771  8010 I bt_vendor: Starting hciattach daemon
08-26 18:20:48.391  7771  8010 I bt_vendor: try to set true
08-26 18:20:48.387  8055  8055 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:48.387  8055  8055 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:48.418  8056  8056 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 18:20:48.495  8062  8062 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 18:20:48.521  8063  8063 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 18:20:48.563  8065  8065 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 18:20:48.576  8066  8066 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-26 18:20:48.588  8067  8067 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 18:20:48.600  8068  8068 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 18:20:48.625  8070  8070 I libmdmdetect: ESOC framework not supported
,08-26 18:20:48.626  8070  8070 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 18:20:48.634  8070  8070 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-26 18:20:48.634  8070  8070 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 18:20:48.634  8070  8070 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 18:20:48.634  8070  8070 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 18:20:48.634  8070  8070 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 18:20:48.634  8070  8070 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 18:20:48.634  8070  8070 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 18:20:48.656  1034  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{13f5c97d type 2 when 139561 com.google.android.gms} when 139561
,08-26 18:20:48.669   307  8073 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-26 18:20:48.673  8070  8071 E QC-QMI  : qmi_client [8070] 15: failed to locate client data
08-26 18:20:48.673   479   479 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-26 18:20:48.674   479   479 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-26 18:20:48.677  1034  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 18:20:48.754  8078  8078 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 18:20:48.767  8079  8079 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-26 18:20:48.794  7771  8010 I bt_vendor: bluetooth satus is on
08-26 18:20:48.794  7771  8010 D bt_hci_bdroid: preload
08-26 18:20:48.794  7771  8054 D bt_userial_mct: userial_open(port:0)
,08-26 18:20:48.794  7771  8054 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 18:20:48.797  7771  8054 I bt_vendor: Done intiailizing UART
,08-26 18:20:48.798  7771  8054 I bt_vendor: Done intiailizing UART
08-26 18:20:48.798  7771  8054 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 18:20:48.799  7771  8054 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 18:20:48.799  7771  8083 D bt_userial_mct: Entering userial_read_thread()
08-26 18:20:48.799  7771  8052 I bt-btu  : btu_task received preload complete event
08-26 18:20:48.799  7771  8052 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 18:20:48.800  7771  8052 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 18:20:48.802  7771  8052 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 18:20:48.806  7771  8052 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 18:20:48.858  7771  8052 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-26 18:20:48.858  7771  8052 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0195061 
08-26 18:20:48.858  7771  8052 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0195061 
,08-26 18:20:48.871  7771  8014 E bt-btif : Calling BTA_HhEnable
,08-26 18:20:48.871  7771  8014 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-26 18:20:48.872  7771  8014 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 18:20:48.873  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 18:20:48.873  7771  8052 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-26 18:20:48.873  7771  8052 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 18:20:48.873  7771  8052 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 18:20:48.873  7771  8052 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 18:20:48.873  7771  8052 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 18:20:48.873  7771  8014 D BluetoothAdapterProperties: Name is: G3
08-26 18:20:48.875  7771  8014 D BluetoothAdapterProperties: Scan Mode:20
08-26 18:20:48.875  7771  8014 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 18:20:48.875  7771  8014 D bt_hci_bdroid: postload
08-26 18:20:48.876  7771  8052 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 18:20:48.876  7771  8054 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 18:20:48.876  7771  8054 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 18:20:48.876  7771  8014 D bte_conf: Device ID record 1 : primary
,08-26 18:20:48.876  7771  8014 D bte_conf:   vendorId            = 00c4
08-26 18:20:48.876  7771  8014 D bte_conf:   vendorIdSource      = 0001,
08-26 18:20:48.876  7771  8014 D bte_conf:   product             = 13a1
,08-26 18:20:48.876  7771  8014 D bte_conf:   version             = 1000
08-26 18:20:48.876  7771  8014 D bte_conf:   clientExecutableURL = ,
08-26 18:20:48.876  7771  8014 D bte_conf:   serviceDescription  = 
,08-26 18:20:48.876  7771  8014 D bte_conf:   documentationURL    = 
,08-26 18:20:48.876  7771  8014 D bte_conf: bte_load_did_conf no section named DID2.
08-26 18:20:48.877  7771  8054 D bt_hci_bdroid: Used up Tx Cmd credits,
08-26 18:20:48.877  7771  8054 D bt_hci_bdroid: Used up Tx Cmd credits
,08-26 18:20:48.878  7771  8054 D bt_hci_bdroid: Used up Tx Cmd credits
,08-26 18:20:48.867  8085  8085 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 18:20:48.867  8085  8085 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 18:20:48.873  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 18:20:48.880  7771  8083 E bt_mct  : hci lib postload completed
08-26 18:20:48.882  7771  8014 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 18:20:48.883  7771  8010 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 18:20:48.883  7771  8010 D BluetoothAdapterProperties: ScanMode =  20
08-26 18:20:48.883  7771  8010 D BluetoothAdapterProperties: State =  11
08-26 18:20:48.884  7771  8010 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
,08-26 18:20:48.884  7771  8010 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 18:20:48.885  7771  8010 D BluetoothAdapterProperties: Setting state to 12
08-26 18:20:48.885  7771  8010 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 18:20:48.885  7771  8014 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 18:20:48.887  1034  1110 D BluetoothManagerService: Message: 60
08-26 18:20:48.888  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 18:20:48.888  1034  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-26 18:20:48.888  7771  8052 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 18:20:48.888  7771  8052 W bt-smp  : Plain text(LSB ~ MSB) = 5b 45 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 18:20:48.889  7771  8052 W bt-smp  : Encrypted text(LSB ~ MSB) = 3f 0f 69 c4 f8 26 0d f3 5b 37 e7 70 cf 0f 2b 1f 
,08-26 18:20:48.889  7771  8052 W bt-btm  : Stopping oneshot timer
08-26 18:20:48.896  6932  6947 D BluetoothPan: onBluetoothStateChange on: true
08-26 18:20:48.896  6932  6947 D BluetoothPan: onBluetoothStateChange call bindService
08-26 18:20:48.903  7771  8010 I BluetoothAdapterState: Entering On State
,08-26 18:20:48.914  7771  8014 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 18:20:48.914  7771  8014 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 18:20:48.919  1034  1110 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 18:20:48.920  1034  1110 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 18:20:48.920  7771  8052 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 18:20:48.920  7771  8052 W bt-smp  : Plain text(LSB ~ MSB) = 9e 77 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 18:20:48.920  7771  8052 W bt-smp  : Encrypted text(LSB ~ MSB) = 58 99 0a e8 28 0c a1 e3 af 7b 34 3b 62 70 38 1a 
08-26 18:20:48.920  7771  8052 W bt-btm  : Stopping oneshot timer
,08-26 18:20:48.926  1855  3502 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 18:20:48.926  7771  8010 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 18:20:48.926  7771  8010 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 18:20:48.926  7771  8010 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-26 18:20:48.927  1034  1034 D BluetoothHeadset: Proxy object connected
08-26 18:20:48.928  7771  8010 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 18:20:48.932  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:48.932  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:48.932  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:48.932  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:48.932  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:48.932  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:48.932  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:48.932  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:48.935  7771  8052 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 18:20:48.935  7771  8052 W bt-smp  : Plain text(LSB ~ MSB) = 60 b2 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 18:20:48.935  7771  8052 W bt-smp  : Encrypted text(LSB ~ MSB) = 18 4e b1 e9 23 c0 8a a0 03 ae 27 bb 7f b1 ec 7f 
,08-26 18:20:48.935  7771  8052 W bt-btm  : Stopping oneshot timer
08-26 18:20:48.939  1034  1034 D BluetoothA2dp: Proxy object connected
08-26 18:20:48.943  6932  6932 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 18:20:48.943  6932  6932 D PanProfile: Bluetooth service connected
08-26 18:20:48.944  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:48.945  1855  1855 D BluetoothHeadset: Proxy object connected
08-26 18:20:48.945  6932  6948 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 18:20:48.947  7771  8052 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-26 18:20:48.947  7771  8052 W bt-smp  : Plain text(LSB ~ MSB) = ad 94 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 18:20:48.947  7771  8052 W bt-smp  : Encrypted text(LSB ~ MSB) = 95 e5 d9 61 b8 86 b7 7e 2c af ed b2 63 a2 8d 04 
08-26 18:20:48.947  7771  8052 W bt-btm  : Stopping oneshot timer
08-26 18:20:48.948  6932  6948 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 18:20:48.954  7771  8010 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-26 18:20:48.957  6932  6932 D BluetoothHeadset: Proxy object connected
08-26 18:20:48.957  6932  6932 D HeadsetProfile: Bluetooth service connected
08-26 18:20:48.960  6932  6948 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 18:20:48.960  6932  6932 D BluetoothInputDevice: Proxy object connected
08-26 18:20:48.960  6932  6932 D HidProfile: Bluetooth service connected
,08-26 18:20:48.963  8091  8091 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 18:20:48.963  7771  8052 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 18:20:48.964  7771  8052 W bt-smp  : Plain text(LSB ~ MSB) = e6 ff 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 18:20:48.964  7771  8052 W bt-smp  : Encrypted text(LSB ~ MSB) = fc 8a 64 55 99 fb 00 2a f0 0c 04 4e 53 0e f0 f1 
08-26 18:20:48.964  7771  8052 W bt-btm  : Stopping oneshot timer
08-26 18:20:48.965  1855  4393 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 18:20:48.967  1855  1855 D BluetoothHeadset: Proxy object connected
08-26 18:20:48.967  1855  3501 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 18:20:48.968  6932  6932 D BluetoothMap: Proxy object connected
08-26 18:20:48.968  6932  6932 D MapProfile: Bluetooth service connected
08-26 18:20:48.968  6932  6932 D BluetoothMap: getConnectedDevices()
08-26 18:20:48.969  7771  7787 V BluetoothMapService: getConnectedDevices()
08-26 18:20:48.971  1855  1855 D BluetoothHeadset: Proxy object connected
08-26 18:20:48.971  6932  7683 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 18:20:48.973  6932  6947 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 18:20:48.977  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 18:20:48.978  1034  1110 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 18:20:48.978  1034  1110 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 18:20:48.978  6932  6932 D BluetoothA2dp: Proxy object connected
08-26 18:20:48.978  6932  6932 D A2dpProfile: Bluetooth service connected
08-26 18:20:48.979  1034  1110 D BluetoothManagerService: Message: 40
08-26 18:20:48.979  1034  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 18:20:48.980  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:48.980  1944  2104 D LGBluetoothAPIService: Message: 1
08-26 18:20:48.980  1944  2104 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 18:20:48.982  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 18:20:48.986  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:48.993  7771  7771 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:48.993  7771  7771 D BluetoothMapService: STATE_ON
08-26 18:20:48.996  1944  2104 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-26 18:20:49.000  6932  6932 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-26 18:20:49.001  6932  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 18:20:49.007  6932  6932 D DockEventReceiver: finishStartingService: stopping service
08-26 18:20:49.012  7771  7771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:49.012  7771  7771 V BluetoothPbapService: Pbap Service onCreate
08-26 18:20:49.013  7771  7771 V BluetoothPbapService: Starting PBAP service
,08-26 18:20:49.014  7771  7771 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,08-26 18:20:49.014  7771  7771 V BluetoothPbapService: Pbap Service onBind
08-26 18:20:49.015  7771  7771 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:49.016  6932  6932 D BluetoothPbap: Proxy object connected
08-26 18:20:49.016  6932  6932 D PbapServerProfile: Bluetooth service connected
08-26 18:20:49.016  7771  7771 V BluetoothPbapService: state: 12
08-26 18:20:49.016  7771  7771 V BluetoothMapService: Handler(): got msg=1
08-26 18:20:49.016  7771  7771 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
,08-26 18:20:49.018  7771  7771 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 18:20:49.019  7771  7771 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 18:20:49.019  7771  8099 D BluetoothMapMasInstance: MAS initSocket()
,08-26 18:20:49.020  1944  1944 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 18:20:49.020  7771  7771 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 18:20:49.020  1944  2104 D LGBluetoothAPIService: Message: 100
08-26 18:20:49.020  1944  2104 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 18:20:49.020  7771  7771 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:49.020  7771  7771 V BluetoothPbapReceiver: ***********state = 12
08-26 18:20:49.020  7771  8099 D BluetoothMapMasInstance:   masId = 00
08-26 18:20:49.020  7771  8099 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 18:20:49.020  7771  8099 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 18:20:49.020  7771  8099 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 18:20:49.021  7771  7771 V BluetoothPbapService: Handler(): got msg=1
08-26 18:20:49.022  7771  7771 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 18:20:49.025  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 18:20:49.025  7771  8100 V BluetoothPbapService: Pbap Service initSocket
08-26 18:20:49.025  2140  2140 D c       : Getting all permits...
08-26 18:20:49.025  2140  2140 D a       : Opening database...
08-26 18:20:49.029  2140  2140 D a       : Opening database auth.proximity.permit_store...
,08-26 18:20:49.030  2140  2140 D a       : Closing database...
08-26 18:20:49.031  1034  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:49.031  1034  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:49.034  7771  8099 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 18:20:49.035  7771  8100 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 18:20:49.036  7771  8099 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 18:20:49.036  7771  8099 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 18:20:49.036  7771  8099 D BluetoothMapMasInstance: Accepting socket connection...
08-26 18:20:49.040  7771  8014 D BluetoothAdapterProperties: Scan Mode:21
,08-26 18:20:49.041  7771  8014 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-26 18:20:49.042  7771  8100 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 18:20:49.042  7771  8100 V BluetoothPbapService: Succeed to create listening socket 
08-26 18:20:49.042  7771  8100 V BluetoothPbapService: Accepting socket connection...
08-26 18:20:49.044  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:49.050  6932  6932 D BluetoothPermissionRequest: onReceive
08-26 18:20:49.052  6932  6932 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 18:20:49.054  6932  6932 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 18:20:49.058  7771  7771 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 18:20:49.060  7771  7771 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 18:20:49.069  7771  7771 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-26 18:20:49.098  7771  7771 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-26 18:20:49.098  7771  7771 V BtOppService: onCreate
08-26 18:20:49.104  7771  7771 V BluetoothOppNotification: send message
08-26 18:20:49.108  7771  7771 V BtOppService: Starting RfcommListener
08-26 18:20:49.117  7771  7771 D BluetoothOppPreference: Dumping Names:  
08-26 18:20:49.117  7771  7771 D BluetoothOppPreference: {}
08-26 18:20:49.117  7771  7771 D BluetoothOppPreference: Dumping Channels:  
08-26 18:20:49.117  7771  7771 D BluetoothOppPreference: {}
08-26 18:20:49.119  7771  7771 V BtOppService: onStartCommand
,08-26 18:20:49.124  7771  7771 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:49.124  7771  7771 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 18:20:49.125  7771  8106 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 18:20:49.129  7771  7771 V BluetoothOppNotification: new notify threadi!
08-26 18:20:49.131  7771  7771 V BluetoothOppNotification: send delay message
,08-26 18:20:49.135  7771  7771 V BtOppService: start RfcommListener
08-26 18:20:49.135  7771  8107 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 18:20:49.136  7771  8106 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 18:20:49.142  7771  8107 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ebc2a68 on behalf of 
08-26 18:20:49.142  7771  8106 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f79ee81 on behalf of 
08-26 18:20:49.143  7771  7771 V BtOppService: RfcommListener started
08-26 18:20:49.144  7771  8103 V BtOppService: Deleted complete outbound shares, number =  0
08-26 18:20:49.146  7771  8108 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 18:20:49.147  7771  8107 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-26 18:20:49.148  1034  1727 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:49.149  7771  8103 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 18:20:49.149  7771  8103 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 18:20:49.151  7771  8103 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@265c0b26 on behalf of 
08-26 18:20:49.154  7771  8106 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 18:20:49.154  7771  8108 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 18:20:49.155  7771  8107 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 18:20:49.156  7771  8108 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-26 18:20:49.157  7771  8108 V BtOppRfcommListener: Started RFCOMM listener....
08-26 18:20:49.157  7771  8107 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25fa8367 on behalf of 
08-26 18:20:49.157  7771  8108 I BtOppRfcommListener: Accept thread started.
08-26 18:20:49.157  7771  8108 V BtOppRfcommListener: Accepting connection...
08-26 18:20:49.158  7771  8107 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 18:20:49.160  7771  8107 V BluetoothOppNotification: outbound notification was removed.
08-26 18:20:49.160  7771  8107 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-26 18:20:49.162  7771  8107 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@85d8514 on behalf of 
08-26 18:20:49.163  7771  8107 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 18:20:49.165  7771  8107 V BluetoothOppNotification: inbound notification was removed.
08-26 18:20:49.165  7771  7771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:49.165  7771  8107 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 18:20:49.165  7771  7771 V BluetoothFtpService: Ftp Service onCreate
08-26 18:20:49.165  7771  7771 I BluetoothFtpService: Ftp Service onCreate
,08-26 18:20:49.166  7771  7771 V BluetoothFtpService: Ftp Service onStartCommand
08-26 18:20:49.166  7771  7771 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:49.166  7771  7771 V BluetoothFtpService: Starting Listening on sockets
08-26 18:20:49.167  7771  7771 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 18:20:49.167  7771  8107 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22edb3b2 on behalf of 
08-26 18:20:49.167  7771  7771 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 18:20:49.167  7771  7771 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 18:20:49.167  7771  7771 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:49.167  7771  7771 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 18:20:49.168  7771  7771 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 18:20:49.170  7771  7771 V BtOppService: ContentObserver received notification
08-26 18:20:49.170  7771  7771 V BtOppService: ContentObserver received notification
08-26 18:20:49.170  7771  7771 V BluetoothFtpService: Handler(): got msg=1
08-26 18:20:49.171  7771  7771 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 18:20:49.171  7771  7771 V BluetoothFtpService: Ftp Service initSocket
08-26 18:20:49.172  7771  8109 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 18:20:49.172  7771  8109 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 18:20:49.173  7771  8109 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39a1ef03 on behalf of 
08-26 18:20:49.174  7771  8109 V BluetoothOppNotification: update too frequent, put in queue
,08-26 18:20:49.175  7771  8109 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-26 18:20:49.177  1034  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:49.177  7771  7771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 18:20:49.179  7771  7771 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-26 18:20:49.179  7771  7771 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 18:20:49.182  7771  8110 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-26 18:20:49.195  7771  7771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f949f
08-26 18:20:49.195  7771  7771 V BluetoothSapService: Sap Service onCreate
,08-26 18:20:49.198  7771  7771 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:49.198  7771  7771 V BluetoothSapService: state: 12
08-26 18:20:49.198  7771  7771 V BluetoothSapService: Starting SAP server process
08-26 18:20:49.200  7771  7771 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 18:20:49.187  8111  8111 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:49.187  8111  8111 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:49.202  7771  8112 V BluetoothSapService: Sap Service initRfcommSocket
08-26 18:20:49.203  1034  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:49.204  7771  8112 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 18:20:49.205  7771  8112 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-26 18:20:49.205  7771  8112 V BluetoothSapService: Succeed to create listening socket 
08-26 18:20:49.205  7771  8112 V BluetoothSapService: Accepting socket connection...
08-26 18:20:49.215  8111  8111 V BT_SAP  : Event pipe created
08-26 18:20:49.215  8111  8111 V BT_SAP  : create_server_socket qcom.sap.server
08-26 18:20:49.215  8111  8111 V BT_SAP  : created socket fd 6
,08-26 18:20:49.276  7797  7819 D UEI.SmartControl: Internal timer expired: 1
08-26 18:20:49.276  7797  7819 D UEI.SmartControl: unbind internal service
,08-26 18:20:49.283  7797  7797 D UEI.SmartControl: Service.onUnbind: IControl
08-26 18:20:49.285  7797  7797 D UEI.SmartControl: Service.onDestroy
08-26 18:20:49.285  7797  7797 D UEI.SmartControl: Lock is in USE false
08-26 18:20:49.285  7797  7797 D UEI.SmartControl: unbind internal service
08-26 18:20:49.288  7797  7797 D serial_port: close(fd = 25)
08-26 18:20:49.293  7797  7797 I UEI.SmartControl: Serial port is closed.
,08-26 18:20:49.297  7797  7797 I UEI.SmartControl: Serial port is closed.
,08-26 18:20:49.297  7797  7797 D UEI.SmartControl: Blaster closed
,08-26 18:20:49.297  7797  7797 D UEI.SmartControl: Shut down QS...
,08-26 18:20:49.297  7797  7797 D UEI.SmartControl: Stopping QS lib
,08-26 18:20:49.298  7797  7797 D UEI.SmartControl: QS lib stop result = true,
08-26 18:20:49.298  7797  7797 D UEI.SmartControl: Stopped QS lib
08-26 18:20:49.298  7797  7797 D UEI.SmartControl: Stopped file observer...
08-26 18:20:49.298  7797  7797 D UEI.SmartControl: QS shutdown complete
08-26 18:20:49.592  6669  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-26 18:20:49.592  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:49.592  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:49.592  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:49.592  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:49.592  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:49.592  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:49.592  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 18:20:49.607  6669  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:49.610  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:49.611  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@389991d9 added. We now have 8 listener(s)
08-26 18:20:49.611  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:49.616  1034  1050 D WifiServiceImplEx: setWifiEnabled: false pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-26 18:20:49.619  1034  1050 D WifiService: setWifiEnabled: false pid=6669, uid=10118
08-26 18:20:49.621  1034  1050 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 18:20:49.626  6669  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:49.627  1034  1990 D WifiServiceImplEx: setWifiEnabled: true pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 18:20:49.628  1034  1990 D WifiService: setWifiEnabled: true pid=6669, uid=10118
08-26 18:20:49.628  1034  1990 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 18:20:49.651  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 18:20:49.651  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 18:20:49.651  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 18:20:49.653  1034  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-26 18:20:49.653  1034  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-26 18:20:49.656  1034  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-26 18:20:49.656  1034  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 18:20:49.656  1034  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 18:20:49.656  1034  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 18:20:49.659  1034  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 18:20:49.659  1034  1539 E WifiHW  : unknown target_country: EU , set to default
08-26 18:20:49.659  1034  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 18:20:49.659  1034  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 18:20:49.659  1034  1539 I WifiUtil: gEnableBmps=1
,08-26 18:20:50.133  7771  7771 V BluetoothOppNotification: new notify threadi!
,08-26 18:20:50.133  7771  7771 V BluetoothOppNotification: send delay message
,08-26 18:20:50.139  7771  8131 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 18:20:50.151  7771  8131 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23ca785f on behalf of 
08-26 18:20:50.152  7771  8131 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-26 18:20:50.155  7771  8131 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-26 18:20:50.156  7771  8131 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@265c62ac on behalf of 
08-26 18:20:50.157  7771  8131 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 18:20:50.158  7771  8131 V BluetoothOppNotification: outbound notification was removed.
08-26 18:20:50.158  7771  8131 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 18:20:50.159  7771  8131 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@386e9b75 on behalf of 
08-26 18:20:50.160  7771  8131 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 18:20:50.161  7771  8131 V BluetoothOppNotification: inbound notification was removed.
08-26 18:20:50.161  7771  8131 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 18:20:50.162  7771  8131 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2bf4070a on behalf of 
08-26 18:20:50.207   307   889 D SoftapController: Softap fwReload - Ok
,08-26 18:20:50.215  1034  1539 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (550ms)
08-26 18:20:50.224   307   889 D CommandListener: Setting iface cfg
08-26 18:20:50.224   307   889 D CommandListener: Trying to bring down wlan0
,08-26 18:20:50.227  1034  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 18:20:50.227  1034  1110 D Tethering: InitialState.processMessage what=4
08-26 18:20:50.235   307   889 D CommandListener: Clearing all IP addresses on wlan0
08-26 18:20:50.236  1034  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 18:20:50.246  1034  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-26 18:20:50.258  1034  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 18:20:50.258  1034  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 18:20:50.258  1034  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 18:20:50.247  8133  8133 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:50.267  1034  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 18:20:50.267  1034  1539 D WifiMonitor: connecting to supplicant
,08-26 18:20:50.274  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:50.257  8133  8133 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:50.279  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 18:20:50.284  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:50.285  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-26 18:20:50.288  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-26 18:20:50.288  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 18:20:50.288  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 18:20:50.288  6932  6932 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 18:20:50.288  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 18:20:50.289  6932  6932 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 18:20:50.290  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 18:20:50.290  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 18:20:50.290  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 18:20:50.290  6932  6932 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 18:20:50.290  6932  6932 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 18:20:50.295  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 18:20:50.295  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 18:20:50.296  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 18:20:50.296  6932  6932 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 18:20:50.296  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 18:20:50.297  6932  6932 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 18:20:50.297  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 18:20:50.297  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 18:20:50.297  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 18:20:50.297  6932  6932 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 18:20:50.297  6932  6932 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 18:20:50.301  8133  8133 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 18:20:50.335  8133  8133 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 18:20:50.335  8133  8133 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-26 18:20:50.351  1034  2035 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8151 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-26 18:20:50.401  8133  8133 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 18:20:50.469  1034  1907 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8173 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 18:20:50.474  8151  8171 W FormManager: Network not available. Please check & try again.
08-26 18:20:50.475  8133  8133 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-26 18:20:50.479  8151  8172 V FormManager: Network unavailable.
08-26 18:20:50.480  8151  8172 V FormManager: Network unavailable.
08-26 18:20:50.482  8133  8133 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-26 18:20:50.483  1034  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-26 18:20:50.483  1034  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 18:20:50.484  1034  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 18:20:50.484  1034  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 18:20:50.484  1034  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 18:20:50.484  1034  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 18:20:50.484  1034  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 18:20:50.485  1034  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 18:20:50.485  1034  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:50.486  1034  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:50.487  1034  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:50.487  1034  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:50.488  1034  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 18:20:50.488  1034  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 18:20:50.488  1034  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 18:20:50.488  1034  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 18:20:50.489  1034  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 18:20:50.489  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:50.489  1034  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 18:20:50.489  1034  1539 E WifiStateMachine: useWiFiOffloading() : false
08-26 18:20:50.489  1034  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 18:20:50.489  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:50.490  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:50.490  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:50.490  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 18:20:50.491  1944  1944 D WfdService: Waiting for WifiP2p enabling
08-26 18:20:50.491  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:50.491  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 18:20:50.492  1034  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 18:20:50.492  1034  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 18:20:50.492  1034  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-26 18:20:50.492  1034  1539 D WifiConfigStore: Loading config and enabling all networks 
08-26 18:20:50.492  1034  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 18:20:50.492  1034  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 18:20:50.499  1034  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-26 18:20:50.503  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:50.503  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:50.503  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:50.503  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:50.503  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:50.503  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:50.503  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:50.503  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:50.505  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:50.509  1034  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 18:20:50.509  1034  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 18:20:50.510  1034  1539 D WifiStateMachine: enableVerboseLogging : level 2
08-26 18:20:50.510  1034  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 18:20:50.511  1034  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 18:20:50.511  1034  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 18:20:50.511  1034  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 18:20:50.511  1034  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 18:20:50.512  1034  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 18:20:50.512  1034  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 18:20:50.512  1034  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 18:20:50.512  1034  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 18:20:50.513  1034  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
,08-26 18:20:50.513  1034  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 18:20:50.513  1034  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 18:20:50.513  1034  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 18:20:50.514  1034  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 18:20:50.515  1034  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 18:20:50.515  1034  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 18:20:50.515  1034  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 18:20:50.515  1034  1539 D WifiNative-HAL: Setting external_sim to 1
08-26 18:20:50.515  1034  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 18:20:50.515  1944  1944 D WfdsService: Supplicant Connection state is changed : true
08-26 18:20:50.515  1944  2286 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 18:20:50.515  1944  2286 D WfdsService: Set the WFDS Monitor: true
,08-26 18:20:50.515  1944  2286 D WfdsMonitor: WfdsMonitorThread create
08-26 18:20:50.515  1944  2286 D WfdsMonitor: WFDS Monitor is created and started
08-26 18:20:50.515  1944  2286 D WfdsService: WiFi: Supplicant connection re-established
08-26 18:20:50.516  7823  7823 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:50.516  1034  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 18:20:50.516  1034  1539 I WifiNative-HAL: startHal
08-26 18:20:50.516  1034  1539 D wifi    : setting scan oui 0xaf68e780
08-26 18:20:50.516  1034  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 18:20:50.516  1034  1539 I WifiNative-HAL: startHal
08-26 18:20:50.516  1034  1539 D wifi    : setting scan oui 0xaf68e780
08-26 18:20:50.517  1944  8192 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 18:20:50.517  1034  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 18:20:50.517  1944  8192 E CtrlSupplicant: Succeed to open control connection
08-26 18:20:50.517  1944  8192 E CtrlSupplicant: Succeed to open monitor connection
08-26 18:20:50.517  1944  8192 D WfdsMonitor: Supplicant connection established
08-26 18:20:50.517  1944  2286 D WfdsService: Connected to the supplicant for wfds
08-26 18:20:50.517  1034  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 18:20:50.517  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 18:20:50.518  8133  8133 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 18:20:50.519  1034  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 18:20:50.519  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 18:20:50.519  8133  8133 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 18:20:50.519  1034  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 18:20:50.519  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 18:20:50.519  8133  8133 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 18:20:50.520  1034  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 18:20:50.520  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 18:20:50.520  8133  8133 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 18:20:50.520  1034  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 18:20:50.520  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 18:20:50.520  8133  8133 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 18:20:50.521  1034  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 18:20:50.521  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 18:20:50.521  8133  8133 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 18:20:50.521  1034  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 18:20:50.521  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 18:20:50.521  8133  8133 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 18:20:50.521  1034  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 18:20:50.522  1034  1539 E WifiNative: : [141,427,156 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 18:20:50.523  1034  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 18:20:50.523  1034  1539 D WifiNative-wlan0: RECONNECT: returned true
08-26 18:20:50.523  1034  1539 D WifiNative-wlan0: doString: [STATUS]
08-26 18:20:50.523  1034  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 18:20:50.523  1034  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 18:20:50.524  1034  1539 D WifiNative-wlan0:    returned wpa_st,ate=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 18:20:50.524  1034  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 18:20:50.524  1034  1539 D WifiNative-wlan0: SET ps 1: returned true
08-26 18:20:50.524  1034  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 18:20:50.525  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 18:20:50.525  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-26 18:20:50.525  1034  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.525  1034  1557 I WifiNative-HAL: startHal
08-26 18:20:50.525  1034  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf68e780
08-26 18:20:50.525  1034  1557 D wifi    : failed to get capabilities : -3
,08-26 18:20:50.525  1034  1557 E WifiScanningService: could not get scan capabilities
08-26 18:20:50.526  1034  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 18:20:50.526  1034  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 18:20:50.526  1034  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.527  1034  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 18:20:50.527   307   889 D CommandListener: Setting iface cfg
08-26 18:20:50.527   307   889 D CommandListener: Trying to bring up p2p0
,08-26 18:20:50.527  1034  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 18:20:50.527  1034  1538 D LGWifiP2pService: P2pEnablingState
08-26 18:20:50.527  1034  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 18:20:50.527  1034  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.527  1034  1538 D LGWifiP2pService: P2p socket connection successful
08-26 18:20:50.527  1034  1538 D LGWifiP2pService: P2pEnabledState
08-26 18:20:50.527  1034  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 18:20:50.528  1034  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 18:20:50.528  1034  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 18:20:50.528  1034  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 18:20:50.528  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 18:20:50.528  8133  8133 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 18:20:50.528  1944  1944 D WfdsService: WifiP2pState is changed : true
08-26 18:20:50.528  1944  2286 D WfdsService: Receive the WFDS_ENABLE Method
08-26 18:20:50.528  1944  2286 D WfdsService: Set the WFDS Monitor: true
08-26 18:20:50.529  1944  2286 D WfdsService: Connected to the supplicant for wfds
08-26 18:20:50.529  1944  2286 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 18:20:50.529  8133  8133 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 18:20:50.529  1944  2286 D WfdsService: selectPreferredScanChannel [36]
08-26 18:20:50.529  1944  2286 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 18:20:50.530  1034  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 18:20:50.530  1034  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 18:20:50.531  1034  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 18:20:50.531  1034  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 18:20:50.531  1034  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 18:20:50.531  1034  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 18:20:50.531  1034  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 18:20:50.531  8133  8133 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 18:20:50.532  1944  1944 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 18:20:50.532  1944  1944 D WfdsService: isConnected: false
08-26 18:20:50.532  1034  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 18:20:50.533  1034  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-26 18:20:50.533  1034  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 18:20:50.533  1034  1538 D LGWifiP2pService: before postfix = G3
08-26 18:20:50.533  1034  1538 D WifiServerServiceExt: postfix byte check : 2
08-26 18:20:50.533  1034  1538 D LGWifiP2pService: after postfix = G3
08-26 18:20:50.533  1034  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 18:20:50.533  1034  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 18:20:50.533  1034  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 18:20:50.533  1034  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 18:20:50.533  1034  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 18:20:50.533  1034  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 18:20:50.533  1034  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 18:20:50.533  1034  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 18:20:50.533  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 18:20:50.533  1034  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 18:20:50.533  1034  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2,p
08-26 18:20:50.534  8133  8133 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 18:20:50.534  8133  8133 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 18:20:50.535  1034  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 18:20:50.535  1034  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 18:20:50.535  1034  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 18:20:50.535  1034  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 18:20:50.535  8133  8133 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 18:20:50.535  8133  8133 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.535  1034  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 18:20:50.535  1944  8192 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 18:20:50.535  8133  8133 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.535  1034  8190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 18:20:50.535  1034  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 18:20:50.535  1034  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-26 18:20:50.535  1034  8190 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.536  1034  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.536  1034  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.536  1034  8190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 18:20:50.536  1034  8190 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.536  1034  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.536  1034  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 18:20:50.536  1034  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.536  1944  8192 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 18:20:50.536  1034  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 18:20:50.536  1034  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 18:20:50.536  1034  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 18:20:50.536  1034  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 18:20:50.537  1034  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 18:20:50.537  1034  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 18:20:50.537  1944  1944 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 18:20:50.537  1944  1944 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 18:20:50.538  1034  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 18:20:50.538  1944  1944 D WfdsService: Update P2p Interface State: 3
08-26 18:20:50.538  1034  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 18:20:50.538  1034  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 18:20:50.538  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-26 18:20:50.540  1034  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 18:20:50.540  1034  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 18:20:50.545  8173  8173 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 18:20:50.548  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 18:20:50.550  1034  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 18:20:50.550  1034  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 18:20:50.550  1034  1538 D LGWifiP2pService: InactiveState
08-26 18:20:50.550  1034  1538 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.550  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.550  1034  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 18:20:50.551  8133  8133 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 18:20:50.551  8133  8133 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 18:20:50.551  1034  8190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 18:20:50.551  1034  8190 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 18:20:50.551  1034  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 18:20:50.551  1034  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 18:20:50.552  1944  8192 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 18:20:50.552  8133  8133 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 18:20:50.552  8133  8133 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.552  1944  8192 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 18:20:50.553  8133  8133 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.553  1944  8192 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 18:20:50.553  1034  8190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 18:20:50.553  1034  8190 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.553  1034  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.553  1034  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.553  1034  8190 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 18:20:50.553  1034  8190 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.553  1034  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.553  1034  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 18:20:50.553  1034  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 18:20:50.554  1034  1538 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.554  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.554  1034  1538 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.554  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.554  1034  1538 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.554  8133  8133 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 18:20:50.554  8133  8133 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 18:20:50.554  1034  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-,REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 18:20:50.554  1034  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 18:20:50.554  1034  8190 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 18:20:50.554  1034  8190 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 18:20:50.555  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:50.555  1034  1538 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.555  1034  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 18:20:50.555  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.555  1034  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 18:20:50.555  1034  1538 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.555  1034  1538 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.555  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.555  1034  1538 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.555  1034  1538 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.555  1944  2286 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 18:20:50.556  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.556  1034  1538 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:50.556  1034  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 18:20:50.556  1034  1539 D WifiNative-wlan0: doBoolean: SCAN
08-26 18:20:50.556  1034  1539 D WifiNative-wlan0: SCAN: returned false
08-26 18:20:50.556  1034  1034 E WifiServerServiceExt: No p2p device connected
08-26 18:20:50.556  1034  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=141461  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 18:20:50.556  1034  1656 I ActivityManager: Killing 7227:com.lge.drmservice/u0a62 (adj 15): empty #17
08-26 18:20:50.574  1034  1893 W libprocessgroup: failed to open /acct/uid_10062/pid_7227/cgroup.procs: No such file or directory
08-26 18:20:50.574  1034  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=141480  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 18:20:50.575  1034  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 18:20:50.575  1034  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 18:20:50.575  1034  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 18:20:50.576  1034  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 18:20:50.576  1034  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-26 18:20:50.578  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:50.578  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:50.578  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 18:20:50.580  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:50.580  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:50.581  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:50.583  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:50.583  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 18:20:50.600  8173  8173 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 18:20:50.602  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:50.608  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:50.613  8151  8196 W FormManager: Network not available. Please check & try again.
,08-26 18:20:50.614  8151  8197 V FormManager: Network unavailable.
08-26 18:20:50.618  8151  8197 V FormManager: Network unavailable.
08-26 18:20:50.625  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 18:20:50.626  4752  4752 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 18:20:50.630  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 18:20:50.633  4752  4752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 18:20:50.636  4752  8198 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 18:20:50.642  4752  8199 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 18:20:50.642  4752  8199 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 18:20:50.675  6669  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:50.675  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:50.675  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:50.675  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:50.675  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:50.675  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:50.675  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:50.675  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 18:20:50.678  6669  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:50.688  6669  6729 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 18:20:50.689  6669  6729 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 18:20:50.691  1034  2053 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8200 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-26 18:20:50.694  6669  6729 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@13c30733 Bundle[{}]
08-26 18:20:50.695  6669  6729 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 18:20:50.696  6669  6729 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-26 18:20:50.696  6669  6729 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 18:20:50.697  6669  6729 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 18:20:50.698  6669  6729 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-26 18:20:50.699  6669  6729 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 18:20:50.708  6669  6729 I System.out: Running OutgoingSocketThread
,08-26 18:20:50.714  6669  8211 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 875)
08-26 18:20:50.716  6669  8211 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40723
08-26 18:20:50.716  6669  8211 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 18:20:50.841  8200  8200 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 18:20:50.841  8200  8200 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 18:20:50.852  8200  8200 V [BNRBootReceiver]: Boot Receiver Return
08-26 18:20:50.854  8200  8200 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 18:20:50.909  1034  1051 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8219 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 18:20:50.913  1034  1051 I ActivityManager: Killing 7252:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-26 18:20:50.933   339   339 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 469us total 22.437ms
,08-26 18:20:50.955   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 466us total 20.098ms
,08-26 18:20:50.973   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 373us total 18.106ms
,08-26 18:20:50.983  1034  1050 W libprocessgroup: failed to open /acct/uid_10085/pid_7252/cgroup.procs: No such file or directory
,08-26 18:20:51.019  8219  8219 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 18:20:51.028  8133  8133 E wpa_supplicant: USIM:  scard_init function
,08-26 18:20:51.029  8133  8133 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 18:20:51.032  1034  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-26 18:20:51.033  1034  8190 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 18:20:51.034  1034  8190 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 18:20:51.034  1034  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
,08-26 18:20:51.034  1034  8190 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 18:20:51.034  1034  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 18:20:51.034  1034  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-26 18:20:51.037  1034  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 18:20:51.041  1034  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 18:20:51.043  1034  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 18:20:51.044  1034  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 18:20:51.044  1034  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 18:20:51.048  8219  8219 D PluginManager: init()
08-26 18:20:51.056  1034  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=141961  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 18:20:51.061  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:51.061  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 18:20:51.062  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:51.066  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.066  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.066  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 18:20:51.073  1034  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=141978  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 18:20:51.076  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.076  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.076  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 18:20:51.078  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:51.078  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-26 18:20:51.084  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:51.084  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:51.085  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 18:20:51.149  8133  8133 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 18:20:51.153  1034  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 18:20:51.153  1034  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 18:20:51.153  1034  8190 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 18:20:51.153  1034  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 18:20:51.154  1034  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=142059  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 18:20:51.154  1034  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 18:20:51.154  1034  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 18:20:51.154  1034  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=142059  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 18:20:51.155  1034  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142060
08-26 18:20:51.156  1034  1110 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 18:20:51.158  1034  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142063
08-26 18:20:51.159  8133  8133 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 18:20:51.159  1034  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 18:20:51.159  8133  8133 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 18:20:51.159  1034  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 18:20:51.160  1034  8190 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 18:20:51.160  1034  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 18:20:51.160  1034  8190 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 18:20:51.160  1034  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 18:20:51.160  1034  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 18:20:51.160  1034  8190 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 18:20:51.161  1034  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 18:20:51.161  1034  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 18:20:51.162  1034  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142067
,08-26 18:20:51.167  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142072
08-26 18:20:51.169  1034  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142074
08-26 18:20:51.169  1034  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=142074  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 18:20:51.171  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:51.172  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:51.172  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.172  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.172  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 18:20:51.173  1034  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=142078  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 18:20:51.174  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:51.174  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.174  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.174  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-26 18:20:51.175  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:51.175  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 18:20:51.176  1034  1539 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:51.176  1034  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:51.176  1034  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:51.177  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:51.177  1034  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 18:20:51.178  1034  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=142083  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 18:20:51.178  1034  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=142083  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 18:20:51.179  1034  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=142084
08-26 18:20:51.179  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:51.179  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:51.179  1034  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=142084
08-26 18:20:51.180  1034  1539 D WifiNative-wlan0: doString: [STATUS]
08-26 18:20:51.180  1034  8190 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 18:20:51.180  1034  8190 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 18:20:51.180  1034  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 18:20:51.181  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:51.182  1034  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-26 18:20:51.191  1034  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 18:20:51.191  1034  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-26 18:20:51.194  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.194  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.194  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 18:20:51.198  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.198  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.198  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 18:20:51.200  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:51.200  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:51.203  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 18:20:51.205  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:51.205  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:51.206  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:51.207  1034  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 18:20:51.207  1034  1545 D ConnectivityService: Got NetworkAgent Messenger
08-26 18:20:51.207  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 18:20:51.207  1034  1545 D ConnectivityService: NetworkAgent connected
08-26 18:20:51.208  1034  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 18:20:51.208  1034  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 18:20:51.208  1034  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 18:20:51.208  1034  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 18:20:51.213  1034  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 18:20:51.213  1034  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 18:20:51.213  1034  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 18:20:51.214  1034  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 18:20:51.214  1034  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-26 18:20:51.218  1034  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 18:20:51.220   307   889 D CommandListener: Setting iface cfg
08-26 18:20:51.223  1034  1539 E WifiStateMachine: Start Dhcp Watchdog 3
08-26 18:20:51.223  1034  8237 D DhcpStateMachine: StoppedState
08-26 18:20:51.223  1034  8237 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:51.223  1034  8237 D DhcpStateMachine: WaitBeforeStartState
08-26 18:20:51.223  1034  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=142128  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 18:20:51.224  1034  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=142129  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 18:20:51.224  1034  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=142129  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 18:20:51.225  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:51.225  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 18:20:51.225  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:51.225  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 18:20:51.226  1034  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=142131  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 18:20:51.227  1034  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=142132  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 18:20:51.227  1034  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=142132  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-26 18:20:51.228  1034  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13908] from screen [on:0 period:-945331300] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 18:20:51.230  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-945331298] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 18:20:51.230  1034  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 18:20:51.233  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:51.234  1034  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-26 18:20:51.235  1034  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:51.235  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:51.236  1034  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:51.236  1034  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:51.236  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:51.237  1034  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 18:20:51.237  1034  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 18:20:51.237  1034  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=170,0,0
08-26 18:20:51.238  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=170,0,0
08-26 18:20:51.238  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 18:20:51.238  8133  8133 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 18:20:51.239  1034  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 18:20:51.239  1034  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 18:20:51.239  1034  1539 D WifiNative-wlan0: SET ps 0: returned true
08-26 18:20:51.239  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 18:20:51.240  8133  8133 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,08-26 18:20:51.240  1034  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
,08-26 18:20:51.240  1034  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 18:20:51.240  1034  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 18:20:51.240  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4423f30 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:51.240  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4423f30 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:51.240  1034  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 18:20:51.241  1034  8237 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:51.241  1034  8237 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 18:20:51.242   307   889 D CommandListener: Setting iface cfg
08-26 18:20:51.242   307   889 D CommandListener: Trying to bring up wlan0
08-26 18:20:51.243  1034  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 18:20:51.243  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:51.243  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 18:20:51.244  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 18:20:51.244  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 18:20:51.245  1034  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-26 18:20:51.246  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-26 18:20:51.246  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 18:20:51.246  1034  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:51.246  1034  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:51.246  8133  8133 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 18:20:51.246  1034  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 18:20:51.246  1034  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 18:20:51.247  8133  8133 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 18:20:51.247  1034  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 18:20:51.247  1034  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 18:20:51.265  1034  1539 D WifiNative-wlan0: SET ps 1: returned true
08-26 18:20:51.266  1034  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 18:20:51.267  1034  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 18:20:51.267  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 18:20:51.267  1034  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 18:20:51.268  1034  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 18:20:51.268  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 18:20:51.269  1034  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 18:20:51.269  1034  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-26 18:20:51.270  1034  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 18:20:51.271  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 18:20:51.271  1034  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 18:20:51.271  1034  1545 D ConnectivityService: ignoring duplicate network state non-change
08-26 18:20:51.275  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:51.275  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:51.276  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.276  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.276  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 18:20:51.276  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:51.278  1034  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 18:20:51.279  1034  1545 D ConnectivityService: Adding iface wlan0 to network 102
,08-26 18:20:51.289  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.289  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.289  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 18:20:51.292  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 18:20:51.294  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.294  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.294  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 18:20:51.294  1034  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 18:20:51.294  1034  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-26 18:20:51.295  1034  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-26 18:20:51.296  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 18:20:51.296   307   889 E Netd    : netlink response contains error (File exists)
08-26 18:20:51.296  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:51.296  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 18:20:51.298  1034  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 18:20:51.298  1034  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-26 18:20:51.298  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 18:20:51.298  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.298  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:51.298  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 18:20:51.299  1034  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 18:20:51.299  1034  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-26 18:20:51.299  1034  1545 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-26 18:20:51.299  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:51.300  1034  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 18:20:51.302  1034  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 18:20:51.303  1034  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-26 18:20:51.303  1034  8236 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:51.303  1034  8236 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 18:20:51.303  1034  8236 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:51.303  1034  8236 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.,com/generate_204 on "NG700"
08-26 18:20:51.304  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:51.304  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 18:20:51.304  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:51.305  1034  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 18:20:51.305  1034  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 18:20:51.305  1034  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:51.305  1034  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 18:20:51.305  1034  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:51.306  1034  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 18:20:51.306  1034  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-26 18:20:51.306  1034  1545 D ConnectivityService:    accepting network in place of null
08-26 18:20:51.306  1034  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:51.306  1855  1855 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 18:20:51.306  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 18:20:51.306  1034  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:51.306  1034  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 18:20:51.307  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:51.307   307  8241 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 18:20:51.307  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 18:20:51.307  1034  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 18:20:51.307  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:51.307  1034  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-26 18:20:51.307  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 18:20:51.308  1034  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 18:20:51.308  1034  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 18:20:51.308  1034  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 18:20:51.309  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 18:20:51.309  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 18:20:51.309  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 18:20:51.309  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 18:20:51.310  1034  1545 D ConnectivityService: validation of new default Network = false
08-26 18:20:51.310  1034  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 18:20:51.310  1034  1545 D DSQN    : enableDat,aServiceNotify 
08-26 18:20:51.310  1034  1545 D DSQN    : start dsqn bin
08-26 18:20:51.317  1034  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 18:20:51.307  8242  8242 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:51.307  8242  8242 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 18:20:51.317  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:51.317  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:51.317  1034  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:51.318  1034  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-26 18:20:51.319  1603  2082 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 18:20:51.329  8242  8242 E DSQN    : DSQN ssw
,08-26 18:20:51.337  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 18:20:51.338  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:51.338  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:51.366   307  8241 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-26 18:20:51.400   307  8241 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-26 18:20:51.433   307   888 D LGDataListener: argv[0]=dsqncommand
08-26 18:20:51.433   307   888 D LGDataListener: argv[1]=wlan0
,08-26 18:20:51.433   307   888 D LGDataListener: argv[2]=1
08-26 18:20:51.433   307   888 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 18:20:51.434  1034  1108 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 18:20:51.434  1034  1108 D DSQN    : start to monitor internet connection
08-26 18:20:51.443  1034  8237 D DhcpStateMachine: DHCPV4 request on wlan0
08-26 18:20:51.444  1034  8237 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 18:20:51.444  1034  8237 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-26 18:20:51.437  8248  8248 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:51.437  8248  8248 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 18:20:51.460  1034  8236 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 16:20:51 GMT], X-Android-Received-Millis=[1472228451460], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472228451432]}
08-26 18:20:51.460  1034  8236 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 18:20:51.460  1034  8236 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-26 18:20:51.461  1034  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-26 18:20:51.461  1034  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 18:20:51.461  1034  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 18:20:51.461  1034  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:51.461  1034  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 18:20:51.461  1034  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-26 18:20:51.462  1034  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 18:20:51.462  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:51.462  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:51.463  1034  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:51.464  1603  2082 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 18:20:51.464  1034  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:51.465  1034  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 18:20:51.465  1034  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 18:20:51.465  8248  8248 I dhcpcd  : version 5.5.6 starting
08-26 18:20:51.466  1855  1855 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:51.467  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 18:20:51.467  8248  8248 E dhcpcd  : get_duid: m
08-26 18:20:51.467  8248  8248 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 18:20:51.467  8248  8248 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 18:20:51.467  1034  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 18:20:51.502  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 18:20:51.503  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:51.505  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 18:20:51.519  8219  8219 W ExternalStrings: load override strings
08-26 18:20:51.519  8219  8219 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 18:20:51.519  8219  8219 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-26 18:20:51.521  8248  8248 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 18:20:51.521  8248  8248 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 18:20:51.521  8248  8248 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 18:20:51.521  8248  8248 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 18:20:51.521  8248  8248 D dhcpcd  : wlan0: sending REQUEST (xid 0x3287c20a), next in 4.81 seconds
08-26 18:20:51.523  8219  8219 D StatusProvider: onCreate
08-26 18:20:51.573  8248  8248 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 18:20:51.581  8219  8219 V Signer  : override build config not found
08-26 18:20:51.582  8219  8219 D Signer  : value of property debug is false
08-26 18:20:51.602  8248  8248 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 18:20:51.602  8248  8248 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-26 18:20:51.603  8248  8248 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-26 18:20:51.603  8248  8248 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 18:20:51.604  8248  8248 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-26 18:20:51.604  8248  8248 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 18:20:51.605  8248  8248 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-26 18:20:51.605  8248  8248 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 18:20:51.613  8219  8219 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-26 18:20:51.613  8219  8219 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,08-26 18:20:51.613  8219  8219 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-26 18:20:51.614  8219  8219 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-26 18:20:51.614  8219  8219 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-26 18:20:51.614  8219  8219 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
,08-26 18:20:51.614  8219  8219 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-26 18:20:51.614  8219  8219 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-26 18:20:51.615  8219  8219 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-26 18:20:51.615  8219  8219 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
,08-26 18:20:51.615  8219  8219 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-26 18:20:51.615  8219  8219 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-26 18:20:51.615  8219  8219 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-26 18:20:51.625  8219  8219 V LGMDMManager: Create singleton instance
08-26 18:20:51.665  8219  8219 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-26 18:20:51.714  6669  6729 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 876)
08-26 18:20:51.714  6669  6729 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 876)
08-26 18:20:51.718  6669  6729 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 881)
08-26 18:20:51.720  6669  6729 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 18:20:51.720  6669  6729 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 882)
08-26 18:20:51.723  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 18:20:51.723  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa9679e added. We now have 2 listener(s)
08-26 18:20:51.724  1034  2008 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 18:20:51.726  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 18:20:51.727  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:51.727  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:51.727  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:51.727  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e7727f added. We now have 9 listener(s)
08-26 18:20:51.727  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:51.727  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 18:20:51.731  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:51.734  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:51.736  6669  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:51.736  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:51.736  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:51.736  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:51.736  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:51.736  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:51.736  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:51.736  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:51.738  6669  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:51.739  6669  6729 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 18:20:51.739  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:51.739  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31087295 added. We now have 3 listener(s)
,08-26 18:20:51.741  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:51.742  8219  8264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 18:20:51.743  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:51.744  1034  2008 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 18:20:51.746  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 18:20:51.746  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:51.746  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:51.747  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:51.747  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27c05faa added. We now have 10 listener(s)
08-26 18:20:51.747  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:51.747  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:51.747  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:51.747  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:51.748  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:51.748  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:51.748  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:51.748  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:51.748  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa9679e removed from the list
08-26 18:20:51.748  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:51.748  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e7727f removed from the list
08-26 18:20:51.748  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:51.748  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:51.749  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:51.749  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:51.750  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:51.750  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:51.750  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:51.750  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e7727f not in the list
08-26 18:20:51.750  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:51.750  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:51.751  6669  6729 I org.thaliproje,ct.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:51.751  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:51.751  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:51.751  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27c05faa removed from the list
08-26 18:20:51.751  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:51.751  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:51.751  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:51.751  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:51.751  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31087295 removed from the list
08-26 18:20:51.752  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:51.752  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@318ab79b added. We now have 2 listener(s)
08-26 18:20:51.755  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:51.755  1034  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:51.758  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 18:20:51.758  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:51.758  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:51.758  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:51.758  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38e39738 added. We now have 9 listener(s)
08-26 18:20:51.758  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:51.759  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 18:20:51.761  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:51.766  6669  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:51.766  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:51.766  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:51.766  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:51.766  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:51.766  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:51.766  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:51.766  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 18:20:51.767  6669  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:51.767  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:51.767  6669  6729 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 18:20:51.769  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:51.769  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@339ccc76 added. We now have 3 listener(s)
08-26 18:20:51.769  1034  1656 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:51.771  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:51.774  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 18:20:51.774  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:51.774  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:51.774  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:51.774  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:51.775  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19533277 added. We now have 10 listener(s)
08-26 18:20:51.775  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:51.775  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:51.775  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 18:20:51.775  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 18:20:51.775  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:51.775  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 18:20:51.778  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 18:20:51.778  1034  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:51.783  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 18:20:51.784  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 18:20:51.787  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 18:20:51.819  1034  2053 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8274 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-26 18:20:51.820  1034  2053 I ActivityManager: Killing 7278:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-26 18:20:51.879  8219  8263 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 18:20:52.036  1034  1990 W libprocessgroup: failed to open /acct/uid_10093/pid_7278/cgroup.procs: No such file or directory
08-26 18:20:52.036  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 18:20:52.042  6669  6729 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 18:20:52.043  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:52.043  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:52.049  1034  8237 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-26 18:20:52.053  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:52.053  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 18:20:52.053  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:52.053  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:52.054  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:52.054  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 18:20:52.054  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:52.054  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@318ab79b removed from the list
08-26 18:20:52.054  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:52.054  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38e39738 removed from the list
08-26 18:20:52.054  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:52.055  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.055  1034  8237 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-26 18:20:52.056  1034  8237 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 18:20:52.056  1034  8237 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 18:20:52.057  1034  8237 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 18:20:52.057  1034  8237 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 18:20:52.057  1034  8237 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 18:20:52.057  1034  8237 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 18:20:52.059  1034  8237 D DhcpStateMachine: RunningState
08-26 18:20:52.062  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 18:20:52.063  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.065  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:52.066  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:52.066  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:52.066  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38e39738 not in the list
08-26 18:20:52.066  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:52.066  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.069  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:52.076  6669  6729 D BluetoothLeScanner: could not find callback wrapper
08-26 18:20:52.076  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:52.076  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:52.076  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:52.077  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19533277 removed from the list
08-26 18:20:52.077  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:52.077  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:52.077  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.077  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:52.077  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@339ccc76 removed from the list
08-26 18:20:52.079  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 18:20:52.079  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c013a02 added. We now have 2 listener(s)
08-26 18:20:52.080  1034  2008 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:52.087  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-26 18:20:52.087  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:52.087  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:52.087  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:52.087  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bbe7f13 added. We now have 9 listener(s)
08-26 18:20:52.088  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:52.088  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 18:20:52.091  8274  8274 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 18:20:52.093  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:52.097  6669  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:52.097  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:52.097  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:52.097  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:52.097  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:52.097  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:52.097  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:52.097  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:52.100  6669  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:52.101  6669  6729 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 18:20:52.101  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:52.101  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d75a349 added. We now have 3 listener(s)
08-26 18:20:52.102  1034  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:52.103  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:52.109  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:52.110  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 18:20:52.110  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:52.110  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:52.110  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:52.111  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364cf44e added. We now have 10 listener(s)
08-26 18:20:52.111  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:52.111  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:52.113  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:52.113  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 18:20:52.113  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 18:20:52.113  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:52.113  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 18:20:52.117  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 18:20:52.117  1034  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:52.121  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 18:20:52.122  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 18:20:52.125  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 18:20:52.125  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:52.127  6669  6729 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 18:20:52.127  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:52.127  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:52.127  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:52.127  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:52.127  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:52.127  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:52.127  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:52.127  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c013a02 removed from the list
08-26 18:20:52.127  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:52.127  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bbe7f13 removed from the list
08-26 18:20:52.127  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:52.127  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.128  8274  8274 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-26 18:20:52.128  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:52.128  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.129  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:52.129  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:52.129  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:52.129  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bbe7f13 not in the list
08-26 18:20:52.129  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:52.129  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.130  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:52.130  6669  6729 D BluetoothLeScanner: could not find callback wrapper
08-26 18:20:52.130  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:52.130  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:52.130  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:52.130  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings,: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364cf44e removed from the list
08-26 18:20:52.130  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:52.130  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:52.131  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.131  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:52.131  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d75a349 removed from the list
08-26 18:20:52.132  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:52.132  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18ec2b05 added. We now have 2 listener(s)
08-26 18:20:52.132  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:52.135  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 18:20:52.135  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:52.135  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:52.135  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:52.135  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c88075a added. We now have 9 listener(s)
08-26 18:20:52.135  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:52.140  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 18:20:52.142  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:52.146  6669  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:52.146  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:52.146  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:52.146  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:52.146  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:52.146  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:52.146  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:52.146  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:52.147  6669  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:52.147  6669  6729 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 18:20:52.147  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:52.147  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37073e68 added. We now have 3 listener(s)
08-26 18:20:52.148  1034  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:52.149  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:52.151  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-26 18:20:52.151  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:52.151  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:52.151  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:52.151  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:52.151  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f897281 added. We now have 10 listener(s)
08-26 18:20:52.151  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:52.151  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:52.151  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 18:20:52.151  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 18:20:52.151  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:52.151  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 18:20:52.155  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 18:20:52.155  1034  1727 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:52.159  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 18:20:52.160  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 18:20:52.161  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 18:20:52.162  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 18:20:52.164  6669  6729 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 18:20:52.166  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:52.166  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:52.166  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:52.166  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:52.166  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:52.166  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:52.166  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:52.167  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18ec2b05 removed from the list
08-26 18:20:52.167  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:52.167  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c88075a removed from the list
08-26 18:20:52.167  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:52.167  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.167  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:52.167  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.168  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:52.168  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:52.168  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:52.168  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c88075a not in the list
08-26 18:20:52.168  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:52.168  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.169  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:52.169  6669  6729 D BluetoothLeScanner: could not find callback wrapper
08-26 18:20:52.169  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:52.169  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:52.169  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:52.170  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f897281 removed from the list
08-26 18:20:52.170  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:52.170  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-,26 18:20:52.170  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.170  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:52.170  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37073e68 removed from the list
08-26 18:20:52.170  8274  8274 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-26 18:20:52.170  8274  8274 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 18:20:52.170  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:52.171  8274  8274 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 18:20:52.171  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c45d914 added. We now have 2 listener(s)
08-26 18:20:52.171  1034  2053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:52.171  8274  8274 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 18:20:52.171  8274  8274 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-26 18:20:52.173  8274  8274 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 18:20:52.173  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 18:20:52.174  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:52.174  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:52.174  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:52.174  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b59b5bd added. We now have 9 listener(s)
08-26 18:20:52.174  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:52.174  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 18:20:52.177  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:52.178  8274  8274 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 18:20:52.183  6669  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:52.183  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:52.183  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 18:20:52.183  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:52.183  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:52.183  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:52.183  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:52.183  6669  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:52.185  6669  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:52.185  6669  6729 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 18:20:52.185  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:52.185  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e955303 added. We now have 3 listener(s)
08-26 18:20:52.185  1034  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 18:20:52.185  8274  8274 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:52.186  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:52.187  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 18:20:52.188  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:52.188  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:52.188  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:52.188  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 18:20:52.188  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c317280 added. We now have 10 listener(s)
08-26 18:20:52.188  6669  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:52.188  6669  6729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:52.188  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:52.188  6669  6729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:52.188  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:52.188  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:52.188  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:52.188  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:52.189  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c45d914 removed from the list
08-26 18:20:52.189  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:52.189  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b59b5bd removed from the list
08-26 18:20:52.189  6669  6729 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:52.189  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.189  8274  8274 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:52.189  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:52.189  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.190  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:52.190  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:52.190  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:52.190  6669  6729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b59b5bd not in the list
08-26 18:20:52.190  6669  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:52.190  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.190  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:52.190  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:52.190  6669  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:52.190  6669  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c317280 removed from the list
08-26 18:20:52.191  6669  6729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:52.191  6669  6729 W org.thalipro,ject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:52.191  6669  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:52.191  6669  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:52.191  6669  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e955303 removed from the list
08-26 18:20:52.191  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 18:20:52.192  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 18:20:52.192  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 18:20:52.192  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:52.192  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 18:20:52.192  6669  6729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:52.200  8274  8274 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 18:20:52.202  8274  8274 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 18:20:52.202  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 18:20:52.203  6669  8307 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 889, name: My test thread name)
08-26 18:20:52.203  6669  8307 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 889, thread name: My test thread name)
08-26 18:20:52.203  6669  8307 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 889, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 18:20:52.205  6932  6932 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 18:20:52.205  6669  8309 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 891, name: My test thread name)
08-26 18:20:52.206  6669  8309 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 891, thread name: My test thread name)
08-26 18:20:52.206  6669  8309 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 891, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 18:20:52.207  6669  6729 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 18:20:52.207  6669  6729 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 18:20:52.207  6669  6729 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 18:20:52.207  6669  6729 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 18:20:52.207  6669  6729 D com.test.thalitest.ThaliTestRunner: Total duration: 23413 ms
08-26 18:20:52.208  6669  6729 I jxcore-log: *Native tests were executed*
08-26 18:20:52.208  6669  6729 I jxcore-log: 
08-26 18:20:52.208  6669  6729 I jxcore-log: Total number of executed tests:  80
08-26 18:20:52.208  6669  6729 I jxcore-log: 
08-26 18:20:52.208  6669  6729 I jxcore-log: Number of passed tests:  80
08-26 18:20:52.208  6669  6729 I jxcore-log: 
08-26 18:20:52.209  6669  6729 I jxcore-log: Number of failed tests:  0
08-26 18:20:52.209  6669  6729 I jxcore-log: 
08-26 18:20:52.209  6669  6729 I jxcore-log: Number of ignored tests:  0
08-26 18:20:52.209  6669  6729 I jxcore-log: 
08-26 18:20:52.209  6669  6729 I jxcore-log: Total duration:  23413
08-26 18:20:52.209  6669  6729 I jxcore-log: 
08-26 18:20:52.209  6669  6729 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 18:20:52.209  6669  6729 I jxcore-log: 
08-26 18:20:52.210  8274  8274 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 18:20:52.212  8219  8263 D LgDataFeature: LgDataFeature() Constructor: none
08-26 18:20:52.212  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:52.212  8219  8263 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 18:20:52.212  8219  8264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 18:20:52.213  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:52.213  6669  6729 I jxcore-log: 
08-26 18:20:52.215  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:52.215  6669  6729 I jxcore-log: 
,08-26 18:20:52.218  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 18:20:52.219  6669  6669 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 18:20:52.220  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:52.220  6669  6729 I jxcore-log: 
08-26 18:20:52.221  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:52.221  6669  6729 I jxcore-log: 
08-26 18:20:52.221  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:52.221  6669  6729 I jxcore-log: 
08-26 18:20:52.223  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:52.223  6669  6729 I jxcore-log: 
08-26 18:20:52.223  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:52.225  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 18:20:52.225  6669  6729 I jxcore-log: 
08-26 18:20:52.226  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 18:20:52.226  6669  6729 I jxcore-log: 
08-26 18:20:52.226  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 18:20:52.226  6669  6729 I jxcore-log: 
08-26 18:20:52.227  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 18:20:52.227  6669  6729 I jxcore-log: 
08-26 18:20:52.228  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 18:20:52.228  6669  6729 I jxcore-log: 
08-26 18:20:52.228  8274  8274 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:52.228  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 18:20:52.228  6669  6729 I jxcore-log: 
08-26 18:20:52.229  8274  8274 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:52.229  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 18:20:52.229  6669  6729 I jxcore-log: 
08-26 18:20:52.230  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 18:20:52.230  6669  6729 I jxcore-log: 
08-26 18:20:52.230  8274  8274 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 18:20:52.230  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 18:20:52.230  6669  6729 I jxcore-log: 
08-26 18:20:52.230  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 18:20:52.230  6669  6729 I jxcore-log: 
,08-26 18:20:52.231  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 18:20:52.231  6669  6729 I jxcore-log: 
08-26 18:20:52.231  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 18:20:52.231  6669  6729 I jxcore-log: 
08-26 18:20:52.232  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:52.232  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 18:20:52.232  6669  6729 I jxcore-log: 
08-26 18:20:52.232  8219  8264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 18:20:52.234  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 18:20:52.234  6669  6729 I jxcore-log: 
08-26 18:20:52.235  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 18:20:52.235  6669  6729 I jxcore-log: 
08-26 18:20:52.235  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 18:20:52.235  6669  6729 I jxcore-log: 
08-26 18:20:52.236  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 18:20:52.236  6669  6729 I jxcore-log: 
08-26 18:20:52.236  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:52.236  6669  6729 I jxcore-log: 
08-26 18:20:52.237  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:52.237  6669  6729 I jxcore-log: 
08-26 18:20:52.237  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:52.237  6669  6729 I jxcore-log: 
08-26 18:20:52.238  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:52.238  6669  6729 I jxcore-log: 
08-26 18:20:52.238  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 18:20:52.238  6669  6729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:52.238  6669  6729 I jxcore-log: 
08-26 18:20:52.243  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:52.248  8274  8274 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:52.249  8274  8274 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:52.249  8274  8274 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 18:20:52.251  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-26 18:20:52.251  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 18:20:52.252  6932  6932 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 18:20:52.252  6932  6932 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 18:20:52.252  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 18:20:52.253  6932  6932 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 18:20:52.253  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 18:20:52.253  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 18:20:52.253  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 18:20:52.253  6932  6932 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 18:20:52.253  6932  6932 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-26 18:20:52.254  6932  6932 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 18:20:52.256  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:52.256  8219  8264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 18:20:52.262  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:52.267  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:52.273  8274  8274 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:52.274  8274  8274 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:52.274  8274  8274 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 18:20:52.276  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 18:20:52.276  8219  8264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 18:20:52.283  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:52.290  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:52.296  8219  8263 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-26 18:20:52.297  8274  8274 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:52.298  8274  8274 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:52.298  8274  8274 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 18:20:52.301  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:52.302  8219  8264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 18:20:52.309  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:52.312  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:52.319  8274  8274 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:52.320  8274  8274 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:52.320  8219  8263 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-26 18:20:52.320  8274  8274 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 18:20:52.323  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:52.323  8219  8264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 18:20:52.325  8219  8263 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-26 18:20:52.325  8219  8263 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-26 18:20:52.326  8219  8263 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 18:20:52.326  8219  8263 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-26 18:20:52.326  8219  8263 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-26 18:20:52.329  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 18:20:52.332  8219  8263 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-26 18:20:52.333  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:52.334  1034  1539 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 18:20:52.334  1034  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 18:20:52.335  1034  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 18:20:52.335  1034  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 18:20:52.335  1034  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 18:20:52.336  1034  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 18:20:52.336  8274  8274 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:52.336  8274  8274 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:52.336  8274  8274 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 18:20:52.338  1034  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-26 18:20:52.338  1034  1545 D ConnectivityService: identical MTU - not setting
08-26 18:20:52.338  1034  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 18:20:52.338  1034  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 18:20:52.338  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:52.338  1034  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:52.339  1034  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 18:20:52.339  1603  2082 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 18:20:52.340  8219  8263 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-26 18:20:52.342  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:52.342  8219  8264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 18:20:52.353  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:52.356  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:52.360  8274  8274 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:52.360  8274  8274 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:52.365  8274  8274 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 18:20:52.368  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:52.369  8219  8264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 18:20:52.376  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:52.380  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:52.385  8274  8274 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:52.385  8274  8274 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:52.386  8274  8274 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 18:20:52.389  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:52.389  8219  8264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 18:20:52.392  8173  8173 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 18:20:52.395  8173  8173 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 18:20:52.397  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 18:20:52.401  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:52.408  8274  8274 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:52.409  8274  8274 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 18:20:52.410  8274  8274 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 18:20:52.411  8274  8274 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 18:20:52.411  8274  8274 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 18:20:52.414  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 18:20:52.416  8219  8264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 18:20:52.416  8173  8173 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 18:20:52.417  8173  8173 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 18:20:52.419  6932  6932 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 18:20:52.422  6932  6932 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 18:20:52.426  8274  8274 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 18:20:52.426  8274  8274 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 18:20:52.427  8274  8274 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 18:20:52.428  8274  8274 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 18:20:52.428  8274  8274 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-26 18:20:52.430  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 18:20:52.460  8274  8274 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 18:20:52.461  8274  8274 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 18:20:52.461  8274  8274 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-26 18:20:52.484  8311  8311 D AndroidRuntime: 
08-26 18:20:52.484  8311  8311 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 18:20:52.486  8311  8311 D AndroidRuntime: CheckJNI is OFF
,08-26 18:20:52.498  8274  8274 D LgDataFeature: LgDataFeature() Constructor: none
08-26 18:20:52.498  8274  8274 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 18:20:52.504  8274  8274 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-26 18:20:52.505  8274  8274 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
,08-26 18:20:52.505  8274  8274 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164,
08-26 18:20:52.505  8274  8274 V SoundPool: doLoad: loading sample sampleID=1
,08-26 18:20:52.506  8274  8274 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-26 18:20:52.509  7797  7797 D UEI.SmartControl: QS Service created
08-26 18:20:52.509  8274  8320 V SoundPool: Start decode
08-26 18:20:52.509  8274  8320 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 18:20:52.511   312  1383 V MediaPlayerService: decode(22, 10857164, 17813)
08-26 18:20:52.511   312  1383 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 18:20:52.511   312  1383 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 18:20:52.511   312  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 18:20:52.512   312  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 18:20:52.512   312  1383 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 18:20:52.512   312  1383 V MediaPlayerService: player type = 3
08-26 18:20:52.512   312  1383 V AwesomePlayer: AwesomePlayer create()
08-26 18:20:52.513   312  1383 V AwesomePlayer: reset_l() 
08-26 18:20:52.513   312  1383 V AwesomePlayer: cancelPlayerEvents
08-26 18:20:52.513   312  1383 V AwesomePlayer: setAudioSink() 
08-26 18:20:52.513   312  1383 V AwesomePlayer: reset_l() 
08-26 18:20:52.513   312  1383 V AudioCache: notify(0xb0409600, 8, 0, 0)
08-26 18:20:52.513   312  1383 V AudioCache: ignored
08-26 18:20:52.513   312  1383 V AwesomePlayer: cancelPlayerEvents
08-26 18:20:52.514   312  1383 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 18:20:52.514   312  1383 V AwesomePlayer: setDataSource_l dataSource
08-26 18:20:52.514   312  1383 V LGParserOSAL: SniffLGParser start
08-26 18:20:52.514   312  1383 V LGParserOSAL: MainType:5, SubType=0
08-26 18:20:52.514   312  1383 V LGParserOSAL: #### check Mime : application/ogg
08-26 18:20:52.514   312  1383 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 18:20:52.514   312  1383 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 18:20:52.515  8274  8274 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-26 18:20:52.522  8274  8274 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 18:20:52.522  7797  7797 I UEI.SmartControl: Service initServices...
08-26 18:20:52.523  8274  8274 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 18:20:52.523  7797  7797 D UEI.SmartControl: QS start get config
,08-26 18:20:52.532  8274  8274 V LGMDMManager: Create singleton instance
08-26 18:20:52.566   312  1383 V LGParserOSAL: supported mime: application/ogg
08-26 18:20:52.566   312  1383 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 18:20:52.566   312  1383 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 18:20:52.566   312  1383 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 18:20:52.566   312  1383 V AwesomePlayer: AudioTrack Setting
08-26 18:20:52.566   312  1383 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 18:20:52.566   312  1383 V AwesomePlayer: setAudioSource() 
08-26 18:20:52.566   312  1383 V MediaPlayerService: prepare
08-26 18:20:52.566   312  1383 V AwesomePlayer: prepareAsync_l() 
08-26 18:20:52.566   312  1383 V MediaPlayerService: wait for prepare
08-26 18:20:52.566   312  8331 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 18:20:52.566   312  8331 V AwesomePlayer: initAudioDecoder() 
08-26 18:20:52.566   312  8331 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 18:20:52.566   312  8331 V AudioSystem: isOffloadSupported()
08-26 18:20:52.566   312  8331 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 18:20:52.566   312  8331 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 18:20:52.566   312  8331 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 18:20:52.566   312  8331 V AwesomePlayer: getUseOffload() = 0 
08-26 18:20:52.566   312  8331 V OMXCodec: OMXCodec::Create
08-26 18:20:52.566   312  8331 V OMXCodec: findMatchingCodecs()
08-26 18:20:52.567   312  8331 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 18:20:52.567   312  8331 V OMXCodec: matchingCodecs.size()=1
08-26 18:20:52.567   312  8331 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-26 18:20:52.568   312  8331 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 18:20:52.568   312  8331 V LGCodecAdapter: LG Codec Adapter start
08-26 18:20:52.568   312  8331 V OMXCodec: OMXCodec Createtor
08-26 18:20:52.568   312  8331 V OMXCodec: setComponentRole
08-26 18:20:52.568   312  8331 V OMXCodec: configureCodec protected=0
08-26 18:20:52.568   312  8331 V LGCodecAdapter: called getLGCodecSpecificData
08-26 18:20:52.568   312  8331 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 18:20:52.568   312  8331 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 18:20:52.569   312  8331 V LGCodecOSAL: Called LGconfigureCodecMSG
,08-26 18:20:52.569   312  8331 V LGCodecOSAL: Not support LGCodec
08-26 18:20:52.569   312  8331 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 18:20:52.569   312  8331 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 18:20:52.569   312  8331 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 18:20:52.569   312  8331 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 18:20:52.569   312  8331 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 18:20:52.569   312  8331 V AudioSystem: isOffloadSupported()
08-26 18:20:52.569   312  8331 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 18:20:52.569   312  8331 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 18:20:52.569   312  8331 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 18:20:52.569   312  8331 V OMXCodec: init()
08-26 18:20:52.569   312  8331 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 18:20:52.569   312  8331 V OMXCodec: allocateBuffers
08-26 18:20:52.569   312  8331 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 18:20:52.569   312  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 18:20:52.569   312  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
08-26 18:20:52.569   312  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-26 18:20:52.569   312  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-26 18:20:52.569   312  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-26 18:20:52.569   312  8331 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 18:20:52.569   312  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 18:20:52.570   312  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-26 18:20:52.570   312  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-26 18:20:52.570   312  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-26 18:20:52.570   312  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57d01f0 on output port
08-26 18:20:52.570   312  8331 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 18:20:52.572   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 18:20:52.572   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 18:20:52.572   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 18:20:52.572   312  8331 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 18:20:52.572   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 18:20:52.572   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 18:20:52.572   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-26 18:20:52.572   312  8331 V OMXCodec: init() mAsyncCompletion wait free! 
08-26 18:20:52.572   312  8331 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 18:20:52.572   312  8331 V AudioCache: notify(0xb0409600, 5, 0, 0)
08-26 18:20:52.572   312  8331 V AudioCache: ignored
08-26 18:20:52.572   312  8331 V AudioCache: notify(0xb0409600, 1, 0, 0)
08-26 18:20:52.572   312  8331 V AudioCache: prepared
08-26 18:20:52.572   312  1383 V AudioCache: wait - success
08-26 18:20:52.572   312  1383 V MediaPlayerService: start
08-26 18:20:52.572   312  1383 V AwesomePlayer: play_l() 
08-26 18:20:,52.572   312  1383 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 18:20:52.572   312  1383 V AwesomePlayer: createAudioPlayer_l
08-26 18:20:52.572   312  1383 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 18:20:52.572   312  1383 V AwesomePlayer: startAudioPlayer_l() 
08-26 18:20:52.572   312  1383 D AudioPlayer: start of Playback, useOffload 0
08-26 18:20:52.572   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 18:20:52.572   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
,08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044868592
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-26 18:20:52.575   312  8333 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,08-26 18:20:52.575   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-26 18:20:52.576   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-26 18:20:52.576   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-26 18:20:52.576   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57d0790 on output port
08-26 18:20:52.576   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 18:20:52.576   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 18:20:52.577   312  1383 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 18:20:52.577   312  1383 V AudioCache: notify(0xb0409600, 6, 0, 0)
,08-26 18:20:52.577   312  1383 V AudioCache: ignored
08-26 18:20:52.577   312  1383 V MediaPlayerService: wait for playback complete
08-26 18:20:52.582   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.582   312  8334 V AudioCache: memcpy(0xaf0f9000, 0xb177f000, 4096)
08-26 18:20:52.583   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.583   312  8334 V AudioCache: memcpy(0xaf0fa000, 0xb177f000, 4096)
08-26 18:20:52.583   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.583   312  8334 V AudioCache: memcpy(0xaf0fb000, 0xb177f000, 4096)
08-26 18:20:52.584   312  8334 V AudioCache: write(0xb177f000, 4096),
08-26 18:20:52.584   312  8334 V AudioCache: memcpy(0xaf0fc000, 0xb177f000, 4096)
08-26 18:20:52.585   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.585   312  8334 V AudioCache: memcpy(0xaf0fd000, 0xb177f000, 4096)
08-26 18:20:52.585   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.585   312  8334 V AudioCache: memcpy(0xaf0fe000, 0xb177f000, 4096)
08-26 18:20:52.586   312  8334 V AudioCache: write(0xb177f000, 4096)
,08-26 18:20:52.586   312  8334 V AudioCache: memcpy(0xaf0ff000, 0xb177f000, 4096)
08-26 18:20:52.586   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.586   312  8334 V AudioCache: memcpy(0xaf100000, 0xb177f000, 4096)
08-26 18:20:52.587   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.587   312  8334 V AudioCache: memcpy(0xaf101000, 0xb177f000, 4096)
08-26 18:20:52.588   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.588   312  8334 V AudioCache: memcpy(0xaf102000, 0xb177f000, 4096)
08-26 18:20:52.588   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.588   312  8334 V AudioCache: memcpy(0xaf103000, 0xb177f000, 4096)
08-26 18:20:52.589   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.589   312  8334 V AudioCache: memcpy(0xaf104000, 0xb177f000, 4096)
,08-26 18:20:52.590   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.590   312  8334 V AudioCache: memcpy(0xaf105000, 0xb177f000, 4096)
08-26 18:20:52.590   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.590   312  8334 V AudioCache: memcpy(0xaf106000, 0xb177f000, 4096)
,08-26 18:20:52.591   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.591   312  8334 V AudioCache: memcpy(0xaf107000, 0xb177f000, 4096)
,08-26 18:20:52.591   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.591   312  8334 V AudioCache: memcpy(0xaf108000, 0xb177f000, 4096)
08-26 18:20:52.592   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.592   312  8334 V AudioCache: memcpy(0xaf109000, 0xb177f000, 4096)
08-26 18:20:52.593   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.593   312  8334 V AudioCache: memcpy(0xaf10a000, 0xb177f000, 4096)
08-26 18:20:52.593   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.593   312  8334 V AudioCache: memcpy(0xaf10b000, 0xb177f000, 4096)
08-26 18:20:52.594   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.594   312  8334 V AudioCache: memcpy(0xaf10c000, 0xb177f000, 4096)
08-26 18:20:52.595   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.595   312  8334 V AudioCache: memcpy(0xaf10d000, 0xb177f000, 4096)
08-26 18:20:52.595   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.595   312  8334 V AudioCache: memcpy(0xaf10e000, 0xb177f000, 4096)
08-26 18:20:52.596   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.596   312  8334 V AudioCache: memcpy(0xaf10f000, 0xb177f000, 4096)
08-26 18:20:52.597   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.597   312  8334 V AudioCache: memcpy(0xaf110000, 0xb177f000, 4096)
08-26 18:20:52.597   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.597   312  8334 V AudioCache: memcpy(0xaf111000, 0xb177f000, 4096)
08-26 18:20:52.598   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.598   312  8334 V AudioCache: memcpy(0xaf112000, 0xb177f000, 4096)
08-26 18:20:52.599   312  8334 V AudioCache: write(0xb177f000, 4096)
,08-26 18:20:52.599   312  8334 V AudioCache: memcpy(0xaf113000, 0xb177f000, 4096)
08-26 18:20:52.599   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.599   312  8334 V AudioCache: memcpy(0xaf114000, 0xb177f000, 4096)
08-26 18:20:52.600   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.600   312  8334 V AudioCache: memcpy(0xaf115000, 0xb177f000, 4096)
08-26 18:20:52.601   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.601   312  8334 V AudioCache: memcpy(0xaf116000, 0xb177f000, 4096)
08-26 18:20:52.601   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.601   312  8334 V AudioCache: memcpy(0xaf117000, 0xb177f000, 4096)
08-26 18:20:52.602   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.602   312  8334 V AudioCache: memcpy(0xaf118000, 0xb177f000, 4096)
08-26 18:20:52.603   312  8334 V AudioCache: write(0xb177f000, 4096)
,08-26 18:20:52.603   312  8334 V AudioCache: memcpy(0xaf119000, 0xb177f000, 4096)
08-26 18:20:52.603   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.603   312  8334 V AudioCache: memcpy(0xaf11a000, 0xb177f000, 4096)
08-26 18:20:52.604   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.604   312  8334 V AudioCache: memcpy(0xaf11b000, 0xb177f000, 4096)
08-26 18:20:52.604   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.605   312  8334 V AudioCache: memcpy(0xaf11c000, 0xb177f000, 4096)
08-26 18:20:52.605   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.605   312  8334 V AudioCache: memcpy(0xaf11d000, 0xb177f000, 4096)
08-26 18:20:52.606   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.606   312  8334 V AudioCache: memcpy(0xaf11e000, 0xb177f000, 4096)
08-26 18:20:52.606   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.607   312  8334 V AudioCache: memcpy(0xaf11f000, 0xb177f000, 4096)
08-26 18:20:52.607   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.607   312  8334 V AudioCache: memcpy(0xaf120000, 0xb177f000, 4096)
08-26 18:20:52.608   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.608   312  8334 V AudioCache: memcpy(0xaf121000, 0xb177f000, 4096)
08-26 18:20:52.608   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.608   312  8334 V AudioCache: memcpy(0xaf122000, 0xb177f000, 4096)
08-26 18:20:52.609   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.609   312  8334 V AudioCache: memcpy(0xaf123000, 0xb177f000, 4096)
08-26 18:20:52.610   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.610   312  8334 V AudioCache: memcpy(0xaf124000, 0xb177f000, 4096)
08-26 18:20:52.610  8311  8311 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-26 18:20:52.610   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.610   312  8334 V AudioCache: memcpy(0xaf125000, 0xb177f000, 4096)
08-26 18:20:52.611   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.611   312  8334 V AudioCache: memcpy(0xaf126000, 0xb177f000, 4096)
08-26 18:20:52.612   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.612   312  8334 V AudioCache: memcpy(0xaf127000, 0xb177f000, 4096)
08-26 18:20:52.612   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.612   312  8334 V AudioCache: memcpy(0xaf128000, 0xb177f000, 4096)
08-26 18:20:52.613   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.613   312  8334 V AudioCache: memcpy(0xaf129000, 0xb177f000, 4096)
08-26 18:20:52.613   312  8334 V AudioCache: write(0xb177f000, 4096)
08-26 18:20:52.613   312  8334 V AudioCache: memcpy(0xaf12a000, 0xb177f000, 4096)
08-26 18:20:52.614   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
,08-26 18:20:52.614   312  8334 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
,08-26 18:20:52.614   312  8334 V AwesomePlayer: postAudioEOS() 
08-26 18:20:52.614   312  8334 V AudioCache: write(0xb177f000, 280)
08-26 18:20:52.614   312  8334 V AudioCache: memcpy(0xaf12b000, 0xb177f000, 280)
08-26 18:20:52.615   312  8331 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 18:20:52.615   312  8331 V AwesomePlayer: onStreamDone
08-26 18:20:52.615   312  8331 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 18:20:52.615   312  8331 V AudioCache: notify(0xb0409600, 2, 0, 0)
08-26 18:20:52.615   312  8331 V AudioCache: playback complete
08-26 18:20:52.615   312  8331 V AwesomePlayer: pause_l() 
08-26 18:20:52.615   312  8331 V AudioCache: notify(0xb0409600, 7, 0, 0)
08-26 18:20:52.615   312  8331 V AudioCache: ignored
08-26 18:20:52.615   312  8331 V AwesomePlayer: cancelPlayerEvents
08-26 18:20:52.615   312  1383 V AudioCache: wait - success
08-26 18:20:52.615   312  1383 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 18:20:52.615   312  8331 D AudioPlayer: Pause Playback at 1068125
08-26 18:20:52.617   312  1383 V AwesomePlayer: reset_l() 
08-26 18:20:52.617   312  1383 V AudioCache: notify(0xb0409600, 8, 0, 0)
08-26 18:20:52.617   312  1383 V AudioCache: ignored
08-26 18:20:52.617   312  1383 V AwesomePlayer: cancelPlayerEvents
08-26 18:20:52.617   312  1383 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-26 18:20:52.617   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 18:20:52.617   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 18:20:52.617   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 18:20:52.617   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 18:20:52.617   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 18:20:52.617   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 18:20:52.617   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 18:20:52.617   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-26 18:20:52.617   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57d0790 on port 1
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-26 18:20:52.618   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCo,mpletion wait free!!
08-26 18:20:52.618   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 18:20:52.618   312  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 18:20:52.618   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 18:20:52.618   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 18:20:52.618   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 18:20:52.619   312  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-26 18:20:52.619   312  1383 D AudioPlayer: AudioPlayer releasing audio source
08-26 18:20:52.619   312  1383 D AudioPlayer: AudioPlayer done releasing audio source
08-26 18:20:52.619   312  1383 V AwesomePlayer: reset_l() 
08-26 18:20:52.619   312  1383 V AwesomePlayer: cancelPlayerEvents
08-26 18:20:52.619   312  1383 V AwesomePlayer: ~AwesomePlayer call
08-26 18:20:52.619   312  1383 V AwesomePlayer: reset_l() 
08-26 18:20:52.619   312  1383 V AwesomePlayer: cancelPlayerEvents
08-26 18:20:52.619  8274  8320 V SoundPool: close(31)
08-26 18:20:52.619  8274  8320 V SoundPool: pointer = 0x9fe89000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 18:20:52.620  1034  1091 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-26 18:20:52.620  1034  1091 I ActivityManager: Killing 6669:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-26 18:20:52.631  8274  8274 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-26 18:20:52.651  1034  2035 I WindowState: WIN DEATH: Window{2fd1741f u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 18:20:52.651  1034  1544 D WifiService: Client connection lost with reason: 4
,08-26 18:20:52.657  1034  2035 D InputDispatcher: Window went away: Window{2fd1741f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 18:20:52.675  8274  8274 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-26 18:20:52.795  7797  7797 I UEI.SmartControl: Supports setup maps: true
,08-26 18:20:52.797  7797  7797 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 18:20:52.797  7797  7797 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 18:20:52.797  7797  7797 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 18:20:52.797  7797  7797 I UEI.SmartControl: ### init IR Blaster...
08-26 18:20:52.801  7797  7797 D serial_port: Configuring serial port
08-26 18:20:52.801  7797  7797 E UEI.SmartControl: UEIBLaster setting for 616
08-26 18:20:52.801  7797  7797 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 18:20:52.801  7797  7797 I UEI.SmartControl: configuring settings for MAXQ616
08-26 18:20:52.801  7797  7797 I UEI.SmartControl: Get version...
08-26 18:20:52.818  7797  8337 D UEI.SmartControl: serial port data available: 21
,08-26 18:20:52.845  7797  7797 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 18:20:52.845  7797  7797 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 18:20:52.845  7797  7797 I UEI.SmartControl: QS saving settings...
08-26 18:20:52.847  7797  7797 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 18:20:52.863  7797  8337 D UEI.SmartControl: serial port data available: 4
,08-26 18:20:52.893  7797  8340 I UEI.SmartControl: Device manager: loading config....
,08-26 18:20:52.894  7797  7797 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 18:20:52.894  7797  8340 D UEI.SmartControl: ----------- loading internal config...
08-26 18:20:52.902  7797  8340 E UEI.SmartControl: Loading SETTINGS...
08-26 18:20:52.903  1034  1091 I ActivityManager:   Force finishing activity ActivityRecord{12701ff8 u0 com.test.thalitest/.MainActivity t6}
08-26 18:20:52.908  7797  8340 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 18:20:52.932  7797  8339 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 18:20:52.932  7797  8339 D UEI.SmartControl: -----service ready thread exits
08-26 18:20:52.947   335   366 E GBMv2   : DFP En is all cleared set to be enabled
,08-26 18:20:52.951  1034  1907 W ActivityManager: Spurious death for ProcessRecord{120eadf2 6669:com.test.thalitest/u0a118}, curProc for 6669: null
08-26 18:20:52.953  1034  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-26 18:20:52.955  1034  1123 I ActivityManager:   Force finishing activity ActivityRecord{12701ff8 u0 com.test.thalitest/.MainActivity t6 f}
08-26 18:20:52.955  1034  1123 W ActivityManager: Duplicate finish request for ActivityRecord{12701ff8 u0 com.test.thalitest/.MainActivity t6 f}
,08-26 18:20:52.981  8274  8274 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8511
08-26 18:20:52.989  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-26 18:20:53.000  1034  1424 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 18:20:53.009  2479  2682 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 18:20:53.009  1998  1998 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-26 18:20:53.009  2735  2735 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-26 18:20:53.011  7771  7771 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-26 18:20:53.011  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 18:20:53.061  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 18:20:53.073  5016  5016 I art     : Explicit concurrent mark sweep GC freed 8251(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 491us total 106.936ms
,08-26 18:20:53.077  1944  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-26 18:20:53.078  1944  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{b83a0c5 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 18:20:53.079  2036  2036 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-26 18:20:53.081  2036  2036 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-26 18:20:53.086  4915  4915 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-26 18:20:53.086  4915  4915 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-26 18:20:53.086  4915  4915 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-26 18:20:53.086  4915  4915 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-26 18:20:53.086  4915  4915 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 18:20:53.086  4915  4915 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 18:20:53.086  4915  4915 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 18:20:53.086  4915  4915 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 18:20:53.087  4915  4915 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:53.087  4915  4915 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:53.087  4915  4915 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 18:20:53.087  4915  4915 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 18:20:53.091  1944  2940 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-26 18:20:53.091  1944  2940 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1f65aa1a co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 18:20:53.109  7797  7797 E UEI.SmartControl: Services init done
08-26 18:20:53.109  7797  7797 D UEI.SmartControl: QS Service init finished
,08-26 18:20:53.116  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-26 18:20:53.118  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-26 18:20:53.119  2036  2081 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-26 18:20:53.123  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-26 18:20:53.125  2036  2036 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-26 18:20:53.126  2036  2036 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-26 18:20:53.128  2036  2036 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-26 18:20:53.129  1909  1909 D ActionManagerService: notifyUserLog: 1000003
08-26 18:20:53.129  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:53.129  2735  4914 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-26 18:20:53.130  7797  7797 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 18:20:53.130  7797  7797 D UEI.SmartControl: QS Service version code: 201091
08-26 18:20:53.132  1034  2053 V SIM_STK : Menu title from STK is T-Mobile
08-26 18:20:53.144  7797  7797 D UEI.SmartControl: Service requested: Control
,08-26 18:20:53.151  1909  1909 D ActionManagerService: notifyUserLog: 1000004
08-26 18:20:53.151  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-26 18:20:53.152  2735  4914 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-26 18:20:53.153  2735  2758 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 18:20:53.153  7797  7797 D UEI.SmartControl: Internal service binding...
08-26 18:20:53.154  8274  8274 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 18:20:53.154  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-26 18:20:53.154  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-26 18:20:53.155  7797  7813 I UEI.SmartControl: ------ IControl API: 11
08-26 18:20:53.155  7797  7813 D UEI.SmartControl: File observer start...
08-26 18:20:53.155  1603  1670 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 18:20:53.155  7797  7813 E UEI.SmartControl: IR Port is disabled: false
08-26 18:20:53.155  1603  1670 D KeyguardModel: createShortcutInfo...
08-26 18:20:53.155  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:53.155  7797  7813 D UEI.SmartControl: Starting file observer...
08-26 18:20:53.156  7797  7813 I UEI.SmartControl: Registering callback...
08-26 18:20:53.159  7797  7812 I UEI.SmartControl: ------ IControl API: 19
,08-26 18:20:53.159  7797  7812 I UEI.SmartControl: Registering Services Ready callback...
08-26 18:20:53.159  7797  7812 I UEI.SmartControl: Notify client services are ready...
08-26 18:20:53.160  8274  8291 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 18:20:53.160  8274  8318 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 18:20:53.161  8274  8318 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 18:20:53.161  8274  8274 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 18:20:53.161  8274  8274 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-26 18:20:53.161  7797  7813 I UEI.SmartControl: ------ IControl API: 8
08-26 18:20:53.163  8274  8274 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 18:20:53.163  8274  8274 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 18:20:53.163  8274  8274 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 18:20:53.164  8274  8274 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , create_time: 1430832262123
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , display: false
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , animation: false }
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , create_time: 1430832262287
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , display: false
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , animation: false }
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , create_time: 1472216588858
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , display: false
08-26 18:20:53.164  2036  2036 I GBoardWebViewUtils: , animation: false }
08-26 18:20:53.164  1603  1670 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 18:20:53.165  1603  1670 D KeyguardModel: createShortcutInfo...
08-26 18:20:53.164  8274  8274 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 18:20:53.165  8274  8274 D QRemote : [,QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-26 18:20:53.175  2036  8351 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-26 18:20:53.175  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:53.183  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:53.183  8274  8274 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-26 18:20:53.184  1034  1034 I art     : Explicit concurrent mark sweep GC freed 79823(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.408ms total 206.278ms
08-26 18:20:53.184  1034  1123 I art     : WaitForGcToComplete blocked for 199.052ms for cause Explicit
08-26 18:20:53.187  1603  1670 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 18:20:53.187  1603  1670 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 18:20:53.187  1603  1670 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 18:20:53.188  1603  1670 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 18:20:53.189  1603  1670 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 18:20:53.189  1603  1670 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 18:20:53.202  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:53.204  1603  1670 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 18:20:53.204  1603  1670 D KeyguardModel: createShortcutInfo...
,08-26 18:20:53.208  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:53.210  1603  1670 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 18:20:53.210  1603  1670 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 18:20:53.212  8274  8274 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-26 18:20:53.212  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:53.213  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 18:20:53.213  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-26 18:20:53.217  1603  1670 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 18:20:53.217  1603  1670 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-26 18:20:53.218  1872  1872 D SplitUIManager: split_name #11 / not available #0
08-26 18:20:53.219  1872  1872 D SplitUIService: removed split : 
08-26 18:20:53.219  1603  1670 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 18:20:53.219  1603  1670 D KeyguardModel: createShortcutInfo...
08-26 18:20:53.228  1034  1956 V SIM_STK : Menu title from STK is T-Mobile
,08-26 18:20:53.228  1034  1956 V SIM_STK : Menu title from STK is T-Mobile
08-26 18:20:53.235  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:53.238  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 18:20:53.243  8219  8219 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-26 18:20:53.247  1819  1819 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-26 18:20:53.249  1603  1670 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 18:20:53.249  1603  1670 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 18:20:53.249  1603  1670 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 18:20:53.249  1603  1670 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 18:20:53.250  1603  1670 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 18:20:53.250  1603  1670 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 18:20:53.251  1603  1670 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 18:20:53.251  1603  1670 D KeyguardModel: createShortcutInfo...
08-26 18:20:53.254  1034  1034 D administrator: Handling package changes for user 0
08-26 18:20:53.257  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
,08-26 18:20:53.290  1872  1872 D SplitUIManager: split_name #11 / not available #0
08-26 18:20:53.290  1872  1872 I SplitUIService: split app #11
,08-26 18:20:53.291  2140  2140 I ConfigService: onCreate
08-26 18:20:53.291  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-26 18:20:53.295  1034  1893 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 18:20:53.296  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-26 18:20:53.296  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 18:20:53.297  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 18:20:53.297  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 18:20:53.297  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 18:20:53.297  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 18:20:53.297  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 18:20:53.297  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 18:20:53.297  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 18:20:53.297  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 18:20:53.297  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 18:20:53.297  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 18:20:53.297  7771  7771 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 18:20:53.298  2036  2036 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-26 18:20:53.298  1819  1819 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-26 18:20:53.304  2140  2140 I ConfigService: onBind returning update interface
08-26 18:20:53.304  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-26 18:20:53.305  2140  2140 I ConfigService: onBind returning config service
,08-26 18:20:53.309  1603  1670 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 18:20:53.309  1603  1670 D KeyguardModel: createShortcutInfo...
08-26 18:20:53.310  1603  1670 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 18:20:53.310  1603  1670 D KeyguardModel: createShortcutInfo...
08-26 18:20:53.312  1603  1670 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 18:20:53.312  1603  1670 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 18:20:53.313  1603  1670 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 18:20:53.313  1603  1670 D KeyguardModel: createShortcutInfo...
08-26 18:20:53.316  1603  1670 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 18:20:53.316  1603  1670 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 18:20:53.319  2140  2140 I ConfigService: onDestroy
08-26 18:20:53.319  1603  1670 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 18:20:53.319  1603  1670 D KeyguardModel: createShortcutInfo...
,08-26 18:20:53.320  1603  1670 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 18:20:53.320  1603  1670 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 18:20:53.322  1603  1670 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 18:20:53.322  1603  1670 D KeyguardModel: createShortcutInfo...
08-26 18:20:53.324  1819  8355 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-26 18:20:53.335  1603  1603 D KeyguardModel: handleShortcutListChanged...
,08-26 18:20:53.335  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 18:20:53.357  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-26 18:20:53.357  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 18:20:53.357  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 18:20:53.359  1034  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-26 18:20:53.360  6173  8360 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-26 18:20:53.367  7114  7114 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-26 18:20:53.367  1819  8362 I PeopleContactsSync: CP2 sync disabled
08-26 18:20:53.369  1819  5205 I Icing   : doRemovePackageData com.test.thalitest
,08-26 18:20:53.376  1034  1907 I ActivityManager: Killing 7351:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-26 18:20:53.388   325   431 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-26 18:20:53.389  3294  8364 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-26 18:20:53.411  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-26 18:20:53.413  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 18:20:53.415  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-26 18:20:53.416  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-26 18:20:53.417  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-26 18:20:53.418  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-26 18:20:53.433  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-26 18:20:53.433  2036  2139 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-26 18:20:53.433  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 18:20:53.433  2036  2139 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-26 18:20:53.448  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-26 18:20:53.448  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 18:20:53.449  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 18:20:53.455  2036  2036 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-26 18:20:53.468  1034  1893 W libprocessgroup: failed to open /acct/uid_10005/pid_7351/cgroup.procs: No such file or directory
08-26 18:20:53.469  2577  2577 D [Concierge]Service: onStartCommand(). Type : 8
08-26 18:20:53.469  2577  2577 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-26 18:20:53.470  2577  2577 D [Concierge]Service: Update widget ID : 11
08-26 18:20:53.471  2036  2036 D [Concierge]WidgetView: change position of spinner
08-26 18:20:53.472  2577  2577 D [Concierge]Service: onStartCommand(). Type : 0
08-26 18:20:53.472  1034  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e41b641 u0 com.lge.launcher2/.Launcher t5} time:144389
08-26 18:20:53.473  2036  2036 I [Concierge]WidgetView: initWebView(). Time : 1472228453473
08-26 18:20:53.480  1034  1123 I art     : Explicit concurrent mark sweep GC freed 9155(517KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.483ms total 295.229ms
08-26 18:20:53.482  2380  8368 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 18:20:53.508  1034  1051 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8369 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-26 18:20:53.512  2140  2340 I art     : Explicit concurrent mark sweep GC freed 8201(484KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 638us total 28.542ms
08-26 18:20:53.520  1819  8361 W GmsApplication: Using Auth Proxy for data requests.
,08-26 18:20:53.523  1819  8361 W GmsApplication: Using Auth Proxy for data requests.
08-26 18:20:53.529  2036  2036 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 205540740
08-26 18:20:53.529  2036  2036 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-26 18:20:53.530  2036  2036 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 18:20:53.532  2036  2036 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@5a768d4
,08-26 18:20:53.532  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-26 18:20:53.533  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 18:20:53.533  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 18:20:53.539  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-26 18:20:53.539  2036  2036 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-26 18:20:53.540  2036  2036 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 18:20:53.540  2036  2036 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472228337689, New one : 1472228453473
08-26 18:20:53.540  2036  2036 D [Concierge]WidgetView: Unregister all receivers
08-26 18:20:53.540  2036  2036 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 18:20:53.541  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 18:20:53.542  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-26 18:20:53.543  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-26 18:20:53.544  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-26 18:20:53.545  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-26 18:20:53.546  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-26 18:20:53.553  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 18:20:53.553  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 18:20:53.577  8311  8311 D AndroidRuntime: Shutting down VM
,08-26 18:20:53.600  8369  8369 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 18:20:53.601  8369  8369 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 18:20:53.601  8369  8369 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 18:20:53.602  8369  8369 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 18:20:53.608  2036  2036 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-26 18:20:53.610  1034  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8387 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-26 18:20:53.616  2036  2036 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-26 18:20:53.616  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-26 18:20:53.618  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 18:20:53.638  2036  2036 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@144d7629 time:144556
,08-26 18:20:53.678  1034  1907 I ActivityManager: Killing 7823:com.google.android.talk/u0a72 (adj 15): empty #17
,08-26 18:20:53.743  2036  2036 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-26 18:20:53.773  1034  2032 W libprocessgroup: failed to open /acct/uid_10072/pid_7823/cgroup.procs: No such file or directory
,08-26 18:20:53.775  8369  8369 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-26 18:20:53.782  2036  2865 I GBoardtInterface: onReloaded()
08-26 18:20:53.783  2036  2036 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-26 18:20:53.784  2735  2785 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-26 18:20:53.787  2735  2784 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 18:20:53.790  8369  8369 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-26 18:20:53.792  1909  1909 D ActionManagerService: notifyUserLog: 1000001
08-26 18:20:53.793  2735  4914 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-26 18:20:53.793  2735  4914 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-26 18:20:53.796  1909  1909 D ActionManagerService: notifyUserLog: 1000001
,08-26 18:20:53.797  2735  4914 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-26 18:20:53.797  2735  4914 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-26 18:20:53.797  2735  4914 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-26 18:20:53.797  2735  4914 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-26 18:20:53.798  2735  2784 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 18:20:53.800  2036  2036 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-26 18:20:53.800  2036  2036 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-26 18:20:53.802  2036  2036 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-26 18:20:53.802  2036  2036 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 18:20:53.804  2036  2036 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-26 18:20:53.804  2036  2036 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 18:20:53.825  8369  8369 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 18:20:53.844  8369  8369 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 18:20:53.845  8369  8369 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 18:20:53.859  1034  1090 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-26 18:20:53.896  8369  8369 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)

```
