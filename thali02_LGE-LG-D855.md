#### Test 832760823d6df89_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-31 11:15:39.612  1081  2309 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6520 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-31 11:15:39.682  6520  6520 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:15:39.683  6520  6520 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:15:39.684  6520  6520 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 11:15:39.685  6520  6520 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
--------- beginning of main
08-31 11:15:39.780  6520  6520 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-31 11:15:39.796  6520  6520 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-31 11:15:39.841  6520  6520 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:15:39.880  6520  6520 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:15:39.880  6520  6520 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:15:40.003  6520  6520 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
08-31 11:15:40.064  1081  1747 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6548 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-31 11:15:40.065  1081  1747 I ActivityManager: Killing 6005:com.android.vending/u0a44 (adj 15): empty #17
08-31 11:15:40.124  1081  1558 W libprocessgroup: failed to open /acct/uid_10044/pid_6005/cgroup.procs: No such file or directory
08-31 11:15:40.150  6548  6548 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:15:40.150  6548  6548 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 11:15:40.151  6548  6548 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-31 11:15:40.151  6548  6548 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 11:15:40.253  6548  6548 I AppConfig: Total System Memory = 2995761152
08-31 11:15:40.264  6548  6548 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-31 11:15:40.301  1081  1926 I ActivityManager: Killing 5420:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-31 11:15:40.331  2014  2014 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-31 11:15:40.331  1081  2060 W libprocessgroup: failed to open /acct/uid_10085/pid_5420/cgroup.procs: No such file or directory
08-31 11:15:40.331  2014  2014 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-31 11:15:40.337  2014  2014 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-31 11:15:40.364  6363  6363 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-31 11:15:40.374  6363  6363 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-31 11:15:40.387   336   417 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-31 11:15:40.391  3236  6568 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-31 11:15:40.437  1081  1104 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6569 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:15:40.756  6569  6569 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-31 11:15:40.767  6587  6587 D AndroidRuntime: 
08-31 11:15:40.767  6587  6587 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 11:15:40.770  6587  6587 D AndroidRuntime: CheckJNI is OFF
08-31 11:15:40.828  6569  6569 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:15:40.828  6569  6569 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:15:40.879  6587  6587 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 11:15:40.883  1081  2037 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 11:15:40.902  1951  1967 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-31 11:15:40.906  1081  2037 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-31 11:15:40.908  1081  2037 D ActivityManager: setTaskToReturnTo : TaskRecord{26de390d #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 11:15:40.908  1081  2037 D ActivityManager: setTaskToReturnTo : TaskRecord{26de390d #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 11:15:40.910  6569  6569 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-31 11:15:40.913  1081  2037 D WindowStateEx: AppWindowTokenEx init.. 
08-31 11:15:40.915   342   377 E GBMv2   : DFP En is all cleared set to be enabled
08-31 11:15:40.930  6569  6569 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-31 11:15:40.931  6569  6569 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-31 11:15:40.942  6569  6569 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-31 11:15:40.942  6569  6569 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-31 11:15:40.950  1081  2037 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6631 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 11:15:40.951  6587  6587 D AndroidRuntime: Shutting down VM
08-31 11:15:40.960  1081  1105 I ActivityManager: Killing 6084:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-31 11:15:41.011  1081  2309 W libprocessgroup: failed to open /acct/uid_10097/pid_6084/cgroup.procs: No such file or directory
08-31 11:15:41.019  1951  4409 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-31 11:15:41.019  1951  4409 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1df676d3 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 11:15:41.020  1951  1967 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-31 11:15:41.021  1951  1967 D SplitWindowPolicy: topRunningActivity=ActivityInfo{14571210 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 11:15:41.023  5019  6649 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-31 11:15:41.036  2841  2856 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-31 11:15:41.039  2841  2856 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1a5c6ee4 on behalf of 6569
08-31 11:15:41.078  1081  2309 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6650 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:15:41.082  1081  1747 V SIM_STK : Menu title from STK is T-Mobile
08-31 11:15:41.085  6631  6631 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-31 11:15:41.091  6569  6569 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-31 11:15:41.120  6569  6569 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-31 11:15:41.145  5019  6649 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 121 ms] updated apps [took 121 ms] 
,08-31 11:15:41.172  6631  6631 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-31 11:15:41.181  6631  6631 I LibraryLoader: Loading: webviewchromium
08-31 11:15:41.185  6631  6631 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4182-4186)
08-31 11:15:41.186  6631  6631 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 11:15:41.198  6650  6650 D DocsApplication: Installing DEX configuration.
,08-31 11:15:41.203  6631  6631 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {92a2f9}
08-31 11:15:41.204  6631  6631 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:15:41.205  6631  6631 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 11:15:41.212  6631  6631 I BrowserStartupController: Initializing chromium process, renderers=0
08-31 11:15:41.213  6631  6631 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:15:41.217  6650  6650 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-31 11:15:41.220  6650  6650 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1a5dfba7 com.google.android.apps.docs}
08-31 11:15:41.225   323  1383 V AudioPolicyService: registerClient() client 0xb558a2c0, uid 10118
08-31 11:15:41.226  6631  6631 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-31 11:15:41.226  6631  6631 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-31 11:15:41.226  6631  6631 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-31 11:15:41.234  1081  1176 D BluetoothManagerService: Message: 20
08-31 11:15:41.234  1081  1176 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@95c7f7d:true
08-31 11:15:41.239  6650  6650 D TAG     : onCreate()
,08-31 11:15:41.245  6631  6631 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:15:41.245  6631  6631 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:15:41.245  6631  6631 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:15:41.245  6631  6631 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:15:41.245  6631  6631 I Adreno-EGL: Remote Branch: 
08-31 11:15:41.245  6631  6631 I Adreno-EGL: Local Patches: 
08-31 11:15:41.245  6631  6631 I Adreno-EGL: Reconstruct Branch: 
08-31 11:15:41.262  6650  6650 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,08-31 11:15:41.303  6631  6683 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-31 11:15:41.308  6631  6631 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-31 11:15:41.322  6631  6631 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:15:41.325  6631  6631 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-31 11:15:41.328  6631  6631 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-31 11:15:41.330  6631  6631 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-31 11:15:41.330  6631  6631 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-31 11:15:41.340  6631  6631 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-31 11:15:41.345  6631  6631 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 11:15:41.345  6631  6631 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:15:41.368  6631  6695 D OpenGLRenderer: Render dirty regions requested: true
08-31 11:15:41.368  6631  6695 I OpenGLRenderer: Initialized EGL, version 1.4
08-31 11:15:41.374  6631  6695 D OpenGLRenderer: Enabling debug mode 0
08-31 11:15:41.381  6631  6631 D Atlas   : Validating map...
,08-31 11:15:41.384  1081  1695 D SplitWindow: check instance of lgWin Window{25dbc70f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 11:15:41.427  6631  6693 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 11:15:41.427  6631  6693 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:15:41.510  1081  1177 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +500ms (total +594ms)
08-31 11:15:41.511  1081  1177 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2f0e70c2 u0 com.test.thalitest/.MainActivity t6} time:104512
08-31 11:15:41.512  6631  6631 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@20b9fa1c time:104513
08-31 11:15:41.610  6631  6631 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 11:15:41.685  6631  6709 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435145216
,08-31 11:15:41.700  6631  6709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 11:15:41.700  6631  6709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 11:15:41.700  6631  6709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 11:15:41.700  6631  6709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 11:15:41.700  6631  6709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 11:15:41.701  6631  6709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fbee420 added. We now have 1 listener(s)
08-31 11:15:41.706  1081  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:15:41.708  6631  6709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-31 11:15:41.709  6631  6709 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:15:41.710  6631  6709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:15:41.711  6631  6709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:15:41.718  6631  6709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 11:15:41.718  6631  6709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 11:15:41.718  6631  6709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 11:15:41.718  6631  6709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-31 11:15:41.718  6631  6709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 11:15:41.718  6631  6709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 11:15:41.718  6631  6709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 11:15:41.718  6631  6709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 11:15:41.718  6631  6709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 11:15:41.718  6631  6709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 11:15:41.718  6631  6709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 11:15:41.718  6631  6709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 11:15:41.718  6631  6709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 11:15:41.718  6631  6709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 11:15:41.718  6631  6709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c22f27f added. We now have 1 listener(s)
08-31 11:15:41.719  6631  6709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:15:41.731  1081  1424 D WifiService: New client listening to asynchronous messages
,08-31 11:15:41.733  6631  6709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:15:41.733  6631  6709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 11:15:41.733  6631  6709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 11:15:41.733  6631  6709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 11:15:41.733  6631  6709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-31 11:15:41.735  6631  6709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:41.736  1081  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:15:41.736  6631  6709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-31 11:15:41.743  6631  6709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 11:15:41.744  6631  6709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:15:41.744  6631  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:41.744  6631  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:41.744  6631  6709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:41.744  6631  6709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:15:41.744  6631  6709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:41.744  6631  6709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:41.744  6631  6709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:41.744  6631  6709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 11:15:41.744  6631  6709 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:15:41.746  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:41.747  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:41.748  6631  6709 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 11:15:41.771  6631  6693 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-31 11:15:41.771  6631  6693 I chromium: 
,08-31 11:15:41.811  6631  6631 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 11:15:41.901  6631  6631 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-31 11:15:41.901  6631  6631 I chromium: 
,08-31 11:15:42.146  1802  5159 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-31 11:15:42.226  1802  5159 I art     : Explicit concurrent mark sweep GC freed 23790(1552KB) AllocSpace objects, 12(192KB) LOS objects, 51% free, 29MB/61MB, paused 1.676ms total 59.002ms
,08-31 11:15:42.253  1802  5159 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,08-31 11:15:42.278  1802  5159 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-31 11:15:42.503  6650  6650 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:15:42.503  6650  6650 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:15:42.671  6631  6712 W jxcore-log: Initializing JXcore engine
08-31 11:15:42.671  6631  6712 W jxcore-log: JXcore engine is ready
,08-31 11:15:42.715  1081  1968 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6726 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-31 11:15:42.717  1081  1968 I ActivityManager: Killing 5540:com.lge.bnr/1000 (adj 15): empty #17
08-31 11:15:42.715  6712  6712 W Thread-781: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[6131]" dev="sockfs" ino=6131 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-31 11:15:42.715  6712  6712 W Thread-781: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-31 11:15:42.715  6712  6712 W Thread-781: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9902]" dev="sockfs" ino=9902 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-31 11:15:42.715  6712  6712 W Thread-781: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-31 11:15:42.715  6712  6712 W Thread-781: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32795]" dev="sockfs" ino=32795 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-31 11:15:42.734  6631  6712 W jxcore-log: Starting JXcore engine
,08-31 11:15:42.741   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 414us total 26.255ms
08-31 11:15:42.760   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 396us total 18.605ms
,08-31 11:15:42.774  6251  6264 W art     : Suspending all threads took: 15.143ms
,08-31 11:15:42.779   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 19.371ms
08-31 11:15:42.817   342   381 E GBMv2   : DFP En is all cleared set to be enabled
,08-31 11:15:42.818   342   381 E GBMv2   : Set value is all cleared set the max
08-31 11:15:42.818   342   381 I GBMv2   : DFP Enabled. Ignore VFP set
08-31 11:15:42.890  6631  6712 W jxcore-log: Platform android
08-31 11:15:42.890  6631  6712 W jxcore-log: 
08-31 11:15:42.890  6631  6712 W jxcore-log: Process ARCH arm
08-31 11:15:42.890  6631  6712 W jxcore-log: 
,08-31 11:15:42.965  1081  1747 I art     : Explicit concurrent mark sweep GC freed 27347(1322KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 3.117ms total 140.272ms
,08-31 11:15:42.966  1081  2309 W libprocessgroup: failed to open /acct/uid_1000/pid_5540/cgroup.procs: No such file or directory
08-31 11:15:42.975  6650  6650 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-31 11:15:43.023  6726  6726 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-31 11:15:43.045  6726  6726 I LockScreenSettings: New app installed broadcast received ..
08-31 11:15:43.048  6726  6726 I LockScreenSettings: Number of installed packages  1
,08-31 11:15:43.106  1081  1695 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6755 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-31 11:15:43.150  6631  6712 I jxcore-log: JXcore Cordova bridge is ready!
08-31 11:15:43.150  6631  6712 I jxcore-log: 
08-31 11:15:43.150  6631  6712 W jxcore-log: JXcore engine is started
,08-31 11:15:43.155  6631  6709 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-31 11:15:43.159  6631  6631 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-31 11:15:43.167  6755  6755 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:15:43.511  1081  2032 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:15:43.566  1081  1968 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6789 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 11:15:43.637  6789  6789 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-31 11:15:43.637  6789  6789 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-31 11:15:43.671  1081  2309 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6811 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-31 11:15:43.672  1081  2309 I ActivityManager: Killing 5265:com.lge.clock/u0a10 (adj 15): empty #17
,08-31 11:15:43.806  1081  1104 W libprocessgroup: failed to open /acct/uid_10010/pid_5265/cgroup.procs: No such file or directory
,08-31 11:15:43.888  6811  6811 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-31 11:15:43.914  6811  6811 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-31 11:15:43.921  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-31 11:15:43.965  1081  1558 I ActivityManager: Killing 6112:com.google.android.gm/u0a64 (adj 15): empty #17
,08-31 11:15:44.111  1081  1105 W libprocessgroup: failed to open /acct/uid_10064/pid_6112/cgroup.procs: No such file or directory
,08-31 11:15:46.574  6650  6650 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-31 11:15:46.580  1081  2037 I ActivityManager: Killing 5899:com.google.android.talk/u0a72 (adj 15): empty #17
08-31 11:15:46.671  1081  1896 W libprocessgroup: failed to open /acct/uid_10072/pid_5899/cgroup.procs: No such file or directory
,08-31 11:15:47.562  6650  6719 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-31 11:15:48.477  1081  2032 I ActivityManager: Killing 5673:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-31 11:15:48.500  5638  5638 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-31 11:15:48.502  5638  5638 W System.err: android.os.DeadObjectException
,08-31 11:15:48.502  5638  5638 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,08-31 11:15:48.502  5638  5638 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-31 11:15:48.502  5638  5638 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,08-31 11:15:48.503  5638  5638 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-31 11:15:48.503  5638  5638 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 11:15:48.503  5638  5638 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 11:15:48.503  5638  5638 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:15:48.503  5638  5638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:15:48.503  5638  5638 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:15:48.503  5638  5638 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,08-31 11:15:48.503  5638  5638 W System.err: ,	at java.lang.reflect.Method.invoke(Native Method)
,08-31 11:15:48.503  5638  5638 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372),
08-31 11:15:48.503  5638  5638 W System.err: ,	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:15:48.503  5638  5638 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:15:48.503  5638  5638 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-31 11:15:48.503  5638  5638 W System.err: android.os.DeadObjectException
,08-31 11:15:48.504  5638  5638 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:15:48.504  5638  5638 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 11:15:48.504  5638  5638 W System.err: 	,at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-31 11:15:48.504  5638  5638 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-31 11:15:48.504  5638  5638 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 11:15:48.504  5638  5638 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 11:15:48.504  5638  5638 W System.err: 	,at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:15:48.504  5638  5638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:15:48.504  5638  5638 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:15:48.504  5638  5638 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,08-31 11:15:48.504  5638  5638 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:15:48.504  5638  5638 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:15:48.504  5638  5638 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:15:48.504  5638  5638 W System.err: ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:15:48.504  5638  5638 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-31 11:15:48.504  5638  5638 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-31 11:15:48.773  1081  1105 W libprocessgroup: failed to open /acct/uid_1000/pid_5673/cgroup.procs: No such file or directory
08-31 11:15:48.774  1081  1105 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-31 11:15:48.795  5638  5638 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-31 11:15:48.795  5638  5638 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 11:15:48.836  1081  1986 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6840 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 11:15:48.838  5638  5638 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-31 11:15:48.917  6840  6840 D UEI.SmartControl: Quickset Services start...
08-31 11:15:48.918  6840  6840 I UEI.SmartControl: Manufacture = LGE
,08-31 11:15:48.919  6840  6840 D UEI.SmartControl: Id = LGNevo
08-31 11:15:48.921  6840  6840 D UEI.SmartControl: File observer start...
08-31 11:15:48.921  6840  6840 E UEI.SmartControl: IR Port is disabled: false
08-31 11:15:48.922  6840  6840 D UEI.SmartControl: Starting file observer...
08-31 11:15:48.922  6840  6840 D UEI.SmartControl: Extracting JNI libs...
08-31 11:15:48.922  6840  6840 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-31 11:15:49.000  6840  6840 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-31 11:15:49.000  6840  6840 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-31 11:15:49.000  6840  6840 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-31 11:15:49.027  6840  6840 I UEI.SmartControl: --- Selecting new region: 6
,08-31 11:15:49.030  6840  6840 I UEI.SmartControl: Model = LG-D855
08-31 11:15:49.031  6840  6840 D UEI.SmartControl: QS Service created
08-31 11:15:49.043  6840  6840 I UEI.SmartControl: Service initServices...
,08-31 11:15:49.048  6840  6840 D UEI.SmartControl: QS start get config
08-31 11:15:49.082  6840  6840 D UEI.SmartControl: Loading JNI Libs...
,08-31 11:15:49.355  6840  6840 I UEI.SmartControl: Supports setup maps: true
,08-31 11:15:49.363  6840  6840 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 11:15:49.363  6840  6840 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 11:15:49.363  6840  6840 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 11:15:49.363  6840  6840 I UEI.SmartControl: ### init IR Blaster...
08-31 11:15:49.369  6840  6840 D serial_port: Configuring serial port
08-31 11:15:49.373  6840  6840 E UEI.SmartControl: UEIBLaster setting for 616
08-31 11:15:49.373  6840  6840 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 11:15:49.374  6840  6840 I UEI.SmartControl: configuring settings for MAXQ616
08-31 11:15:49.374  6840  6840 I UEI.SmartControl: Get version...
08-31 11:15:49.392  6840  6875 D UEI.SmartControl: serial port data available: 21
,08-31 11:15:49.421  6840  6840 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 11:15:49.421  6840  6840 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 11:15:49.422  6840  6840 I UEI.SmartControl: QS saving settings...
,08-31 11:15:49.426  6840  6840 D UEI.SmartControl: IR Blaster version: 25672567
08-31 11:15:49.446  6840  6875 D UEI.SmartControl: serial port data available: 4
,08-31 11:15:49.483  6840  6840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-31 11:15:49.490  6840  6878 I UEI.SmartControl: Device manager: loading config....
08-31 11:15:49.490  6840  6878 D UEI.SmartControl: ----------- loading internal config...
08-31 11:15:49.501  6840  6840 E UEI.SmartControl: Services init done
08-31 11:15:49.501  6840  6840 D UEI.SmartControl: QS Service init finished
,08-31 11:15:49.504  6840  6840 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 11:15:49.504  6840  6840 D UEI.SmartControl: QS Service version code: 201091
08-31 11:15:49.505  6840  6840 D UEI.SmartControl: Service requested: Control
08-31 11:15:49.508  6840  6878 E UEI.SmartControl: Loading SETTINGS...
08-31 11:15:49.510  6840  6840 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 11:15:49.512  1081  1695 I ActivityManager: Killing 5638:com.lge.qremote/u0a112 (adj 15): empty #17
08-31 11:15:49.517  6840  6878 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-31 11:15:49.541  6840  6877 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 11:15:49.541  6840  6877 D UEI.SmartControl: -----service ready thread exits
,08-31 11:15:49.611  1081  1927 W libprocessgroup: failed to open /acct/uid_10112/pid_5638/cgroup.procs: No such file or directory
,08-31 11:15:49.618  6840  6840 D UEI.SmartControl: Internal service binding...
,08-31 11:15:49.758  2784  2784 I MusicWidget: mDelayedStopHandler : unbind
,08-31 11:15:49.769  2184  2184 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-31 11:15:49.769  2184  2184 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-31 11:15:49.770  2184  2184 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-31 11:15:49.772  2184  2184 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-31 11:15:49.772  2184  2184 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-31 11:15:49.772  2184  2184 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-31 11:15:49.774  2184  2184 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-31 11:15:49.774  2184  2184 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,08-31 11:15:49.778  1081  2037 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1c38e6eecom.lge.music.MediaPlaybackService$5@24ab078f
08-31 11:15:49.778  2184  2184 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-31 11:15:49.779  2184  2184 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:15:49.780  2184  2184 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:15:49.780  2184  2184 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:15:49.781  2184  2184 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@2ed175b5
08-31 11:15:49.781  2184  2184 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:15:49.782  2184  2184 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-31 11:15:49.782  2184  2184 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:15:49.783  2184  2184 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-31 11:15:49.783  2184  2184 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-31 11:15:49.783  2184  2184 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:15:49.784  2184  2184 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:15:49.785  2184  2184 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:15:49.785  2184  2184 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:15:49.786  2184  2184 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 11:15:49.787  2184  2184 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
,08-31 11:15:49.790  2184  2184 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-31 11:15:49.791  2184  2184 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-31 11:15:49.791  2184  2184 V MediaPlayer[Native]: reset
08-31 11:15:49.797  2184  2184 V MediaPlayer[Native]: setListener
08-31 11:15:49.797  2184  2184 V MediaPlayer[Native]: disconnect
08-31 11:15:49.797  2184  2184 V MediaPlayer[Native]: destructor
08-31 11:15:49.797   323   323 V AudioFlinger: releasing 16 from 2184 for -1
08-31 11:15:49.797   323   323 V AudioFlinger:  decremented refcount to 0
08-31 11:15:49.797   323   323 V AudioFlinger: purging stale effects
08-31 11:15:49.797  2184  2184 V MediaPlayer[Native]: disconnect
08-31 11:15:49.799  2184  2184 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,08-31 11:15:49.801  2184  2184 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-31 11:15:49.802  2184  2184 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-31 11:15:49.803  2184  2184 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-31 11:15:49.803  2184  2184 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-31 11:15:49.803  2184  2184 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-31 11:15:49.804  2184  2184 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 549059100
08-31 11:15:49.804  2184  2184 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 549059100
08-31 11:15:49.817  2184  2184 I SmartShareClient: [SmartShareManagerClient] terminate service: 2184/MediaPlaybackService/509913923
,08-31 11:15:49.822  2184  2184 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-31 11:15:49.822  2184  2184 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@270c3625
08-31 11:15:49.824  2184  2184 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-31 11:15:49.825  2184  2184 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-31 11:15:49.826  2184  2184 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-31 11:15:49.826  2184  2184 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-31 11:15:49.827  1081  1747 I ActivityManager: Killing 5581:com.android.calendar/u0a13 (adj 15): empty #17
08-31 11:15:49.829  2184  2184 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
,08-31 11:15:49.921  1081  1105 W libprocessgroup: failed to open /acct/uid_10013/pid_5581/cgroup.procs: No such file or directory
,08-31 11:15:52.672  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 11:15:52.672  6631  6712 I jxcore-log: 
08-31 11:15:52.674  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 11:15:52.674  6631  6712 I jxcore-log: 
,08-31 11:15:52.682  6631  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:15:52.682  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:52.682  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:52.682  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:52.682  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:15:52.682  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:52.682  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:52.682  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:52.684  6631  6712 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:52.687  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 11:15:52.687  6631  6712 I jxcore-log: 
,08-31 11:15:52.688  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 11:15:52.688  6631  6712 I jxcore-log: 
08-31 11:15:53.197  6631  6712 I jxcore-log: Unit Test app is loaded
08-31 11:15:53.197  6631  6712 I jxcore-log: 
,08-31 11:15:53.208  6631  6631 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 11:15:53.208  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:15:53.208  6631  6712 I jxcore-log: 
08-31 11:15:53.212  6631  6712 D executeNativeTests: Running unit tests
,08-31 11:15:53.294  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:15:53.294  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 added. We now have 2 listener(s)
08-31 11:15:53.295  1081  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:15:53.299  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:15:53.299  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:15:53.299  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:15:53.300  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:15:53.300  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 added. We now have 2 listener(s)
08-31 11:15:53.300  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:15:53.300  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:15:53.303  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:53.307  6631  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:15:53.307  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:53.307  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:53.307  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:53.307  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:15:53.307  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:53.307  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:53.307  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:15:53.311  6631  6712 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:53.311  6631  6712 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:15:53.314  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:53.315  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:53.322  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 11:15:53.323  6631  6712 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:15:53.323  6631  6712 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:15:53.325  6631  6712 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-31 11:15:53.325  6631  6712 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 11:15:53.325  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:15:53.325  6631  6712 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:15:53.325  6631  6712 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:15:53.326  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.326  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.326  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.327  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.327  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.327  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:15:53.327  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:15:53.327  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 removed from the list
08-31 11:15:53.327  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.327  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 removed from the list
08-31 11:15:53.327  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.327  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.328  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.328  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.329  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.329  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.329  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.329  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.331  6631  6712 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 11:15:53.331  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.331  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STAR,TED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.331  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.331  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.331  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.331  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.331  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.331  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:15:53.331  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.331  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.331  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.331  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.331  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.331  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.332  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:15:53.332  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.332  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.332  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
,08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:15:53.336  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 11:15:53.337  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:15:53.337  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:15:53.337  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:15:53.337  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:15:53.337  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:15:53.337  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:15:53.337  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:15:53.337  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-31 11:15:53.337  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 11:15:53.337  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:15:53.337  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 11:15:53.337  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:15:53.337  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.338  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.338  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:15:53.338  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.338  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.338  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.338  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
,08-31 11:15:53.338  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.338  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.338  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.338  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.338  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-31 11:15:53.338  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.338  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.339  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.339  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:15:53.339  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.339  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.340  6631  6712 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:15:53.341  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:53.344  6631  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:15:53.344  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-31 11:15:53.344  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:53.344  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:53.344  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:15:53.344  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:53.344  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:53.344  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:53.345  6631  6712 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:53.345  6631  6712 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-31 11:15:53.346  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:15:53.347  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-31 11:15:53.348  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:15:53.348  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:15:53.348  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-31 11:15:53.348  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:53.348  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:15:53.352  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:15:53.352  1081  2310 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:15:53.355  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:15:53.360  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:15:53.361  6631  6712 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 11:15:53.361  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:15:53.362  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:15:53.363  6631  6712 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 11:15:53.363  6631  6712 I io.jxcore.node.ConnectionHelper: start: OK
08-31 11:15:53.365  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.365  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.365  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.365  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.365  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.365  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:15:53.365  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.365  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.365  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.365  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.365  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.366  6631  6712 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:15:53.367  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:53.369  6631  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:15:53.369  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:53.369  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:53.369  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:53.369  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:15:53.369  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:53.369  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:53.369  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:15:53.370  6631  6712 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:53.370  6631  6712 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:15:53.371  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:53.371  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:15:53.371  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:15:53.371  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:15:53.371  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:53.371  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:15:53.372  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:53.374  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:15:53.375  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:15:53.375  6631  6712 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 11:15:53.376  6631  6712 I io.jxcore.node.ConnectionHelper: start: OK
08-31 11:15:53.377  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.377  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.377  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.377  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.377  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.377  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:15:53.377  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.377  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.377  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.377  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.377  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.377  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.377  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.378  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.378  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.379  6631  6712 D BluetoothLeScanne,r: could not find callback wrapper
08-31 11:15:53.379  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:53.379  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.379  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.379  6631  6712 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:15:53.380  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:53.382  6631  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:15:53.382  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:53.382  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:53.382  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:53.382  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:15:53.382  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:53.382  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:53.382  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:53.383  6631  6712 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:53.383  6631  6712 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:15:53.384  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:53.385  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:53.385  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:15:53.385  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:15:53.385  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:15:53.385  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:53.385  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:15:53.388  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:15:53.388  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:15:53.389  6631  6712 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 11:15:53.389  6631  6712 I io.jxcore.node.ConnectionHelper: start: OK
08-31 11:15:53.390  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.390  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.390  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.390  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.390  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.390  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.391  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.391  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.391  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:15:53.391  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.391  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.391  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.391  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.391  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.391  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.391  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.392  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.392  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.392  6631  6712 D BluetoothLeScanner: could not find callback wrapper
08-31 11:15:53.392  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:53.392  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.392  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.393  6631  6712 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 11:15:53.393  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.393  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.393  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.393  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.393  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.393  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.393  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.393  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.393  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.393  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.393  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.393  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.393  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.393  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.394  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.394  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.394  6631  6712 D BluetoothLeScanner: could not find callback wrapper
08-31 11:15:53.394  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:53.394  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.394  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.395  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 11:15:53.395  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.395  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.395  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.395  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.396  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.396  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.396  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.396  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.396  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.396  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.396  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.396  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.396  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.396  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.397  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.397  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.397  6631  6712 D BluetoothLeScanner: could not find callback wrapper
08-31 11:15:53.397  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:53.397  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.397  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.397  6631  6712 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 11:15:53.398  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.398  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.398  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.398  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.398  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.398  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.398  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.398  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.398  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.398  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.398  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.398  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.398  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.398  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.399  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.399  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.399  6631  6712 D BluetoothLeScanner: could not find callback wrapper
08-31 11:15:53.399  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:53.399  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.399  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.400  6631  6712 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 11:15:53.400  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.400  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.400  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.400  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.400  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.400  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.400  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.400  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:15:53.400  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.400  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.400  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.400  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.400  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.400  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.401  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.401  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.401  6631  6712 D BluetoothLeScanner: could not find callback wrapper
08-31 11:15:53.401  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:53.401  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.401  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.402  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:15:53.402  6631  6712 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:15:53.402  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:15:53.402  6631  6712 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:15:53.402  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:15:53.402  6631  6712 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:15:53.402  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.402  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.402  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.402  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.402  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.402  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.402  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.402  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.402  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.402  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.402  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.402  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.402  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.402  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.404  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.404  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.404  6631  6712 D BluetoothLeScanner: could not find callback wrapper
08-31 11:15:53.404  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:53.404  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.404  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.404  6631  6712 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:15:53.405  6631  6712 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:15:53.405  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 11:15:53.406  6631  6712 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:15:53.406  6631  6712 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 11:15:53.406  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 11:15:53.406  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:15:53.406  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:15:53.406  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 11:15:53.406  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 11:15:53.407  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:15:53.407  6631  6712 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 11:15:53.407  6631  6712 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:15:53.407  6631  6712 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 11:15:53.407  6631  6712 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:15:53.407  6631  6712 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:15:53.407  6631  6712 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 11:15:53.407  6631  6712 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:15:53.408  6631  6712 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:15:53.408  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 11:15:53.410  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 11:15:53.410  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 11:15:53.410  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 11:15:53.411  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 11:15:53.411  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 11:15:53.411  6631  6712 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 11:15:53.411  6631  6712 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:15:53.411  6631  6712 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 11:15:53.411  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.411  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.411  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.411  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.411  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.411  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.412  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 11:15:53.412  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.412  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.412  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.412  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.412  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.412  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.412  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.412  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.413  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.413  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.413  6631  6712 D BluetoothLeScanner: could not find callback wrapper
08-31 11:15:53.413  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:53.413  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.413  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.414  6631  6712 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 11:15:53.414  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.414  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.414  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.414  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.414  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.415  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.415  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.415  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.415  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.415  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.415  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.415  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.415  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.415  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.415  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.415  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.416  6631  6712 D BluetoothLeScanner: could not find callback wrapper
08-31 11:15:53.416  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:53.416  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.416  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.418  6631  6712 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 11:15:53.418  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.418  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.418  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.419  6631  6888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 845)
08-31 11:15:53.430  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.430  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.430  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.430  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.430  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.430  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.430  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.430  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.430  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.430  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.430  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.432  6631  6889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 845
08-31 11:15:53.432  6631  6889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 845)
08-31 11:15:53.432  6631  6889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 845)
08-31 11:15:53.433  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.433  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.433  6631  6712 D BluetoothLeScanner: could not find callback wrapper
08-31 11:15:53.433  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:53.433  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.433  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.434  6631  6712 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 11:15:53.434  6631  6712 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 11:15:53.434  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:15:53.434  6631  6712 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 11:15:53.434  6631  6712 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:15:53.434  6631  6712 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 11:15:53.434  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:15:53.434  6631  6712 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 11:15:53.434  6631  6712 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:15:53.434  6631  6712 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:15:53.434  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:15:53.434  6631  6712 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 11:15:53.435  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.435  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.435  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.435  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.435  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.435  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.435  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.435  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.435  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.435  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.435  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.435  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.435  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.435  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.436  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.436  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.437  6631  6712 D BluetoothLeScanner: could not find callback wrapper
08-31 11:15:53.437  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:53.437  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.437  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.437  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.437  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.437  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.437  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.437  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.437  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.437  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.437  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.437  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.438  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.438  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.438  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.438  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.438  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.438  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.438  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.438  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.438  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.440  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.440  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.440  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.440  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.440  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.440  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.440  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.440  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.440  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.440  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.440  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.441  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.441  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.441  6631  6712 D BluetoothLeScanner: could not find callback wrapper
08-31 11:15:53.441  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:53.441  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.441  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.442  6631  6712 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 11:15:53.443  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:53.444  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 11:15:53.445  6631  6712 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 11:15:53.445  6631  6712 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 11:15:53.446  1081  1747 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:15:53.447  6631  6895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:15:53.447  6631  6631 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 11:15:53.447  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 11:15:53.447  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:15:53.448  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:15:53.448  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 11:15:53.448  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 11:15:53.448  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 11:15:53.448  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.448  6631  6712 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 11:15:53.449  4243  4383 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-31 11:15:53.450  6631  6895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-31 11:15:53.450  6631  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 11:15:53.450  6631  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 11:15:53.451  6631  6631 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 11:15:53.452  6631  6631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 11:15:53.452  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.452  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.452  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:15:53.452  6631  6712 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:15:53.452  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:15:53.453  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:15:53.454  6631  6712 D BluetoothLeScanner: could not find callback wrapper
08-31 11:15:53.454  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:15:53.454  6631  6712 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:15:53.454  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.454  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.455  6631  6712 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:15:53.456  6631  6631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:15:53.456  6631  6631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:15:53.456  6631  6631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:15:53.456  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.456  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.456  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.456  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.457  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.457  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.457  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.457  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.457  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.457  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.457  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.457  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.457  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.457  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.457  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.458  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.458  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.458  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.458  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.460  6631  6712 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 11:15:53.460  6631  6712 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 11:15:53.460  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:15:53.460  6631  6712 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:15:53.461  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.461  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.461  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.461  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.462  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.462  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.462  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.462  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.462  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.462  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.462  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.462  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.462  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.462  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.463  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.463  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.463  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.463  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.465  1081  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:15:53.465  1081  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:15:53.466  1081  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:15:53.466  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.466  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.466  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.467  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.467  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.467  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.467  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.467  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.467  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.467  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.467  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.467  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.467  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.467  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.468  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.468  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.468  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.468  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.469  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:15:53.469  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:15:53.469  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:15:53.469  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:15:53.469  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.469  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.469  6631  6712 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f072f0 not in the list
08-31 11:15:53.469  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.469  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.469  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:15:53.469  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.469  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.469  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:15:53.469  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:15:53.470  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:15:53.470  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:15:53.470  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:15:53.470  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19064069 not in the list
08-31 11:15:53.471  6631  6712 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 11:15:53.471  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:15:53.471  6631  6712 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 11:15:53.471  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:15:53.471  6631  6712 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 11:15:53.471  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:15:53.473  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 11:15:53.473  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 11:15:53.473  6631  6712 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 11:15:53.473  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:15:53.473  6631  6712 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 11:15:53.473  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:15:53.473  6631  6712 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 11:15:53.473  6631  6712 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 11:15:53.474  6631  6712 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 11:15:53.474  6631  6712 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 11:15:53.474  6631  6712 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 11:15:53.475  6631  6712 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 11:15:53.475  6631  6712 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 11:15:53.475  6631  6712 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 11:15:53.475  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:15:53.475  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ffc19c6 added. We now have 2 listener(s)
08-31 11:15:53.475  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:15:53.477  6631  6712 D BluetoothAdapter: enable(): BT is already enabled..!
08-31 11:15:53.478  1081  2309 D WifiServiceImplEx: setWifiEnabled: true pid=6631, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 11:15:53.478  1081  2309 D WifiService: setWifiEnabled: true pid=6631, uid=10118
08-31 11:15:53.478  1081  2309 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 11:15:53.479  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:15:53.479  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23557d87 added. We now have 3 listener(s)
08-31 11:15:53.479  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:15:53.482  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:15:53.482  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@350fc4b4 added. We now have 4 listener(s)
08-31 11:15:53.482  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:15:53.483  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:15:53.483  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cddc8dd added. We now have 5 listener(s)
08-31 11:15:53.483  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:15:53.484  1081  2309 D WifiServiceImplEx: setWifiEnabled: false pid=6631, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 11:15:53.484  1081  2309 D WifiService: setWifiEnabled: false pid=6631, uid=10118
08-31 11:15:53.485  1081  2309 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:15:53.502  1081  1375 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-31 11:15:53.503  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 11:15:53.503  1081  1375 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 11:15:53.503  1081  1375 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-31 11:15:53.503  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-31 11:15:53.503  1081  1375 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 11:15:53.503  1081  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:15:53.503  1081  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:15:53.504  1081  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:15:53.504  1081  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:15:53.504  1081  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:15:53.505  1081  1896 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@34d58af5 mBinding = false
08-31 11:15:53.505  1081  1081 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:15:53.506  1081  1081 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:15:53.506  1081  1081 D Ulp_jni : JNI:system_update. Event-4
08-31 11:15:53.517  1081  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 11:15:53.517  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-31 11:15:53.517  1081  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:53.517  2654  2654 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:15:53.517  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:53.517  1081  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:15:53.517  1081  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:15:53.518  1081  1375 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:15:53.518   318   912 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:15:53.518  1081  2807 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:53.525  1081  1176 D BluetoothManagerService: Message: 2
08-31 11:15:53.527  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:15:53.527  1081  1176 D BluetoothManagerService: Sending off request.
08-31 11:15:53.527  1081  1081 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:15:53.527  4243  4268 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-31 11:15:53.527  1081  1081 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:15:53.528  1081  1081 D Ulp_jni : JNI:system_update. Event-4
08-31 11:15:53.528  4243  4345 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-31 11:15:53.528  4243  4345 D BluetoothAdapterProperties: Setting state to 13
08-31 11:15:53.528  4243  4345 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 11:15:53.529  4243  4345 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 11:15:53.529  4243  4345 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 11:15:53.530  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:53.530  6631  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:15:53.530  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:53.530  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:53.530  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:53.530  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:53.530  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:53.530  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:53.530  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:53.530  1081  1176 D BluetoothManagerService: Message: 60
08-31 11:15:53.530  1081  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 11:15:53.530  1081  1176 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-31 11:15:53.531  4243  4350 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:15:53.531  4243  4345 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 11:15:53.532  4243  4345 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 11:15:53.532  4243  4621 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:15:53.533  4243  4612 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 11:15:53.533  4243  4612 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:15:53.533  4243  4612 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 11:15:53.533  4243  4612 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 11:15:53.533  4243  4612 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 11:15:53.533  4243  4612 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 11:15:53.533  4243  4612 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 11:15:53.533  4243  4612 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-31 11:15:53.533  4243  4658 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:15:53.533  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 11:15:53.533  4243  4660 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:15:53.533  4243  4468 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-31 11:15:53.534  4243  4659 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:15:53.535  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:15:53.535  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:15:53.535  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for, PSM: 0x001b
08-31 11:15:53.535  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:15:53.535  4243  4468 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:15:53.535  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:15:53.535  4243  4468 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:15:53.535  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:15:53.535  4243  4468 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:15:53.535  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-31 11:15:53.535  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 11:15:53.535  4243  4468 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 11:15:53.535  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:15:53.536  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:15:53.538  4243  4243 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:15:53.538  4243  4243 D BluetoothMapService: STATE_TURNING_OFF
08-31 11:15:53.538  4243  4243 V BluetoothMapService: Handler(): got msg=4
08-31 11:15:53.538  4243  4243 D BluetoothMapService: MAP Service closeService in
08-31 11:15:53.538  4243  4243 D BluetoothMapMasInstance: MAP Service shutdown
08-31 11:15:53.538  4243  4243 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:15:53.538  4243  4243 V BluetoothMapService: MAP Service closeService out
08-31 11:15:53.538  4243  4243 V BtOppService: Receiver DISABLED_ACTION 
08-31 11:15:53.539  4243  4243 I BtOppRfcommListener: stopping Accept Thread
08-31 11:15:53.539  4243  4243 V BtOppRfcommListener: close mBtServerSocket
08-31 11:15:53.539  4243  4243 V BtOppRfcommListener: waiting for thread to terminate
08-31 11:15:53.539  4243  4658 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 11:15:53.539  4243  4243 V BtOppRfcommListener: done waiting for thread to terminate
08-31 11:15:53.540  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:53.540  6631  6712 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:53.540  6631  6712 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:15:53.543  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:53.548  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:53.550  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:53.550  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:53.550  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:53.550  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:53.550  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:53.550  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:53.550  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:53.550  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:15:53.550  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:53.551  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:53.551  6631  6631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:15:53.559  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:15:53.572  1081  2010 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-31 11:15:53.572  1081  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:53.572  1081  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:53.572  1081  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-31 11:15:53.572  1081  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:53.572  1081  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 11:15:53.575  1081  1427 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 11:15:53.575  1081  1427 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-31 11:15:53.576   318  6906 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 11:15:53.577  1081  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-31 11:15:53.578  1081  1174 D DSQN    : Dns fail occured do internet check.
08-31 11:15:53.578  1081  1081 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-31 11:15:53.578  1081  1081 D DSQN    : try Internet connection check
08-31 11:15:53.586  1081  1172 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6909 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 11:15:53.591  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:15:53.591  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:53.591  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:53.591  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:53.591  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:53.591  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:53.591  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:15:53.591  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:53.591  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:53.592  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:53.592  6631  6631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:15:53.593  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:53.593  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:53.593  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:53.593  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:53.593  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:53.593  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:53.593  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:15:53.593  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:53.593  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:53.593  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:53.593  6631  6631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:15:53.595  6631  6888 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-31 11:15:53.595  6631  6888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 845)
08-31 11:15:53.616  1081  1172 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6930 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-31 11:15:53.618  4243  4243 V BtOppService: onDestroy
,08-31 11:15:53.619  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:15:53.619  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:15:53.622  4243  4243 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-31 11:15:53.622  1951  1951 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-31 11:15:53.622  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:53.623  1081  1427 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-31 11:15:53.623  1081  1427 D DSQN    : disableDataServiceNotify
08-31 11:15:53.623  1081  1427 D DSQN    : stop dsqn bin
08-31 11:15:53.623  1081  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:53.624  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:53.624   318  6939 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 11:15:53.624  1081  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:53.624  1081  6912 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-31 11:15:53.625  1081  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-31 11:15:53.625  1081  1174 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 11:15:53.625  1081  6908 D DSQN    : ThreadInternetCheck internet check NOK 
08-31 11:15:53.625  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:53.625  1081  6908 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
08-31 11:15:53.625  1081  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:53.625  1081  1374 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:53.625  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:53.626  1081  1374 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1a893c3f
08-31 11:15:53.626  1081  1375 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 11:15:53.626  1081  1374 D LGWifiP2pService: P2pDisablingState
08-31 11:15:53.626  1081  1374 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:53.626  1081  1374 D LGWifiP2pService: p2p socket connection lost
08-31 11:15:53.626  1081  1374 D LGWifiP2pService: P2pDisabledState
08-31 11:15:53.626  1081  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:53.626  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:53.627  1081  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:53.627  1081  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-31 11:15:53.627  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 11:15:53.627  1081  1081 D WifiHS20: hidePasspointNotification off =false
08-31 11:15:53.627  2654  2654 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:15:53.628  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:53.628  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:53.628  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:15:53.628  1081  1081 D WifiHS20: hidePasspointNotification off =false
08-31 11:15:53.628  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 11:15:53.628  1951  1951 D WfdsService: WifiP2pState is changed : false
08-31 11:15:53.628  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:53.628  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:53.628  1951  2279 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 11:15:53.628  1951  2279 D WfdsService: Set the WFDS Monitor: false
08-31 11:15:53.628  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:15:53.628  1081  1081 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 11:15:53.628  1081  1081 D RttService: SCAN_AVAILABLE : 1
08-31 11:15:53.629  1081  1539 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:53.629  1081  1540 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:53.629  1951  2279 D WfdsMonitor: WFDS Monitor is stopped
08-31 11:15:53.629  1951  2729 D CtrlSupplicant: Received on exit socket, terminate
,08-31 11:15:53.629  1951  2729 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 11:15:53.629  1951  2279 D WfdsService: STATE : WfdsDisabledState - enter
08-31 11:15:53.629  1951  2729 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 11:15:53.630  1951  2729 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
,08-31 11:15:53.630  1951  2279 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 11:15:53.630  1081  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:15:53.630  1081  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:15:53.630  1951  2284 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 11:15:53.630  1081  1375 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:15:53.630  1081  1374 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:15:53.630  1081  1374 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:53.630   318   912 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:15:53.632  1081  1375 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 11:15:53.632  1081  1081 D WifiHS20: hidePasspointNotification off =false
08-31 11:15:53.632  1081  1375 D WifiNative-p2p0: TERMINATE: returned true
08-31 11:15:53.632  1081  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:15:53.632  1081  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:15:53.632  1081  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-31 11:15:53.633  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:53.633  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:53.633  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-31 11:15:53.635  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-31 11:15:53.636  1081  1081 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 11:15:53.638  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:53.638  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:53.638  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:53.638  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:53.638  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:15:53.638  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:53.638  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:15:53.638  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:53.638  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:53.639  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:53.639  6631  6631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:15:53.639  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:15:53.639  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:15:53.640  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:15:53.640  1081  1081 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-31 11:15:53.641  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:53.641  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:53.641  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:53.641  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:53.641  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:15:53.641  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:53.641  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:15:53.641  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:53.641  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:15:53.641  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:53.642  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:53.642  6631  6631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:15:53.655  6909  6909 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:15:53.655  6909  6909 W ResourcesMana,ger: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-31 11:15:53.655  6909  6909 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:15:53.656  6909  6909 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,08-31 11:15:53.656  6909  6909 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 11:15:53.657  6909  6909 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 11:15:53.689  1081  1427 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-31 11:15:53.689  1081  1427 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:15:53.689  1081  1427 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:15:53.689  1081  1427 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:15:53.690  1081  1427 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-31 11:15:53.690  1081  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:53.690  1081  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:53.690  1081  2806 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-31 11:15:53.691  1081  1427 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-31 11:15:53.691  1081  1427 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 11:15:53.691  1081  1427 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:15:53.692  1081  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 11:15:53.692  1081  1427 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:15:53.692  1081  1427 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:15:53.692  1081  1427 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:15:53.692  1081  1081 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 11:15:53.692  1081  1427 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:15:53.693  1585  1795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 11:15:53.693  1081  1427 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:15:53.694  1081  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 11:15:53.694  1081  1375 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:15:53.694  1081  1375 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:15:53.694  1081  1427 D NetworkManagementService: Removing idletimer
08-31 11:15:53.694  1081  1427 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:53.694  1862  1862 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:15:53.695  1081  1081 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 11:15:53.695  1081  1081 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:15:53.695  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 11:15:53.695  1081  1081 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:15:53.695  1081  1081 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:15:53.695  1081  1081 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:15:53.695  1081  1081 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: ,[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:15:53.695  1081  1081 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:15:53.698  1081  1427 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-31 11:15:53.714  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 11:15:53.714  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:15:53.715  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:53.716  6930  6930 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-31 11:15:53.716  6930  6930 W LG Account v2.2: No ProfileInfo entries
08-31 11:15:53.716  6930  6930 I LG Account v2.2: isEnabled: false
08-31 11:15:53.716  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:53.716  6930  6930 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 11:15:53.716  6930  6930 I Feature : [Lifetracker]Country: EU
08-31 11:15:53.716  6930  6930 I Feature : [Lifetracker]Operator: OPEN
08-31 11:15:53.716  6930  6930 I Feature : [Lifetracker]Ranking support: false
08-31 11:15:53.716  6930  6930 I Feature : [Lifetracker]Comfort support: false
08-31 11:15:53.716  6930  6930 I Feature : [Lifetracker]Accessory: true
08-31 11:15:53.716  6930  6930 I Feature : [Lifetracker]Health device: true
08-31 11:15:53.716  6930  6930 I Feature : [Lifetracker]Extra Pedometer: false
08-31 11:15:53.716  6930  6930 I Feature : [Lifetracker]Blood glucose device: false
08-31 11:15:53.717  6930  6930 I Feature : [Lifetracker]Device Number: 3
08-31 11:15:53.723  1081  2807 D DhcpStateMachine: StoppedState
08-31 11:15:53.723  1081  2807 D DhcpStateMachine: StoppedState{ when=-93ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:53.725  1081  1375 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-31 11:15:53.725  1081  1375 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-31 11:15:53.728  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:15:53.763  6909  6909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-31 11:15:53.766  2654  2654 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 11:15:53.766  2654  2654 I wpa_supplicant: monitor socket send errors count : 1
08-31 11:15:53.766  2654  2654 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1951-2\x00 that cannot receive messages
08-31 11:15:53.767  1081  2310 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6950 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 11:15:53.767  1081  2723 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-31 11:15:53.767  1081  2723 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 11:15:53.768  1081  2310 I ActivityManager: Killing 6181:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-31 11:15:53.801  1081  1176 D BluetoothManagerService: Message: 20
08-31 11:15:53.801  1081  1176 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e9f88c4:true
08-31 11:15:53.803  1081  1968 W libprocessgroup: failed to open /acct/uid_10014/pid_6181/cgroup.procs: No such file or directory
08-31 11:15:53.806  4243  4243 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:15:53.806  4243  4243 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:15:53.806  4243  4243 V BluetoothPbapReceiver: ***********state = 13
08-31 11:15:53.807  4243  4243 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-31 11:15:53.808  2654  2654 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:15:53.809  1081  1176 D Tethering: InitialState.processMessage what=4
,08-31 11:15:53.809  2654  2654 W wpa_supplicant: USIM:  scard_deinit function
08-31 11:15:53.809  1081  2723 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-31 11:15:53.809  1081  2723 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:15:53.809  1081  2723 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:15:53.810  4243  4243 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:15:53.810  4243  4243 V BluetoothPbapService: state: 13
08-31 11:15:53.810  4243  4243 V BluetoothPbapService: Pbap Service closeService in
08-31 11:15:53.810  1081  2723 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 11:15:53.810  1081  2723 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:15:53.810  1081  2723 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:15:53.811  1081  1375 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116803
08-31 11:15:53.811  1081  1375 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116804
08-31 11:15:53.812  1081  1375 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=116804  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 11:15:53.812  4243  4243 V BluetoothPbapService: successfully stopped pbap service
08-31 11:15:53.812  4243  4243 V BluetoothPbapService: Pbap Service closeService out
08-31 11:15:53.812  4243  4243 V BluetoothPbapService: Pbap Service onDestroy
08-31 11:15:53.812  4243  4243 V BluetoothPbapService: Pbap Service closeService in
08-31 11:15:53.812  4243  4243 V BluetoothPbapService: Pbap Service closeService out
08-31 11:15:53.812  1081  1375 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=116805  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 11:15:53.812  4243  4243 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-31 11:15:53.812  1081  1176 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:15:53.813  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:15:53.815  1585  1585 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:15:53.816  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:53.816  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:53.818  1081  1375 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:15:53.818  1081  1176 D BluetoothManagerService: Message: 30
08-31 11:15:53.819  1081  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-31 11:15:53.825  1081  1176 D BluetoothManagerService: Message: 30
08-31 11:15:53.827  6909  6909 D LocalBluetoothProfileManager: Adding local MAP profile
08-31 11:15:53.828  6909  6909 D BluetoothMap: Create BluetoothMap proxy object
08-31 11:15:53.829  1081  1176 D BluetoothManagerService: Message: 30
08-31 11:15:53.832  1081  1176 D BluetoothManagerService: Message: 30
,08-31 11:15:53.833  6909  6909 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-31 11:15:53.833  6909  6909 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-31 11:15:53.840  1585  1585 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-31 11:15:53.841  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:53.841  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:53.843  6909  6909 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-31 11:15:53.846  6909  6909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-31 11:15:53.850  6950  6950 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:15:53.852  6950  6950 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:15:53.853  6950  6950 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:15:53.853  6909  6909 D DockEventReceiver: finishStartingService: stopping service
08-31 11:15:53.854  1081  1695 I ActivityManager: Killing 6251:com.android.defcontainer/u0a4 (adj 15): empty #17
08-31 11:15:53.860  6909  6909 D BluetoothInputDevice: Proxy object connected
08-31 11:15:53.860  6909  6909 D HidProfile: Bluetooth service connected
,08-31 11:15:53.861  6909  6909 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:15:53.861  6909  6909 D PanProfile: Bluetooth service connected
08-31 11:15:53.862  6909  6909 D BluetoothMap: Proxy object connected
08-31 11:15:53.862  6909  6909 D MapProfile: Bluetooth service connected
08-31 11:15:53.862  6909  6909 D BluetoothMap: getConnectedDevices()
08-31 11:15:53.862  6909  6909 D BluetoothMap: Bluetooth is Not enabled
08-31 11:15:53.862  6909  6909 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 11:15:53.880  2654  2654 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 11:15:53.880  1081  2723 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-31 11:15:53.880  1081  2723 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 11:15:53.880  1081  2723 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-31 11:15:53.880  1081  1375 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-31 11:15:53.900  1081  2309 W libprocessgroup: failed to open /acct/uid_10004/pid_6251/cgroup.procs: No such file or directory
,08-31 11:15:53.907  1081  1172 I ActivityManager: Waited long enough for: ServiceRecord{b9f777b u0 com.google.android.gms/.wearable.service.WearableService}
08-31 11:15:53.918  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:15:53.957  6631  6631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:15:53.967  6909  6909 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:15:53.968  6909  6909 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:15:53.978  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:15:53.979  6909  6909 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 11:15:53.984  6909  6909 D BluetoothPermissionRequest: onReceive
,08-31 11:15:53.984  1081  1375 D WifiOffDelayIfNotUsed: stopMonitoring
08-31 11:15:53.985  1081  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:15:53.985  1081  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:15:53.985  1081  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:15:53.986  1951  1951 D WfdsService: Supplicant Connection state is changed : false
08-31 11:15:53.987  1951  2279 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-31 11:15:53.987  1951  2279 D WfdsService: Set the WFDS Monitor: false
08-31 11:15:53.987  1951  2279 D WfdsMonitor: WFDS Monitor is stopped
08-31 11:15:53.988  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 11:15:53.989  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:53.990  6909  6909 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 11:15:53.992  2441  2441 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:53.997  1081  1081 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-31 11:15:53.998  1081  1387 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
,08-31 11:15:53.998  1081  1387 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-31 11:15:53.999  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:53.999  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:53.999  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:53.999  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:53.999  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:15:53.999  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:53.999  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-31 11:15:53.999  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:53.999  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:15:54.003  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:54.003  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:54.003  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:54.003  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:54.003  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:15:54.003  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:54.003  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:15:54.003  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:54.003  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:15:54.017  6909  6909 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 11:15:54.021  1081  1105 I ActivityManager: Killing 6430:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-31 11:15:54.050  1081  1896 W libprocessgroup: failed to open /acct/uid_10008/pid_6430/cgroup.procs: No such file or directory
,08-31 11:15:54.051  4243  4243 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-31 11:15:54.051  4243  4243 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-31 11:15:54.051  4243  4243 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-31 11:15:54.056  4243  4243 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:15:54.056  4243  4243 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 11:15:54.057  4243  4243 V BluetoothFtpService: Ftp Service onStartCommand
08-31 11:15:54.057  4243  4243 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:15:54.057  4243  4243 V BluetoothFtpService: Ftp Service closeService
08-31 11:15:54.057  4243  4243 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-31 11:15:54.058  4243  4243 V BluetoothFtpService: successfully stopped ftp service
08-31 11:15:54.059  4243  4243 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:15:54.059  4243  4243 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:15:54.059  4243  4243 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:15:54.059  4243  4243 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:15:54.059  4243  4243 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-31 11:15:54.059  4243  4243 V BluetoothSapReceiver: Calling SAP service start service with action = null,
08-31 11:15:54.060  4243  4243 V BluetoothFtpService: Ftp Service onDestroy,
,08-31 11:15:54.060  4243  4243 V BluetoothFtpService: Ftp Service closeService
08-31 11:15:54.135  1081  2037 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6982 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-31 11:15:54.139  4243  4243 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:15:54.139  4243  4243 V BluetoothSapService: state: 13
08-31 11:15:54.139  4243  4243 V BluetoothSapService: Stopping SAP server process
08-31 11:15:54.144  4243  4243 V BluetoothSapService: Sap Service closeSapService in
08-31 11:15:54.144  4243  4243 V BluetoothSapService: Close listen Socket : 
08-31 11:15:54.144  4243  4243 V BluetoothSapService: Close rfcomm Socket : 
08-31 11:15:54.145  4243  4243 V BluetoothSapService: Close sapd  Socket : 
08-31 11:15:54.151  4243  4243 V BluetoothSapService: Sap Service closeSapService out
08-31 11:15:54.151  4243  4243 V BluetoothSapService: Sap Service onDestroy
08-31 11:15:54.151  4243  4243 V BluetoothSapService: Sap Service closeSapService in
08-31 11:15:54.151  4243  4243 V BluetoothSapService: Close listen Socket : 
08-31 11:15:54.151  4243  4243 V BluetoothSapService: Close rfcomm Socket : 
08-31 11:15:54.151  4243  4243 V BluetoothSapService: Close sapd  Socket : 
,08-31 11:15:54.192  1081  2037 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6999 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 11:15:54.193  4243  4243 V BluetoothSapService: Sap Service closeSapService out
08-31 11:15:54.220  6982  6982 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 11:15:54.250  6982  6982 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-31 11:15:54.253  6999  6999 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:15:54.270  1081  1105 I ActivityManager: Killing 6470:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-31 11:15:54.299  6982  6982 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-31 11:15:54.300  6982  6982 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-31 11:15:54.300  6982  6982 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-31 11:15:54.301  6982  6982 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-31 11:15:54.301  6982  6982 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-31 11:15:54.303  6982  6982 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-31 11:15:54.309  6982  6982 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-31 11:15:54.321  1081  2060 W libprocessgroup: failed to open /acct/uid_10011/pid_6470/cgroup.procs: No such file or directory
,08-31 11:15:54.331  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:15:54.334  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:15:54.353  6982  6982 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 11:15:54.357  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:15:54.360  6982  6982 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-31 11:15:54.364  6982  6982 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-31 11:15:54.365  6950  6950 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:15:54.365  6950  6950 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:15:54.366  6950  6950 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:15:54.372  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:15:54.380  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:15:54.388  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:15:54.388  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:15:54.391  6982  6982 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 11:15:54.395  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:15:54.399  6950  6950 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:15:54.399  6950  6950 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-31 11:15:54.399  6950  6950 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:15:54.404  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:15:54.411  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:15:54.422  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:15:54.423  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:15:54.425  6982  6982 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:15:54.481  6840  6876 D serial_port: close(fd = 25)
,08-31 11:15:54.485  6840  6879 D UEI.SmartControl: Internal timer expired: 1
08-31 11:15:54.486  6840  6879 D UEI.SmartControl: unbind internal service
08-31 11:15:54.489  1081  2010 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7019 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-31 11:15:54.494  6840  6840 D UEI.SmartControl: Service.onUnbind: IControl
08-31 11:15:54.494  6840  6840 D UEI.SmartControl: Service.onDestroy
08-31 11:15:54.495  6840  6840 D UEI.SmartControl: Lock is in USE false
08-31 11:15:54.495  6840  6840 D UEI.SmartControl: unbind internal service
08-31 11:15:54.495  6840  6840 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2ed175b5
08-31 11:15:54.495  6840  6840 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-31 11:15:54.495  6840  6840 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-31 11:15:54.495  6840  6840 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-31 11:15:54.496  6840  6840 W System.err: 	at com.uei.control.Service.c(Unknown Source)
,08-31 11:15:54.496  6840  6840 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-31 11:15:54.496  6840  6840 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-31 11:15:54.496  6840  6840 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-31 11:15:54.496  6840  6840 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-31 11:15:54.496  6840  6840 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:15:54.496  6840  6840 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:15:54.496  6840  6840 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:15:54.496  6840  6840 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:15:54.496  6840  6840 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:15:54.496  6840  6840 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:15:54.496  6840  6840 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:15:54.496  6840  6840 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2ed175b5
08-31 11:15:54.498  6840  6876 I UEI.SmartControl: Serial port is closed.
08-31 11:15:54.499  6840  6840 I UEI.SmartControl: Serial port is closed.
08-31 11:15:54.502  6840  6840 I UEI.SmartControl: Serial port is closed.
08-31 11:15:54.502  6840  6840 D UEI.SmartControl: Blaster closed
08-31 11:15:54.502  6840  6840 D UEI.SmartControl: Shut down QS...
08-31 11:15:54.503  6840  6840 D UEI.SmartControl: Stopping QS lib
08-31 11:15:54.504  6840  6840 D UEI.SmartControl: QS lib stop result = true
08-31 11:15:54.504  6840  6840 D UEI.SmartControl: Stopped QS lib
08-31 11:15:54.505  6840  6840 D UEI.SmartControl: Stopped file observer...
08-31 11:15:54.505  6840  6840 D UEI.SmartControl: QS shutdown complete
,08-31 11:15:54.552  4243  4468 W bt-btif : ag scb idx 1 not allocated
08-31 11:15:54.552  4243  4468 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:15:54.552  4243  4350 D bt_hci_bdroid: cleanup
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:15:54.553  4243  4468 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:15:54.553  4243  4468 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 11:15:54.553  4243  4470 I bt_lpm  : LPM is already off!!!
08-31 11:15:54.553  4243  4593 I bt_userial_mct: exiting userial_read_thread
08-31 11:15:54.553  4243  4593 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 11:15:54.554  4243  4350 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 11:15:54.554  4243  4470 I bt_vendor: hw_epilog_process
,08-31 11:15:54.555  4243  4350 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 11:15:54.555  4243  4350 D bt_userial_mct: userial_close
08-31 11:15:54.555  4243  4350 E bt_userial_mct: pthread_join() FAILED result:3
08-31 11:15:54.555  4243  4350 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-31 11:15:54.584  6950  6950 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:15:54.589  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:15:54.602  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:15:54.609  4243  4350 D bt_hci_bdroid: set_power 0
08-31 11:15:54.609  4243  4350 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 11:15:54.609  4243  4350 I bt_vendor: bluetooth satus is on
08-31 11:15:54.609  4243  4350 I bt_vendor: bt-vendor : resetting BT status
08-31 11:15:54.609  4243  4350 I bt_vendor: Starting hciattach daemon
08-31 11:15:54.609  4243  4350 I bt_vendor: try to set false
,08-31 11:15:54.615  4243  4350 I bt_vendor: Starting hciattach daemon
08-31 11:15:54.615  4243  4350 I bt_vendor: try to set false
08-31 11:15:54.617  4243  4350 I bt_vendor: cleanup
08-31 11:15:54.618  4243  4468 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 11:15:54.618  4243  4350 I GKI_LINUX: GKI_exit_task 0 done
08-31 11:15:54.619  4243  4350 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-31 11:15:54.622  4243  4345 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 11:15:54.625  4243  4243 D HeadsetService: Received stop request...Stopping profile...
,08-31 11:15:54.627  4243  4243 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 11:15:54.627  4243  4243 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:15:54.627  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31ad723e
08-31 11:15:54.628  4243  4384 D HeadsetStateMachine: Exit Disconnected: -1
08-31 11:15:54.628  1081  1081 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
08-31 11:15:54.630  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-31 11:15:54.630  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-31 11:15:54.631  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-31 11:15:54.632  1081  1081 D BluetoothHeadset: Proxy object disconnected
08-31 11:15:54.632  1081  1081 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 11:15:54.632  4243  4243 D A2dpService: Received stop request...Stopping profile...
08-31 11:15:54.632  4243  4433 D A2dpStateMachine: Exit Disconnected: -1
08-31 11:15:54.633  4243  4243 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-31 11:15:54.637  4243  4243 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 11:15:54.637  4243  4243 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:15:54.637  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31ad723e
08-31 11:15:54.638  4243  4345 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 11:15:54.639  1081  1081 D BluetoothA2dp: Proxy object disconnected
08-31 11:15:54.639  1081  1081 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-31 11:15:54.639  4243  4243 D HidService: Received stop request...Stopping profile...
,08-31 11:15:54.640  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31ad723e
,08-31 11:15:54.641  4243  4243 D HealthService: Received stop request...Stopping profile...
08-31 11:15:54.642  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31ad723e
08-31 11:15:54.643  4243  4243 D HeadsetStateMachine: Unbinding service...
08-31 11:15:54.643  6909  6909 D BluetoothInputDevice: Proxy object disconnected
08-31 11:15:54.644  6909  6909 D HidProfile: Bluetooth service disconnected
,08-31 11:15:54.644  4243  4243 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:15:54.644  4243  4243 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:15:54.644  4243  4243 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:15:54.644  4243  4243 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:15:54.644  4243  4243 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 11:15:54.644  4243  4243 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:15:54.645  4243  4243 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 11:15:54.645  4243  4243 D PanService: Received stop request...Stopping profile...
08-31 11:15:54.646  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31ad723e
08-31 11:15:54.647  4243  4243 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:15:54.647  4243  4243 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 11:15:54.647  4243  4243 D BtGatt.GattService: stop()
08-31 11:15:54.647  4243  4243 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 11:15:54.647  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:15:54.648  6909  6909 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:15:54.648  6909  6909 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:15:54.648  6909  6909 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 11:15:54.649  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31ad723e
08-31 11:15:54.649  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 11:15:54.650  4243  4243 D BluetoothMapService: Received stop request...Stopping profile...
08-31 11:15:54.650  4243  4243 D BluetoothMapService: stop()
08-31 11:15:54.650  4243  4243 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 11:15:54.651  4243  4243 D BluetoothMapEmailAppObserver: removeReceiver()
08-31 11:15:54.650  7019  7039 W FormManager: Network not available. Please check & try again.
08-31 11:15:54.651  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31ad723e
08-31 11:15:54.652  4243  4243 I BluetoothA2dpServiceJni: cleanupNative
08-31 11:15:54.653  4243  4434 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-31 11:15:54.653  4243  4243 I GKI_LINUX: GKI_exit_task 2 done
08-31 11:15:54.653  4243  4243 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 11:15:54.654  4243  4243 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:15:54.654  4243  4243 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 11:15:54.654  4243  4243 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:15:54.654  4243  4243 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:15:54.654  4243  4243 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:15:54.655  4243  4243 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:15:54.655  4243  4243 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 11:15:54.656  4243  4243 V BluetoothMapService: Handler(): got msg=4
08-31 11:15:54.656  4243  4243 D BluetoothMapService: MAP Service closeService in
08-31 11:15:54.656  4243  4243 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:15:54.656  4243  4243 V BluetoothMapService: MAP Service closeService out
08-31 11:15:54.656  4243  4243 D BluetoothMapService: cleanup()
08-31 11:15:54.656  4243  4243 D BluetoothMapService: MAP Service closeService in
08-31 11:15:54.656  4243  4243 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:15:54.657  4243  4243 V BluetoothMapService: MAP Service closeService out
08-31 11:15:54.657  4243  4345 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 11:15:54.657  4243  4345 D BluetoothAdapterProperties: Setting state to 10
08-31 11:15:54.657  4243  4345 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 11:15:54.657  1081  1176 D BluetoothManagerService: Message: 60
08-31 11:15:54.657  1081  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 11:15:54.657  4243  4345 I BluetoothAdapterState: Entering OffState
08-31 11:15:54.657  1081  1176 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-31 11:15:54.658  1862  4407 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:15:54.659  6909  6928 D BluetoothPan: onBluetoothStateChange on: false
08-31 11:15:54.659  6909  6927 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 11:15:54.660  1081  1176 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:15:54.660  6909  6928 D BluetoothMap: onBluetoothStateChange: up=false
08-31 11:15:54.661  1081  1176 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:15:54.661  6909  6927 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 11:15:54.661  1862  1878 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:15:54.662  1862  4854 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:15:54.663  1081  1176 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 11:15:54.663  1081  1176 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-31 11:15:54.666  1081  1176 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
,08-31 11:15:54.666  1081  1176 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 11:15:54.666  6909  6909 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:15:54.666  1081  1176 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@34d58af5 mBinding = false
08-31 11:15:54.666  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 11:15:54.666  1081  1176 D BluetoothManagerService: Sending unbind request.
08-31 11:15:54.666  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:15:54.667  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 11:15:54.667  6909  6909 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:15:54.667  6909  6909 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:15:54.667  1081  1176 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-31 11:15:54.670  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:15:54.671  1951  2129 D LGBluetoothAPIService: Message: 2
08-31 11:15:54.671  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:15:54.672  1951  2129 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@38f3c109 mBinding = false
08-31 11:15:54.672  1951  2129 D LGBluetoothAPIService: Sending unbind request.
08-31 11:15:54.673  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:54.675  6909  6909 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 11:15:54.675  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:54.675  6909  6909 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-31 11:15:54.675  6909  6909 D LGBluetoothEventManager: [BTUI] clear device connection state
08-31 11:15:54.677  1585  1585 D BluetoothAdapter: 21309784: getState() :  mService = null. Returning STATE_OFF
08-31 11:15:54.677  1585  1585 D BluetoothAdapter: 21309784: getState() :  mService = null. Returning STATE_OFF
,08-31 11:15:54.684  4243  4350 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-31 11:15:54.685  4243  4243 I GKI_LINUX: GKI_exit_task 1 done
08-31 11:15:54.685  4243  4243 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 11:15:54.685  4243  4243 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 11:15:54.685  4243  4243 I art     : --- WEIRD: removing null entry 246
08-31 11:15:54.685  4243  4243 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-31 11:15:54.685  4243  4243 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 11:15:54.685  6909  6909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 11:15:54.686  4243  4243 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-31 11:15:54.687  7019  7040 V FormManager: Network unavailable.
08-31 11:15:54.688  4243  4243 I art     : System.exit called, status: 0
08-31 11:15:54.688  4243  4243 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 11:15:54.695  7019  7040 V FormManager: Network unavailable.
08-31 11:15:54.697  6909  6909 D DockEventReceiver: finishStartingService: stopping service
08-31 11:15:54.698  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:15:54.698  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-31 11:15:54.700  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:15:54.705  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:15:54.713   323   323 V AudioFlinger: 4243 died, releasing its sessions
08-31 11:15:54.713   323   323 V AudioFlinger:  pid 1862 @ 0
08-31 11:15:54.713   323   323 V AudioFlinger:  pid 3333 @ 1
08-31 11:15:54.713   323   323 V AudioFlinger:  pid 3333 @ 2
08-31 11:15:54.714  6909  6909 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-31 11:15:54.714  6950  6950 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-31 11:15:54.714  6950  6950 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:15:54.714  6950  6950 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:15:54.721  4764  7051 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:15:54.723  4764  7051 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:15:54.726  4764  7049 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 11:15:54.749  1081  1896 I ActivityManager: Process com.android.bluetooth (pid 4243) has died
,08-31 11:15:54.749  1081  1896 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-31 11:15:54.756  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:15:54.758  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:15:54.767  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:15:54.782  6909  6909 D BluetoothPermissionRequest: onReceive
,08-31 11:15:54.785  7019  7054 W FormManager: Network not available. Please check & try again.
08-31 11:15:54.787  6909  6909 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 11:15:54.787  6909  6909 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-31 11:15:54.792  7019  7055 V FormManager: Network unavailable.
08-31 11:15:54.793  6909  6909 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:15:54.866  1081  1558 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7056 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-31 11:15:54.869  1081  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1ccdfc8d type 2 when 117850 com.google.android.gms} when 117850
08-31 11:15:54.878  7019  7055 V FormManager: Network unavailable.
,08-31 11:15:54.895  1081  2060 I ActivityManager: Killing 6491:com.android.contacts/u0a19 (adj 15): empty #17
,08-31 11:15:54.905   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 467us total 34.799ms
08-31 11:15:54.910  6982  6982 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 11:15:54.912  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 11:15:54.912  6982  6982 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-31 11:15:54.926   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 443us total 20.379ms
08-31 11:15:54.947   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 19.906ms
,08-31 11:15:54.951  6982  6982 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:15:54.951  6982  6982 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:15:54.958  6982  6982 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-31 11:15:54.959  6982  6982 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-31 11:15:54.959  6982  6982 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-31 11:15:54.959  6982  6982 V SoundPool: doLoad: loading sample sampleID=1
,08-31 11:15:54.960  6982  6982 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 11:15:54.961  6982  7075 V SoundPool: Start decode
08-31 11:15:54.961  6982  7075 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-31 11:15:54.962   323  1383 V MediaPlayerService: decode(23, 10857164, 17813)
08-31 11:15:54.962   323  1383 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-31 11:15:54.962   323  1383 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-31 11:15:54.962   323  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-31 11:15:54.962   323  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-31 11:15:54.962   323  1383 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-31 11:15:54.962   323  1383 V MediaPlayerService: player type = 3
08-31 11:15:54.962   323  1383 V AwesomePlayer: AwesomePlayer create()
08-31 11:15:54.963   323  1383 V AwesomePlayer: reset_l() 
08-31 11:15:54.963   323  1383 V AwesomePlayer: cancelPlayerEvents
08-31 11:15:54.963   323  1383 V AwesomePlayer: setAudioSink() 
08-31 11:15:54.963   323  1383 V AwesomePlayer: reset_l() 
08-31 11:15:54.963   323  1383 V AudioCache: notify(0xb5474700, 8, 0, 0)
08-31 11:15:54.963   323  1383 V AudioCache: ignored
08-31 11:15:54.963   323  1383 V AwesomePlayer: cancelPlayerEvents
08-31 11:15:54.963   323  1383 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-31 11:15:54.963   323  1383 V AwesomePlayer: setDataSource_l dataSource
08-31 11:15:54.963   323  1383 V LGParserOSAL: SniffLGParser start
08-31 11:15:54.963   323  1383 V LGParserOSAL: MainType:5, SubType=0
08-31 11:15:54.963   323  1383 V LGParserOSAL: #### check Mime : application/ogg
08-31 11:15:54.963   323  1383 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-31 11:15:54.963   323  1383 E MediaExtractor: Use LGExtractor :application/ogg 
08-31 11:15:54.982  1081  2310 W libprocessgroup: failed to open /acct/uid_10019/pid_6491/cgroup.procs: No such file or directory
,08-31 11:15:54.992  6840  6840 D UEI.SmartControl: QS Service created
08-31 11:15:54.992  6982  6982 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-31 11:15:54.994  6982  6982 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 11:15:54.995  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-31 11:15:55.009  6840  6840 I UEI.SmartControl: Service initServices...
08-31 11:15:55.010  6840  6840 D UEI.SmartControl: QS start get config
08-31 11:15:55.013  6982  6982 V LGMDMManager: Create singleton instance
08-31 11:15:55.013  7056  7056 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-31 11:15:55.014  7056  7056 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:15:55.014  7056  7056 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 11:15:55.015   323  1383 V LGParserOSAL: supported mime: application/ogg
08-31 11:15:55.015  7056  7056 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 11:15:55.015   323  1383 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-31 11:15:55.015   323  1383 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
,08-31 11:15:55.015   323  1383 V AwesomePlayer: mBitrate = -1 bits/sec
08-31 11:15:55.015   323  1383 V AwesomePlayer: AudioTrack Setting
08-31 11:15:55.015   323  1383 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-31 11:15:55.015   323  1383 V AwesomePlayer: setAudioSource() 
08-31 11:15:55.015   323  1383 V MediaPlayerService: prepare
08-31 11:15:55.015   323  1383 V AwesomePlayer: prepareAsync_l() 
08-31 11:15:55.015   323  1383 V MediaPlayerService: wait for prepare
08-31 11:15:55.015   323  7076 V AwesomePlayer: onPrepareAsyncEvent() 
08-31 11:15:55.015   323  7076 V AwesomePlayer: initAudioDecoder() 
08-31 11:15:55.015   323  7076 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 11:15:55.015   323  7076 V AudioSystem: isOffloadSupported()
08-31 11:15:55.015   323  7076 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 11:15:55.015   323  7076 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 11:15:55.015   323  7076 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 11:15:55.015   323  7076 V AwesomePlayer: getUseOffload() = 0 
08-31 11:15:55.015   323  7076 V OMXCodec: OMXCodec::Create
08-31 11:15:55.015   323  7076 V OMXCodec: findMatchingCodecs()
08-31 11:15:55.016   323  7076 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-31 11:15:55.016   323  7076 V OMXCodec: matchingCodecs.size()=1
08-31 11:15:55.016   323  7076 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-31 11:15:55.018   323  7076 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-31 11:15:55.019   323  7076 V LGCodecAdapter: LG Codec Adapter start
08-31 11:15:55.019   323  7076 V OMXCodec: OMXCodec Createtor
08-31 11:15:55.019   323  7076 V OMXCodec: setComponentRole
08-31 11:15:55.019   323  7076 V OMXCodec: configureCodec protected=0
08-31 11:15:55.019   323  7076 V LGCodecAdapter: called getLGCodecSpecificData
08-31 11:15:55.019   323  7076 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-31 11:15:55.019   323  7076 V LGCodecOSAL: Called LGconfigureCodecMETA
08-31 11:15:55.019   323  7076 V LGCodecOSAL: Called LGconfigureCodecMSG
08-31 11:15:55.019   323  7076 V LGCodecOSAL: Not support LGCodec
08-31 11:15:55.019   323  7076 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 11:15:55.019   323  7076 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-31 11:15:55.019   323  7076 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-31 11:15:55.019   323  7076 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-31 11:15:55.019   323  7076 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 11:15:55.019   323  7076 V AudioSystem: isOffloadSupported()
08-31 11:15:55.019   323  7076 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 11:15:55.019   323  7076 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 11:15:55.019   323  7076 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-31 11:15:55.019   323  7076 V OMXCodec: init()
08-31 11:15:55.019   323  7076 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-31 11:15:55.019   323  7076 V OMXCodec: allocateBuffers
08-31 11:15:55.019   323  7076 V OMXCodec: allocateBuffersOnPort portIndex=0
08-31 11:15:55.019   323  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on, input port
08-31 11:15:55.020   323  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on input port
08-31 11:15:55.020   323  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
08-31 11:15:55.020   323  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b81f0 on input port
08-31 11:15:55.020   323  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8240 on input port
08-31 11:15:55.020   323  7076 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 11:15:55.020   323  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 11:15:55.020   323  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b88d0 on output port
08-31 11:15:55.020   323  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8970 on output port
08-31 11:15:55.020   323  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b89c0 on output port
08-31 11:15:55.020   323  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8d30 on output port
08-31 11:15:55.020   323  7076 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 11:15:55.029   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 11:15:55.029   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 11:15:55.029   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-31 11:15:55.029   323  7076 V OMXCodec: init() mAsyncCompletion wait!!! 
,08-31 11:15:55.029   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-31 11:15:55.029   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-31 11:15:55.029   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-31 11:15:55.029   323  7076 V OMXCodec: init() mAsyncCompletion wait free! 
,08-31 11:15:55.029   323  7076 V AwesomePlayer: finishAsyncPrepare_l() 
08-31 11:15:55.029   323  7076 V AudioCache: notify(0xb5474700, 5, 0, 0)
08-31 11:15:55.029   323  7076 V AudioCache: ignored
08-31 11:15:55.029   323  7076 V AudioCache: notify(0xb5474700, 1, 0, 0)
08-31 11:15:55.029   323  7076 V AudioCache: prepared
08-31 11:15:55.029   323  1383 V AudioCache: wait - success
08-31 11:15:55.029   323  1383 V MediaPlayerService: start
08-31 11:15:55.030   323  1383 V AwesomePlayer: play_l() 
08-31 11:15:55.030   323  1383 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-31 11:15:55.030   323  1383 V AwesomePlayer: createAudioPlayer_l
08-31 11:15:55.030   323  1383 V AwesomePlayer: seekAudioIfNecessary_l() 
08-31 11:15:55.030   323  1383 V AwesomePlayer: startAudioPlayer_l() 
08-31 11:15:55.030   323  1383 D AudioPlayer: start of Playback, useOffload 0
08-31 11:15:55.030   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 11:15:55.030   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 11:15:55.032   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-31 11:15:55.032   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-31 11:15:55.032   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-31 11:15:55.032   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-31 11:15:55.032   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-31 11:15:55.032   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517456
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517616
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517696
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974518576
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-31 11:15:55.033   323  7078 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b89c0 on output port
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8970 on output port
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b88d0 on output port
08-31 11:15:55.033   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-31 11:15:55.034   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-31 11:15:55.034   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-31 11:15:55.035   323  1383 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-31 11:15:55.035   323,  1383 V AudioCache: notify(0xb5474700, 6, 0, 0)
08-31 11:15:55.035   323  1383 V AudioCache: ignored
08-31 11:15:55.035   323  1383 V MediaPlayerService: wait for playback complete
08-31 11:15:55.036   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.036   323  7079 V AudioCache: memcpy(0xac200000, 0xb57f4000, 4096)
08-31 11:15:55.037   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.037   323  7079 V AudioCache: memcpy(0xac201000, 0xb57f4000, 4096)
08-31 11:15:55.037   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.037   323  7079 V AudioCache: memcpy(0xac202000, 0xb57f4000, 4096)
08-31 11:15:55.038   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.038   323  7079 V AudioCache: memcpy(0xac203000, 0xb57f4000, 4096)
08-31 11:15:55.039   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.039   323  7079 V AudioCache: memcpy(0xac204000, 0xb57f4000, 4096)
08-31 11:15:55.039   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.039   323  7079 V AudioCache: memcpy(0xac205000, 0xb57f4000, 4096)
08-31 11:15:55.040   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.040   323  7079 V AudioCache: memcpy(0xac206000, 0xb57f4000, 4096)
08-31 11:15:55.041   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.041   323  7079 V AudioCache: memcpy(0xac207000, 0xb57f4000, 4096)
08-31 11:15:55.041   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.042   323  7079 V AudioCache: memcpy(0xac208000, 0xb57f4000, 4096)
08-31 11:15:55.042  7056  7056 D BluetoothAdapterApp: Loading JNI Library
08-31 11:15:55.042   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.042   323  7079 V AudioCache: memcpy(0xac209000, 0xb57f4000, 4096)
,08-31 11:15:55.043   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.043   323  7079 V AudioCache: memcpy(0xac20a000, 0xb57f4000, 4096)
08-31 11:15:55.044   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.044   323  7079 V AudioCache: memcpy(0xac20b000, 0xb57f4000, 4096)
08-31 11:15:55.044   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.044   323  7079 V AudioCache: memcpy(0xac20c000, 0xb57f4000, 4096)
08-31 11:15:55.045   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.045   323  7079 V AudioCache: memcpy(0xac20d000, 0xb57f4000, 4096)
08-31 11:15:55.046   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.046   323  7079 V AudioCache: memcpy(0xac20e000, 0xb57f4000, 4096)
,08-31 11:15:55.046   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.046   323  7079 V AudioCache: memcpy(0xac20f000, 0xb57f4000, 4096)
08-31 11:15:55.047   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.047   323  7079 V AudioCache: memcpy(0xac210000, 0xb57f4000, 4096)
08-31 11:15:55.047   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.047   323  7079 V AudioCache: memcpy(0xac211000, 0xb57f4000, 4096)
08-31 11:15:55.048   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.048   323  7079 V AudioCache: memcpy(0xac212000, 0xb57f4000, 4096)
08-31 11:15:55.049   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.049   323  7079 V AudioCache: memcpy(0xac213000, 0xb57f4000, 4096)
08-31 11:15:55.049   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.049   323  7079 V AudioCache: memcpy(0xac214000, 0xb57f4000, 4096)
08-31 11:15:55.050   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.050   323  7079 V AudioCache: memcpy(0xac215000, 0xb57f4000, 4096)
08-31 11:15:55.051   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.051   323  7079 V AudioCache: memcpy(0xac216000, 0xb57f4000, 4096)
08-31 11:15:55.051   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.051   323  7079 V AudioCache: memcpy(0xac217000, 0xb57f4000, 4096)
08-31 11:15:55.052   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.052   323  7079 V AudioCache: memcpy(0xac218000, 0xb57f4000, 4096)
08-31 11:15:55.052   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.052   323  7079 V AudioCache: memcpy(0xac219000, 0xb57f4000, 4096)
08-31 11:15:55.053   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.053   323  7079 V AudioCache: memcpy(0xac21a000, 0xb57f4000, 4096)
08-31 11:15:55.054   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.054   323  7079 V AudioCache: memcpy(0xac21b000, 0xb57f4000, 4096)
08-31 11:15:55.054   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.054   323  7079 V AudioCache: memcpy(0xac21c000, 0xb57f4000, 4096)
08-31 11:15:55.055   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.055   323  7079 V AudioCache: memcpy(0xac21d000, 0xb57f4000, 4096)
08-31 11:15:55.055   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.055   323  7079 V AudioCache: memcpy(0xac21e000, 0xb57f4000, 4096)
08-31 11:15:55.056   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.056   323  7079 V AudioCache: memcpy(0xac21f000, 0xb57f4000, 4096)
08-31 11:15:55.056   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.056   323  7079 V AudioCache: memcpy(0xac220000, 0xb57f4000, 4096)
08-31 11:15:55.057   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.057   323  7079 V AudioCache: memcpy(0xac221000, 0xb57f4000, 4096)
08-31 11:15:55.058   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.058   323  7079 V AudioCache: memcpy(0xac222000, 0xb57f4000, 4096)
08-31 11:15:55.058   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.058   323  7079 V AudioCache: memcpy(0xac223000, 0xb57f4000, 4096)
08-31 11:15:55.059   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.059   323  7079 V AudioCache: memcpy(0xac224000, 0xb57f4000, 4096)
08-31 11:15:55.059   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.059   323  7079 V AudioCache: memcpy(0xac225000, 0xb57f4000, 4096)
08-31 11:15:55.060   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.060   323  7079 V AudioCache: memcpy(0xac226000, 0xb57f4000, 4096)
08-31 11:15:55.060   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.061   323  7079 V AudioCache: memcpy(0xac227000, 0xb57f4000, 4096)
08-31 11:15:55.061   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.061   323  7079 V AudioCache: memcpy(0xac228000, 0xb57f4000, 4096)
08-31 11:15:55.062   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.062   323  7079 V AudioCache: mem,cpy(0xac229000, 0xb57f4000, 4096)
08-31 11:15:55.062   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.062   323  7079 V AudioCache: memcpy(0xac22a000, 0xb57f4000, 4096)
08-31 11:15:55.063   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.063   323  7079 V AudioCache: memcpy(0xac22b000, 0xb57f4000, 4096)
08-31 11:15:55.063   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.063   323  7079 V AudioCache: memcpy(0xac22c000, 0xb57f4000, 4096)
08-31 11:15:55.064   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.064   323  7079 V AudioCache: memcpy(0xac22d000, 0xb57f4000, 4096)
08-31 11:15:55.064   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.064   323  7079 V AudioCache: memcpy(0xac22e000, 0xb57f4000, 4096)
08-31 11:15:55.065   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.065   323  7079 V AudioCache: memcpy(0xac22f000, 0xb57f4000, 4096)
08-31 11:15:55.065   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.065   323  7079 V AudioCache: memcpy(0xac230000, 0xb57f4000, 4096)
08-31 11:15:55.066   323  7079 V AudioCache: write(0xb57f4000, 4096)
08-31 11:15:55.066   323  7079 V AudioCache: memcpy(0xac231000, 0xb57f4000, 4096)
08-31 11:15:55.066   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-31 11:15:55.066   323  7079 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 11:15:55.066   323  7079 V AwesomePlayer: postAudioEOS() 
08-31 11:15:55.066   323  7079 V AudioCache: write(0xb57f4000, 280)
08-31 11:15:55.066   323  7079 V AudioCache: memcpy(0xac232000, 0xb57f4000, 280)
08-31 11:15:55.069   323  7076 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-31 11:15:55.069   323  7076 V AwesomePlayer: onStreamDone
08-31 11:15:55.069   323  7076 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-31 11:15:55.069   323  7076 V AudioCache: notify(0xb5474700, 2, 0, 0)
08-31 11:15:55.069   323  7076 V AudioCache: playback complete
08-31 11:15:55.069   323  7076 V AwesomePlayer: pause_l() 
08-31 11:15:55.069   323  7076 V AudioCache: notify(0xb5474700, 7, 0, 0)
08-31 11:15:55.069   323  7076 V AudioCache: ignored
08-31 11:15:55.069   323  7076 V AwesomePlayer: cancelPlayerEvents
08-31 11:15:55.069   323  1383 V AudioCache: wait - success
08-31 11:15:55.069   323  1383 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-31 11:15:55.069   323  7076 D AudioPlayer: Pause Playback at 1068125
08-31 11:15:55.069   323  1383 V AwesomePlayer: reset_l() 
08-31 11:15:55.069   323  1383 V AudioCache: notify(0xb5474700, 8, 0, 0)
08-31 11:15:55.069   323  1383 V AudioCache: ignored
08-31 11:15:55.069   323  1383 V AwesomePlayer: cancelPlayerEvents
08-31 11:15:55.070   323  1383 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-31 11:15:55.070   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-31 11:15:55.070   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-31 11:15:55.070   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-31 11:15:55.070   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
,08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8240 on port 0
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b81f0 on port 0
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1,
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 0
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b88d0 on port 1
,08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8970 on port 1
08-31 11:15:55.070   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-31 11:15:55.071   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b89c0 on port 1
08-31 11:15:55.071   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:15:55.071   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-31 11:15:55.071   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 11:15:55.071   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 11:15:55.071   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-31 11:15:55.071   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-31 11:15:55.071   323  7078 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-31 11:15:55.071   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 11:15:55.071   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-31 11:15:55.071   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-31 11:15:55.072   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-31 11:15:55.072   323  1383 D AudioPlayer: AudioPlayer releasing audio source
08-31 11:15:55.072   323  1383 D AudioPlayer: AudioPlayer done releasing audio source
08-31 11:15:55.072   323  1383 V AwesomePlayer: reset_l() 
08-31 11:15:55.072   323  1383 V AwesomePlayer: cancelPlayerEvents
08-31 11:15:55.072   323  1383 V AwesomePlayer: ~AwesomePlayer call
08-31 11:15:55.073   323  1383 V AwesomePlayer: reset_l() 
08-31 11:15:55.073   323  1383 V AwesomePlayer: cancelPlayerEvents
08-31 11:15:55.073  6982  7075 V SoundPool: close(31)
08-31 11:15:55.073  6982  7075 V SoundPool: pointer = 0xa0018000, size = 205080, sampleRate = 48000, numChannels = 2
08-31 11:15:55.076  7056  7056 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1a5dfba7 Instance Count = 1
08-31 11:15:55.082  7056  7056 D BluetoothAdapterApp: onCreate
08-31 11:15:55.097  7056  7056 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-31 11:15:55.097  7056  7056 D ProfileConfigQcom: Adding HeadsetService
08-31 11:15:55.097  7056  7056 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 11:15:55.098  7056  7056 D ProfileConfigQcom: Adding A2dpService
08-31 11:15:55.098  7056  7056 D ProfileConfigQcom: [BTUI] HidService is supported
08-31 11:15:55.098  7056  7056 D ProfileConfigQcom: Adding HidService
08-31 11:15:55.098  7056  7056 D ProfileConfigQcom: [BTUI] HealthService is supported
08-31 11:15:55.098  7056  7056 D ProfileConfigQcom: Adding HealthService
08-31 11:15:55.098  7056  7056 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-31 11:15:55.099  7056  7056 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 11:15:55.100  7056  7056 D ProfileConfigQcom: Adding PanService
08-31 11:15:55.100  7056  7056 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 11:15:55.100  7056  7056 D ProfileConfigQcom: Adding GattService
08-31 11:15:55.100  7056  7056 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 11:15:55.100  7056  7056 D ProfileConfigQcom: Adding BluetoothMapService
08-31 11:15:55.100  7056  7056 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 11:15:55.102  7056  7056 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-31 11:15:55.106  6909  6909 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 11:15:55.107  7056  7056 V LGMDMManagerInternal: Create singleton instance
08-31 11:15:55.110  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-31 11:15:55.111  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-31 11:15:55.113  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1909
08-31 11:15:55.118   318  7083 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 11:15:55.118  1081  1174 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 11:15:55.138  4922  7082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-31 11:15:55.156  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:15:55.159  7056  7056 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-31 11:15:55.159  7056  7056 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:15:55.159  7056  7056 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:15:55.160  7056  7056 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:15:55.160  7056  7056 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-31 11:15:55.165  6999  6999 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-31 11:15:55.437  6840  6840 I UEI.SmartControl: Supports setup maps: true
,08-31 11:15:55.444  6840  6840 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 11:15:55.444  6840  6840 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 11:15:55.444  6840  6840 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 11:15:55.444  6840  6840 I UEI.SmartControl: ### init IR Blaster...
08-31 11:15:55.447  6840  6840 D serial_port: Configuring serial port
08-31 11:15:55.447  6840  6840 E UEI.SmartControl: UEIBLaster setting for 616
08-31 11:15:55.447  6840  6840 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 11:15:55.448  6840  6840 I UEI.SmartControl: configuring settings for MAXQ616
08-31 11:15:55.448  6840  6840 I UEI.SmartControl: Get version...
08-31 11:15:55.465  6840  7093 D UEI.SmartControl: serial port data available: 21
,08-31 11:15:55.491  6840  6840 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-31 11:15:55.491  6840  6840 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 11:15:55.491  6840  6840 I UEI.SmartControl: QS saving settings...
,08-31 11:15:55.492  6840  6840 D UEI.SmartControl: IR Blaster version: 25672567
08-31 11:15:55.508  6840  7093 D UEI.SmartControl: serial port data available: 4
,08-31 11:15:55.540  6840  6840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-31 11:15:55.546  6840  6840 E UEI.SmartControl: Services init done
,08-31 11:15:55.546  6840  6840 D UEI.SmartControl: QS Service init finished
08-31 11:15:55.547  6840  7102 I UEI.SmartControl: Device manager: loading config....
08-31 11:15:55.548  6840  6840 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 11:15:55.548  6840  6840 D UEI.SmartControl: QS Service version code: 201091
08-31 11:15:55.548  6840  7102 D UEI.SmartControl: ----------- loading internal config...
08-31 11:15:55.548  6840  6840 D UEI.SmartControl: Service requested: Control
08-31 11:15:55.557  6840  7102 E UEI.SmartControl: Loading SETTINGS...
,08-31 11:15:55.563  6840  6840 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 11:15:55.566  6840  6840 D UEI.SmartControl: Internal service binding...
08-31 11:15:55.566  6982  6982 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-31 11:15:55.567  6840  6856 I UEI.SmartControl: ------ IControl API: 11
08-31 11:15:55.567  6840  6856 D UEI.SmartControl: File observer start...
08-31 11:15:55.568  6840  6856 E UEI.SmartControl: IR Port is disabled: false
08-31 11:15:55.568  6840  6856 D UEI.SmartControl: Starting file observer...
08-31 11:15:55.570  6840  6856 I UEI.SmartControl: Registering callback...
08-31 11:15:55.570  6840  7102 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 11:15:55.571  6840  6855 I UEI.SmartControl: ------ IControl API: 19
08-31 11:15:55.572  6840  6855 I UEI.SmartControl: Registering Services Ready callback...
08-31 11:15:55.577  6840  7101 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 11:15:55.577  6840  7101 D UEI.SmartControl: -----service ready thread exits
08-31 11:15:55.577  6982  6997 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-31 11:15:55.578  6982  7073 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-31 11:15:55.578  6982  7073 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-31 11:15:55.579  6982  6982 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
,08-31 11:15:55.579  6982  6982 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-31 11:15:55.580  6840  6856 I UEI.SmartControl: ------ IControl API: 8
08-31 11:15:55.582  6982  6982 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-31 11:15:55.583  6982  6982 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-31 11:15:55.583  6982  6982 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-31 11:15:55.583  6982  6982 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-31 11:15:55.584  6982  6982 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-31 11:15:55.585  6982  6982 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-31 11:15:55.586  6982  6982 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-31 11:15:55.590  6982  6982 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 11:15:55.591  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 11:15:55.593  6982  6982 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 11:15:55.593  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 11:15:55.595  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 11:15:55.596  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-31 11:15:55.597  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-31 11:15:55.598  6982  6982 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472634955597]
08-31 11:15:55.600  6982  6982 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-31 11:15:55.603  1081  1104 I ActivityManager: Killing 6548:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-31 11:15:55.626  6982  7104 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-31 11:15:55.639  1081  1104 I ActivityManager: Killing 6520:com.lge.email/u0a23 (adj 15): empty #18
,08-31 11:15:55.671  1081  1986 W libprocessgroup: failed to open /acct/uid_10027/pid_6548/cgroup.procs: No such file or directory
,08-31 11:15:55.676  1081  1927 W libprocessgroup: failed to open /acct/uid_10023/pid_6520/cgroup.procs: No such file or directory
08-31 11:15:55.685  6982  6982 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-31 11:15:55.686  6982  6982 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 11:15:55.687  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-31 11:15:55.687  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-31 11:15:55.689  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-31 11:15:55.689  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-31 11:15:55.690  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-31 11:15:55.700  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-31 11:15:55.971  1081  1362 V AlarmManager: RTC_WAKEUP set : Alarm{3b633045 type 0 when 1472634955947 com.android.vending} when 1472634955947
,08-31 11:15:56.034  1081  2010 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:15:56.170  6569  6569 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-31 11:15:56.562  1081  1747 D WifiServiceImplEx: setWifiEnabled: true pid=6631, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-31 11:15:56.563  1081  1747 D WifiService: setWifiEnabled: true pid=6631, uid=10118
,08-31 11:15:56.564  1081  1747 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:15:56.599  1081  1081 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 11:15:56.599  1081  1081 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-31 11:15:56.599  1081  1081 D Ulp_jni : JNI:system_update. Event-4
,08-31 11:15:56.600  1081  1375 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-31 11:15:56.601  1081  1375 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-31 11:15:56.603  1081  1375 E WifiUtil: wfc_util_ffile_check_copy(): pid[1081] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-31 11:15:56.603  1081  1375 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 11:15:56.603  1081  1375 E WifiUtil: wfc_util_ffile_check_copy(): pid[1081] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-31 11:15:56.603  1081  1375 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 11:15:56.603  1081  1375 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-31 11:15:56.603  1081  1375 E WifiHW  : unknown target_country: EU , set to default
08-31 11:15:56.603  1081  1375 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-31 11:15:56.603  1081  1375 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-31 11:15:56.603  1081  1375 I WifiUtil: gEnableBmps=1
08-31 11:15:56.696  1081  1427 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:15:56.715  1081  1176 D Tethering: MasterInitialState.processMessage what=3
08-31 11:15:56.725  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:15:56.733  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:56.736  1081  1427 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:15:56.736  1081  1171 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 11:15:56.738  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-31 11:15:56.744  6363  6402 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 11:15:56.759  1081  1176 D Tethering: MasterInitialState.processMessage what=3
,08-31 11:15:56.765  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:56.766  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:56.774  5706  5706 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 11:15:56.800  5706  5706 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 11:15:56.821  2246  2246 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:15:56.863  1081  1171 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:15:56.901  1081  2037 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7125 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-31 11:15:56.908  1081  1171 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:15:56.909  1081  1171 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 11:15:56.974  7125  7125 I AppUp4:AppBoxCP: onCreate
,08-31 11:15:56.975  7125  7125 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-31 11:15:56.985  7125  7125 I AppUp4:DB:  setFingerPrint start
08-31 11:15:56.985  7125  7125 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-31 11:15:56.994  7125  7125 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-31 11:15:56.994  7125  7125 I AppUp4:DB:  SDK version = 21
08-31 11:15:56.994  7125  7125 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-31 11:15:56.997  7125  7125 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-31 11:15:56.998  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 11:15:56.999  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:15:57.001  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 11:15:57.002  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 11:15:57.008  7125  7125 I AppUp4:CustModeStarterReceiver: onReceive
08-31 11:15:57.050  7125  7125 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:15:57.051  7125  7125 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:15:57.058  7125  7125 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@92a2f9
,08-31 11:15:57.058  7125  7125 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-31 11:15:57.058  7125  7125 D AppUp4:CustFacade: isPhone : true
08-31 11:15:57.060  7125  7125 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:15:57.061  7125  7125 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-31 11:15:57.061  7125  7125 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-31 11:15:57.062  7125  7143 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,08-31 11:15:57.063  7125  7143 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-31 11:15:57.063  7125  7143 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-31 11:15:57.067  1081  2037 I ActivityManager: Killing 6650:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-31 11:15:57.123  1081  1558 W libprocessgroup: failed to open /acct/uid_10061/pid_6650/cgroup.procs: No such file or directory
,08-31 11:15:57.125  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 11:15:57.125  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:15:57.130  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:15:57.135  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:15:57.146  4764  7153 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 11:15:57.151  4764  7154 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:15:57.151  4764  7154 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:15:57.231  1081  1695 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7155 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-31 11:15:57.260  1081  1176 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:15:57.261  1081  1176 D Tethering: InitialState.processMessage what=4
08-31 11:15:57.261  1081  1176 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 11:15:57.265   318   912 D SoftapController: Softap fwReload - Ok
08-31 11:15:57.266  1081  1375 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (654ms)
08-31 11:15:57.267   318   912 D CommandListener: Setting iface cfg
08-31 11:15:57.268   318   912 D CommandListener: Trying to bring down wlan0
08-31 11:15:57.270   318   912 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:15:57.273  1081  1375 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-31 11:15:57.275  7173  7173 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:15:57.275  7173  7173 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 11:15:57.306  7173  7173 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 11:15:57.315  7155  7155 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:15:57.316  7155  7155 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:15:57.317  7155  7155 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 11:15:57.318  7155  7155 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 11:15:57.341  7173  7173 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 11:15:57.341  7173  7173 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-31 11:15:57.374  1081  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:15:57.374  1081  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:15:57.374  1081  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:15:57.375  1081  1375 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 11:15:57.375  1081  1375 D WifiMonitor: connecting to supplicant
,08-31 11:15:57.381  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:57.382  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 11:15:57.384  1081  1081 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-31 11:15:57.386  7155  7155 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-31 11:15:57.386  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:57.387  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:15:57.414  7155  7155 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-31 11:15:57.414  7173  7173 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 11:15:57.477  7173  7173 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-31 11:15:57.497  7173  7173 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-31 11:15:57.498  7173  7173 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-31 11:15:57.501  1081  1375 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-31 11:15:57.502  1081  1375 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 11:15:57.504  1081  1375 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-31 11:15:57.504  1081  1375 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 11:15:57.505  1081  7175 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-31 11:15:57.505  1081  1375 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:15:57.505  1081  7175 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 11:15:57.505  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 11:15:57.505  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-31 11:15:57.505  1081  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:15:57.505  1081  7175 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 11:15:57.505  1081  7175 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-31 11:15:57.506  1081  1375 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 11:15:57.506  1081  1375 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 11:15:57.506  1081  1375 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 11:15:57.506  1081  1375 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 11:15:57.507  1081  1375 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-31 11:15:57.507  1081  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:15:57.507  1081  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:15:57.507  1081  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:15:57.508  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:57.508  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:57.508  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:57.508  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:57.509  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:15:57.509  1081  1375 D WifiNative-wlan0: doBoolean: SET update_config 1
08-31 11:15:57.511  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:57.511  1951  1951 D WfdService: Waiting for WifiP2p enabling
08-31 11:15:57.513  1081  1375 D WifiNative-wlan0: SET update_config 1: returned true
08-31 11:15:57.513  1081  1375 D WifiConfigStore: Loading config and enabling all networks 
,08-31 11:15:57.513  1081  1081 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 11:15:57.514  1081  1387 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 11:15:57.515  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:57.515  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:57.515  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:57.515  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:57.515  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:57.515  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:57.515  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:15:57.515  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:57.515  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:15:57.515  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:57.515  6631  6631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:15:57.516  1081  1375 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 11:15:57.517  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:57.517  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:57.517  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:57.517  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:57.517  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:15:57.517  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:57.517  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:15:57.517  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:57.517  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:15:57.517  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:57.517  6631  6631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:15:57.519  1081  1375 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-31 11:15:57.526  1081  1375 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-31 11:15:57.535  1081  1375 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 11:15:57.535  1081  1375 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 11:15:57.536  1081  1375 D WifiStateMachine: enableVerboseLogging : level 2
08-31 11:15:57.536  1081  1375 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 11:15:57.536  1081  1375 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-31 1,1:15:57.536  1081  1375 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 11:15:57.536  1081  1375 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-31 11:15:57.536  1081  1375 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 11:15:57.537  1081  1375 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 11:15:57.537  1081  1375 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 11:15:57.537  1081  1375 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 11:15:57.537  1081  1375 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-31 11:15:57.538  1081  1375 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 11:15:57.538  1081  1375 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,08-31 11:15:57.538  1081  1375 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 11:15:57.538  1081  1375 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 11:15:57.538  1081  1375 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 11:15:57.540  1951  1951 D WfdsService: Supplicant Connection state is changed : true
08-31 11:15:57.540  1951  2279 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 11:15:57.540  1951  2279 D WfdsService: Set the WFDS Monitor: true
08-31 11:15:57.540  1951  2279 D WfdsMonitor: WfdsMonitorThread create
,08-31 11:15:57.540  1951  2279 D WfdsMonitor: WFDS Monitor is created and started
08-31 11:15:57.540  1951  2279 D WfdsService: WiFi: Supplicant connection re-established
08-31 11:15:57.541  1951  7176 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-31 11:15:57.541  1081  1375 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:15:57.541  1951  7176 E CtrlSupplicant: Succeed to open control connection
08-31 11:15:57.541  1081  1375 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 11:15:57.542  1951  7176 E CtrlSupplicant: Succeed to open monitor connection
08-31 11:15:57.542  1951  7176 D WfdsMonitor: Supplicant connection established
08-31 11:15:57.542  1951  2279 D WfdsService: Connected to the supplicant for wfds
08-31 11:15:57.542  1081  1375 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 11:15:57.542  1081  1375 D WifiNative-HAL: Setting external_sim to 1
08-31 11:15:57.542  1081  1375 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 11:15:57.543  1081  1375 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 11:15:57.543  1081  1375 I WifiNative-HAL: startHal
08-31 11:15:57.543  1081  1375 D wifi    : setting scan oui 0xaf677720
08-31 11:15:57.543  1081  1375 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:15:57.543  1081  1375 I WifiNative-HAL: startHal
08-31 11:15:57.543  1081  1375 D wifi    : setting scan oui 0xaf677720
08-31 11:15:57.544  1081  1375 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 11:15:57.544  1081  1375 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 11:15:57.544  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 11:15:57.544  7173  7173 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 11:15:57.545  1081  1375 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 11:15:57.545  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 11:15:57.545  7173  7173 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 11:15:57.546  1081  1375 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 11:15:57.546  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 11:15:57.546  7173  7173 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 11:15:57.546  1081  1375 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 11:15:57.546  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 11:15:57.546  7173  7173 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 11:15:57.547  1081  1375 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 11:15:57.547  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 11:15:57.547  7173  7173 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 11:15:57.547  1081  1375 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 11:15:57.547  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 11:15:57.547  7173  7173 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 11:15:57.548  1081  1375 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 11:15:57.548  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 11:15:57.548  7173  7173 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 11:15:57.548  1081  1375 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 11:15:57.549  1081  1375 E WifiNative: : [120,541,460 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 11:15:57.549  1081  1375 D WifiNative-wlan0: doBoolean: RECONNECT
,08-31 11:15:57.550  1081  1375 D WifiNative-wlan0: RECONNECT: returned true
08-31 11:15:57.550  1081  1375 D WifiNative-wlan0: doString: [STATUS]
08-31 11:15:57.550  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 11:15:57.551  1081  1375 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 11:15:57.551  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 11:15:57.551  1081  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:15:57.551  1081  1375 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:15:57.551  1081  1374 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.553   318   912 D CommandListener: Setting iface cfg
08-31 11:15:57.553   318   912 D CommandListener: Trying to bring up p2p0
08-31 11:15:57.553  1081  1374 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 11:15:57.553  1081  1374 D LGWifiP2pService: P2pEnablingState
08-31 11:15:57.553  1081  1374 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.553  1081  1374 D LGWifiP2pService: P2p socket connection successful
08-31 11:15:57.553  1081  1374 D LGWifiP2pService: P2pEnabledState
08-31 11:15:57.554  1081  1374 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 11:15:57.554  1081  1081 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 11:15:57.554  1081  1539 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:15:57.554  1081  1539 I WifiNative-HAL: startHal
08-31 11:15:57.554  1081  1539 D wifi    : getting scan capabilities on interface[1] = 0xaf677720
08-31 11:15:57.554  1081  1539 D wifi    : failed to get capabilities : -3
08-31 11:15:57.554  1081  1539 E WifiScanningService: could not get scan capabilities
08-31 11:15:57.555  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-31 11:15:57.555  1951  1951 D WfdsService: WifiP2pState is changed : true
08-31 11:15:57.555  1951  2279 D WfdsService: Receive the WFDS_ENABLE Method
08-31 11:15:57.555  1951  2279 D WfdsService: Set the WFDS Monitor: true
08-31 11:15:57.555  1951  2279 D WfdsService: Connected to the supplicant for wfds
08-31 11:15:57.555  1951  2279 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 11:15:57.555  1081  1081 D RttService: SCAN_AVAILABLE : 3
08-31 11:15:57.555  7173  7173 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
,08-31 11:15:57.555  1951  2279 D WfdsService: selectPreferredScanChannel [36]
08-31 11:15:57.555  1951  2279 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 11:15:57.555  1081  1375 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 11:15:57.556  1081  1540 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.556  1081  1375 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 11:15:57.556  1951  1951 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 11:15:57.556  1081  1375 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-31 11:15:57.556  1081  1374 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 11:15:57.557  1081  1375 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 11:15:57.557  1951  1951 D WfdsService: isConnected: false
08-31 11:15:57.557  1081  1375 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 11:15:57.557  1081  1374 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 11:15:57.557  1081  1375 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 11:15:57.557  1081  1374 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 11:15:57.558  1081  1374 D WifiNative-p2p0: SET device_name G3: returned true
08-31 11:15:57.558  1081  1374 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 11:15:57.558  1081  1374 D LGWifiP2pService: before postfix = G3
08-31 11:15:57.558  1081  1375 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 11:15:57.558  1081  1374 D WifiServerServiceExt: postfix byte check : 2
08-31 11:15:57.558  1081  1374 D LGWifiP2pService: after postfix = G3
08-31 11:15:57.558  1081  1375 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 11:15:57.558  1081  1374 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 11:15:57.558  7173  7173 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 11:15:57.558  1081  1374 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 11:15:57.558  1081  1374 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 11:15:57.558  1081  1374 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 11:15:57.558  1081  1374 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-31 11:15:57.559  1081  1374 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 11:15:57.559  1081  1374 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-31 11:15:57.559  1081  1374 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 11:15:57.559  1081  1374 D WifiNative-HAL: p2pGetDeviceAddress
08-31 11:15:57.559  1081  1374 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-31 11:15:57.561  1951  1951 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 11:15:57.561  1081  1374 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-31 11:15:57.561  1951  1951 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 11:15:57.561  1081  1374 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-31 11:15:57.562  1951  1951 D WfdsService: Update P2p Interface State: 3
08-31 11:15:57.562  1081  1374 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 11:15:57.562  1081  1374 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-31 11:15:57.562  1081  1375 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-31 11:15:57.562  1081  1374 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 11:15:57.562  1081  1375 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 11:15:57.562  1081  1374 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 11:15:57.563  1081  1374 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-31 11:15:57.563  1081  1375 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 11:15:57.563  1081  1374 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 11:15:57.563  1,081  1375 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-31 11:15:57.578  7173  7173 E wpa_supplicant: disconnect_rssi_lvl: -100
,08-31 11:15:57.578  1081  1374 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-31 11:15:57.578  1081  1374 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 11:15:57.578  1081  1375 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 11:15:57.578  1081  1374 D LGWifiP2pService: InactiveState
08-31 11:15:57.579  1081  1375 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 11:15:57.579  1081  1374 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.579  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.579  1081  1374 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-31 11:15:57.579  1081  1375 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 11:15:57.579  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-31 11:15:57.580  7173  7173 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 11:15:57.582  7173  7173 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:15:57.582  1081  7175 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:15:57.583  7173  7173 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 11:15:57.583  1081  7175 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:15:57.583  7173  7173 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:15:57.583  1081  7175 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:15:57.583  1081  7175 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:15:57.583  1081  7175 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:15:57.583  1081  7175 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:15:57.583  1081  7175 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:15:57.583  1081  7175 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:15:57.584  7173  7173 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:15:57.584  1081  1374 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 11:15:57.584  1081  1374 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.584  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.585  7173  7173 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 11:15:57.585  1951  7176 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:15:57.586  1951  7176 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:15:57.586  1951  7176 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:15:57.586  7173  7173 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:15:57.587  7173  7173 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 11:15:57.588  7173  7173 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:15:57.588  1081  7175 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:15:57.588  1081  7175 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:15:57.588  1951  7176 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:15:57.588  1081  1374 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=3 target=com.android.i,nternal.util.StateMachine$SmHandler }
08-31 11:15:57.588  1081  1374 D LGWifiP2pService: InactiveState{ when=-9ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.588  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.588  1081  1374 D LGWifiP2pService: DefaultState{ when=-9ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.588  7173  7173 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:15:57.589  1081  1081 E WifiServerServiceExt: No p2p device connected
08-31 11:15:57.589  1081  1375 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 11:15:57.589  1951  7176 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:15:57.589  1081  1375 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:15:57.590  1081  1375 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:15:57.590  1081  1375 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:15:57.590  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-31 11:15:57.590  1081  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:15:57.590  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.590  7173  7173 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
,08-31 11:15:57.590  7173  7173 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:15:57.591  1081  1375 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
,08-31 11:15:57.591  1081  1375 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 11:15:57.592  1081  1375 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 11:15:57.592  1081  1375 D WifiNative-wlan0: doBoolean: SCAN
,08-31 11:15:57.592  1081  7175 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:15:57.592  1081  7175 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-31 11:15:57.592  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:15:57.592  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-31 11:15:57.592  1081  7175 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:15:57.592  1081  7175 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-31 11:15:57.592  1081  7175 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:15:57.592  1081  7175 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-31 11:15:57.592  1081  1375 D WifiNative-wlan0: SCAN: returned false
08-31 11:15:57.592  1081  7175 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:15:57.592  1081  7175 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-31 11:15:57.592  1081  7175 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:15:57.592  1081  7175 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:15:57.592  1081  7175 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-31 11:15:57.592  1081  7175 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:15:57.592  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
,08-31 11:15:57.592  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:15:57.592  1081  7175 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-31 11:15:57.592  1081  7175 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:15:57.593  1081  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=120585  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-31 11:15:57.595  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:15:57.595  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 11:15:57.596  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:57.596  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:15:57.596  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:57.596  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 11:15:57.597  1081  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=120590  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-31 11:15:57.598  1081  1375 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:15:57.598  1081  1375 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-31 11:15:57.599  1081  1375 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:15:57.600  1081  1375 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:15:57.601  1081  1375 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-31 11:15:57.601  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:15:57.602  1081  1081 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-31 11:15:57.622  1081  2309 I art     : Explicit concurrent mark sweep GC freed 64126(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 3.242ms total 178.584ms
,08-31 11:15:57.622  1081  1374 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.622  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.623  1081  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.623  1081  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.623  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.623  1081  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:57.624  1951  2279 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 11:15:57.633  7155  7155 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 11:15:57.688  7155  7155 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:15:57.688  7155  7155 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:15:57.844  7155  7155 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 11:15:57.891  3333  3333 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 11:15:57.891  3333  3333 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 11:15:57.891  3333  3333 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-31 11:15:57.936  1081  1747 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7190 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-31 11:15:57.943  7019  7188 W FormManager: Network not available. Please check & try again.
08-31 11:15:57.946  7019  7189 V FormManager: Network unavailable.
08-31 11:15:57.948  7019  7189 V FormManager: Network unavailable.
08-31 11:15:57.958  7155  7155 I HubEmail: JNI_OnLoad()
08-31 11:15:57.958  7155  7155 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 11:15:57.959  7155  7155 I HubEmail: registerNatives()
08-31 11:15:57.959  7155  7155 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 11:15:57.959  7155  7155 I HubEmail: registerNativeMethods()
08-31 11:15:57.959  7155  7155 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 11:15:57.959  7155  7155 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-31 11:15:57.971  1081  2010 I ActivityManager: Killing 6726:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-31 11:15:58.001  1081  1104 W libprocessgroup: failed to open /acct/uid_10080/pid_6726/cgroup.procs: No such file or directory
,08-31 11:15:58.008  7155  7207 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.084  7190  7190 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:15:58.085  7190  7190 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:15:58.088  7190  7190 D PhoneMonitor: Register our PhoneStateListener
08-31 11:15:58.108  7190  7190 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-31 11:15:58.115  7190  7190 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 11:15:58.125  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-31 11:15:58.125  1081  7175 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-31 11:15:58.126  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-31 11:15:58.126  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-31 11:15:58.126  1081  7175 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-31 11:15:58.126  7173  7173 E wpa_supplicant: USIM:  scard_init function
08-31 11:15:58.127  7173  7173 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-31 11:15:58.129  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 11:15:58.129  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-31 11:15:58.130  1081  1375 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 11:15:58.131  1081  1375 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 11:15:58.131  1081  1375 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 11:15:58.132  1081  1375 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 11:15:58.132  1081  1375 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-31 11:15:58.145  7190  7190 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-31 11:15:58.146  7190  7190 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-31 11:15:58.146  7190  7190 D TelephonyAutoProfiling: [parse] Load xml
08-31 11:15:58.149  7190  7190 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-31 11:15:58.149  7190  7190 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-31 11:15:58.149  7190  7190 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-31 11:15:58.149  7190  7190 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-31 11:15:58.149  7190  7190 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-31 11:15:58.149  7190  7190 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-31 11:15:58.149  7190  7190 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-31 11:15:58.149  7190  7190 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-31 11:15:58.150  7190  7190 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-31 11:15:58.150  7190  7190 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-31 11:15:58.150  7190  7190 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-31 11:15:58.150  7190  7190 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-31 11:15:58.150  7190  7190 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-31 11:15:58.150  7190  7190 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-31 11:15:58.150  7190  7190 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-31 11:15:58.150  7190  7190 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-31 11:15:58.150  7190  7190 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-31 11:15:58.157  7190  7190 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-31 11:15:58.185  1081  2309 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7212 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:15:58.186  1081  2309 I ActivityManager: Killing 6755:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-31 11:15:58.187  1081  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=121179  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 11:15:58.241  1081  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=121234  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 11:15:58.242  1081  1896 W libprocessgroup: failed to open /acct/uid_10097/pid_6755/cgroup.procs: No such file or directory
,08-31 11:15:58.246  7173  7173 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 11:15:58.251  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 11:15:58.251  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-31 11:15:58.251  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 11:15:58.251  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-31 11:15:58.251  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:15:58.251  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:15:58.252  1081  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=121245  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 11:15:58.253  1081  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=121245  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 11:15:58.253  1081  1375 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121246
08-31 11:15:58.254  1081  1375 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121246
08-31 11:15:58.254  1081  1375 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121247
08-31 11:15:58.255  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121247
08-31 11:15:58.255  1081  1375 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121248
08-31 11:15:58.256  1081  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=121248  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 11:15:58.257  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:15:58.257  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 11:15:58.258  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.258  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.258  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-31 11:15:58.261  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:58.261  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:15:58.261  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:15:58.261  7173  7173 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:15:58.261  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 11:15:58.261  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:15:58.261  7173  7173 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:15:58.261  1081  7175 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 11:15:58.261  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 11:15:58.261  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:15:58.262  1081  7175 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:15:58.263  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:15:58.263  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:15:58.271  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.271  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.271  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 11:15:58.272  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:15:58.272  1081  1081 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-31 11:15:58.283  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 11:15:58.284  1081  1176 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 11:15:58.285  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:15:58.287  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.287  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.287  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 11:15:58.289  1081  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=121281  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 11:15:58.291  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:58.292  1081  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=121284  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 11:15:58.292  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.293  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.293  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 11:15:58.293  1081  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=121285  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 11:15:58.293  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:15:58.293  1081  1375 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121286
08-31 11:15:58.293  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:15:58.293  1081  1081 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-31 11:15:58.293  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:15:58.294  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:58.294  1081  1375 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121287
08-31 11:15:58.295  1081  1375 D WifiNative-wlan0: doString: [STATUS]
,08-31 11:15:58.295  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:15:58.296  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:15:58.296  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:15:58.296  1081  1375 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 11:15:58.297  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:15:58.298  1081  1375 I WifiServiceExtension: setVHTCapabilityType  : false
08-31 11:15:58.299  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:58.305  1081  1375 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 11:15:58.305  1081  1375 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-31 11:15:58.310  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.310  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.310  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 11:15:58.314  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.314  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.314  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 11:15:58.317  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:15:58.317  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:15:58.318  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:58.320  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:15:58.320  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:15:58.321  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:15:58.328  1081  1375 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-31 11:15:58.328  1081  1427 D ConnectivityService: Got NetworkAgent Messenger
08-31 11:15:58.328  1081  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:15:58.328  1081  1427 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 11:15:58.328  1081  1427 D ConnectivityService: NetworkAgent connected
08-31 11:15:58.329  1081  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:15:58.329  1081  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:15:58.329  1081  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:15:58.345  1081  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 11:15:58.345  1081  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:15:58.345  1081  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:15:58.345  1081  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:15:58.345  1081  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-31 11:15:58.358  1081  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-31 11:15:58.360   318   912 D CommandListener: Setting iface cfg
08-31 11:15:58.362  1081  1375 E WifiStateMachine: Start Dhcp Watchdog 2
08-31 11:15:58.362  1081  7236 D DhcpStateMachine: StoppedState
08-31 11:15:58.363  1081  7236 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:58.363  1081  7236 D DhcpStateMachine: WaitBeforeStartState
08-31 11:15:58.363  1081  1375 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=121355  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:15:58.364  1081  1375 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=121356  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:15:58.364  1081  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=121357  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:15:58.365  1081  1375 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:15:58.365  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:15:58.366  1081  1375 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:15:58.366  1081  1375 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:15:58.366  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:15:58.367  1081  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:15:58.367  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:15:58.367  1081  1081 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-31 11:15:58.368  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:15:58.368  1081  1081 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-31 11:15:58.369  1081  1375 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121361  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:15:58.369  1081  1375 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121362  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:15:58.370  1081  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121362  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:15:58.371  1081  1375 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:75370] from screen [on:0 period:-538824157] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-31 11:15:58.374  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-538824154] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 11:15:58.374  1081  1375 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 11:15:58.377  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:58.380  1081  1427 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-31 11:15:58.380  1081  1375 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:58.381  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:58.381  1081  1375 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:58.381  1081  1375 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:58.382  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:58.382  1081  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-31 11:15:58.383  1081  1427 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 11:15:58.384  1081  1375 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=99,0,0
08-31 11:15:58.384  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=99,0,0
08-31 11:15:58.384  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 11:15:58.384  7173  7173 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-31 11:15:58.385  1081  1375 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 11:15:58.385  1081  1375 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 11:15:58.385  1081  1375 D WifiNative-wlan0: SET ps 0: returned true
08-31 11:15:58.385  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-31 11:15:58.386  7173  7173 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 11:15:58.386  1081  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 11:15:58.386  1081  1375 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 11:15:58.386  1081  1375 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 11:15:58.386  1081  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@32cb548b target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:58.386  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@32cb548b target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:58.386  1081  1375 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 11:15:58.386  1081  7236 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:58.386  1081  7236 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 11:15:58.388   318   912 D CommandListener: Setting iface cfg
08-31 11:15:58.388   318   912 D CommandListener: Trying to bring up wlan0
08-31 11:15:58.389  1081  1375 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-31 11:15:58.390  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:15:58.390  1081  1081 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 11:15:58.391  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:15:58.391  1081  1081 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 11:15:58.392  1081  1375 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:58.392  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:58.392  1081  1375 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:58.393  1081  1375 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:58.393  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:58.393  1081  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:58.394  1081  1427 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 11:15:58.394  1081  1375 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 11:15:58.394  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 11:15:58.395  1081  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:58.395  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:58.395  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 ,11:15:58.395  7173  7173 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:15:58.395  1081  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:15:58.395  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 11:15:58.395  7173  7173 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,08-31 11:15:58.396  1081  1375 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 11:15:58.396  1081  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:15:58.413  1081  1375 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:15:58.413  1081  1427 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 11:15:58.414  1081  1375 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 11:15:58.414  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 11:15:58.414  1081  1375 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-31 11:15:58.415  1081  1427 D ConnectivityService: ignoring duplicate network state non-change
08-31 11:15:58.417  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:15:58.417  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:15:58.418  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:58.419  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.419  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.420  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 11:15:58.421  1081  1427 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 11:15:58.421  1081  1427 D ConnectivityService: Adding iface wlan0 to network 101
08-31 11:15:58.426  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.427  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.427  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 11:15:58.428  1081  1375 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 11:15:58.430  1081  1081 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 11:15:58.439  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.439  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.439  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 11:15:58.439  1081  1081 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 11:15:58.439  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.439  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:58.439  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 11:15:58.441  1951  1951 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-31 11:15:58.444  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:15:58.444  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 11:15:58.446  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:58.451  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:15:58.451  1585  1585 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 11:15:58.451  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:58.452  1081  1427 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 11:15:58.452  1081  1427 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-31 11:15:58.454  1081  1427 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-31 11:15:58.455   318   912 E Netd    : netlink response contains error (File exists)
08-31 11:15:58.455  1081  1427 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-31 11:15:58.456  1081  1427 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-31 11:15:58.456  1081  1427 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-31 11:15:58.456  1081  1427 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-31 11:15:58.457  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:15:58.457  1585  1585 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 11:15:58.457  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:58.489  1081  1986 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7240 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-31 11:15:58.490  1081  1986 I ActivityManager: Killing 6789:com.lge.eula/1000 (adj 15): empty #17
08-31 11:15:58.529  1081  1427 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,08-31 11:15:58.530  1081  1427 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 11:15:58.530  1081  1695 W libprocessgroup: failed to open /acct/uid_1000/pid_6789/cgroup.procs: No such file or directory
08-31 11:15:58.530  1081  1427 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-31 11:15:58.530  1081  1427 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-31 11:15:58.530  1081  1427 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:15:58.530  1081  1427 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:15:58.530  1081  7233 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:58.530  1081  1427 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 11:15:58.530  1081  7233 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 11:15:58.530  1081  1427 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:15:58.530  1081  1427 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 11:15:58.530  1081  7233 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:58.530  1081  1427 D ConnectivityService: currentScore = 0, newScore = 20
08-31 11:15:58.530  1081  1427 D ConnectivityService:    accepting network in place of null
08-31 11:15:58.530  1081  1427 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:15:58.530  1081  7233 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 11:15:58.530  1081  1375 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:15:58.530  1081  1375 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:15:58.531  1081  1427 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 11:15:58.531  1081  1427 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 11:15:58.531  1081  1427 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:15:58.532  1862  1862 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:15:58.532  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TE,THERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 11:15:58.533   318  7258 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-31 11:15:58.538  1081  1427 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:15:58.538  1081  1427 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 11:15:58.539  1081  1427 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 11:15:58.539  1081  1427 D ConnectivityService: validation of new default Network = false
08-31 11:15:58.540  1081  1427 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 11:15:58.540  1081  1427 D DSQN    : enableDataServiceNotify 
08-31 11:15:58.540  1081  1427 D DSQN    : start dsqn bin
08-31 11:15:58.553  1081  1427 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-31 11:15:58.553  1081  1427 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 11:15:58.553  1081  1427 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:15:58.554  1081  1427 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:15:58.555  1585  1795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 11:15:58.555  7259  7259 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:15:58.555  7259  7259 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:15:58.566  1081  1081 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 11:15:58.567  1081  1081 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:15:58.567  1081  1081 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:15:58.567  1081  1081 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-31 11:15:58.573  7259  7259 E DSQN    : DSQN ssw
,08-31 11:15:58.585  1081  1373 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-31 11:15:58.587  1081  7236 D DhcpStateMachine: DHCPV4 request on wlan0
08-31 11:15:58.588  1081  7236 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-31 11:15:58.588  1081  7236 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-31 11:15:58.585  7263  7263 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:15:58.585  7263  7263 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:15:58.594  7263  7263 I dhcpcd  : version 5.5.6 starting
08-31 11:15:58.595  7263  7263 E dhcpcd  : get_duid: m
08-31 11:15:58.595  7263  7263 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 11:15:58.595  7263  7263 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-31 11:15:58.626  1081  1374 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:58.626  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:58.626  1081  1374 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:15:58.633  1081  1375 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 11:15:58.633  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 11:15:58.633  1081  1375 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 11:15:58.634  1081  1375 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 11:15:58.634  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 11:15:58.634  1081  1375 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 11:15:58.636  1081  2309 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7269 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:15:58.638  1081  2309 I ActivityManager: Killing 6811:com.lge.bnr/1000 (adj 15): empty #17
,08-31 11:15:58.658  7263  7263 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 11:15:58.658  7263  7263 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-31 11:15:58.658  7263  7263 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 11:15:58.658  7263  7263 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-31 11:15:58.658  7263  7263 D dhcpcd  : wlan0: sending REQUEST (xid 0x57d30e66), next in 3.64 seconds
08-31 11:15:58.706  7263  7263 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-31 11:15:58.710  7263  7263 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 11:15:58.710  7263  7263 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-31 11:15:58.710  7263  7263 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 11:15:58.710  7263  7263 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-31 11:15:58.710  7263  7263 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 11:15:58.711  7263  7263 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 11:15:58.711  7263  7263 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 11:15:58.711  7263  7263 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-31 11:15:58.720  1081  1926 W libprocessgroup: failed to open /acct/uid_1000/pid_6811/cgroup.procs: No such file or directory
,08-31 11:15:58.735  1585  1585 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-31 11:15:58.737  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:58.738  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:15:58.753  1802  7288 I CheckinService: active receiver: enabled
08-31 11:15:58.757  7269  7269 I art     : Almond Protected OAT
08-31 11:15:58.769  1802  7288 I CheckinService: Preparing to send checkin request
08-31 11:15:58.769  1802  7288 I EventLogService: Accumulating logs since 1472634880243
,08-31 11:15:58.816  1802  7288 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-31 11:15:58.825  7269  7269 D WeatherApplication: removeAccount
08-31 11:15:58.827  7269  7269 D WeatherApplication: Account.length = 0
08-31 11:15:58.828  7269  7269 E WeatherApplication: OPERATOR:OPEN
,08-31 11:15:58.836  7269  7269 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:15:58
08-31 11:15:58.839  7269  7269 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 11:15:58.839  7269  7269 D Weather.Utils: 2 : All the weather widget is gone.
,08-31 11:15:58.844  7269  7269 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 11:15:58.846  7269  7269 D WeatherAncestor: connectivity changed - connection : true
08-31 11:15:58.847  7269  7269 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-31 11:15:58.854  7269  7269 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 11:15:58.855  7269  7269 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-31 11:15:58.855  7269  7269 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-31 11:15:58.870  7269  7269 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 11:15:58.870  7269  7269 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:15:58
,08-31 11:15:58.897  1081  1695 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7308 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:15:58.898  1081  1695 I ActivityManager: Killing 2184:com.lge.music/u0a34 (adj 15): empty #17
08-31 11:15:58.912   323  1382 V AudioFlinger: 2184 died, releasing its sessions
,08-31 11:15:58.912   323  1382 V AudioFlinger:  pid 1862 @ 0
08-31 11:15:58.912   323  1382 V AudioFlinger:  pid 3333 @ 1
08-31 11:15:58.912   323  1382 V AudioFlinger:  pid 3333 @ 2
,08-31 11:15:58.990  1081  7236 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-31 11:15:58.993  1081  7236 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-31 11:15:58.993  1081  7236 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 11:15:58.994  1081  7236 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-31 11:15:58.994  1081  7236 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
,08-31 11:15:58.994  1081  7236 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,08-31 11:15:58.994  1081  7236 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-31 11:15:58.994  1081  7236 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 11:15:58.995  1081  7236 D DhcpStateMachine: RunningState
08-31 11:15:59.016  1081  2309 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7327 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-31 11:15:59.031  1081  1104 W libprocessgroup: failed to open /acct/uid_10034/pid_2184/cgroup.procs: No such file or directory
,08-31 11:15:59.112  7327  7327 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 11:15:59.113  7327  7327 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 11:15:59.145   281   433 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 11:15:59.145   281   433 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 11:15:59.145   281   433 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:15:59.147  7327  7327 I MultiDex: VM with version 2.1.0 has multidex support
08-31 11:15:59.147  7308  7345 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-31 11:15:59.147  7327  7327 I MultiDex: install
08-31 11:15:59.147  7327  7327 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-31 11:15:59.152   281   433 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 11:15:59.152   281   433 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 11:15:59.152   281   433 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 11:15:59.155  7308  7345 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-31 11:15:59.159  7327  7327 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-31 11:15:59.163   281   433 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 11:15:59.163   281   433 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 11:15:59.163   281   433 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 11:15:59.163  7308  7350 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-31 11:15:59.166   281   433 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 11:15:59.166   281   433 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 11:15:59.166   281   433 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 11:15:59.166  7308  7350 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-31 11:15:59.230   318  7258 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-31 11:15:59.378  7308  7308 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-31 11:15:59.390  7308  7308 I LibraryLoader: Loading: webviewchromium
,08-31 11:15:59.402  7308  7308 I LibraryLoader: Time to load native libraries: 12 ms (timestamps 2390-2402)
,08-31 11:15:59.403  7308  7308 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:15:59.417  7308  7308 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2a7a9c08}
,08-31 11:15:59.419  7308  7308 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:15:59.420  7308  7308 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 11:15:59.434  7308  7308 I BrowserStartupController: Initializing chromium process, renderers=0
,08-31 11:15:59.436  7308  7308 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 11:15:59.454  7308  7308 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-31 11:15:59.455  7308  7308 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-31 11:15:59.455  7308  7308 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-31 11:15:59.460   323   323 V AudioPolicyService: registerClient() client 0xb57f55e0, uid 10093
08-31 11:15:59.461  7308  7370 W AudioManagerAndroid: Requires BLUETOOTH permission
08-31 11:15:59.476  7308  7308 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:15:59.476  7308  7308 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:15:59.476  7308  7308 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:15:59.476  7308  7308 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:15:59.476  7308  7308 I Adreno-EGL: Remote Branch: 
08-31 11:15:59.476  7308  7308 I Adreno-EGL: Local Patches: 
08-31 11:15:59.476  7308  7308 I Adreno-EGL: Reconstruct Branch: 
,08-31 11:15:59.532   318  7258 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-31 11:15:59.555  1081  1427 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-31 11:15:59.566  7327  7343 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:15:59.567  7327  7343 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:15:59.588  7308  7308 I NSApplication: Starting up...
,08-31 11:15:59.603  1081  1105 D WifiServiceImplEx: setWifiEnabled: false pid=6631, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-31 11:15:59.603  1081  1105 D WifiService: setWifiEnabled: false pid=6631, uid=10118
08-31 11:15:59.603  1081  1105 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:15:59.621  1081  1375 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 11:15:59.621  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 11:15:59.622  1081  1375 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 11:15:59.622  1081  1375 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-31 11:15:59.622  1081  1081 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:15:59.622  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-31 11:15:59.622  1081  1375 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 11:15:59.622  1081  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:15:59.622  1081  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:15:59.623  1081  1081 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:15:59.623  1081  1081 D Ulp_jni : JNI:system_update. Event-4
08-31 11:15:59.623  1081  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:15:59.623  1081  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:15:59.635  1081  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 11:15:59.635  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 11:15:59.635  7173  7173 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:15:59.635  1081  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:59.635  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:59.636  1081  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:15:59.636  1081  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:15:59.636  1081  1375 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:15:59.636   318   912 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:15:59.642  7383  7383 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-31 11:15:59.645  1081  7236 D DhcpStateMachine: RunningState{ when=-9ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:59.660  1081  7233 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.ConnectException: failed to connect to clients3.google.com/2a00:1450:400d:807::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-31 11:15:59.665  1081  2010 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7387 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-31 11:15:59.665  1081  2010 I ActivityManager: Killing 6950:com.lge.sync/1000 (adj 15): empty #17
08-31 11:15:59.679  1081  1427 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 11:15:59.679  1081  1427 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-31 11:15:59.716  7383  7383 I dex2oat : dex2oat took 74.516ms (threads: 4)
,08-31 11:15:59.729  7327  7343 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:15:59.729  7327  7343 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:15:59.729  7327  7343 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:15:59.729  7327  7343 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:15:59.729  7327  7343 I Adreno-EGL: Remote Branch: 
08-31 11:15:59.729  7327  7343 I Adreno-EGL: Local Patches: 
08-31 11:15:59.729  7327  7343 I Adreno-EGL: Reconstruct Branch: 
,08-31 11:15:59.730  1081  1427 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-31 11:15:59.730  1081  1427 D DSQN    : disableDataServiceNotify
08-31 11:15:59.730  1081  1427 D DSQN    : stop dsqn bin
08-31 11:15:59.744  1081  1427 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-31 11:15:59.744  1081  1427 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:15:59.744  1081  1427 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:15:59.744  1081  1427 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:15:59.744  1081  1427 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-31 11:15:59.744  1081  1427 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-31 11:15:59.744  1585  1795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 11:15:59.744  1081  7233 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:59.744  1081  7233 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:59.744  1081  7233 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 11:15:59.744  1081  1427 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 11:15:59.745  1081  1427 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:15:59.755  1081  2310 W libprocessgroup: failed to open /acct/uid_1000/pid_6950/cgroup.procs: No such file or directory
,08-31 11:15:59.756  1081  1427 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:15:59.756  1081  1427 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 11:15:59.756  1081  1427 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:15:59.757  1081  1427 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:15:59.757  1081  1427 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:15:59.757  1081  1374 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:59.757  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:59.757  1081  1374 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1a893c3f
08-31 11:15:59.757  1081  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:59.757  1081  1374 D LGWifiP2pService: P2pDisablingState
08-31 11:15:59.757  1081  1374 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:59.757  1081  1374 D LGWifiP2pService: p2p socket connection lost
08-31 11:15:59.757  1081  1374 D LGWifiP2pService: P2pDisabledState
08-31 11:15:59.757  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:59.758  1081  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:59.758  1081  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:59.758  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:59.759  1081  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:15:59.759  1081  1375 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 11:15:59.759  1081  1375 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:15:59.759  1081  1375 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:15:59.759  1081  1375 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-31 11:15:59.759  1081  1374 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:59.760  1081  1374 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:59.760  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 11:15:59.760  7173  7173 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:15:59.760  1081  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:15:59.760  1081  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:15:59.760  1081  1081 D WifiHS20: hidePasspointNotification off =false
08-31 11:15:59.760  1081  1375 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:15:59.761   318   912 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:15:59.761  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:15:59.761  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:15:59.762  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:59.762  1081  1427 D NetworkManagementService: Removing idletimer
08-31 11:15:59.762  1081  1427 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.,provider.Settings.Global, returning read-only value.
08-31 11:15:59.762  1081  1427 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 11:15:59.762  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:59.762  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:59.763  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:15:59.763  1951  1951 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-31 11:15:59.763  1081  1081 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 11:15:59.763  1081  1081 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:15:59.763  1081  1081 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:15:59.763  1081  1081 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:15:59.765  1862  1862 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:15:59.765  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 11:15:59.766  1081  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 11:15:59.766  1081  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 11:15:59.767  1081  1081 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 11:15:59.767  1081  1081 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:15:59.768  1081  1081 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:15:59.768  1081  1081 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:15:59.769  1081  1081 D WifiHS20: hidePasspointNotification off =false
,08-31 11:15:59.779  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 11:15:59.779  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:59.779  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:59.779  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:15:59.779  1081  1081 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 11:15:59.779  1081  1081 D RttService: SCAN_AVAILABLE : 1
08-31 11:15:59.779  1081  1540 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:59.780  1081  1539 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:59.780  1951  1951 D WfdsService: WifiP2pState is changed : false
08-31 11:15:59.783  1951  2279 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 11:15:59.783  1951  2279 D WfdsService: Set the WFDS Monitor: false
08-31 11:15:59.784  1081  1375 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 11:15:59.784  1081  1375 D WifiNative-p2p0: TERMINATE: returned true
08-31 11:15:59.784  1081  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:15:59.784  1081  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:15:59.784  1081  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:15:59.785  1081  1081 D WifiHS20: hidePasspointNotification off =false
,08-31 11:15:59.790  1951  2279 D WfdsMonitor: WFDS Monitor is stopped
08-31 11:15:59.790  1951  7176 D CtrlSupplicant: Received on exit socket, terminate
08-31 11:15:59.790  1951  7176 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 11:15:59.790  1951  2279 D WfdsService: STATE : WfdsDisabledState - enter
08-31 11:15:59.790  1951  7176 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 11:15:59.790  1951  7176 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-31 11:15:59.790  1951  2279 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 11:15:59.790  1951  2284 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 11:15:59.792  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:59.792  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:15:59.792  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:15:59.794  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-31 11:15:59.796  1081  1081 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 11:15:59.796  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:59.796  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:59.796  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:59.796  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:59.796  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:15:59.796  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:59.796  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:15:59.796  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:59.796  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:15:59.796  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:59.796  6631  6631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:15:59.797  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:59.797  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:15:59.797  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:15:59.797  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:15:59.797  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:15:59.797  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:15:59.797  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:15:59.797  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:15:59.797  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:15:59.797  6631  6631 W org.thalipr,oject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:15:59.797  6631  6631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:15:59.802  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:15:59.802  1081  1081 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,08-31 11:15:59.808  7387  7387 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:15:59.815  1585  1585 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:15:59.816  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:59.816  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:15:59.829  1585  1585 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:15:59.830  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:59.830  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:59.831  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:15:59.831  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:15:59.832  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:59.833  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 11:15:59.833  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:15:59.834  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:15:59.835  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:15:59.843  7327  7343 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:15:59.843  7327  7343 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:15:59.843  7327  7343 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:15:59.843  7327  7343 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:15:59.843  7327  7343 I Adreno-EGL: Remote Branch: 
08-31 11:15:59.843  7327  7343 I Adreno-EGL: Local Patches: 
08-31 11:15:59.843  7327  7343 I Adreno-EGL: Reconstruct Branch: 
08-31 11:15:59.879  7327  7343 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 11:15:59.879  7327  7343 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 11:15:59.879  7327  7343 I Adreno-EGL: Build Date: 12/12/14 금
08-31 11:15:59.879  7327  7343 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 11:15:59.879  7327  7343 I Adreno-EGL: Remote Branch: 
08-31 11:15:59.879  7327  7343 I Adreno-EGL: Local Patches: 
08-31 11:15:59.879  7327  7343 I Adreno-EGL: Reconstruct Branch: 
,08-31 11:15:59.883  1081  7236 D DhcpStateMachine: StoppedState
08-31 11:15:59.883  1081  7236 D DhcpStateMachine: StoppedState{ when=-123ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:15:59.883  1081  1375 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-31 11:15:59.884  1081  1375 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-31 11:15:59.920  7173  7173 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 11:15:59.920  7173  7173 I wpa_supplicant: monitor socket send errors count : 1
08-31 11:15:59.920  7173  7173 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1951-4\x00 that cannot receive messages
,08-31 11:15:59.924  1081  7175 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-31 11:15:59.924  1081  7175 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 11:15:59.963  7173  7173 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:15:59.964  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-31 11:15:59.964  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:15:59.964  1081  7175 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 11:15:59.964  1081  7175 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 11:15:59.964  7173  7173 W wpa_supplicant: USIM:  scard_deinit function
08-31 11:15:59.965  1081  1176 D Tethering: InitialState.processMessage what=4
08-31 11:15:59.965  1081  1375 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122958
08-31 11:15:59.966  1081  1375 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122958
08-31 11:15:59.966  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:15:59.966  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:15:59.966  1081  1176 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 11:15:59.967  1081  1375 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=122959  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 11:15:59.967  1081  1375 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=122959  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 11:15:59.967  1081  1375 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:15:59.968  1081  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:16:00.043  1585  1585 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-31 11:16:00.043  1585  1585 I KeyguardUpdateMonitor: called onTimeUpdated()
08-31 11:16:00.043  1585  1585 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-31 11:16:00.043  1585  1585 I [SystemUI]Clock: called onTimeUpdated()
08-31 11:16:00.044  1585  1585 I LgeClockWidgetControlView: called onTimeUpdated()
08-31 11:16:00.044  1585  1585 I [SystemUI]DateView: called onTimeUpdated()
08-31 11:16:00.045  1585  1585 I [SystemUI]DateView: called onTimeUpdated()
08-31 11:16:00.045  1585  1585 D KeyguardUpdateMonitor: handleTimeUpdate
08-31 11:16:00.045  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 11:16:00.047  6363  6402 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 11:16:00.062  2246  2246 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:00.071  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 11:16:00.071  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:00.071  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 11:16:00.071  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 11:16:00.072  7125  7125 I AppUp4:CustModeStarterReceiver: onReceive
08-31 11:16:00.075  7125  7125 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@92a2f9
08-31 11:16:00.075  7125  7125 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-31 11:16:00.075  7125  7125 D AppUp4:CustFacade: isPhone : true
08-31 11:16:00.076  7125  7125 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:16:00.076  7125  7125 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-31 11:16:00.078  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:00.078  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:16:00.080  7173  7173 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 11:16:00.080  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:16:00.083  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:16:00.085  1081  7175 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-31 11:16:00.085  1081  7175 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 11:16:00.085  1081  7175 D WifiMonitor: Disconnecting from the supplicant, no more events
08-31 11:16:00.085  1081  1375 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-31 11:16:00.086  1081  1375 D WifiOffDelayIfNotUsed: stopMonitoring
08-31 11:16:00.086  1081  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:16:00.086  1081  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:16:00.086  1081  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:16:00.087  1951  1951 D WfdsService: Supplicant Connection state is changed : false
08-31 11:16:00.087  1951  2279 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-31 11:16:00.087  1951  2279 D WfdsService: Set the WFDS Monitor: false
08-31 11:16:00.087  1951  2279 D WfdsMonitor: WFDS Monitor is stopped
08-31 11:16:00.087  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 11:16:00.087  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:16:00.090  2441  2441 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:00.092  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:00.092  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:00.093  1081  1081 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-31 11:16:00.093  1081  1387 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-31 11:16:00.093  1081  1387 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-31 11:16:00.098  4764  7423 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:16:00.102  4764  7424 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:00.102  4764  7424 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:16:00.103  7155  7155 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 11:16:00.114  1081  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=99113952, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1081
,08-31 11:16:00.123  7155  7426 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:00.127  3333  3333 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 11:16:00.127  3333  3333 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:00.127  3333  3333 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-31 11:16:00.129  7190  7190 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 11:16:00.129  7190  7190 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 11:16:00.141  7269  7269 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:0
,08-31 11:16:00.145  7019  7428 W FormManager: Network not available. Please check & try again.
,08-31 11:16:00.146  7019  7429 V FormManager: Network unavailable.
08-31 11:16:00.147  7269  7269 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 11:16:00.147  7269  7269 D Weather.Utils: 2 : All the weather widget is gone.
08-31 11:16:00.148  7269  7269 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 11:16:00.148  7269  7269 D WeatherAncestor: connectivity changed - connection : true
08-31 11:16:00.148  7269  7269 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@199cb89f
08-31 11:16:00.149  7019  7429 V FormManager: Network unavailable.
08-31 11:16:00.149  7269  7269 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 11:16:00.149  7269  7269 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 11:16:00.149  7269  7269 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 11:16:00.149  7269  7269 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 11:16:00.149  7269  7269 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:0
08-31 11:16:00.164  2621  2621 D [Concierge]Service: onStartCommand(). Type : 9
,08-31 11:16:00.186  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:16:00.186  6909  6909 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:16:00.186  6909  6909 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:16:00.186  6909  6909 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 11:16:00.186  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-31 11:16:00.187  6909  6909 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:16:00.187  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 11:16:00.187  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:16:00.187  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 11:16:00.187  6909  6909 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:16:00.187  6909  6909 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:16:00.228  1081  1926 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7434 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 11:16:00.233  7019  7432 W FormManager: Network not available. Please check & try again.
08-31 11:16:00.245  7019  7433 V FormManager: Network unavailable.
,08-31 11:16:00.248  7019  7433 V FormManager: Network unavailable.
,08-31 11:16:00.265   318  7452 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 11:16:00.266  1081  1174 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 11:16:00.267  1802  7288 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-31 11:16:00.275  1802  7288 I CheckinService: active receiver: disabled
,08-31 11:16:00.304  7434  7434 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:16:00.307  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:16:00.312  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:00.313  1081  1896 I ActivityManager: Killing 6930:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-31 11:16:00.343  1081  2032 W libprocessgroup: failed to open /acct/uid_10037/pid_6930/cgroup.procs: No such file or directory
,08-31 11:16:00.369  7434  7434 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:16:00.374  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:16:00.383  7019  7456 W FormManager: Network not available. Please check & try again.
08-31 11:16:00.385  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:16:00.395  7019  7457 V FormManager: Network unavailable.
08-31 11:16:00.402  7019  7457 V FormManager: Network unavailable.
,08-31 11:16:00.415  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:16:00.416  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:16:00.418  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:16:00.422  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 11:16:00.433  4764  7458 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:16:00.437  4764  7459 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:16:00.438  4764  7459 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 11:16:00.496  1081  1747 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7460 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 11:16:00.521   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 472us total 21.954ms
,08-31 11:16:00.537  6840  7103 D UEI.SmartControl: Internal timer expired: 2
,08-31 11:16:00.537  6840  7103 D UEI.SmartControl: unbind internal service
,08-31 11:16:00.545   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 20.728ms
,08-31 11:16:00.562   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 314us total 16.736ms
,08-31 11:16:00.603  6840  7097 D serial_port: close(fd = 24)
,08-31 11:16:00.608  6840  7097 I UEI.SmartControl: Serial port is closed.
,08-31 11:16:00.623  7460  7460 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 11:16:00.624  7460  7460 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-31 11:16:00.635  7460  7460 V [BNRBootReceiver]: Boot Receiver Return
08-31 11:16:00.637  7460  7460 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-31 11:16:00.641  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:00.663  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:00.674  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:00.695  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:16:00.696  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:00.701  6982  6982 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:16:00.709  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-31 11:16:00.715  6909  6909 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 11:16:00.723  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:16:00.740  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:00.752  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:16:00.764  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:16:00.765  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:00.768  6982  6982 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:16:00.774  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:00.787  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:00.798  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:00.809  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:16:00.810  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:00.811  6982  6982 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:16:00.818  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:00.832  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:00.840  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:00.849  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:00.850  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:00.851  6982  6982 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 11:16:00.857  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:00.870  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:00.878  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:00.886  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:00.887  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:00.888  6982  6982 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 11:16:00.894  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:00.903  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:00.914  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:00.923  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:16:00.923  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:00.924  6982  6982 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:16:00.930  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:00.947  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:00.958  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:00.970  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:16:00.971  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:00.972  6982  6982 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:16:00.986  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:16:01.013  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:01.025  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:16:01.037  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:01.038  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:16:01.042  6982  6982 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:16:01.051  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:01.071  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:01.090  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:01.101  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:16:01.102  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:01.104  6982  6982 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:16:01.111  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:01.123  7434  7434 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-31 11:16:01.143  1081  1424 D WifiService: New client listening to asynchronous messages
,08-31 11:16:01.144  7434  7434 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:16:01.154  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:01.167  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:01.176  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:01.176  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:16:01.178  6982  6982 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 11:16:01.179  6982  6982 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 11:16:01.179  6982  6982 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 11:16:01.185  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:01.190  7434  7434 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-31 11:16:01.193  7434  7434 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:16:01.197  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:01.204  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:01.212  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:01.212  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:16:01.213  6982  6982 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-31 11:16:01.214  6982  6982 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 11:16:01.214  6982  6982 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 11:16:01.217  1081  1104 I ActivityManager: Killing 6999:com.lge.settings.easy/1000 (adj 15): empty #17
08-31 11:16:01.252  1081  1558 W libprocessgroup: failed to open /acct/uid_1000/pid_6999/cgroup.procs: No such file or directory
,08-31 11:16:01.256  2246  2246 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-31 11:16:01.265  2246  2246 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-31 11:16:01.268  2246  2246 D c       : Getting all permits...
08-31 11:16:01.268  2246  2246 D a       : Opening database...
08-31 11:16:01.274  2246  2246 D a       : Opening database auth.proximity.permit_store...
08-31 11:16:01.275  2246  2246 D a       : Closing database...
08-31 11:16:01.285  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:16:01.292  7434  7434 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:16:01.296  7434  7434 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:16:01.296  7434  7434 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:16:01.299  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:01.306  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:01.314  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:01.314  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:16:01.316  6982  6982 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:16:01.321  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:01.325  7434  7434 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:16:01.325  7434  7434 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:16:01.325  7434  7434 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:16:01.330  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:01.338  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:01.346  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:16:01.346  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:01.348  6982  6982 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:16:01.354  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:01.358  7434  7434 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 11:16:01.358  7434  7434 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:16:01.358  7434  7434 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:16:01.363  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:01.373  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:01.380  1081  1375 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-538821148] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 11:16:01.382  1081  1375 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-538821146] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 11:16:01.384  6982  6982 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:16:01.384  6982  6982 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:01.387  6982  6982 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:16:01.397  7434  7434 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:16:01.405  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:16:01.409  7019  7489 W FormManager: Network not available. Please check & try again.
08-31 11:16:01.410  7019  7490 V FormManager: Network unavailable.
,08-31 11:16:01.416  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:01.417  7019  7490 V FormManager: Network unavailable.
08-31 11:16:01.432  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-31 11:16:01.432  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:16:01.434  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:16:01.437  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:16:01.445  4764  7491 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 11:16:01.447  7434  7434 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-31 11:16:01.447  7434  7434 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 11:16:01.447  7434  7434 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 11:16:01.451  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:16:01.457  4764  7493 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:16:01.457  4764  7493 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 11:16:01.463  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:01.469  7019  7494 W FormManager: Network not available. Please check & try again.
08-31 11:16:01.471  7019  7495 V FormManager: Network unavailable.
08-31 11:16:01.480  6982  6982 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-31 11:16:01.480  6982  6982 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1909
,08-31 11:16:01.482  1081  1081 D PowerManagerServiceEx: releaseWakeLockInternal: lock=99113952 [*alarm*], flags=0x0
08-31 11:16:01.481  7019  7495 V FormManager: Network unavailable.
,08-31 11:16:01.489  2246  2246 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-31 11:16:01.540  1081  1427 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:01.549  1081  1171 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:01.549  1081  1176 D Tethering: MasterInitialState.processMessage what=3
08-31 11:16:01.557  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:01.558  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:01.563  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 11:16:01.564  5706  5706 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 11:16:01.566  6363  6402 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 11:16:01.571  1081  1171 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 11:16:01.583  2246  2246 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:01.592  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 11:16:01.592  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:01.592  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 11:16:01.592  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 11:16:01.594  7125  7125 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 11:16:01.597  7125  7125 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@92a2f9
08-31 11:16:01.597  7125  7125 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:16:01.597  7125  7125 D AppUp4:CustFacade: isPhone : true
08-31 11:16:01.598  7125  7125 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:16:01.598  7125  7125 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 11:16:01.602  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:01.603  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:16:01.604  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 11:16:01.610  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 11:16:01.616  4764  7507 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 11:16:01.618  7155  7155 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 11:16:01.621  4764  7508 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:01.621  4764  7508 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:16:01.654  7155  7509 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:16:01.654  7019  7511 W FormManager: Network not available. Please check & try again.
08-31 11:16:01.665  3333  3333 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 11:16:01.665  3333  3333 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:01.666  3333  3333 I LgeMiscReceiver: networkInfo.isConnected() = true
08-31 11:16:01.666  3333  3333 D PhoneState: setPdpRejectCasuse : false
08-31 11:16:01.672  7190  7190 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 11:16:01.672  7190  7190 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 11:16:01.673  7019  7512 V FormManager: Network unavailable.
,08-31 11:16:01.687  7269  7269 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:1
,08-31 11:16:01.689  7019  7512 V FormManager: Network unavailable.
,08-31 11:16:01.694  7269  7269 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-31 11:16:01.694  7269  7269 D Weather.Utils: 2 : All the weather widget is gone.
08-31 11:16:01.694  7269  7269 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 11:16:01.695  7269  7269 D WeatherAncestor: connectivity changed - connection : true
08-31 11:16:01.695  7269  7269 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@199cb89f
,08-31 11:16:01.696  7269  7269 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 11:16:01.696  7269  7269 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 11:16:01.696  7269  7269 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 11:16:01.696  7269  7269 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-31 11:16:01.696  7269  7269 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:1
08-31 11:16:02.630  1081  1695 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:02.631  1081  1695 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-31 11:16:02.657  1081  1081 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:16:02.657  1081  1081 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:16:02.657  1081  1081 D Ulp_jni : JNI:system_update. Event-4
,08-31 11:16:02.661  1081  1176 D BluetoothManagerService: Message: 1
08-31 11:16:02.661  1081  1176 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-31 11:16:02.693  1081  1176 D BluetoothManagerService: Message: 20
08-31 11:16:02.693  1081  1176 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1246f741:true
,08-31 11:16:02.697  7056  7056 D BluetoothAdapterState: make
08-31 11:16:02.702  7056  7056 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 11:16:02.702  7056  7056 I bluedroid-qcom: init
08-31 11:16:02.703  7056  7525 I BluetoothAdapterState: Entering OffState
08-31 11:16:02.704  7056  7056 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 11:16:02.704  7056  7056 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 11:16:02.704  7056  7056 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 11:16:02.704  7056  7056 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 11:16:02.704  7056  7056 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 11:16:02.706  7056  7056 I bluedroid-qcom: get_profile_interface socket
08-31 11:16:02.706  7056  7056 I bluedroid-qcom: get_profile_interface map_client
,08-31 11:16:02.711  7056  7529 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 11:16:02.713  7056  7529 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 11:16:02.705  7528  7528 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:02.705  7528  7528 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:02.721  1081  1081 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 11:16:02.722  1081  1081 D BluetoothManagerService: Stored Bluetooth name: G3
,08-31 11:16:02.729  1081  1081 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-31 11:16:02.729  1081  1176 D BluetoothManagerService: Message: 40
08-31 11:16:02.729  1081  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 11:16:02.730  7056  7072 I bluedroid-qcom: config_hci_snoop_log
08-31 11:16:02.732  1081  1176 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 11:16:02.732  1081  1176 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 11:16:02.732  7528  7528 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 11:16:02.732  7528  7528 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 11:16:02.732  7528  7528 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-31 11:16:02.735  7528  7528 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-31 11:16:02.743  7056  7525 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-31 11:16:02.744  7056  7529 D BluetoothAdapterProperties: Name is: G3
08-31 11:16:02.744  7056  7525 D BluetoothAdapterProperties: Setting state to 11
08-31 11:16:02.744  7056  7525 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 11:16:02.745  1081  1176 D BluetoothManagerService: Message: 60
08-31 11:16:02.745  1081  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 11:16:02.745  1081  1176 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 11:16:02.747  7528  7528 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 11:16:02.747  7528  7528 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-31 11:16:02.752  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:16:02.754  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:16:02.757  1081  1427 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:02.758  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:02.762  6909  6909 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-31 11:16:02.763  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:02.765  1081  1427 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:02.782  7056  7056 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-31 11:16:02.785  7056  7056 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:02.785  7056  7056 V BluetoothPbapReceiver: ***********state = 11
,08-31 11:16:02.794  1081  1176 D Tethering: MasterInitialState.processMessage what=3
08-31 11:16:02.794  7056  7525 I LGBluetoothServiceJni: classInitNative: succeeds
08-31 11:16:02.801  1081  1176 D Tethering: MasterInitialState.processMessage what=3
08-31 11:16:02.805  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:02.808  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:02.810  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:02.811  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 11:16:02.812  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:02.813  7056  7525 D BluetoothBondStateMachine: make
08-31 11:16:02.814  5706  5706 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 11:16:02.814  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:16:02.819  7056  7525 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:02.819  7056  7546 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 11:16:02.819  7056  7525 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 11:16:02.820  7056  7525 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:02.820  7056  7525 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 11:16:02.820  7056  7525 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-31 11:16:02.824  7056  7525 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:16:02.824  6363  6402 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 11:16:02.863  1081  2309 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7547 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-31 11:16:02.876  7056  7056 D HeadsetService: Received start request. Starting profile...
08-31 11:16:02.876  5706  5706 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 11:16:02.877  7056  7056 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 11:16:02.877  7056  7056 D LGBluetoothHfpAdapter: Version 1.6
08-31 11:16:02.880  7056  7525 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:16:02.883  7056  7056 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 11:16:02.884  7056  7056 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 11:16:02.885  7056  7056 D HeadsetStateMachine: make
08-31 11:16:02.889  7056  7525 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:16:02.901  7056  7525 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:16:02.907  1081  1171 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:02.908  7056  7525 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:16:02.916  7056  7525 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:16:02.931  7056  7056 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 11:16:02.932  7056  7056 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:16:03.019  1081  1986 I art     : Explicit concurrent mark sweep GC freed 116029(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.240ms total 97.011ms
,08-31 11:16:03.021  2246  2246 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:03.026  7056  7525 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:16:03.026  7056  7056 D HeadsetStateMachine: max_hf_connections = 1
08-31 11:16:03.026  7056  7056 I bluedroid-qcom: get_profile_interface handsfree
08-31 11:16:03.036  7547  7547 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-31 11:16:03.036  7547  7547 W LG Account v2.2: No ProfileInfo entries
08-31 11:16:03.037  7547  7547 I LG Account v2.2: isEnabled: false
08-31 11:16:03.037  7547  7547 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 11:16:03.037  7547  7547 I Feature : [Lifetracker]Country: EU
08-31 11:16:03.037  7547  7547 I Feature : [Lifetracker]Operator: OPEN
08-31 11:16:03.037  7547  7547 I Feature : [Lifetracker]Ranking support: false
08-31 11:16:03.037  7547  7547 I Feature : [Lifetracker]Comfort support: false
08-31 11:16:03.037  7547  7547 I Feature : [Lifetracker]Accessory: true
08-31 11:16:03.037  7547  7547 I Feature : [Lifetracker]Health device: true
08-31 11:16:03.037  7547  7547 I Feature : [Lifetracker]Extra Pedometer: false
08-31 11:16:03.037  7547  7547 I Feature : [Lifetracker]Blood glucose device: false
08-31 11:16:03.037  7547  7547 I Feature : [Lifetracker]Device Number: 3
08-31 11:16:03.038  7056  7056 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 11:16:03.039  7056  7525 V LGMDMManager: Create singleton instance
08-31 11:16:03.039   323  1382 V AudioPolicyService: registerClient() client 0xb57edcc0, uid 1002
08-31 11:16:03.040  7056  7525 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 11:16:03.042   323   323 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 11:16:03.042   323   323 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:16:03.042   323   323 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:16:03.042  7056  7056 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 11:16:03.043   323  4394 V AudioFlinger: registerClient() client 0xb5581718, pid 7056
08-31 11:16:03.043   323  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:16:03.043   323  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:16:03.043  1081  1968 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:16:03.043  1081  1968 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:16:03.044  1585  1605 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:16:03.044  1585  1605 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:16:03.044  1862  4854 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:16:03.044  1862  4854 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:16:03.044  7056  7072 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:16:03.044  7056  7072 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 11:16:03.044  3333  3351 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:16:03.044  3333  3351 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:16:03.044   323  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:16:03.044   323  1376 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:16:03.044  1081  2060 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:16:03.044  1081  2060 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:16:03.044  7056  7072 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:16:03.044  7056  7072 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 11:16:03.045  7056  7056 V ToneGenerator: Create Track: 0xb4928080
08-31 11:16:03.045  7056  7056 V AudioTr,ack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 11:16:03.045  7056  7056 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 11:16:03.045   323   323 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 11:16:03.045   323   323 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 11:16:03.045   323   323 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:16:03.045   323   323 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:16:03.045   323  4394 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 11:16:03.046   323  1382 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 11:16:03.046   323  1382 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 11:16:03.046   323  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:16:03.046   323  1382 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:16:03.046  7056  7056 V AudioSystem: getLatency() output 2, latency 50
08-31 11:16:03.046  7056  7056 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 11:16:03.046  7056  7056 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 11:16:03.047  3333  3349 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:16:03.047  3333  3349 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:16:03.047  1585  3115 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:16:03.047  1585  3115 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:16:03.047  1862  1878 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:16:03.047  1862  1878 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:16:03.048   323  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
,08-31 11:16:03.048   323  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 11:16:03.048   323  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 11:16:03.048   323  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 11:16:03.049   323  1383 V AudioFlinger: createTrack() lSessionId: 20
08-31 11:16:03.050  7056  7056 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 11:16:03.050   323   323 V AudioFlinger: acquiring 20 from 7056, for 7056
08-31 11:16:03.050   323   323 V AudioFlinger:  added new entry for 20
08-31 11:16:03.051  7056  7056 V ToneGenerator: ToneGenerator INIT OK, time: 126052
08-31 11:16:03.051  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
,08-31 11:16:03.052  7056  7564 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 11:16:03.052  7056  7564 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:16:03.052  7056  7564 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:16:03.052  7056  7564 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,08-31 11:16:03.052   323  4394 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7056
08-31 11:16:03.054   323  4394 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 11:16:03.054   323  4394 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 11:16:03.054   323  4394 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 11:16:03.054   323  4394 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 11:16:03.054   323  4394 V voice   : voice_set_parameters: exit with code(0)
08-31 11:16:03.054   323  4394 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 11:16:03.054   323  4394 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 11:16:03.054   323  4394 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 11:16:03.054   323  4394 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 11:16:03.054   323  4394 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 11:16:03.054   323  4394 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 11:16:03.054  7056  7564 V ToneGenerator: ToneGenerator destructor
08-31 11:16:03.054  7056  7564 V ToneGenerator: stopTone
08-31 11:16:03.054  7056  7564 V ToneGenerator: Delete Track: 0xb4928080
08-31 11:16:03.054  7056  7564 V AudioTrack: ~AudioTrack, releasing session id from 7056 on behalf of 7056
08-31 11:16:03.054   323  1382 V AudioFlinger: releasing 20 from 7056 for 7056
08-31 11:16:03.054   323  1382 V AudioFlinger:  decremented refcount to 0
08-31 11:16:03.054   323  1382 V AudioFlinger: purging stale effects
08-31 11:16:03.054   323  1382 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 11:16:03.054   323  1382 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 11:16:03.054   323  1273 V AudioPolicyService: AudioCommandThread() waking up
08-31 11:16:03.054   323  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 11:16:03.054   323  1273 V AudioPolicyManager: releaseOutput() 2
08-31 11:16:03.054   323  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 11:16:03.054   323  1382 V AudioFlinger: PlaybackThread::Track destructor
08-31 11:16:03.054   323  1382 V AudioFlinger: removeClient_l() pid 7056, calling pid 323
08-31 11:16:03.056  1081  1986 W Process : Unable to open /proc/7569/status
08-31 11:16:03.057  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:03.057  1081  1171 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:03.058  1081  1171 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:16:03.058  1081  1171 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:16:03.060  7056  7056 D A2dpService: Received start request. Starting profile...
08-31 11:16:03.060  7056  7056 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 11:16:03.061  7056  7056 V Avrcp   : make
08-31 11:16:03.062  7056  7056 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-31 11:16:03.062  7056  7056 I bluedroid-qcom: get_profile_interface avrcp
08-31 11:16:03.064  6909  6909 D BluetoothPermissionRequest: onReceive
08-31 11:16:03.065  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 11:16:03.065  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:03.065  71,25  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 11:16:03.065  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-31 11:16:03.067  7125  7125 I AppUp4:CustModeStarterReceiver: onReceive
08-31 11:16:03.068  6909  6909 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:16:03.070  7056  7056 V AudioManager: registerRemoteController: size of Media player list: 0
08-31 11:16:03.072  7056  7056 E AudioManager: No RCC entry present to update
08-31 11:16:03.072  7056  7056 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 11:16:03.073  7125  7125 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@92a2f9
08-31 11:16:03.073  7125  7125 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:16:03.073  7125  7125 D AppUp4:CustFacade: isPhone : true
08-31 11:16:03.074  7125  7125 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:16:03.074  7125  7125 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 11:16:03.075  7056  7056 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-31 11:16:03.076  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 11:16:03.076  7056  7056 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 11:16:03.077  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:03.077  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:16:03.078  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 11:16:03.081  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 11:16:03.081  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 11:16:03.084  4764  7572 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:16:03.086  4764  7573 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:03.086  4764  7573 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:16:03.146  7155  7155 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 11:16:03.174  7155  7575 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:16:03.179  3333  3333 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 11:16:03.179  3333  3333 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:03.179  3333  3333 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 11:16:03.186  7190  7190 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 11:16:03.186  7190  7190 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-31 11:16:03.187  7019  7577 W FormManager: Network not available. Please check & try again.
08-31 11:16:03.195  7019  7578 V FormManager: Network unavailable.
08-31 11:16:03.197  7269  7269 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:3
08-31 11:16:03.198  7269  7269 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 11:16:03.199  7269  7269 D Weather.Utils: 2 : All the weather widget is gone.
,08-31 11:16:03.199  1081  1896 V SIM_STK : Menu title from STK is T-Mobile
08-31 11:16:03.199  1081  1896 V SIM_STK : Menu title from STK is T-Mobile
08-31 11:16:03.199  7269  7269 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 11:16:03.199  7269  7269 D WeatherAncestor: connectivity changed - connection : true
08-31 11:16:03.199  7269  7269 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@199cb89f
08-31 11:16:03.199  7019  7578 V FormManager: Network unavailable.
08-31 11:16:03.200  7269  7269 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 11:16:03.200  7269  7269 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 11:16:03.200  7269  7269 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 11:16:03.200  7269  7269 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 11:16:03.200  7269  7269 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:3
08-31 11:16:03.225  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 11:16:03.226  6363  6402 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 11:16:03.242  2246  2246 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:03.253  1081  2037 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-31 11:16:03.257  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 11:16:03.257  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:03.257  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-31 11:16:03.257  7125  7125 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 11:16:03.259  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 11:16:03.259  7125  7125 I AppUp4:CustModeStarterReceiver: onReceive
08-31 11:16:03.262  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 11:16:03.262  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 11:16:03.262  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 11:16:03.262  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 11:16:03.262  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:16:03.262  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 11:16:03.262  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 11:16:03.262  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 11:16:03.262  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:16:03.262  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 11:16:03.263  7056  7056 I BluetoothA2dpServiceJni: classInitNative
08-31 11:16:03.263  7056  7056 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:16:03.263  7056  7056 D A2dpStateMachine: make
08-31 11:16:03.263  7125  7125 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@92a2f9
08-31 11:16:03.263  7125  7125 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:16:03.263  7125  7125 D AppUp4:CustFacade: isPhone : true
08-31 11:16:03.264  7125  7125 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:16:03.264  7125  7125 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 11:16:03.265  7056  7056 I bluedroid-qcom: get_profile_interface a2dp
08-31 11:16:03.265  7056  7580 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 11:16:03.268  7056  7056 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:16:03.268  7056  7056 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 11:16:03.269  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:03.269  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:16:03.270  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:03.271  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:16:03.271  7056  7056 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 11:16:03.272  7056  7579 D A2dpStateMachine: Enter Disconnected: -2
08-31 11:16:03.273  7056  7056 D HidService: Received start request. Starting profile...
08-31 11:16:03.273  7056  7056 I bluedroid-qcom: get_profile_interface hidhost
08-31 11:16:03.273  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:03.274  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:16:03.274  7056  7056 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 11:16:03.276  7056  7056 D HealthService: Received start request. Starting profile...
08-31 11:16:03.276  4764  7582 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 11:16:03.277  7056  7056 I bluedroid-qcom: get_profile_interface health
08-31 11:16:03.278  7056  7056 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 11:16:03.278  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:03.278  7056  7056 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 11:16:03.281  7056  7056 D PanService: Received start request. Starting profile...
08-31 11:16:03.281  7056  7056 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:16:03.281  7056  7056 I bluedroid-qcom: get_profile_interface pan
,08-31 11:16:03.283  7155  7155 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 11:16:03.287  7056  7056 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-31 11:16:03.287  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:03.287  7056  7056 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 11:16:03.291  7056  7056 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:16:03.291  7056  7056 D BtGatt.GattService: Received start request. Starting profile...
08-31 11:16:03.292  7056  7056 D BtGatt.GattService: start()
08-31 11:16:03.292  7056  7056 I bluedroid-qcom: get_profile_interface gatt
08-31 11:16:03.292  7056  7056 D BtGatt.AdvertiseManager: advertise manager created
08-31 11:16:03.292  4764  7583 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:03.292  4764  7583 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:16:03.302  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
,08-31 11:16:03.302  7056  7056 D HeadsetStateMachine: Proxy object connected
,08-31 11:16:03.303  7056  7056 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 11:16:03.303  7056  7056 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-31 11:16:03.305  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:03.306  7056  7056 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 11:16:03.307  7056  7056 V BluetoothMapService: BluetoothMapBinder()
08-31 11:16:03.308  7056  7056 D BluetoothMapService: Received start request. Starting profile...
08-31 11:16:03.308  7056  7056 D BluetoothMapService: start()
08-31 11:16:03.310  7155  7589 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:03.310  7019  7590 W FormManager: Network not available. Please check & try again.
08-31 11:16:03.311  7056  7056 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 11:16:03.311  7056  7056 D BluetoothMapEmailAppObserver: createReceiver()
08-31 11:16:03.313  7056  7056 D BluetoothMapEmailAppObserver: initObservers()
08-31 11:16:03.313  7056  7056 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 11:16:03.316  3333  3333 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-31 11:16:03.316  3333  3333 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:03.316  3333  3333 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 11:16:03.318  7019  7591 V FormManager: Network unavailable.
08-31 11:16:03.319  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:03.320  7056  7564 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 11:16:03.321  7056  7564 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 11:16:03.321  7056  7564 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 11:16:03.321  7190  7190 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 11:16:03.322  7190  7190 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 11:16:03.323  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:16:03.325  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:16:03.327  7019  7591 V FormManager: Network unavailable.
08-31 11:16:03.328  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 11:16:03.330  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:16:03.331  7056  7056 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 11:16:03.333  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:16:03.335  7056  7056 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 11:16:03.335  7056  7056 V BluetoothMapService: Handler(): got msg=1
08-31 11:16:03.336  7056  7525 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 11:16:03.336  7056  7525 I bluedroid-qcom: enable
08-31 11:16:03.336  7056  7594 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 11:16:03.336  7056  7594 I bt-btu  : btu_task pending for preload complete event
08-31 11:16:03.336  7056  7525 I bt_hci_bdroid: init
08-31 11:16:03.338  7056  7525 I bt_vendor: bt-vendor : init
08-31 11:16:03.338  7056  7525 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 11:16:03.338  7056  7525 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 11:16:03.338  7056  7525 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 11:16:03.338  7056  7525 D bt_userial_mct: userial_init
08-31 11:16:03.338  7056  7525 D bt_hci_bdroid: set_power 1
08-31 11:16:03.338  7056  7525 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 11:16:03.338  7056  7525 I bt_vendor: Starting hciattach daemon
08-31 11:16:03.338  7056  7525 I bt_vendor: try to set true
08-31 11:16:03.335  7597  7597 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:03.340  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:03.342  7269  7269 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:3
,08-31 11:16:03.335  7597  7597 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 11:16:03.344  7269  7269 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 11:16:03.344  7269  7269 D Weather.Utils: 2 : All the weather widget is gone.
08-31 11:16:03.344  7269  7269 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 11:16:03.344  7269  7269 D WeatherAncestor: connectivity changed - connection : true
08-31 11:16:03.344  7269  7269 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@199cb89f
08-31 11:16:03.345  7269  7269 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 11:16:03.345  7269  7269 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 11:16:03.345  7269  7269 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 11:16:03.345  7269  7269 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 11:16:03.345  7269  7269 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:16:3
08-31 11:16:03.347  7056  7056 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:16:03.347  7056  7056 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:16:03.347  7056  7056 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:16:03.347  7056  7056 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:03.347  7056  7056 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 11:16:03.363  7598  7598 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 11:16:03.403  1081  2060 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7602 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 11:16:03.430  7619  7619 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 11:16:03.441  7622  7622 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 11:16:03.467  7624  7624 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 11:16:03.470  7602  7602 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:16:03.481  7625  7625 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-31 11:16:03.487  1081  1747 I ActivityManager: Killing 6569:com.android.vending/u0a44 (adj 15): empty #17
08-31 11:16:03.496  7626  7626 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 11:16:03.507  7627  7627 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-31 11:16:03.530  7629  7629 I libmdmdetect: ESOC framework not supported
,08-31 11:16:03.531  7629  7629 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-31 11:16:03.537  1081  2037 W libprocessgroup: failed to open /acct/uid_10044/pid_6569/cgroup.procs: No such file or directory
08-31 11:16:03.540  7629  7629 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-31 11:16:03.540  7629  7629 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-31 11:16:03.540  7629  7629 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-31 11:16:03.540  7629  7629 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 11:16:03.540  7629  7629 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 11:16:03.540  7629  7629 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-31 11:16:03.540  7629  7629 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-31 11:16:03.582  7629  7630 E QC-QMI  : qmi_client [7629] 14: failed to locate client data
08-31 11:16:03.583   465   465 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-31 11:16:03.583   465   465 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-31 11:16:03.635  1081  1172 W ProcessCpuTracker: Skipping unknown process pid 7539
,08-31 11:16:03.636  1081  1172 W ProcessCpuTracker: Skipping unknown process pid 7542
,08-31 11:16:03.681  7634  7634 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 11:16:03.703  7635  7635 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 11:16:03.741  7056  7525 I bt_vendor: bluetooth satus is on
,08-31 11:16:03.741  7056  7525 D bt_hci_bdroid: preload
08-31 11:16:03.741  7056  7596 D bt_userial_mct: userial_open(port:0)
,08-31 11:16:03.741  7056  7596 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 11:16:03.745  7056  7596 I bt_vendor: Done intiailizing UART
,08-31 11:16:03.746  7056  7596 I bt_vendor: Done intiailizing UART
08-31 11:16:03.746  7056  7596 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 11:16:03.746  7056  7596 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 11:16:03.746  7056  7637 D bt_userial_mct: Entering userial_read_thread()
08-31 11:16:03.747  7056  7594 I bt-btu  : btu_task received preload complete event
08-31 11:16:03.747  7056  7594 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-31 11:16:03.747  7056  7594 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-31 11:16:03.749  7056  7594 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 11:16:03.753  7056  7594 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 11:16:03.846  7056  7594 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-31 11:16:03.846  7056  7594 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0226061 
08-31 11:16:03.846  7056  7594 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0226061 
,08-31 11:16:03.893  7056  7529 E bt-btif : Calling BTA_HhEnable
,08-31 11:16:03.901  7056  7529 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-31 11:16:03.902  7056  7529 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-31 11:16:03.903  7056  7594 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-31 11:16:03.903  7056  7594 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-31 11:16:03.903  7056  7594 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-31 11:16:03.903  7056  7594 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 11:16:03.903  7056  7594 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-31 11:16:03.906  7056  7529 D BluetoothAdapterProperties: Name is: G3
08-31 11:16:03.907  1081  1081 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 11:16:03.909  7056  7529 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:16:03.910  1081  1081 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 11:16:03.910  7056  7529 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:16:03.910  7056  7529 D bt_hci_bdroid: postload
08-31 11:16:03.910  7056  7596 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:16:03.912  7056  7529 D bte_conf: Device ID record 1 : primary
08-31 11:16:03.912  7056  7529 D bte_conf:   vendorId            = 00c4
08-31 11:16:03.912  7056  7529 D bte_conf:   vendorIdSource      = 0001
08-31 11:16:03.912  7056  7529 D bte_conf:   product             = 13a1
08-31 11:16:03.912  7056  7529 D bte_conf:   version             = 1000
08-31 11:16:03.912  7056  7529 D bte_conf:   clientExecutableURL = 
08-31 11:16:03.912  7056  7529 D bte_conf:   serviceDescription  = 
08-31 11:16:03.912  7056  7529 D bte_conf:   documentationURL    = 
08-31 11:16:03.912  7056  7529 D bte_conf: bte_load_did_conf no section named DID2.
08-31 11:16:03.916  7056  7594 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-31 11:16:03.921  7056  7525 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 11:16:03.921  7056  7525 D BluetoothAdapterProperties: ScanMode =  20
08-31 11:16:03.921  7056  7525 D BluetoothAdapterProperties: State =  11
08-31 11:16:03.922  7056  7525 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 11:16:03.922  7056  7525 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 11:16:03.922  7056  7525 D BluetoothAdapterProperties: Setting state to 12
08-31 11:16:03.922  7056  7525 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 11:16:03.925  7056  7596 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:16:03.925  7056  7596 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:16:03.925  7056  7596 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:16:03.929  7056  7525 I BluetoothAdapterState: Entering On State
08-31 11:16:03.915  7642  7642 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:03.915  7642  7642 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:03.943  7056  7594 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:16:03.943  7056  7594 W bt-smp  : Plain text(LSB ~ MSB) = bd e0 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:16:03.943  7056  7594 W bt-smp  : Encrypted text(LSB ~ MSB) = e1 14 1e b8 58 ce c4 7c 7e 50 17 6a 34 7f ed d0 
08-31 11:16:03.943  7056  7594 W bt-btm  : Stopping oneshot timer
08-31 11:16:03.943  7056  7596 D bt_hci_bdroid: Used up Tx Cmd credits
,08-31 11:16:03.946  7056  7637 E bt_mct  : hci lib postload completed
08-31 11:16:03.947  1081  1176 D BluetoothManagerService: Message: 60
08-31 11:16:03.948  7056  7529 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 11:16:03.948  7056  7529 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 11:16:03.947  1081  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 11:16:03.955  1081  1176 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-31 11:16:03.959  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:03.959  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:03.959  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:16:03.959  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:03.959  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:03.959  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:03.959  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:03.959  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:16:03.964  7056  7525 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 11:16:03.964  7056  7525 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 11:16:03.964  7056  7525 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-31 11:16:03.965  1862  1878 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:16:03.967  7056  7525 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 11:16:03.969  6631  6631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:16:03.972  7056  7529 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:16:03.972  7056  7529 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-31 11:16:03.980  7056  7525 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-31 11:16:03.986  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:03.986  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:03.986  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:16:03.986  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:03.986  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:03.986  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:03.986  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:03.986  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:16:03.991  6631  6631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:16:03.998  6909  6928 D BluetoothPan: onBluetoothStateChange on: true
08-31 11:16:03.998  6909  6928 D BluetoothPan: onBluetoothStateChange call bindService
08-31 11:16:04.001  1862  1862 D BluetoothHeadset: Proxy object connected
08-31 11:16:04.008  6909  6909 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:16:04.009  6909  6909 D PanProfile: Bluetooth service connected
08-31 11:16:04.010  6909  7177 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 11:16:04.015  1081  1176 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:16:04.016  1081  1081 D BluetoothHeadset: Proxy object connected
08-31 11:16:04.018  6909  6927 D BluetoothMap: onBluetoothStateChange: up=true
08-31 11:16:04.022  7056  7594 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:16:04.022  7056  7594 W bt-smp  : Plain text(LSB ~ MSB) = e5 93 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:16:04.022  7056  7594 W bt-smp  : Encrypted text(LSB ~ MSB) = 99 9a ff 3c da c0 2a 5a 95 5e 5f 62 d1 3f b2 cf 
08-31 11:16:04.022  7056  7594 W bt-btm  : Stopping oneshot timer
08-31 11:16:04.022  1081  1176 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:16:04.023  6909  6909 D BluetoothMap: Proxy object connected
08-31 11:16:04.023  6909  6909 D MapProfile: Bluetooth service connected
08-31 11:16:04.023  6909  6909 D BluetoothMap: getConnectedDevices()
,08-31 11:16:04.025  1081  1081 D BluetoothA2dp: Proxy object connected
08-31 11:16:04.025  6909  6927 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 11:16:04.028  1862  4407 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:16:04.029  7657  7657 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-31 11:16:04.033  1862  4854 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:16:04.033  1862  1862 D BluetoothHeadset: Proxy object connected
08-31 11:16:04.033  7056  7072 V BluetoothMapService: getConnectedDevices()
08-31 11:16:04.034  6909  6909 D BluetoothInputDevice: Proxy object connected
08-31 11:16:04.034  6909  6909 D HidProfile: Bluetooth service connected
08-31 11:16:04.035  1862  1862 D BluetoothHeadset: Proxy object connected
,08-31 11:16:04.035  1081  1176 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 11:16:04.036  1081  1176 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 11:16:04.037  1081  1081 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-31 11:16:04.037  1081  1176 D BluetoothManagerService: Message: 40
08-31 11:16:04.037  1081  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 11:16:04.037  7056  7594 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:16:04.037  7056  7594 W bt-smp  : Plain text(LSB ~ MSB) = 39 23 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:16:04.037  7056  7594 W bt-smp  : Encrypted text(LSB ~ MSB) = 27 4b a1 3a 21 6e f9 e1 4c 70 56 2b 32 ed 00 63 
08-31 11:16:04.038  7056  7594 W bt-btm  : Stopping oneshot timer
08-31 11:16:04.038  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:04.038  1951  2129 D LGBluetoothAPIService: Message: 1
08-31 11:16:04.039  1951  2129 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 11:16:04.040  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:16:04.047  6909  6909 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 11:16:04.049  6631  6631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 11:16:04.051  1081  1176 D BluetoothManagerService: Message: 30
08-31 11:16:04.052  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:04.052  1951  2129 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-31 11:16:04.052  7056  7594 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:16:04.053  7056  7594 W bt-smp  : Plain text(LSB ~ MSB) = 81 60 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:16:04.053  7056  7594 W bt-smp  : Encrypted text(LSB ~ MSB) = 95 4a cf e4 b1 c7 d6 b9 9d d2 a4 d5 91 b3 0c 95 
08-31 11:16:04.053  7056  7594 W bt-btm  : Stopping oneshot timer
08-31 11:16:04.054  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:04.056  7056  7056 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:04.057  7056  7056 D BluetoothMapService: STATE_ON
08-31 11:16:04.058  6909  6909 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 11:16:04.059  7056  7056 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-31 11:16:04.059  7056  7056 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 11:16:04.061  1951  1951 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-31 11:16:04.061  1951  2129 D LGBluetoothAPIService: Message: 100
08-31 11:16:04.062  1951  2129 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 11:16:04.062  1081  1176 D BluetoothManagerService: Message: 30
08-31 11:16:04.066  7056  7594 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:16:04.066  7056  7594 W bt-smp  : Plain text(LSB ~ MSB) = dc df 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:16:04.066  7056  7594 W bt-smp  : Encrypted text(LSB ~ MSB) = c7 85 af f0 e5 0c 5f 2e 2b b1 53 af 5d 42 75 76 
08-31 11:16:04.066  7056  7594 W bt-btm  : Stopping oneshot timer
08-31 11:16:04.068  6909  6909 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 11:16:04.070  6909  6909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 11:16:04.072  6909  6909 D BluetoothA2dp: Proxy object connected
08-31 11:16:04.073  6909  6909 D A2dpProfile: Bluetooth service connected
08-31 11:16:04.075  6909  6909 D BluetoothHeadset: Proxy object connected
08-31 11:16:04.076  6909  6909 D HeadsetProfile: Bluetooth service connected
,08-31 11:16:04.081  6909  6909 D DockEventReceiver: finishStartingService: stopping service
08-31 11:16:04.085  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:04.085  7056  7056 V BluetoothPbapService: Pbap Service onCreate
08-31 11:16:04.085  7056  7056 V BluetoothPbapService: Starting PBAP service
08-31 11:16:04.086  7056  7056 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 11:16:04.086  7056  7056 V BluetoothPbapService: Pbap Service onBind
08-31 11:16:04.087  7056  7056 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:16:04.087  6909  6909 D BluetoothPbap: Proxy object connected
08-31 11:16:04.087  7056  7056 V BluetoothPbapService: state: 12
08-31 11:16:04.087  7056  7056 V BluetoothMapService: Handler(): got msg=1
08-31 11:16:04.088  7056  7056 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 11:16:04.088  6909  6909 D PbapServerProfile: Bluetooth service connected
08-31 11:16:04.088  7056  7056 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:16:04.089  7056  7056 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:04.089  7056  7056 V BluetoothPbapReceiver: ***********state = 12
08-31 11:16:04.090  7056  7663 D BluetoothMapMasInstance: MAS initSocket()
08-31 11:16:04.090  7056  7056 V BluetoothPbapService: Handler(): got msg=1
08-31 11:16:04.090  7056  7663 D BluetoothMapMasInstance:   masId = 00
08-31 11:16:04.090  7056  7663 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 11:16:04.090  7056  7663 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 11:16:04.090  7056  7663 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 11:16:04.092  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:16:04.092  1081  2060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:04.092  7056  7056 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 11:16:04.093  2246  2246 D c       : Getting all permits...
08-31 11:16:04.093  2246  2246 D a       : Opening database...
08-31 11:16:04.093  7056  7663 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:04.093  7056  7664 V BluetoothPbapService: Pbap Service initSocket
08-31 11:16:04.094  1081  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:04.095  7056  7663 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 11:16:04.095  7056  7663 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 11:16:04.095  7056  7663 D BluetoothMapMasInstance: Accepting socket connection...
08-31 11:16:04.095  7056  7529 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:16:04.095  7056  7529 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-31 11:16:04.097  2246  2246 D a       : Opening database auth.proximity.permit_store...
08-31 11:16:04.098  2246  2246 D a       : Closing database...
08-31 11:16:04.099  7056  7664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:04.099  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:04.100  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:04.101  7056  7664 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 11:16:04.101  7056  7664 V BluetoothPbapService: Succeed to create listening socket 
08-31 11:16:04.101  7056  7664 V BluetoothPbapService: Accepting socket connection...
08-31 11:16:04.107  6909  6909 D BluetoothPermissionRequest: onReceive
08-31 11:16:04.109  6909  6909 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 11:16:04.110  6909  6909 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 11:16:04.113  7056  7056 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-31 11:16:04.114  7056  7056 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-31 11:16:04.119  7056  7056 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-31 11:16:04.144  7056  7056 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-31 11:16:04.144  7056  7056 V BtOppService: onCreate
08-31 11:16:04.148  7056  7056 V BluetoothOppNotification: send message
08-31 11:16:04.153  7056  7056 V BtOppService: Starting RfcommListener
08-31 11:16:04.158  7056  7056 D BluetoothOppPreference: Dumping Names:  
08-31 11:16:04.158  7056  7056 D BluetoothOppPreference: {}
,08-31 11:16:04.158  7056  7056 D BluetoothOppPreference: Dumping Channels:  
08-31 11:16:04.158  7056  7056 D BluetoothOppPreference: {}
08-31 11:16:04.160  7056  7056 V BtOppService: onStartCommand
08-31 11:16:04.168  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:04.169  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 11:16:04.170  7056  7671 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 11:16:04.174  7056  7667 V BtOppService: Deleted complete outbound shares, number =  0
08-31 11:16:04.175  7056  7056 V BluetoothOppNotification: new notify threadi!
08-31 11:16:04.176  7056  7667 V BtOppService: Deleted complete inbound failed shares, number = 0
,08-31 11:16:04.176  7056  7056 V BluetoothOppNotification: send delay message
08-31 11:16:04.177  7056  7056 V BtOppService: start RfcommListener
08-31 11:16:04.179  7056  7667 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 11:16:04.180  7056  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 11:16:04.181  7056  7056 V BtOppService: RfcommListener started
08-31 11:16:04.181  7056  7667 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@194be68 on behalf of 
08-31 11:16:04.181  7056  7056 V BtOppService: ContentObserver received notification
,08-31 11:16:04.181  7056  7056 V BtOppService: ContentObserver received notification
08-31 11:16:04.183  7056  7673 V BtOppRfcommListener: Starting RFCOMM listener....
08-31 11:16:04.184  1081  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:04.184  7056  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ac8f281 on behalf of 
08-31 11:16:04.184  7308  7347 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-31 11:16:04.185  7056  7673 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:04.185  7056  7671 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 11:16:04.185  7056  7672 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 11:16:04.186  7056  7673 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-31 11:16:04.186  7056  7673 V BtOppRfcommListener: Started RFCOMM listener....
08-31 11:16:04.186  7056  7673 I BtOppRfcommListener: Accept thread started.
08-31 11:16:04.186  7056  7673 V BtOppRfcommListener: Accepting connection...
08-31 11:16:04.187  7056  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 11:16:04.187  7056  7671 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@238bf26 on behalf of 
08-31 11:16:04.188  7056  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39cb2767 on behalf of 
,08-31 11:16:04.189  7056  7672 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-31 11:16:04.191  7056  7671 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 11:16:04.191  7056  7671 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 11:16:04.192  7056  7672 V BluetoothOppNotification: outbound notification was removed.
08-31 11:16:04.192  7056  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 11:16:04.193  7056  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@222b5914 on behalf of 
08-31 11:16:04.193  7056  7671 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b1135bd on behalf of 
08-31 11:16:04.194  7056  7672 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 11:16:04.194  7056  7671 V BluetoothOppNotification: update too frequent, put in queue
08-31 11:16:04.195  7056  7671 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 11:16:04.196  7056  7672 V BluetoothOppNotification: inbound notification was removed.
08-31 11:16:04.196  7056  7672 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 11:16:04.197  7056  7672 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31e1a7b2 on behalf of 
08-31 11:16:04.197  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:04.198  7056  7056 V BluetoothFtpService: Ftp Service onCreate
08-31 11:16:04.198  7056  7056 I BluetoothFtpService: Ftp Service onCreate
08-31 11:16:04.198  7056  7056 V BluetoothFtpService: Ftp Service onStartCommand
08-31 11:16:04.198  7056  7056 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:04.198  7056  7056 V BluetoothFtpService: Starting Listening on sockets
08-31 11:16:04.198  7056  7056 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:16:04.199  7056  7056 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:16:04.199  7056  7056 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:16:04.199  7056  7056 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:04.199  7056  7056 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 11:16:04.199  7056  7056 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 11:16:04.201  7056  7056 V BluetoothFtpService: Handler(): got msg=1
,08-31 11:16:04.201  7056  7056 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 11:16:04.202  7056  7056 V BluetoothFtpService: Ftp Service initSocket
08-31 11:16:04.204  1081  1747 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:04.205  7056  7056 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:04.209  7056  7056 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-31 11:16:04.209  7056  7056 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 11:16:04.211  7056  7675 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-31 11:16:04.225  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
,08-31 11:16:04.225  7056  7056 V BluetoothSapService: Sap Service onCreate
08-31 11:16:04.227  7056  7056 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:04.227  7056  7056 V BluetoothSapService: state: 12
08-31 11:16:04.227  7056  7056 V BluetoothSapService: Starting SAP server process
,08-31 11:16:04.229  7056  7056 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-31 11:16:04.231  7056  7677 V BluetoothSapService: Sap Service initRfcommSocket
08-31 11:16:04.225  7676  7676 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:04.232  1081  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:04.225  7676  7676 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:04.232  7056  7677 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:04.233  7056  7677 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-31 11:16:04.233  7056  7677 V BluetoothSapService: Succeed to create listening socket 
08-31 11:16:04.234  7056  7677 V BluetoothSapService: Accepting socket connection...
08-31 11:16:04.243  7676  7676 V BT_SAP  : Event pipe created
08-31 11:16:04.243  7676  7676 V BT_SAP  : create_server_socket qcom.sap.server
08-31 11:16:04.243  7676  7676 V BT_SAP  : created socket fd 6
,08-31 11:16:04.760  1081  1374 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:16:04.760  1081  1374 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:16:04.789  1081  1375 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-31 11:16:04.789  1081  1375 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-31 11:16:05.062  1081  2032 I ActivityManager: Killing 7460:com.lge.bnr/1000 (adj 15): empty #17
,08-31 11:16:05.094  1081  1926 W libprocessgroup: failed to open /acct/uid_1000/pid_7460/cgroup.procs: No such file or directory
,08-31 11:16:05.178  7056  7056 V BluetoothOppNotification: new notify threadi!
,08-31 11:16:05.188  7056  7056 V BluetoothOppNotification: send delay message
08-31 11:16:05.194  7056  7687 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 11:16:05.204  1081  1695 I ActivityManager: Killing 7434:com.lge.sync/1000 (adj 15): empty #17
,08-31 11:16:05.227  7056  7687 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@48b9c5f on behalf of 
08-31 11:16:05.228  7056  7687 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-31 11:16:05.232  1081  1424 D WifiService: Client connection lost with reason: 4
08-31 11:16:05.233  7056  7687 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 11:16:05.234  7056  7687 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@990b6ac on behalf of 
08-31 11:16:05.235  7056  7687 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 11:16:05.237  7056  7687 V BluetoothOppNotification: outbound notification was removed.
08-31 11:16:05.237  7056  7687 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 11:16:05.238  7056  7687 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f4e5f75 on behalf of 
08-31 11:16:05.238  7056  7687 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-31 11:16:05.243  7056  7687 V BluetoothOppNotification: inbound notification was removed.
,08-31 11:16:05.243  7056  7687 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-31 11:16:05.244  7056  7687 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ef27b0a on behalf of 
,08-31 11:16:05.248  1081  1747 W libprocessgroup: failed to open /acct/uid_1000/pid_7434/cgroup.procs: No such file or directory
08-31 11:16:05.683  1081  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 11:16:05.683  1081  1558 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@334c191d mBinding = false
,08-31 11:16:05.714  1081  1081 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:16:05.714  1081  1081 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:16:05.714  1081  1081 D Ulp_jni : JNI:system_update. Event-4
,08-31 11:16:05.717  1081  1176 D BluetoothManagerService: Message: 2
08-31 11:16:05.718  1081  1176 D BluetoothManagerService: Sending off request.
08-31 11:16:05.718  7056  7071 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-31 11:16:05.719  7056  7525 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-31 11:16:05.719  7056  7525 D BluetoothAdapterProperties: Setting state to 13
08-31 11:16:05.719  7056  7525 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 11:16:05.720  7056  7525 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 11:16:05.720  7056  7525 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 11:16:05.722  7056  7529 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:16:05.726  7056  7525 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-31 11:16:05.730  7056  7664 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:16:05.730  7056  7673 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:16:05.731  7056  7663 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 11:16:05.731  7056  7663 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:16:05.731  7056  7663 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 11:16:05.731  7056  7663 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 11:16:05.731  7056  7663 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 11:16:05.731  7056  7663 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 11:16:05.731  7056  7663 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 11:16:05.731  7056  7663 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-31 11:16:05.731  7056  7525 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 11:16:05.732  7056  7675 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:16:05.733  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 11:16:05.733  7056  7594 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-31 11:16:05.737  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:16:05.737  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:16:05.737  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:16:05.737  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:16:05.737  7056  7594 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:16:05.737  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:16:05.737  7056  7594 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:16:05.737  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:16:05.737  7056  7594 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:16:05.737  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-31 11:16:05.737  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 11:16:05.737  7056  7594 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 11:16:05.742  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:05.742  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:05.742  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:05.742  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:16:05.742  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:05.742  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:05.742  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:05.742  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:05.742  6631  6631 V io.jxcore.node.ConnectivityMonito,r:     - active network type is Wi-Fi: false
,08-31 11:16:05.747  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:05.747  6631  6631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:16:05.750  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:05.750  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:05.750  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:05.750  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:16:05.750  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:05.750  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:16:05.750  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:05.750  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:05.750  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:16:05.759  6631  6631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:16:05.759  6631  6631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:16:05.763  1081  1176 D BluetoothManagerService: Message: 60
08-31 11:16:05.763  1081  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 11:16:05.763  1081  1176 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-31 11:16:05.768  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:05.769  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-31 11:16:05.779  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:05.781  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:05.783  7056  7056 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:05.783  7056  7056 D BluetoothMapService: STATE_TURNING_OFF
08-31 11:16:05.783  7056  7056 V BluetoothMapService: Handler(): got msg=4
08-31 11:16:05.783  7056  7056 D BluetoothMapService: MAP Service closeService in
08-31 11:16:05.783  7056  7056 D BluetoothMapMasInstance: MAP Service shutdown
08-31 11:16:05.783  7056  7056 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:16:05.783  7056  7056 V BluetoothMapService: MAP Service closeService out
08-31 11:16:05.784  7056  7056 V BtOppService: Receiver DISABLED_ACTION 
08-31 11:16:05.785  7056  7056 I BtOppRfcommListener: stopping Accept Thread
08-31 11:16:05.785  7056  7056 V BtOppRfcommListener: close mBtServerSocket
08-31 11:16:05.785  7056  7673 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 11:16:05.788  7056  7056 V BtOppRfcommListener: waiting for thread to terminate
08-31 11:16:05.788  7056  7056 V BtOppRfcommListener: done waiting for thread to terminate
08-31 11:16:05.793  7056  7677 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:16:05.797  6909  6909 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-31 11:16:05.802  6909  6909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 11:16:05.806  7056  7056 V BtOppService: onDestroy
08-31 11:16:05.808  7056  7056 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-31 11:16:05.813  7056  7056 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-31 11:16:05.813  7056  7056 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:05.813  7056  7056 V BluetoothPbapReceiver: ***********state = 13
08-31 11:16:05.815  7056  7056 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-31 11:16:05.817  7056  7056 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:05.817  7056  7056 V BluetoothPbapService: state: 13
08-31 11:16:05.817  7056  7056 V BluetoothPbapService: Pbap Service closeService in
08-31 11:16:05.820  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:16:05.824  7056  7056 V BluetoothPbapService: successfully stopped pbap service
08-31 11:16:05.824  7056  7056 V BluetoothPbapService: Pbap Service closeService out
,08-31 11:16:05.827  7056  7056 V BluetoothPbapService: Pbap Service onDestroy
08-31 11:16:05.827  7056  7056 V BluetoothPbapService: Pbap Service closeService in
08-31 11:16:05.827  7056  7056 V BluetoothPbapService: Pbap Service closeService out
08-31 11:16:05.827  7056  7056 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-31 11:16:05.854  6909  6909 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:16:05.858  6909  6909 D BluetoothPbap: Proxy object disconnected
08-31 11:16:05.858  6909  6909 D PbapServerProfile: Bluetooth service disconnected
08-31 11:16:05.866  6909  6909 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-31 11:16:05.873  6909  6909 D BluetoothPermissionRequest: onReceive
,08-31 11:16:05.873  6909  6909 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 11:16:05.878  6909  6909 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:16:05.882  7056  7056 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-31 11:16:05.882  7056  7056 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-31 11:16:05.882  7056  7056 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-31 11:16:05.887  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:05.887  7056  7056 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 11:16:05.889  7056  7056 V BluetoothFtpService: Ftp Service onStartCommand
08-31 11:16:05.889  7056  7056 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:05.889  7056  7056 V BluetoothFtpService: Ftp Service closeService
08-31 11:16:05.889  7056  7056 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-31 11:16:05.890  7056  7056 V BluetoothFtpService: successfully stopped ftp service
08-31 11:16:05.890  7056  7056 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:16:05.890  7056  7056 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:16:05.890  7056  7056 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:16:05.891  7056  7056 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:05.891  7056  7056 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-31 11:16:05.891  7056  7056 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 11:16:05.892  7056  7056 V BluetoothFtpService: Ftp Service onDestroy
08-31 11:16:05.892  7056  7056 V BluetoothFtpService: Ftp Service closeService
08-31 11:16:05.895  7056  7056 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:05.895  7056  7056 V BluetoothSapService: state: 13
08-31 11:16:05.895  7056  7056 V BluetoothSapService: Stopping SAP server process
,08-31 11:16:05.897  7056  7056 V BluetoothSapService: Sap Service closeSapService in
,08-31 11:16:05.897  7056  7056 V BluetoothSapService: Close listen Socket : 
,08-31 11:16:05.897  7056  7056 V BluetoothSapService: Close rfcomm Socket : 
,08-31 11:16:05.897  7056  7056 V BluetoothSapService: Close sapd  Socket : 
08-31 11:16:05.899  7056  7056 V BluetoothSapService: Sap Service closeSapService out
,08-31 11:16:05.899  7056  7056 V BluetoothSapService: Sap Service onDestroy
08-31 11:16:05.899  7056  7056 V BluetoothSapService: Sap Service closeSapService in
08-31 11:16:05.899  7056  7056 V BluetoothSapService: Close listen Socket : 
08-31 11:16:05.899  7056  7056 V BluetoothSapService: Close rfcomm Socket : 
08-31 11:16:05.899  7056  7056 V BluetoothSapService: Close sapd  Socket : 
08-31 11:16:05.901  7056  7056 V BluetoothSapService: Sap Service closeSapService out
08-31 11:16:06.640  7056  7529 D bt_hci_bdroid: cleanup
,08-31 11:16:06.652  7056  7596 I bt_lpm  : LPM is already off!!!
08-31 11:16:06.652  7056  7637 I bt_userial_mct: exiting userial_read_thread
08-31 11:16:06.652  7056  7637 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 11:16:06.653  7056  7594 W bt-btif : ag scb idx 1 not allocated
08-31 11:16:06.653  7056  7594 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 11:16:06.653  7056  7594 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:16:06.653  7056  7594 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 11:16:06.654  7056  7529 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 11:16:06.654  7056  7596 I bt_vendor: hw_epilog_process
08-31 11:16:06.655  7056  7529 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 11:16:06.655  7056  7529 D bt_userial_mct: userial_close
08-31 11:16:06.655  7056  7529 E bt_userial_mct: pthread_join() FAILED result:3
08-31 11:16:06.655  7056  7529 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-31 11:16:06.659  7056  7529 D bt_hci_bdroid: set_power 0
08-31 11:16:06.659  7056  7529 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 11:16:06.659  7056  7529 I bt_vendor: bluetooth satus is on
08-31 11:16:06.659  7056  7529 I bt_vendor: bt-vendor : resetting BT status
08-31 11:16:06.659  7056  7529 I bt_vendor: Starting hciattach daemon
08-31 11:16:06.659  7056  7529 I bt_vendor: try to set false
08-31 11:16:06.663  7056  7529 I bt_vendor: Starting hciattach daemon
08-31 11:16:06.663  7056  7529 I bt_vendor: try to set false
,08-31 11:16:06.667  7056  7529 I bt_vendor: cleanup
08-31 11:16:06.668  7056  7594 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 11:16:06.668  7056  7529 I GKI_LINUX: GKI_exit_task 0 done
08-31 11:16:06.668  7056  7529 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-31 11:16:06.670  7056  7525 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 11:16:06.675  7056  7056 D HeadsetService: Received stop request...Stopping profile...
,08-31 11:16:06.679  7056  7056 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 11:16:06.679  7056  7056 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:16:06.679  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:06.680  7056  7564 D HeadsetStateMachine: Exit Disconnected: -1
08-31 11:16:06.685  7056  7525 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 11:16:06.685  1081  1081 D BluetoothHeadset: Proxy object disconnected
08-31 11:16:06.685  1081  1081 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 11:16:06.686  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-31 11:16:06.686  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-31 11:16:06.686  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-31 11:16:06.688  7056  7056 D A2dpService: Received stop request...Stopping profile...
,08-31 11:16:06.692  7056  7579 D A2dpStateMachine: Exit Disconnected: -1
08-31 11:16:06.693  7056  7056 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-31 11:16:06.694  7056  7056 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 11:16:06.694  7056  7056 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:16:06.694  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:06.696  1081  1081 D BluetoothA2dp: Proxy object disconnected
08-31 11:16:06.696  1081  1081 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-31 11:16:06.698  7056  7056 D HidService: Received stop request...Stopping profile...
08-31 11:16:06.698  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:06.700  7056  7056 D HealthService: Received stop request...Stopping profile...
,08-31 11:16:06.703  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:06.706  7056  7056 D HeadsetStateMachine: Unbinding service...
08-31 11:16:06.706  7056  7056 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:16:06.707  7056  7056 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:16:06.707  7056  7056 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:16:06.707  7056  7056 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:16:06.707  7056  7056 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 11:16:06.707  7056  7056 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:16:06.707  7056  7056 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 11:16:06.708  7056  7056 D PanService: Received stop request...Stopping profile...
08-31 11:16:06.709  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:06.710  7056  7056 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:16:06.711  7056  7056 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 11:16:06.711  7056  7056 D BtGatt.GattService: stop()
08-31 11:16:06.711  7056  7056 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 11:16:06.716  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:06.718  7056  7056 D BluetoothMapService: Received stop request...Stopping profile...
08-31 11:16:06.718  7056  7056 D BluetoothMapService: stop()
08-31 11:16:06.719  7056  7056 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 11:16:06.719  7056  7056 D BluetoothMapEmailAppObserver: removeReceiver()
08-31 11:16:06.720  7056  7056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@199cb89f
08-31 11:16:06.721  7056  7056 I BluetoothA2dpServiceJni: cleanupNative
08-31 11:16:06.721  7056  7580 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 11:16:06.721  7056  7056 I GKI_LINUX: GKI_exit_task 2 done
08-31 11:16:06.722  7056  7056 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 11:16:06.722  7056  7056 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:16:06.722  7056  7056 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 11:16:06.722  7056  7056 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:16:06.723  7056  7056 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:16:06.723  7056  7056 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:16:06.723  7056  7056 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:16:06.723  7056  7056 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 11:16:06.726  7056  7056 V BluetoothMapService: Handler(): got msg=4
08-31 11:16:06.726  7056  7056 D BluetoothMapService: MAP Service closeService in
08-31 11:16:06.726  7056  7056 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:16:06.726  7056  7056 V BluetoothMapService: MAP Service closeService out
,08-31 11:16:06.729  7056  7525 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 11:16:06.731  7056  7525 D BluetoothAdapterProperties: Setting state to 10
08-31 11:16:06.731  7056  7525 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 11:16:06.731  7056  7056 D BluetoothMapService: cleanup()
08-31 11:16:06.731  7056  7056 D BluetoothMapService: MAP Service closeService in
08-31 11:16:06.731  7056  7056 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 11:16:06.731  7056  7056 V BluetoothMapService: MAP Service closeService out
08-31 11:16:06.732  1081  1176 D BluetoothManagerService: Message: 60
08-31 11:16:06.733  1081  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 11:16:06.733  1081  1176 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-31 11:16:06.733  7056  7525 I BluetoothAdapterState: Entering OffState
08-31 11:16:06.733  1862  2545 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:16:06.734  6909  7177 D BluetoothPan: onBluetoothStateChange on: false
08-31 11:16:06.735  6909  7177 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:16:06.735  6909  7177 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:16:06.736  6909  7177 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 11:16:06.739  1081  1176 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 11:16:06.742  6909  7177 D BluetoothMap: onBluetoothStateChange: up=false
08-31 11:16:06.744  6909  6909 D BluetoothInputDevice: Proxy object disconnected
08-31 11:16:06.744  6909  6909 D HidProfile: Bluetooth service disconnected
08-31 11:16:06.744  1081  1176 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:16:06.744  6909  7177 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 11:16:06.745  1862  1877 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:16:06.745  1862  1878 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:16:06.746  1081  1176 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 11:16:06.746  1081  1176 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-31 11:16:06.748  1081  1176 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-31 11:16:06.748  1081  1176 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 11:16:06.748  1081  1176 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@334c191d mBinding = false
08-31 11:16:06.749  1081  1176 D BluetoothManagerService: Sending unbind request.
08-31 11:16:06.754  7056  7529 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-31 11:16:06.757  7056  7056 I GKI_LINUX: GKI_exit_task 1 done
08-31 11:16:06.757  7056  7056 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 11:16:06.758  7056  7056 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 11:16:06.758  7056  7056 I art     : --- WEIRD: removing null entry 248
08-31 11:16:06.758  7056  7056 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-31 11:16:06.758  7056  7056 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 11:16:06.759  7056  7056 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-31 11:16:06.760  1081  1176 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-31 11:16:06.762  7056  7056 I art     : System.exit called, status: 0
08-31 11:16:06.762  7056  7056 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 11:16:06.782   323  1382 V AudioFlinger: 7056 died, releasing its sessions
08-31 11:16:06.782   323  1382 V AudioFlinger:  pid 1862 @ 0
08-31 11:16:06.782   323  1382 V AudioFlinger:  pid 3333 @ 1
08-31 11:16:06.782   323  1382 V AudioFlinger:  pid 3333 @ 2
,08-31 11:16:06.786  1951  1951 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-31 11:16:06.786  1951  2129 D LGBluetoothAPIService: Message: 101
08-31 11:16:06.787  1951  2129 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-31 11:16:06.787  1951  2129 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-31 11:16:06.787  1951  2129 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-31 11:16:06.794  6909  6909 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-31 11:16:06.829  1081  1558 I ActivityManager: Process com.android.bluetooth (pid 7056) has died
08-31 11:16:06.829  1081  1558 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-31 11:16:06.830  1081  1558 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-31 11:16:06.836  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:16:06.837  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:16:06.840  1951  2129 D LGBluetoothAPIService: Message: 2
08-31 11:16:06.840  1951  2129 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-31 11:16:06.841  6909  6909 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-31 11:16:06.842  6909  6909 D LGBluetoothEventManager: [BTUI] clear device connection state
08-31 11:16:06.844  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:06.846  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:06.847  1585  1585 D BluetoothAdapter: 21309784: getState() :  mService = null. Returning STATE_OFF
08-31 11:16:06.847  1585  1585 D BluetoothAdapter: 21309784: getState() :  mService = null. Returning STATE_OFF
08-31 11:16:06.849  6909  6909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 11:16:06.891  1081  1986 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7735 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-31 11:16:06.893  6909  6909 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:16:06.969  7735  7735 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 11:16:06.970  7735  7735 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:16:06.970  7735  7735 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 11:16:06.971  7735  7735 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 11:16:06.993  7735  7735 D BluetoothAdapterApp: Loading JNI Library
,08-31 11:16:07.029  7735  7735 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1a5dfba7 Instance Count = 1
,08-31 11:16:07.035  7735  7735 D BluetoothAdapterApp: onCreate
,08-31 11:16:07.059  7735  7735 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-31 11:16:07.060  7735  7735 D ProfileConfigQcom: Adding HeadsetService
,08-31 11:16:07.060  7735  7735 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-31 11:16:07.060  7735  7735 D ProfileConfigQcom: Adding A2dpService
,08-31 11:16:07.060  7735  7735 D ProfileConfigQcom: [BTUI] HidService is supported
,08-31 11:16:07.060  7735  7735 D ProfileConfigQcom: Adding HidService
,08-31 11:16:07.061  7735  7735 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-31 11:16:07.061  7735  7735 D ProfileConfigQcom: Adding HealthService
08-31 11:16:07.061  7735  7735 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-31 11:16:07.062  7735  7735 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 11:16:07.062  7735  7735 D ProfileConfigQcom: Adding PanService
08-31 11:16:07.062  7735  7735 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 11:16:07.063  7735  7735 D ProfileConfigQcom: Adding GattService
,08-31 11:16:07.063  7735  7735 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 11:16:07.063  7735  7735 D ProfileConfigQcom: Adding BluetoothMapService
08-31 11:16:07.063  7735  7735 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 11:16:07.064  7735  7735 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:16:07.065  7735  7735 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:07.066  7735  7735 V BluetoothPbapReceiver: ***********state = 10
08-31 11:16:07.067  7735  7735 V LGMDMManagerInternal: Create singleton instance
,08-31 11:16:07.134  7735  7735 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-31 11:16:07.134  7735  7735 D LGBluetoothAPIServer: [BTUI] onBind()
,08-31 11:16:07.139  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:16:07.139  1951  1951 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-31 11:16:07.140  1951  2129 D LGBluetoothAPIService: Message: 100
08-31 11:16:07.140  1951  2129 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 11:16:07.149  6909  6909 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-31 11:16:07.163  6909  6909 D BluetoothPermissionRequest: onReceive
,08-31 11:16:07.166  6909  6909 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 11:16:07.166  6909  6909 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-31 11:16:07.168  6909  6909 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:16:07.172  7735  7735 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-31 11:16:07.176  7735  7735 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:16:07.180  7735  7735 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:16:07.181  7735  7735 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:16:07.181  7735  7735 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:16:07.182  7735  7735 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:07.182  7735  7735 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-31 11:16:07.190  7602  7602 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-31 11:16:08.799  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:16:08.799  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:16:08.825  1585  1585 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-31 11:16:08.859  2061  2061 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-31 11:16:08.905  1081  1364 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 11:16:08.932  1081  1172 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7775 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-31 11:16:08.936  1585  1585 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-31 11:16:08.937  1585  1585 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-31 11:16:08.942  1081  1081 D administrator: Handling package changes for user 0
08-31 11:16:08.984  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 11:16:09.008  7775  7775 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 11:16:09.061  1081  1081 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-31 11:16:09.061  1081  1081 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-31 11:16:09.111  7775  7775 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:16:09.111  7775  7775 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:16:09.119  1081  1171 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:16:09.125  1081  1171 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-31 11:16:09.133  2441  2441 V GmsNetworkLocationProvi: DISABLE
08-31 11:16:09.133  2061  2061 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-31 11:16:09.170  1081  1171 D LocationProviderProxy: applying state to connected service
08-31 11:16:09.171  2441  2441 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-31 11:16:09.273  7775  7813 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-31 11:16:09.274  7775  7813 I Babel   : MmsConfig.loadMmsSettings
08-31 11:16:09.284  7775  7813 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-31 11:16:09.284  7775  7813 I Babel   : MmsConfig.loadFromDatabase
,08-31 11:16:09.309  7775  7813 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-31 11:16:09.309  7775  7813 I Babel   : MmsConfig.loadFromResources
08-31 11:16:09.311  7775  7813 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-31 11:16:09.312  7775  7813 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-31 11:16:09.325  7775  7775 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:09.331  7775  7809 W AudioCapabilities: Unsupported mime audio/evrc
08-31 11:16:09.333  7775  7809 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 11:16:09.335  7775  7809 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:16:09.348  7775  7809 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-31 11:16:09.349  7775  7809 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 11:16:09.351  7775  7809 W AudioCapabilities: Unsupported mime audio/evrc
08-31 11:16:09.360  1802  7817 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-31 11:16:09.360  1802  7817 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-31 11:16:09.369  7125  7125 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 11:16:09.374  7125  7125 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@92a2f9
08-31 11:16:09.374  7125  7125 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 11:16:09.374  7125  7125 D AppUp4:CustFacade: isPhone : true
08-31 11:16:09.375  7125  7125 D AppUp4:CustModeStarterReceiver: begin check event
08-31 11:16:09.375  7125  7125 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-31 11:16:09.376  1802  5159 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-31 11:16:09.388  7775  7809 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 11:16:09.397  7775  7809 W VideoCapabilities: Unsupported mime video/divx
08-31 11:16:09.401  7775  7809 W VideoCapabilities: Unsupported mime video/divx311
,08-31 11:16:09.408  7775  7809 W VideoCapabilities: Unsupported mime video/divx4
08-31 11:16:09.415  7775  7809 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-31 11:16:09.425  1081  2060 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7825 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-31 11:16:09.431  1081  1747 I ActivityManager: Killing 6840:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-31 11:16:09.446  6982  6982 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-31 11:16:09.446  6982  6982 W System.err: android.os.DeadObjectException
08-31 11:16:09.446  7775  7809 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-31 11:16:09.446  6982  6982 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:16:09.447  6982  6982 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 11:16:09.447  6982  6982 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-31 11:16:09.447  6982  6982 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-31 11:16:09.447  6982  6982 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 11:16:09.447  6982  6982 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 11:16:09.447  6982  6982 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:16:09.447  6982  6982 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:16:09.447  6982  6982 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:16:09.447  6982  6982 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,08-31 11:16:09.447  6982  6982 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:09.447  6982  6982 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:16:09.447  6982  6982 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:16:09.447  6982  6982 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:16:09.447  6982  6982 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-31 11:16:09.448  6982  6982 W System.err: android.os.DeadObjectException
08-31 11:16:09.449  6982  6982 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:16:09.449  6982  6982 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 11:16:09.449  6982  6982 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-31 11:16:09.449  6982  6982 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,08-31 11:16:09.449  6982  6982 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,08-31 11:16:09.449  6982  6982 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
,08-31 11:16:09.449  6982  6982 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:16:09.449  6982  6982 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,08-31 11:16:09.449  6982  6982 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:16:09.449  6982  6982 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:16:09.449  6982  6982 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:09.449  6982  6982 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:16:09.449  6982  6982 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:16:09.449  6982  6982 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:16:09.449  6982  6982 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-31 11:16:09.450  6982  6982 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-31 11:16:09.453  7775  7809 W AudioCapabilities: Unsupported mime audio/eac3
08-31 11:16:09.454  7775  7809 W AudioCapabilities: Unsupported mime audio/ac3
08-31 11:16:09.455  7775  7809 W AudioCapabilities: Unsupported mime audio/g726
08-31 11:16:09.456  7775  7809 W AudioCapabilities: Unsupported mime audio/wma-voice
08-31 11:16:09.457  7775  7809 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-31 11:16:09.458  7775  7809 W AudioCapabilities: Unsupported mime audio/adpcm
08-31 11:16:09.460  7775  7809 W VideoCapabilities: Unsupported mime video/theora
08-31 11:16:09.462  7775  7809 W VideoCapabilities: Unsupported mime video/mjpg
08-31 11:16:09.661   279   279 E lowmemorykiller: Error opening /proc/6840/oom_score_adj; errno=2
,08-31 11:16:09.666  1081  1896 W ActivityManager: Exception when unbinding service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service
08-31 11:16:09.666  1081  1896 W ActivityManager: android.os.DeadObjectException
08-31 11:16:09.666  1081  1896 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:16:09.666  1081  1896 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 11:16:09.666  1081  1896 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-31 11:16:09.666  1081  1896 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-31 11:16:09.666  1081  1896 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-31 11:16:09.666  1081  1896 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-31 11:16:09.666  1081  1896 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-31 11:16:09.666  1081  1896 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-31 11:16:09.666  1081  1896 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-31 11:16:09.666  1081  1896 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 11:16:09.670  6982  6982 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-31 11:16:09.671  6982  6982 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 11:16:09.678  1081  2309 W libprocessgroup: failed to open /acct/uid_1000/pid_6840/cgroup.procs: No such file or directory
,08-31 11:16:09.704  7825  7825 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:16:09.704  7825  7825 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:16:09.704  7825  7825 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-31 11:16:09.706  7825  7825 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-31 11:16:09.706  7825  7825 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-31 11:16:09.717  1081  1927 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7843 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 11:16:09.718  6982  6982 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-31 11:16:09.766  1081  1427 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-31 11:16:09.778  7843  7843 D UEI.SmartControl: Quickset Services start...
,08-31 11:16:09.780  7843  7843 I UEI.SmartControl: Manufacture = LGE
08-31 11:16:09.780  7843  7843 D UEI.SmartControl: Id = LGNevo
08-31 11:16:09.781  7843  7843 D UEI.SmartControl: File observer start...
08-31 11:16:09.782  7843  7843 E UEI.SmartControl: IR Port is disabled: false
08-31 11:16:09.782  7843  7843 D UEI.SmartControl: Starting file observer...
08-31 11:16:09.782  7843  7843 D UEI.SmartControl: Extracting JNI libs...
08-31 11:16:09.782  7843  7843 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-31 11:16:09.784  7825  7825 I SystemConfig: BUILD Country: EU
08-31 11:16:09.784  7825  7825 I SystemConfig: BUILD Operator: OPEN
08-31 11:16:09.817  1081  2010 I ActivityManager: Killing 6982:com.lge.qremote/u0a112 (adj 15): empty #17
,08-31 11:16:09.852  7843  7843 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-31 11:16:09.852  7843  7843 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-31 11:16:09.852  7843  7843 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-31 11:16:09.873  7843  7843 I UEI.SmartControl: --- Selecting new region: 6
08-31 11:16:09.874  7843  7843 I UEI.SmartControl: Model = LG-D855
,08-31 11:16:09.875  7843  7843 D UEI.SmartControl: QS Service created
,08-31 11:16:09.935  1081  2310 W libprocessgroup: failed to open /acct/uid_10112/pid_6982/cgroup.procs: No such file or directory
,08-31 11:16:09.970  7843  7843 I UEI.SmartControl: Service initServices...
,08-31 11:16:09.976  7843  7843 D UEI.SmartControl: QS start get config
,08-31 11:16:10.016  1081  2010 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7865 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-31 11:16:10.024  7825  7863 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-31 11:16:10.024  7825  7863 I SystemConfig: existFile = false
08-31 11:16:10.025  7825  7863 I SystemConfig: canReadFile = false
08-31 11:16:10.025  7825  7863 I SystemConfig: systemFeature RCS result false
08-31 11:16:10.025  7825  7863 D SystemConfig: refreshRcsSupport() :false
08-31 11:16:10.037  7843  7843 D UEI.SmartControl: Loading JNI Libs...
,08-31 11:16:10.090  7865  7865 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:16:10.091  7865  7865 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 11:16:10.091  7865  7865 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-31 11:16:10.091  7865  7865 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 11:16:10.210  7865  7865 I AppConfig: Total System Memory = 2995761152
,08-31 11:16:10.220  7865  7865 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-31 11:16:10.291  7843  7843 I UEI.SmartControl: Supports setup maps: true
08-31 11:16:10.293  7843  7843 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 11:16:10.293  7843  7843 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 11:16:10.293  7843  7843 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 11:16:10.294  7843  7843 I UEI.SmartControl: ### init IR Blaster...
,08-31 11:16:10.301  1081  2060 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7887 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:16:10.301  7843  7843 D serial_port: Configuring serial port
08-31 11:16:10.301  1081  2060 I ActivityManager: Killing 7155:com.lge.email/u0a23 (adj 15): empty #17
08-31 11:16:10.304  7843  7843 E UEI.SmartControl: UEIBLaster setting for 616
08-31 11:16:10.304  7843  7843 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 11:16:10.304  7843  7843 I UEI.SmartControl: configuring settings for MAXQ616
08-31 11:16:10.305  7843  7843 I UEI.SmartControl: Get version...
08-31 11:16:10.321  7843  7896 D UEI.SmartControl: serial port data available: 21
,08-31 11:16:10.340  1081  2309 W libprocessgroup: failed to open /acct/uid_10023/pid_7155/cgroup.procs: No such file or directory
,08-31 11:16:10.348  7843  7843 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-31 11:16:10.348  7843  7843 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 11:16:10.348  7843  7843 I UEI.SmartControl: QS saving settings...
08-31 11:16:10.349  7843  7843 D UEI.SmartControl: IR Blaster version: 25672567
08-31 11:16:10.365  7843  7896 D UEI.SmartControl: serial port data available: 4
,08-31 11:16:10.396  7843  7908 I UEI.SmartControl: Device manager: loading config....
08-31 11:16:10.396  7843  7843 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-31 11:16:10.397  7843  7908 D UEI.SmartControl: ----------- loading internal config...
08-31 11:16:10.399  7843  7843 E UEI.SmartControl: Services init done
08-31 11:16:10.399  7843  7843 D UEI.SmartControl: QS Service init finished
08-31 11:16:10.399  7843  7843 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 11:16:10.399  7843  7843 D UEI.SmartControl: QS Service version code: 201091
08-31 11:16:10.399  7843  7843 D UEI.SmartControl: Service requested: Control
08-31 11:16:10.404  7843  7908 E UEI.SmartControl: Loading SETTINGS...
08-31 11:16:10.405  7843  7843 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 11:16:10.406  7843  7843 D UEI.SmartControl: Service.onUnbind: IControl
08-31 11:16:10.406  7843  7843 D UEI.SmartControl: Service.onDestroy
08-31 11:16:10.406  7843  7843 D UEI.SmartControl: Lock is in USE false
,08-31 11:16:10.406  7843  7843 D UEI.SmartControl: unbind internal service
08-31 11:16:10.407  7843  7843 D serial_port: close(fd = 25)
08-31 11:16:10.412  7843  7843 I UEI.SmartControl: Serial port is closed.
08-31 11:16:10.412  7843  7843 I UEI.SmartControl: Serial port is closed.
,08-31 11:16:10.416  7843  7908 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 11:16:10.418  7843  7907 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 11:16:10.418  7843  7907 D UEI.SmartControl: -----service ready thread exits
08-31 11:16:10.419  7843  7843 D UEI.SmartControl: Blaster closed
08-31 11:16:10.419  7843  7843 D UEI.SmartControl: Shut down QS...
08-31 11:16:10.419  7843  7843 D UEI.SmartControl: Stopping QS lib
08-31 11:16:10.420  7843  7843 D UEI.SmartControl: QS lib stop result = true
08-31 11:16:10.420  7843  7843 D UEI.SmartControl: Stopped QS lib
08-31 11:16:10.420  7843  7843 D UEI.SmartControl: Stopped file observer...
08-31 11:16:10.420  7843  7843 D UEI.SmartControl: QS shutdown complete
08-31 11:16:10.421  7843  7843 D UEI.SmartControl: QS Service created
08-31 11:16:10.430  7843  7843 I UEI.SmartControl: Service initServices...
08-31 11:16:10.430  7843  7843 D UEI.SmartControl: QS start get config
,08-31 11:16:10.492  7887  7887 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-31 11:16:10.573  7887  7887 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:16:10.573  7887  7887 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:16:10.625  7887  7887 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-31 11:16:10.645  7887  7887 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 11:16:10.646  7887  7887 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 11:16:10.662  7887  7887 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:16:10.662  7887  7887 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-31 11:16:10.678  1081  2010 I ActivityManager: Killing 7019:com.lge.formmanager/u0a26 (adj 15): empty #17
08-31 11:16:10.787  1081  1968 W libprocessgroup: failed to open /acct/uid_10026/pid_7019/cgroup.procs: No such file or directory
,08-31 11:16:10.811  5019  7930 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-31 11:16:10.812  7843  7843 I UEI.SmartControl: Supports setup maps: true
08-31 11:16:10.814  7843  7843 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 11:16:10.815  7843  7843 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 11:16:10.815  7843  7843 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 11:16:10.815  7843  7843 I UEI.SmartControl: ### init IR Blaster...
08-31 11:16:10.818  7843  7843 D serial_port: Configuring serial port
08-31 11:16:10.818  7843  7843 E UEI.SmartControl: UEIBLaster setting for 616
08-31 11:16:10.818  7843  7843 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 11:16:10.818  7843  7843 I UEI.SmartControl: configuring settings for MAXQ616
08-31 11:16:10.818  7843  7843 I UEI.SmartControl: Get version...
08-31 11:16:10.835  7843  7931 D UEI.SmartControl: serial port data available: 21
,08-31 11:16:10.849  1081  1104 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7932 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-31 11:16:10.860  7843  7843 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 11:16:10.860  7843  7843 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 11:16:10.860  7843  7843 I UEI.SmartControl: QS saving settings...
08-31 11:16:10.861  7843  7843 D UEI.SmartControl: IR Blaster version: 25672567
08-31 11:16:10.861  2841  2857 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-31 11:16:10.865  2841  2857 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@32c2ba02 on behalf of 7887
,08-31 11:16:10.874  7887  7887 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-31 11:16:10.878  7843  7931 D UEI.SmartControl: serial port data available: 4
,08-31 11:16:10.894  7887  7887 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-31 11:16:10.906  7843  7957 I UEI.SmartControl: Device manager: loading config....
08-31 11:16:10.906  7843  7957 D UEI.SmartControl: ----------- loading internal config...
08-31 11:16:10.906  7843  7843 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-31 11:16:10.909  7843  7957 E UEI.SmartControl: Loading SETTINGS...
08-31 11:16:10.912  7843  7957 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 11:16:10.925  7843  7956 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 11:16:10.925  7843  7956 D UEI.SmartControl: -----service ready thread exits
,08-31 11:16:10.983  1081  1927 I art     : Explicit concurrent mark sweep GC freed 40650(1953KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.631ms total 101.029ms
,08-31 11:16:10.989  7843  7843 E UEI.SmartControl: Services init done
08-31 11:16:10.989  7843  7843 D UEI.SmartControl: QS Service init finished
08-31 11:16:10.993  7843  7843 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 11:16:10.993  7843  7843 D UEI.SmartControl: QS Service version code: 201091
08-31 11:16:10.995  7843  7843 D UEI.SmartControl: Service requested: Control
,08-31 11:16:10.997  1081  2060 I ActivityManager: Killing 6363:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-31 11:16:11.023  7932  7932 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-31 11:16:11.051  1081  2010 W libprocessgroup: failed to open /acct/uid_1000/pid_6363/cgroup.procs: No such file or directory
,08-31 11:16:11.053  7843  7843 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@2ed175b5 that was originally bound here
08-31 11:16:11.053  7843  7843 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@2ed175b5 that was originally bound here
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:16:11.053  7843  7843 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:16:11.055  7843  7843 D UEI.SmartControl: Internal service binding...
08-31 11:16:11.062  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-31 11:16:11.062  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-31 11:16:11.062  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-31 11:16:11.062  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-31 11:16:11.062  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-31 11:16:11.062  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-31 11:16:11.079  1081  2010 I ActivityManager: Killing 7190:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-31 11:16:11.159  1081  1986 W libprocessgroup: failed to open /acct/uid_10046/pid_7190/cgroup.procs: No such file or directory
,08-31 11:16:11.407  7843  7910 D UEI.SmartControl: Internal timer expired: 2
,08-31 11:16:11.428  1081  2032 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:16:11.452  5019  7930 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 641 ms] updated apps [took 641 ms] 
,08-31 11:16:11.810  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:16:11.810  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b826b23 added. We now have 6 listener(s)
,08-31 11:16:11.811  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:16:11.822  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:11.822  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@233e7820 added. We now have 7 listener(s)
08-31 11:16:11.822  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:11.823  6631  6712 I System.out: IsBluetoothEnabled
08-31 11:16:11.823  1081  1104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:11.824  1081  1104 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-31 11:16:11.824  1081  1176 D BluetoothManagerService: Message: 2
08-31 11:16:11.827  6631  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:11.829  1081  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:11.829  1081  2037 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-31 11:16:11.855  1081  1081 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 11:16:11.855  1081  1081 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 11:16:11.856  1081  1081 D Ulp_jni : JNI:system_update. Event-4
,08-31 11:16:11.859  1081  1176 D BluetoothManagerService: Message: 1
08-31 11:16:11.859  1081  1176 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-31 11:16:11.888  1081  1176 D BluetoothManagerService: Message: 20
08-31 11:16:11.889  1081  1176 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@92390c:true
,08-31 11:16:11.893  7735  7735 D BluetoothAdapterState: make
08-31 11:16:11.898  7735  7735 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 11:16:11.898  7735  7735 I bluedroid-qcom: init
08-31 11:16:11.899  7735  7975 I BluetoothAdapterState: Entering OffState
08-31 11:16:11.900  7735  7735 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 11:16:11.900  7735  7735 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 11:16:11.900  7735  7735 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 11:16:11.900  7735  7735 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 11:16:11.900  7735  7735 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 11:16:11.902  7735  7735 I bluedroid-qcom: get_profile_interface socket
08-31 11:16:11.902  7735  7735 I bluedroid-qcom: get_profile_interface map_client
,08-31 11:16:11.906  7735  7979 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 11:16:11.895  7978  7978 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:11.911  7735  7979 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 11:16:11.905  7978  7978 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:11.920  7978  7978 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 11:16:11.920  7978  7978 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 11:16:11.920  7978  7978 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-31 11:16:11.924  1081  1081 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 11:16:11.925  1081  1081 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 11:16:11.927  1081  1081 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-31 11:16:11.927  1081  1176 D BluetoothManagerService: Message: 40
08-31 11:16:11.927  1081  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 11:16:11.928  7735  7752 I bluedroid-qcom: config_hci_snoop_log
08-31 11:16:11.929  7978  7978 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-31 11:16:11.930  1081  1176 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 11:16:11.930  1081  1176 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 11:16:11.936  7735  7975 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-31 11:16:11.940  7735  7979 D BluetoothAdapterProperties: Name is: G3
08-31 11:16:11.940  7735  7975 D BluetoothAdapterProperties: Setting state to 11
08-31 11:16:11.940  7735  7975 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 11:16:11.941  1081  1176 D BluetoothManagerService: Message: 60
08-31 11:16:11.941  1081  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 11:16:11.941  1081  1176 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 11:16:11.943  7735  7975 I LGBluetoothServiceJni: classInitNative: succeeds
08-31 11:16:11.949  7978  7978 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 11:16:11.949  7978  7978 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-31 11:16:11.954  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:16:11.956  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:11.958  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:11.961  6909  6909 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-31 11:16:11.980  7735  7735 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:16:11.980  7735  7735 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:11.980  7735  7735 V BluetoothPbapReceiver: ***********state = 11
,08-31 11:16:11.982  7735  7975 D BluetoothBondStateMachine: make
,08-31 11:16:11.986  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:16:11.989  7735  7975 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11f53dec
08-31 11:16:11.989  7735  7975 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 11:16:11.989  7735  7975 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11f53dec
08-31 11:16:11.989  7735  7975 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 11:16:11.990  7735  7975 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-31 11:16:11.991  7735  7993 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 11:16:11.994  7735  7975 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:16:11.998  6909  6909 D BluetoothPermissionRequest: onReceive
08-31 11:16:12.002  6909  6909 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:16:12.008  7735  7735 D HeadsetService: Received start request. Starting profile...
08-31 11:16:12.009  7735  7735 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 11:16:12.010  7735  7735 D LGBluetoothHfpAdapter: Version 1.6
,08-31 11:16:12.013  7735  7975 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:16:12.014  7735  7735 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 11:16:12.015  7735  7735 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 11:16:12.016  7735  7735 D HeadsetStateMachine: make
08-31 11:16:12.024  7735  7975 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:16:12.031  7735  7975 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:16:12.036  7735  7975 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:16:12.043  7735  7975 E BluetoothAdapterService: File transfer profiles supported!!
08-31 11:16:12.049  7735  7975 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 11:16:12.057  7735  7735 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:16:12.057  7735  7735 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:16:12.063  7735  7735 D HeadsetStateMachine: max_hf_connections = 1
08-31 11:16:12.063  7735  7735 I bluedroid-qcom: get_profile_interface handsfree
08-31 11:16:12.065  7735  7735 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 11:16:12.066   323   323 V AudioPolicyService: registerClient() client 0xb57edf40, uid 1002
08-31 11:16:12.066   323  1383 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 11:16:12.066   323  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:16:12.066   323  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:16:12.067  7735  7735 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-31 11:16:12.067   323  4394 V AudioFlinger: registerClient() client 0xb55816a0, pid 7735
08-31 11:16:12.068   323  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:16:12.068   323  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:16:12.069  1081  2037 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:16:12.069   323  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:16:12.069  1585  1605 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-31 11:16:12.069   323  1376 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:16:12.069  1585  1605 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:16:12.069  1081  2037 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:16:12.069  1585  1605 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:16:12.069  1585  1605 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:16:12.069  1081  2037 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:16:12.069  3333  3351 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:16:12.069  3333  3351 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:16:12.069  1081  2037 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:16:12.069  3333  3351 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:16:12.069  3333  3351 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:16:12.069  7735  7752 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:16:12.070  7735  7975 V LGMDMManager: Create singleton instance
08-31 11:16:12.070  1862  4407 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 11:16:12.070  1862  4407 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 11:16:12.070  1862  4407 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:16:12.070  1862  4407 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 11:16:12.070  7735  7752 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 11:16:12.070  7735  7735 V ToneGenerator: Create Track: 0xb4928a80
08-31 11:16:12.070  7735  7752 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 11:16:12.070  7735  7735 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
,08-31 11:16:12.070  7735  7752 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 11:16:12.070  7735  7735 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 11:16:12.070   323   323 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 11:16:12.070   323   323 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 11:16:12.070   323   323 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:16:12.070   323   323 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:16:12.071   323  1383 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 11:16:12.071   323  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 11:16:12.071   323  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 11:16:12.071   323  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 11:16:12.071   323  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 11:16:12.071  7735  7735 V AudioSystem: getLatency() output 2, latency 50
,08-31 11:16:12.071  7735  7735 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 11:16:12.071  7735  7735 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 11:16:12.072   323  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 11:16:12.072   323  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 11:16:12.072   323  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 11:16:12.072   323  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 11:16:12.072   323  1382 V AudioFlinger: createTrack() lSessionId: 21
08-31 11:16:12.072  7735  7975 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 11:16:12.073  7735  7735 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 11:16:12.073   323   323 V AudioFlinger: acquiring 21 from 7735, for 7735
08-31 11:16:12.073   323   323 V AudioFlinger:  added new entry for 21
08-31 11:16:12.073  7735  7735 V ToneGenerator: ToneGenerator INIT OK, time: 135074
08-31 11:16:12.073  7735  7735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11f53dec
08-31 11:16:12.075  7735  7735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11f53dec
08-31 11:16:12.077  7735  7997 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 11:16:12.077  7735  7997 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 11:16:12.077  7735  7735 D A2dpService: Received start request. Starting profile...
08-31 11:16:12.078  7735  7735 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 11:16:12.079  7735  7997 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 11:16:12.079  7735  7735 V Avrcp   : make
08-31 11:16:12.079  7735  7997 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,08-31 11:16:12.080  7735  7735 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-31 11:16:12.080  7735  7735 I bluedroid-qcom: get_profile_interface avrcp
08-31 11:16:12.080   323  4394 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7735
,08-31 11:16:12.081   323  4394 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 11:16:12.081   323  4394 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 11:16:12.081   323  4394 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 11:16:12.081   323  4394 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 11:16:12.081   323  4394 V voice   : voice_set_parameters: exit with code(0)
08-31 11:16:12.081   323  4394 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 11:16:12.081   323  4394 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
,08-31 11:16:12.081   323  4394 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 11:16:12.081   323  4394 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 11:16:12.081   323  4394 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 11:16:12.081   323  4394 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 11:16:12.082  7735  7997 V ToneGenerator: ToneGenerator destructor
08-31 11:16:12.082  7735  7997 V ToneGenerator: stopTone
08-31 11:16:12.082  7735  7997 V ToneGenerator: Delete Track: 0xb4928a80
08-31 11:16:12.083   323  1383 V AudioPolicyService: AudioCommandThread() adding release output 2
,08-31 11:16:12.083   323  1383 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 11:16:12.084   323  1273 V AudioPolicyService: AudioCommandThread() waking up
08-31 11:16:12.084   323  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 11:16:12.084   323  1273 V AudioPolicyManager: releaseOutput() 2
08-31 11:16:12.084   323  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 11:16:12.084   323  1383 V AudioFlinger: PlaybackThread::Track destructor
08-31 11:16:12.084   323  1383 V AudioFlinger: removeClient_l() pid 7735, calling pid 323
08-31 11:16:12.084  7735  7997 V AudioTrack: ~AudioTrack, releasing session id from 7735 on behalf of 7735
,08-31 11:16:12.085   323  4394 V AudioFlinger: releasing 21 from 7735 for 7735
08-31 11:16:12.085   323  4394 V AudioFlinger:  decremented refcount to 0
,08-31 11:16:12.085   323  4394 V AudioFlinger: purging stale effects
08-31 11:16:12.093  7735  7735 V AudioManager: registerRemoteController: size of Media player list: 0
08-31 11:16:12.095  7735  7735 E AudioManager: No RCC entry present to update
08-31 11:16:12.095  7735  7735 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 11:16:12.100  7735  7735 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-31 11:16:12.101  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 11:16:12.101  7735  7735 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 11:16:12.106  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 11:16:12.231  1081  1105 V SIM_STK : Menu title from STK is T-Mobile
08-31 11:16:12.231  1081  1105 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:16:12.375  1081  1926 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-31 11:16:12.387  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-31 11:16:12.397  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 11:16:12.398  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 11:16:12.398  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 11:16:12.398  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 11:16:12.398  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:16:12.398  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 11:16:12.399  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 11:16:12.399  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 11:16:12.399  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:16:12.399  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 11:16:12.400  7735  7735 I BluetoothA2dpServiceJni: classInitNative
08-31 11:16:12.400  7735  7735 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:16:12.400  7735  7735 D A2dpStateMachine: make
,08-31 11:16:12.402  7735  7735 I bluedroid-qcom: get_profile_interface a2dp
08-31 11:16:12.402  7735  8010 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 11:16:12.405  7735  7735 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:16:12.406  7735  7735 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 11:16:12.407  7735  7735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11f53dec
08-31 11:16:12.407  7735  8009 D A2dpStateMachine: Enter Disconnected: -2
08-31 11:16:12.408  7735  7735 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 11:16:12.410  7735  7735 D HidService: Received start request. Starting profile...
08-31 11:16:12.411  7735  7735 I bluedroid-qcom: get_profile_interface hidhost
08-31 11:16:12.411  7735  7735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11f53dec
08-31 11:16:12.412  7735  7735 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 11:16:12.414  7735  7735 D HealthService: Received start request. Starting profile...
,08-31 11:16:12.416  7735  7735 I bluedroid-qcom: get_profile_interface health
08-31 11:16:12.416  7735  7735 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 11:16:12.416  7735  7735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11f53dec
08-31 11:16:12.417  7735  7735 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 11:16:12.420  7735  7735 D PanService: Received start request. Starting profile...
08-31 11:16:12.420  7735  7735 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:16:12.420  7735  7735 I bluedroid-qcom: get_profile_interface pan
08-31 11:16:12.428  7735  7735 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-31 11:16:12.428  7735  7735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11f53dec
,08-31 11:16:12.431  7735  7735 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 11:16:12.439  7735  7735 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:16:12.440  7735  7735 D BtGatt.GattService: Received start request. Starting profile...
08-31 11:16:12.440  7735  7735 D BtGatt.GattService: start()
08-31 11:16:12.440  7735  7735 I bluedroid-qcom: get_profile_interface gatt
08-31 11:16:12.441  7735  7735 D BtGatt.AdvertiseManager: advertise manager created
,08-31 11:16:12.447  7735  7735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11f53dec
08-31 11:16:12.449  7735  7735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11f53dec
08-31 11:16:12.450  7735  7735 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 11:16:12.451  7735  7735 V BluetoothMapService: BluetoothMapBinder()
08-31 11:16:12.451  7735  7735 D BluetoothMapService: Received start request. Starting profile...
08-31 11:16:12.451  7735  7735 D BluetoothMapService: start()
08-31 11:16:12.455  7735  7735 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 11:16:12.455  7735  7735 D BluetoothMapEmailAppObserver: createReceiver()
,08-31 11:16:12.458  7735  7735 D BluetoothMapEmailAppObserver: initObservers()
08-31 11:16:12.458  7735  7735 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 11:16:12.468  7735  7735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11f53dec
08-31 11:16:12.468  7735  7735 D HeadsetStateMachine: Proxy object connected
08-31 11:16:12.469  7735  7735 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,08-31 11:16:12.469  7735  7735 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-31 11:16:12.475  7735  7997 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 11:16:12.475  7735  7997 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 11:16:12.476  7735  7997 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 11:16:12.479  7735  7735 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:16:12.480  7735  7735 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:16:12.486  7735  7735 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:16:12.489  7735  7735 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:16:12.492  7735  7735 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 11:16:12.492  7735  7735 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 11:16:12.495  7735  7735 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 11:16:12.500  7735  7735 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 11:16:12.500  7735  7735 V BluetoothMapService: Handler(): got msg=1
08-31 11:16:12.501  7735  7735 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:16:12.501  7735  7735 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:16:12.501  7735  7735 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:16:12.501  7735  7735 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:12.501  7735  7735 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 11:16:12.502  7735  7975 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 11:16:12.502  7735  7975 I bluedroid-qcom: enable
08-31 11:16:12.502  7735  7975 I bt_hci_bdroid: init
08-31 11:16:12.503  7735  7975 I bt_vendor: bt-vendor : init
08-31 11:16:12.503  7735  7975 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 11:16:12.503  7735  7975 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 11:16:12.503  7735  7975 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 11:16:12.503  7735  7975 D bt_userial_mct: userial_init
08-31 11:16:12.507  7735  8017 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 11:16:12.507  7735  7975 D bt_hci_bdroid: set_power 1
08-31 11:16:12.507  7735  7975 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 11:16:12.507  7735  8017 I bt-btu  : btu_task pending for preload complete event
08-31 11:16:12.507  7735  7975 I bt_vendor: Starting hciattach daemon
08-31 11:16:12.507  7735  7975 I bt_vendor: try to set true
,08-31 11:16:12.505  8020  8020 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:12.505  8020  8020 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:12.532  8021  8021 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 11:16:12.603  8027  8027 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 11:16:12.627  8028  8028 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 11:16:12.674  8030  8030 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 11:16:12.691  8031  8031 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-31 11:16:12.706  8032  8032 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 11:16:12.719  8033  8033 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-31 11:16:12.743  8035  8035 I libmdmdetect: ESOC framework not supported
,08-31 11:16:12.744  8035  8035 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-31 11:16:12.752  8035  8035 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-31 11:16:12.752  8035  8035 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-31 11:16:12.752  8035  8035 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-31 11:16:12.753  8035  8035 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 11:16:12.753  8035  8035 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 11:16:12.753  8035  8035 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 11:16:12.753  8035  8035 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-31 11:16:12.789  8035  8036 E QC-QMI  : qmi_client [8035] 15: failed to locate client data
,08-31 11:16:12.793   465   465 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-31 11:16:12.793   465   465 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-31 11:16:12.821  8037  8037 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 11:16:12.837  8038  8038 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 11:16:12.861  7735  7975 I bt_vendor: bluetooth satus is on
08-31 11:16:12.861  7735  7975 D bt_hci_bdroid: preload
08-31 11:16:12.862  7735  8019 D bt_userial_mct: userial_open(port:0)
08-31 11:16:12.862  7735  8019 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 11:16:12.865  7735  8019 I bt_vendor: Done intiailizing UART
08-31 11:16:12.866  7735  8019 I bt_vendor: Done intiailizing UART
08-31 11:16:12.866  7735  8019 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 11:16:12.867  7735  8019 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 11:16:12.867  7735  8017 I bt-btu  : btu_task received preload complete event
08-31 11:16:12.868  7735  8017 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-31 11:16:12.868  7735  8017 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-31 11:16:12.869  7735  8040 D bt_userial_mct: Entering userial_read_thread()
08-31 11:16:12.873  7735  8017 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-31 11:16:12.879  7735  8017 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 11:16:12.879  7735  8017 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 11:16:12.879  7735  8017 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 11:16:12.879  7735  8017 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 11:16:12.879  7735  8017 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 11:16:12.879  7735  8017 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 11:16:12.879  7735  8017 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 11:16:12.879  7735  8017 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 11:16:12.879  7735  8017 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-31 11:16:12.879  7735  8017 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 11:16:12.879  7735  8017 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 11:16:12.879  7735  8017 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 11:16:12.880  7735  8017 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 11:16:12.880  7735  8017 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 11:16:12.880  7735  8017 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 11:16:12.880  7735  8017 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 11:16:12.990  7735  8017 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-31 11:16:12.990  7735  8017 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0226061 
,08-31 11:16:12.990  7735  8017 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0226061 
,08-31 11:16:13.030  7735  7979 E bt-btif : Calling BTA_HhEnable
08-31 11:16:13.031  7735  7979 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-31 11:16:13.031  7735  7979 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-31 11:16:13.035  7735  8017 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-31 11:16:13.035  7735  8017 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-31 11:16:13.035  7735  8017 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-31 11:16:13.035  7735  8017 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 11:16:13.035  7735  8017 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-31 11:16:13.036  1081  1081 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 11:16:13.037  1081  1081 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 11:16:13.037  7735  7979 D BluetoothAdapterProperties: Name is: G3
08-31 11:16:13.039  7735  7979 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:16:13.039  7735  7979 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:16:13.039  7735  7979 D bt_hci_bdroid: postload
08-31 11:16:13.039  7735  8019 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:16:13.040  7735  8019 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:16:13.041  7735  8019 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:16:13.041  7735  8019 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 11:16:13.041  7735  8017 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-31 11:16:13.042  7735  7979 D bte_conf: Device ID record 1 : primary
08-31 11:16:13.042  7735  7979 D bte_conf:   vendorId            = 00c4
08-31 11:16:13.042  7735  7979 D bte_conf:   vendorIdSource      = 0001
08-31 11:16:13.042  7735  7979 D bte_conf:   product             = 13a1
08-31 11:16:13.042  7735  7979 D bte_conf:   version             = 1000
08-31 11:16:13.042  7735  7979 D bte_conf:   clientExecutableURL = 
08-31 11:16:13.042  7735  7979 D bte_conf:   serviceDescription  = 
08-31 11:16:13.042  7735  7979 D bte_conf:   documentationURL    = 
08-31 11:16:13.042  7735  7979 D bte_conf: bte_load_did_conf no section named DID2.
08-31 11:16:13.046  7735  7975 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-31 11:16:13.046  7735  7975 D BluetoothAdapterProperties: ScanMode =  20
08-31 11:16:13.046  7735  7975 D BluetoothAdapterProperties: State =  11
08-31 11:16:13.046  7735  7975 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 11:16:13.046  7735  7975 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120,
,08-31 11:16:13.054  7735  7975 D BluetoothAdapterProperties: Setting state to 12
08-31 11:16:13.055  7735  7975 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 11:16:13.055  7735  7979 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 11:16:13.055  7735  7979 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 11:16:13.055  8045  8045 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:13.055  8045  8045 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 11:16:13.079  7735  8040 E bt_mct  : hci lib postload completed
,08-31 11:16:13.081  7735  8017 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:16:13.081  7735  8017 W bt-smp  : Plain text(LSB ~ MSB) = 6f 8c 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:16:13.082  7735  8017 W bt-smp  : Encrypted text(LSB ~ MSB) = 1e e4 db ca 7e d0 5b 4a 4d 6a e9 56 46 a0 2d f7 
08-31 11:16:13.082  7735  8017 W bt-btm  : Stopping oneshot timer
08-31 11:16:13.082  7735  7975 I BluetoothAdapterState: Entering On State
08-31 11:16:13.083  1081  1176 D BluetoothManagerService: Message: 60
08-31 11:16:13.083  1081  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 11:16:13.083  1081  1176 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-31 11:16:13.094  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:13.094  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:13.094  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:16:13.094  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:13.094  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:13.094  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:13.094  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:13.094  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:16:13.099  7735  8017 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:16:13.099  7735  8017 W bt-smp  : Plain text(LSB ~ MSB) = 48 c6 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:16:13.100  7735  8017 W bt-smp  : Encrypted text(LSB ~ MSB) = 36 77 f2 19 dc ae 20 97 08 39 36 67 c2 06 62 02 
08-31 11:16:13.100  7735  8017 W bt-btm  : Stopping oneshot timer
08-31 11:16:13.101  1862  1877 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:16:13.103  7735  7975 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 11:16:13.103  7735  7975 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 11:16:13.103  7735  7975 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-31 11:16:13.108  7735  7975 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-31 11:16:13.114  6631  6631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:16:13.124  1862  1862 D BluetoothHeadset: Proxy object connected
,08-31 11:16:13.129  7735  8017 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:16:13.129  7735  8017 W bt-smp  : Plain text(LSB ~ MSB) = 7b 26 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:16:13.129  7735  8017 W bt-smp  : Encrypted text(LSB ~ MSB) = 42 94 d5 b3 2a 92 ab 46 95 a2 fb af 02 af 14 e5 
08-31 11:16:13.129  7735  8017 W bt-btm  : Stopping oneshot timer
08-31 11:16:13.130  6909  6928 D BluetoothPan: onBluetoothStateChange on: true
08-31 11:16:13.130  6909  6928 D BluetoothPan: onBluetoothStateChange call bindService
08-31 11:16:13.139  7735  7975 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-31 11:16:13.155  7735  8017 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-31 11:16:13.155  7735  8017 W bt-smp  : Plain text(LSB ~ MSB) = 76 02 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:16:13.155  7735  8017 W bt-smp  : Encrypted text(LSB ~ MSB) = 05 d7 1b 41 33 fa 41 28 5a 04 53 d0 5c eb f4 c2 
,08-31 11:16:13.155  7735  8017 W bt-btm  : Stopping oneshot timer
08-31 11:16:13.157  6909  6928 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:16:13.167  6909  6909 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:16:13.167  6909  6909 D PanProfile: Bluetooth service connected
08-31 11:16:13.172  6909  7177 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:16:13.187  6909  6928 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 11:16:13.191  1081  1176 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:16:13.193  1081  1081 D BluetoothHeadset: Proxy object connected
,08-31 11:16:13.196  7735  8017 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 11:16:13.196  7735  8017 W bt-smp  : Plain text(LSB ~ MSB) = dd e8 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 11:16:13.196  7735  8017 W bt-smp  : Encrypted text(LSB ~ MSB) = 64 84 fb 61 e5 23 97 ee a2 9c a2 1d 32 f9 ac d5 
,08-31 11:16:13.196  7735  8017 W bt-btm  : Stopping oneshot timer
08-31 11:16:13.197  6909  6927 D BluetoothMap: onBluetoothStateChange: up=true
08-31 11:16:13.198  8059  8059 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-31 11:16:13.204  6909  6909 D BluetoothHeadset: Proxy object connected
08-31 11:16:13.204  6909  6909 D HeadsetProfile: Bluetooth service connected
,08-31 11:16:13.208  1081  1176 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:16:13.209  1081  1081 D BluetoothA2dp: Proxy object connected
08-31 11:16:13.210  6909  7177 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 11:16:13.210  6909  6909 D BluetoothA2dp: Proxy object connected
08-31 11:16:13.211  6909  6909 D A2dpProfile: Bluetooth service connected
08-31 11:16:13.218  1862  4854 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:16:13.220  6909  6909 D BluetoothMap: Proxy object connected
08-31 11:16:13.220  6909  6909 D MapProfile: Bluetooth service connected
08-31 11:16:13.220  6909  6909 D BluetoothMap: getConnectedDevices()
08-31 11:16:13.221  7735  7752 V BluetoothMapService: getConnectedDevices()
,08-31 11:16:13.223  6909  6909 D BluetoothInputDevice: Proxy object connected
08-31 11:16:13.223  6909  6909 D HidProfile: Bluetooth service connected
08-31 11:16:13.226  1862  1862 D BluetoothHeadset: Proxy object connected
08-31 11:16:13.226  1862  2545 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:16:13.229  1862  1862 D BluetoothHeadset: Proxy object connected
08-31 11:16:13.230  1081  1176 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 11:16:13.230  1081  1176 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 11:16:13.233  1081  1081 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-31 11:16:13.234  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:13.239  1951  2129 D LGBluetoothAPIService: Message: 1
08-31 11:16:13.239  1951  2129 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 11:16:13.239  1951  2129 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-31 11:16:13.239  1951  2129 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-31 11:16:13.239  1585  1585 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 11:16:13.243  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:13.243  1081  1176 D BluetoothManagerService: Message: 40
08-31 11:16:13.243  1081  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 11:16:13.247  7735  7735 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:13.248  7735  7735 D BluetoothMapService: STATE_ON
08-31 11:16:13.249  6909  6909 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 11:16:13.249  7735  7979 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:16:13.249  7735  7979 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-31 11:16:13.252  6909  6909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-31 11:16:13.258  6909  6909 D DockEventReceiver: finishStartingService: stopping service
08-31 11:16:13.271  7735  7735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11f53dec
08-31 11:16:13.271  7735  7735 V BluetoothPbapService: Pbap Service onCreate
,08-31 11:16:13.272  7735  7735 V BluetoothPbapService: Starting PBAP service
08-31 11:16:13.273  7735  7735 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 11:16:13.273  7735  7735 V BluetoothPbapService: Pbap Service onBind
08-31 11:16:13.275  7735  7735 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:13.275  6909  6909 D BluetoothPbap: Proxy object connected
08-31 11:16:13.275  6909  6909 D PbapServerProfile: Bluetooth service connected
08-31 11:16:13.275  7735  7735 V BluetoothPbapService: state: 12
08-31 11:16:13.275  7735  7735 V BluetoothMapService: Handler(): got msg=1
08-31 11:16:13.276  7735  7735 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 11:16:13.277  7735  7735 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 11:16:13.277  7735  7735 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:13.277  7735  7735 V BluetoothPbapReceiver: ***********state = 12
08-31 11:16:13.278  7735  8072 D BluetoothMapMasInstance: MAS initSocket()
08-31 11:16:13.278  7735  8072 D BluetoothMapMasInstance:   masId = 00
08-31 11:16:13.278  7735  8072 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 11:16:13.278  7735  8072 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 11:16:13.278  7735  8072 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 11:16:13.279  7735  7735 V BluetoothPbapService: Handler(): got msg=1
08-31 11:16:13.279  7735  7735 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,08-31 11:16:13.281  2246  2246 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:16:13.281  7735  8073 V BluetoothPbapService: Pbap Service initSocket
08-31 11:16:13.281  1081  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:13.281  2246  2246 D c       : Getting all permits...
08-31 11:16:13.281  1081  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:13.281  2246  2246 D a       : Opening database...
08-31 11:16:13.284  7735  8072 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:13.285  7735  8073 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:13.285  2246  2246 D a       : Opening database auth.proximity.permit_store...
08-31 11:16:13.286  7735  8073 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 11:16:13.286  7735  8073 V BluetoothPbapService: Succeed to create listening socket 
08-31 11:16:13.286  7735  8073 V BluetoothPbapService: Accepting socket connection...
08-31 11:16:13.287  7735  7979 D BluetoothAdapterProperties: Scan Mode:21
,08-31 11:16:13.287  7735  7979 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-31 11:16:13.288  7735  8072 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 11:16:13.288  7735  8072 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 11:16:13.288  2246  2246 D a       : Closing database...
08-31 11:16:13.288  7735  8072 D BluetoothMapMasInstance: Accepting socket connection...
08-31 11:16:13.289  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:13.293  7735  7979 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:16:13.293  7735  7979 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-31 11:16:13.298  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:13.311  6909  6909 D BluetoothPermissionRequest: onReceive
,08-31 11:16:13.314  6909  6909 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 11:16:13.316  6909  6909 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 11:16:13.319  7735  7735 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-31 11:16:13.321  7735  7735 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-31 11:16:13.327  7735  7735 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-31 11:16:13.348  7735  7735 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-31 11:16:13.348  7735  7735 V BtOppService: onCreate
,08-31 11:16:13.352  7735  7735 V BluetoothOppNotification: send message
08-31 11:16:13.356  7735  7735 V BtOppService: Starting RfcommListener
08-31 11:16:13.362  7735  7735 D BluetoothOppPreference: Dumping Names:  
,08-31 11:16:13.362  7735  7735 D BluetoothOppPreference: {}
08-31 11:16:13.362  7735  7735 D BluetoothOppPreference: Dumping Channels:  
08-31 11:16:13.362  7735  7735 D BluetoothOppPreference: {}
08-31 11:16:13.363  7735  7735 V BtOppService: onStartCommand
08-31 11:16:13.365  7735  8079 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 11:16:13.368  7735  7735 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:13.368  7735  7735 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 11:16:13.372  7735  7735 V BluetoothOppNotification: new notify threadi!
08-31 11:16:13.373  7735  7735 V BluetoothOppNotification: send delay message
08-31 11:16:13.374  7735  7735 V BtOppService: start RfcommListener
08-31 11:16:13.374  7735  8079 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-31 11:16:13.377  7735  8076 V BtOppService: Deleted complete outbound shares, number =  0
08-31 11:16:13.377  7735  8079 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@194be68 on behalf of 
08-31 11:16:13.379  7735  7735 V BtOppService: RfcommListener started
08-31 11:16:13.381  7735  8076 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 11:16:13.382  7735  8079 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 11:16:13.382  7735  8080 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 11:16:13.382  7735  8076 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 11:16:13.383  7735  8081 V BtOppRfcommListener: Starting RFCOMM listener....
,08-31 11:16:13.384  1081  2310 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:13.385  7735  8080 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ac8f281 on behalf of 
08-31 11:16:13.386  7735  8080 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-31 11:16:13.386  7735  8076 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@238bf26 on behalf of 
08-31 11:16:13.387  7735  8081 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:13.390  7735  8081 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-31 11:16:13.391  7735  8081 V BtOppRfcommListener: Started RFCOMM listener....
08-31 11:16:13.391  7735  8081 I BtOppRfcommListener: Accept thread started.
08-31 11:16:13.391  7735  8081 V BtOppRfcommListener: Accepting connection...
08-31 11:16:13.392  7735  8080 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 11:16:13.394  7735  8080 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39cb2767 on behalf of 
08-31 11:16:13.395  7735  8080 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 11:16:13.396  7735  8080 V BluetoothOppNotification: outbound notification was removed.
08-31 11:16:13.396  7735  8080 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 11:16:13.398  7735  8080 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@222b5914 on behalf of 
08-31 11:16:13.399  7735  8080 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-31 11:16:13.400  7735  8080 V BluetoothOppNotification: inbound notification was removed.
08-31 11:16:13.401  7735  8080 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 11:16:13.403  7735  8080 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b1135bd on behalf of 
08-31 11:16:13.403  7735  7735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11f53dec
08-31 11:16:13.404  7735  7735 V BluetoothFtpService: Ftp Service onCreate
08-31 11:16:13.404  7735  7735 I BluetoothFtpService: Ftp Service onCreate
08-31 11:16:13.404  7735  7735 V BluetoothFtpService: Ftp Service onStartCommand
,08-31 11:16:13.404  7735  7735 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:13.405  7735  7735 V BluetoothFtpService: Starting Listening on sockets
08-31 11:16:13.405  7735  7735 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 11:16:13.407  7735  7735 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 11:16:13.407  7735  7735 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 11:16:13.407  7735  7735 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:16:13.407  7735  7735 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 11:16:13.407  7735  7735 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 11:16:13.410  7735  7735 V BtOppService: ContentObserver received notification
08-31 11:16:13.410  7735  7735 V BtOppService: ContentObserver received notification
08-31 11:16:13.410  7735  7735 V BluetoothFtpService: Handler(): got msg=1
08-31 11:16:13.411  7735  7735 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 11:16:13.411  7735  7735 V BluetoothFtpService: Ftp Service initSocket
,08-31 11:16:13.413  7735  8082 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 11:16:13.413  7735  8082 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 11:16:13.416  7735  8082 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23d8d303 on behalf of 
08-31 11:16:13.417  7735  8082 V BluetoothOppNotification: update too frequent, put in queue
08-31 11:16:13.418  7735  8082 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 11:16:13.420  1081  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:13.421  7735  7735 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:13.422  7735  7735 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-31 11:16:13.422  7735  7735 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 11:16:13.424  7735  8083 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-31 11:16:13.441  7735  7735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11f53dec
08-31 11:16:13.441  7735  7735 V BluetoothSapService: Sap Service onCreate
,08-31 11:16:13.443  7735  7735 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:16:13.443  7735  7735 V BluetoothSapService: state: 12
08-31 11:16:13.444  7735  7735 V BluetoothSapService: Starting SAP server process
08-31 11:16:13.446  7735  7735 V BluetoothSapService: SAP Service startRfcommListenerThread
08-31 11:16:13.435  8084  8084 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:13.435  8084  8084 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:13.448  7735  8085 V BluetoothSapService: Sap Service initRfcommSocket
08-31 11:16:13.448  1081  2309 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:13.449  7735  8085 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:16:13.450  7735  8085 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-31 11:16:13.450  7735  8085 V BluetoothSapService: Succeed to create listening socket 
08-31 11:16:13.450  7735  8085 V BluetoothSapService: Accepting socket connection...
08-31 11:16:13.466  8084  8084 V BT_SAP  : Event pipe created
08-31 11:16:13.467  8084  8084 V BT_SAP  : create_server_socket qcom.sap.server
08-31 11:16:13.467  8084  8084 V BT_SAP  : created socket fd 6
,08-31 11:16:13.888  6631  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:13.888  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:13.888  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:16:13.888  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:16:13.888  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:13.888  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:13.888  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:13.888  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:16:13.896  6631  6712 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:16:13.899  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:16:13.899  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12f315d9 added. We now have 8 listener(s)
08-31 11:16:13.899  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:13.904  1081  2309 D WifiServiceImplEx: setWifiEnabled: false pid=6631, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 11:16:13.904  1081  2309 D WifiService: setWifiEnabled: false pid=6631, uid=10118
08-31 11:16:13.905  1081  2309 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:16:13.916  6631  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:13.917  1081  1896 D WifiServiceImplEx: setWifiEnabled: true pid=6631, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 11:16:13.917  1081  1896 D WifiService: setWifiEnabled: true pid=6631, uid=10118
08-31 11:16:13.917  1081  1896 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:16:13.937  1081  1081 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 11:16:13.937  1081  1081 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-31 11:16:13.937  1081  1081 D Ulp_jni : JNI:system_update. Event-4
,08-31 11:16:13.939  1081  1375 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-31 11:16:13.939  1081  1375 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-31 11:16:13.941  1081  1375 E WifiUtil: wfc_util_ffile_check_copy(): pid[1081] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-31 11:16:13.941  1081  1375 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 11:16:13.942  1081  1375 E WifiUtil: wfc_util_ffile_check_copy(): pid[1081] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-31 11:16:13.942  1081  1375 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 11:16:13.942  1081  1375 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-31 11:16:13.942  1081  1375 E WifiHW  : unknown target_country: EU , set to default
08-31 11:16:13.942  1081  1375 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-31 11:16:13.942  1081  1375 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-31 11:16:13.942  1081  1375 I WifiUtil: gEnableBmps=1
08-31 11:16:14.375  7735  7735 V BluetoothOppNotification: new notify threadi!
08-31 11:16:14.376  7735  7735 V BluetoothOppNotification: send delay message
,08-31 11:16:14.409  7735  8098 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-31 11:16:14.428  7735  8098 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@48b9c5f on behalf of 
,08-31 11:16:14.432  7735  8098 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 11:16:14.434  7735  8098 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 11:16:14.435  7735  8098 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@990b6ac on behalf of 
08-31 11:16:14.436  7735  8098 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 11:16:14.437  7735  8098 V BluetoothOppNotification: outbound notification was removed.
08-31 11:16:14.437  7735  8098 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 11:16:14.438  7735  8098 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f4e5f75 on behalf of 
08-31 11:16:14.439  7735  8098 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-31 11:16:14.443  7735  8098 V BluetoothOppNotification: inbound notification was removed.
,08-31 11:16:14.443  7735  8098 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-31 11:16:14.447  7735  8098 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ef27b0a on behalf of 
08-31 11:16:14.611   318   912 D SoftapController: Softap fwReload - Ok
,08-31 11:16:14.620  1081  1375 E NetdConnector: NDC Command {82 softap fwreload wlan0 STA} took too long (673ms)
08-31 11:16:14.631   318   912 D CommandListener: Setting iface cfg
08-31 11:16:14.631   318   912 D CommandListener: Trying to bring down wlan0
,08-31 11:16:14.635  1081  1176 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 11:16:14.642   318   912 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:16:14.650  1081  1375 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-31 11:16:14.645  8106  8106 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 11:16:14.665  8106  8106 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:14.677  1081  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:16:14.677  1081  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:16:14.677  1081  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-31 11:16:14.689  1081  1081 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-31 11:16:14.701  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:16:14.703  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 11:16:14.710  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:14.713  1081  1375 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 11:16:14.713  1081  1375 D WifiMonitor: connecting to supplicant
,08-31 11:16:14.741  8106  8106 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 11:16:14.762  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:16:14.762  6909  6909 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:16:14.763  6909  6909 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:16:14.763  6909  6909 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-31 11:16:14.773  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 11:16:14.775  6909  6909 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:16:14.775  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 11:16:14.775  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:16:14.775  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 11:16:14.775  6909  6909 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:16:14.776  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 11:16:14.776  6909  6909 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:16:14.800  7843  7854 E UEI.SmartControl: file observer is disposed!
,08-31 11:16:14.813  8106  8106 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 11:16:14.813  8106  8106 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-31 11:16:14.818  1081  1176 D Tethering: InitialState.processMessage what=4
,08-31 11:16:14.830  1081  2309 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8124 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-31 11:16:14.832  1081  1176 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 11:16:14.893  8106  8106 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 11:16:14.952  1081  2309 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8146 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 11:16:14.958  8106  8106 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-31 11:16:14.966  8124  8144 W FormManager: Network not available. Please check & try again.
,08-31 11:16:14.970  8106  8106 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 11:16:14.971   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 425us total 19.122ms
08-31 11:16:14.972  1081  1375 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-31 11:16:14.972  1081  1375 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 11:16:14.973  1081  1375 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-31 11:16:14.973  1081  1375 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 11:16:14.973  1081  1375 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:16:14.974  8124  8145 V FormManager: Network unavailable.
08-31 11:16:14.974  1081  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:16:14.974  1081  1375 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:16:14.974  1081  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:16:14.975  1081  1375 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 11:16:14.975  1081  1375 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 11:16:14.975  8124  8145 V FormManager: Network unavailable.
08-31 11:16:14.975  1081  1375 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 11:16:14.976  1081  1375 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 11:16:14.976  1081  1375 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-31 11:16:14.977  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:14.977  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:14.977  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:14.977  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:14.977  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 11:16:14.978  1081  1375 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 11:16:14.978  1081  1375 E WifiStateMachine: useWiFiOffloading() : false
08-31 11:16:14.978  1081  1375 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 11:16:14.979  1081  1375 D WifiNative-wlan0: doBoolean: SET update_config 1
08-31 11:16:14.980  1081  1375 D WifiNative-wlan0: SET update_config 1: returned true
08-31 11:16:14.980  1081  1375 D WifiConfigStore: Loading config and enabling all networks 
08-31 11:16:14.980  1081  1375 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 11:16:14.981  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:16:14.981  1081  1375 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-31 11:16:14.983  1081  8160 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 11:16:14.983  1081  8160 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-31 11:16:14.983  1081  8160 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 11:16:14.983  1081  8160 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-31 11:16:14.984  1081  1081 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,08-31 11:16:14.984  1081  1387 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 11:16:14.984  1951  1951 D WfdService: Waiting for WifiP2p enabling
08-31 11:16:14.990  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:14.990  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:14.990  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:16:14.990  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:14.990  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:14.990  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:16:14.990  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:16:14.990  6631  6631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:16:14.992  6631  6631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:16:14.992  1081  1375 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-31 11:16:14.996   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 406us total 20.680ms
,08-31 11:16:15.002  1081  1375 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 11:16:15.002  1081  1375 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 11:16:15.003  1081  1375 D WifiStateMachine: enableVerboseLogging : level 2
08-31 11:16:15.003  1081  1375 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 11:16:15.003  1081  1375 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-31 11:16:15.003  1081  1375 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 11:16:15.003  1081  1375 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-31 11:16:15.004  1081  1375 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 11:16:15.004  1081  1375 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 11:16:15.004  1081  1375 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 11:16:15.005  1081  1375 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 11:16:15.005  1081  1375 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-31 11:16:15.005  1081  1375 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 11:16:15.005  1081  1375 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,08-31 11:16:15.006  1081  1375 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 11:16:15.006  1081  1375 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 11:16:15.006  1081  1375 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 11:16:15.007  1081  1375 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:16:15.007  1081  1375 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 11:16:15.007  1081  1375 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 11:16:15.007  1081  1375 D WifiNative-HAL: Setting external_sim to 1
08-31 11:16:15.007  1081  1375 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 11:16:15.007  1951  1951 D WfdsService: Supplicant Connection state is changed : true
08-31 11:16:15.008  1951  2279 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 11:16:15.008  1951  2279 D WfdsService: Set the WFDS Monitor: true
08-31 11:16:15.008  1951  2279 D WfdsMonitor: WfdsMonitorThread create
08-31 11:16:15.008  1951  2279 D WfdsMonitor: WFDS Monitor is created and started
08-31 11:16:15.008  1951  2279 D WfdsService: WiFi: Supplicant connection re-established
08-31 11:16:15.008  1081  1375 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 11:16:15.008  1081  1375 I WifiNative-HAL: startHal
08-31 11:16:15.008  1081  1375 D wifi    : setting scan oui 0xaf677720
08-31 11:16:15.008  7775  7775 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.008  1951  8165 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,08-31 11:16:15.009  1951  8165 E CtrlSupplicant: Succeed to open control connection
08-31 11:16:15.009  1951  8165 E CtrlSupplicant: Succeed to open monitor connection
08-31 11:16:15.009  1951  8165 D WfdsMonitor: Supplicant connection established
08-31 11:16:15.009  1081  1375 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:16:15.009  1081  1375 I WifiNative-HAL: startHal
08-31 11:16:15.009  1081  1375 D wifi    : setting scan oui 0xaf677720
08-31 11:16:15.009  1951  2279 D WfdsService: Connected to the supplicant for wfds
08-31 11:16:15.010  1081  1375 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 11:16:15.011  1081  1375 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 11:16:15.011  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 11:16:15.012  8106  8106 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 11:16:15.012  1081  1375 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 11:16:15.012  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 11:16:15.012  8106  8106 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 11:16:15.012  1081  1375 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 11:16:15.012  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 11:16:15.012  1081  2060 I ActivityManager: Killing 7212:com.android.chrome/u0a57 (adj 15): empty #17
08-31 11:16:15.012  8106  8106 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 11:16:15.013  1081  1375 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 11:16:15.013  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 11:16:15.013  8106  8106 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 11:16:15.013  1081  1375 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 11:16:15.013  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 11:16:15.013  8106  8106 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 11:16:15.014  1081  1375 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 11:16:15.014  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 11:16:15.014  8106  8106 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 11:16:15.014  1081  1375 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 11:16:15.014  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 11:16:15.014  8106  8106 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 11:16:15.014  1081  1375 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 11:16:15.015  1081  1375 E WifiNative: : [138,007,365 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 11:16:15.015  1081  1375 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 11:16:15.015  1081  1375 D WifiNative-wlan0: RECONNECT: returned true
08-31 11:16:15.015  1081  1375 D WifiNative-wlan0: doString: [STATUS]
08-31 11:16:15.016  1081  8160 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 11:16:15.016  1081  8160 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 11:16:15.016  1081  1375 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 11:16:15.016  1081  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:16:15.016  1081  1375 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:16:15.017   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 407us total 20.661ms
08-31 11:16:15.017  1081  1374 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.018,   318   912 D CommandListener: Setting iface cfg
08-31 11:16:15.019   318   912 D CommandListener: Trying to bring up p2p0
08-31 11:16:15.019  1081  1374 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 11:16:15.019  1081  1374 D LGWifiP2pService: P2pEnablingState
08-31 11:16:15.020  1081  1374 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.020  1081  1374 D LGWifiP2pService: P2p socket connection successful
08-31 11:16:15.020  1081  1374 D LGWifiP2pService: P2pEnabledState
08-31 11:16:15.038  8146  8146 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:16:15.062  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:16:15.062  1081  2037 W libprocessgroup: failed to open /acct/uid_10057/pid_7212/cgroup.procs: No such file or directory
,08-31 11:16:15.065  1081  1375 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 11:16:15.065  1081  1081 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 11:16:15.065  1081  1375 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 11:16:15.065  1081  1081 D RttService: SCAN_AVAILABLE : 3
08-31 11:16:15.065  1081  1374 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 11:16:15.065  1081  1539 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.065  1081  1375 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-31 11:16:15.065  1081  1539 I WifiNative-HAL: startHal
,08-31 11:16:15.065  1081  1539 D wifi    : getting scan capabilities on interface[1] = 0xaf677720
08-31 11:16:15.065  1081  1539 D wifi    : failed to get capabilities : -3
08-31 11:16:15.065  1081  1539 E WifiScanningService: could not get scan capabilities
08-31 11:16:15.065  1081  1374 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 11:16:15.065  1081  1375 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 11:16:15.066  1081  1540 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.066  1081  1375 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 11:16:15.066  1081  1374 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 11:16:15.066  1081  1374 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 11:16:15.066  1081  1375 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 11:16:15.066  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-31 11:16:15.066  1081  1375 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 11:16:15.066  1081  1375 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 11:16:15.066  1951  1951 D WfdsService: WifiP2pState is changed : true
08-31 11:16:15.066  1081  1374 D WifiNative-p2p0: SET device_name G3: returned true
08-31 11:16:15.066  8106  8106 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 11:16:15.066  1951  2279 D WfdsService: Receive the WFDS_ENABLE Method
08-31 11:16:15.066  1951  2279 D WfdsService: Set the WFDS Monitor: true
08-31 11:16:15.066  1081  1374 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 11:16:15.066  1951  2279 D WfdsService: Connected to the supplicant for wfds
08-31 11:16:15.066  1081  1374 D LGWifiP2pService: before postfix = G3
08-31 11:16:15.066  1951  2279 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 11:16:15.066  1081  1374 D WifiServerServiceExt: postfix byte check : 2
08-31 11:16:15.067  8106  8106 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 11:16:15.067  1081  1374 D LGWifiP2pService: after postfix = G3
08-31 11:16:15.067  1951  2279 D WfdsService: selectPreferredScanChannel [36]
08-31 11:16:15.067  1081  1374 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 11:16:15.067  1951  2279 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 11:16:15.067  1081  1374 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 11:16:15.067  1081  1374 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 11:16:15.067  1081  1374 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 11:16:15.067  1081  1374 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
,08-31 11:16:15.067  1081  1375 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-31 11:16:15.068  1081  1375 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 11:16:15.068  1951  1951 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 11:16:15.068  1081  1375 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 11:16:15.068  1081  1375 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-31 11:16:15.068  8106  8106 E wpa_supplicant: disconnect_rssi_lvl: -100
,08-31 11:16:15.068  1081  1374 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 11:16:15.068  1081  1374 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,08-31 11:16:15.068  1951  1951 D WfdsService: isConnected: false
,08-31 11:16:15.069  1081  1374 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 11:16:15.069  1081  1374 D WifiNative-HAL: p2pGetDeviceAddress
08-31 11:16:15.069  1081  1375 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
,08-31 11:16:15.069  1081  1374 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-31 11:16:15.069  1081  1375 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 11:16:15.070  1081  1375 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
,08-31 11:16:15.070  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-31 11:16:15.070  1081  1374 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-31 11:16:15.070  1081  1374 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,08-31 11:16:15.070  8106  8106 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 11:16:15.070  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:15.071  8106  8106 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ,
08-31 11:16:15.071  1081  8160 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:16:15.071  1081  8160 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:16:15.071  1081  8160 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-31 11:16:15.071  1081  8160 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:16:15.071  8106  8106 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
,08-31 11:16:15.071  8106  8106 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:16:15.072  1951  8165 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:16:15.072  8106  8106 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:16:15.073  1951  8165 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:16:15.073  1951  1951 I WfdStateTracker: handleP2pThisDeviceChanged
,08-31 11:16:15.074  1951  1951 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 11:16:15.074  1951  1951 D WfdsService: Update P2p Interface State: 3
08-31 11:16:15.074  1081  2010 I ActivityManager: Killing 7240:com.lge.drmservice/u0a62 (adj 15): empty #17
08-31 11:16:15.075  1081  8160 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:16:15.075  1081  8160 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:16:15.075  1081  8160 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:16:15.075  1081  8160 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:16:15.075  1081  8160 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-31 11:16:15.075  1081  8160 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:16:15.075  1081  8160 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:16:15.075  1081  8160 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-31 11:16:15.075  1081  1375 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 11:16:15.077  1081  1374 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 11:16:15.077  1081  1374 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-31 11:16:15.077  1081  1374 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 11:16:15.077  1081  1374 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 11:16:15.077  1081  1374 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
,08-31 11:16:15.077  1081  1374 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 11:16:15.078  1081  1375 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:16:15.079  1081  1375 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:16:15.080  1081  1375 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 11:16:15.081  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-31 11:16:15.086  1081  1374 D WifiNative-p2p0: SAVE_CONFIG: returned true
,08-31 11:16:15.086  1081  1374 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 11:16:15.087  8106  8106 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 11:16:15.087  8106  8106 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:16:15.087  1081  8160 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 11:16:15.087  1081  8160 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 11:16:15.087  1081  8160 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-31 11:16:15.088  1081  8160 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-31 11:16:15.088  1081  1375 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-31 11:16:15.088  1081  1375 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 11:16:15.088  1081  1375 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 11:16:15.088  1081  1375 D WifiNative-wlan0: doBoolean: SCAN
08-31 11:16:15.089  1081  1375 D WifiNative-wlan0: SCAN: returned false
08-31 11:16:15.089  1081  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=138082  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 11:16:15.121  1081  1374 D LGWifiP2pService: InactiveState
08-31 11:16:15.121  1081  1374 D LGWifiP2pService: InactiveState{ when=-44ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.121  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=-44ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.121  1081  1374 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-31 11:16:15.122  8106  8106 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 11:16:15.122  1081  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=138115  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 11:16:15.123  8106  8106 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:16:15.123  1081  8160 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:16:15.123  1081  8160 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:16:15.123  1081  8160 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:16:15.123  1081  8160 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 11:16:15.123  1081  1375 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:16:15.123  1951  8165 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 11:16:15.123  8106  8106 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 11:16:15.123  8106  8106 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:16:15.123  1951  8165 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:16:15.123  1081  8160 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:16:15.123  1081  8160 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:16:15.123  1081  8160 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:16:15.123  1081  8160 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:16:15.124  1081  1375 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:16:15.124  1081  1374 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 11:16:15.124  8106  8106 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:16:15.124  1081  1374 D LGWifiP2pService: InactiveState{ when=-46ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.124  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=-46ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.124  1081  1374 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.124  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.124  1081  1374 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.124  1081  1375 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANG,ED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:16:15.124  1081  1374 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.124  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.124  1081  1374 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.124  1081  1374 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.125  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.125  1081  1374 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.125  1081  1375 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:16:15.125  1951  8165 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-31 11:16:15.125  1081  8160 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 11:16:15.125  1081  8160 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:16:15.125  1951  2279 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 11:16:15.125  1081  8160 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:16:15.125  1081  1375 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 11:16:15.125  1081  8160 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 11:16:15.125  1081  1374 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.125  1081  2309 W libprocessgroup: failed to open /acct/uid_10062/pid_7240/cgroup.procs: No such file or directory
08-31 11:16:15.125  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.125  1081  1374 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.126  1081  1081 E WifiServerServiceExt: No p2p device connected
08-31 11:16:15.129  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:16:15.129  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:16:15.130  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:16:15.131  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.131  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.131  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 11:16:15.139  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:16:15.140  1081  1081 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-31 11:16:15.145  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:16:15.145  6909  6909 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:16:15.145  6909  6909 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:16:15.145  6909  6909 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 11:16:15.146  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 11:16:15.146  6909  6909 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:16:15.146  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 11:16:15.146  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:16:15.146  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 11:16:15.146  6909  6909 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:16:15.146  6909  6909 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:16:15.157  8146  8146 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:16:15.163  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 11:16:15.166  8124  8169 W FormManager: Network not available. Please check & try again.
,08-31 11:16:15.173  8124  8170 V FormManager: Network unavailable.
,08-31 11:16:15.174  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:15.184  8124  8170 V FormManager: Network unavailable.
,08-31 11:16:15.193  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 11:16:15.194  4764  4764 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 11:16:15.197  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:16:15.200  4764  4764 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 11:16:15.209  4764  8171 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 11:16:15.215  4764  8172 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-31 11:16:15.216  4764  8172 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 11:16:15.266  1081  2010 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8173 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 11:16:15.422  8173  8173 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 11:16:15.422  8173  8173 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-31 11:16:15.431  8173  8173 V [BNRBootReceiver]: Boot Receiver Return
08-31 11:16:15.432  8173  8173 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-31 11:16:15.481  1081  2060 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8194 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 11:16:15.484  1081  2060 I ActivityManager: Killing 7269:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-31 11:16:15.540  1081  1927 W libprocessgroup: failed to open /acct/uid_10085/pid_7269/cgroup.procs: No such file or directory
,08-31 11:16:15.565  8194  8194 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 11:16:15.593  8194  8194 D PluginManager: init()
,08-31 11:16:15.616  1081  8160 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-31 11:16:15.616  1081  8160 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-31 11:16:15.616  1081  8160 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-31 11:16:15.616  1081  8160 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-31 11:16:15.617  1081  8160 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-31 11:16:15.617  8106  8106 E wpa_supplicant: USIM:  scard_init function
08-31 11:16:15.618  8106  8106 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-31 11:16:15.620  1081  8160 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 11:16:15.620  1081  8160 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-31 11:16:15.621  1081  1375 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-31 11:16:15.626  1081  1375 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-31 11:16:15.627  1081  1375 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-31 11:16:15.628  1081  1375 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-31 11:16:15.629  1081  1375 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-31 11:16:15.635  1081  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=138627  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-31 11:16:15.639  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:16:15.639  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:16:15.640  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:16:15.641  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.641  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.641  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 11:16:15.642  1081  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=138634  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 11:16:15.645  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.645  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.645  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 11:16:15.645  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:16:15.645  1081  1081 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-31 11:16:15.662  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:16:15.662  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:16:15.663  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:16:15.753  1081  8160 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 11:16:15.753  8106  8106 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 11:16:15.753  1081  8160 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-31 11:16:15.753  1081  8160 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 11:16:15.753  1081  8160 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-31 11:16:15.754  1081  8160 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:16:15.754  1081  8160 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-31 11:16:15.759  1081  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138751  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 11:16:15.761  1081  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138753  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 11:16:15.762  1081  1375 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138755
08-31 11:16:15.765  1081  1375 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138757
08-31 11:16:15.766  1081  1375 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138758
08-31 11:16:15.767  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138759
,08-31 11:16:15.768  1081  1375 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138760
08-31 11:16:15.770  1081  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=138762  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 11:16:15.773  8106  8106 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:16:15.773  8106  8106 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:16:15.773  1081  1176 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 11:16:15.775  1081  8160 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:16:15.775  1081  8160 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:16:15.775  1081  8160 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 11:16:15.775  1081  8160 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:16:15.775  1081  8160 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:16:15.775  1081  8160 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 11:16:15.776  1081  8160 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:16:15.776  1081  8160 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 11:16:15.777  1081  8160 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:16:15.777  1081  8160 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:16:15.777  1081  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=138769  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 11:16:15.779  1081  1375 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138772  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-31 11:16:15.780  1081  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138772  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 11:16:15.780  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.781  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.781  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 11:16:15.781  1081  1375 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138773
08-31 11:16:15.781  1081  1375 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138774
08-31 11:16:15.782  1081  1375 D WifiNative-wlan0: doString: [STATUS]
08-31 11:16:15.782  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:16:15.782  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:16:15.783  1081  1375 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-31 11:16:15.784  1081  8160 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 11:16:15.784  1081  8160 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 11:16:15.784  1081  1375 I WifiServiceExtension: setVHTCapabilityType  : false
08-31 11:16:15.786  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:16:15.788  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:16:15.788  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:16:15.790  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:16:15.792  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.792  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.792  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 11:16:15.793  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:16:15.793  1081  1081 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-31 11:16:15.794  1081  1375 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 11:16:15.794  1081  1375 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-31 11:16:15.802  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:16:15.802  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.802  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 11:16:15.805  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.805  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.805  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 11:16:15.810  1081  1375 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-31 11:16:15.810  1081  1427 D ConnectivityService: Got NetworkAgent Messenger
08-31 11:16:15.810  1081  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:16:15.810  1081  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:16:15.810  1081  1427 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 11:16:15.810  1081  1427 D ConnectivityService: NetworkAgent connected
,08-31 11:16:15.811  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:16:15.811  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:16:15.812  1081  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:16:15.812  1081  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:16:15.813  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:16:15.815  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:16:15.815  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:16:15.816  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:16:15.819  1081  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 11:16:15.819  1081  1375 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:16:15.819  1081  1375 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 11:16:15.820  1081  1375 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 11:16:15.820  1081  1375 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 11:16:15.825  1081  1375 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-31 11:16:15.828   318   912 D CommandListener: Setting iface cfg
08-31 11:16:15.833  1081  1375 E WifiStateMachine: Start Dhcp Watchdog 3
08-31 11:16:15.833  1081  8216 D DhcpStateMachine: StoppedState
08-31 11:16:15.833  1081  8216 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.834  1081  8216 D DhcpStateMachine: WaitBeforeStartState
08-31 11:16:15.834  1081  1375 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=138826  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:16:15.834  1081  1375 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=138827  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:16:15.835  1081  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=138827  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:16:15.836  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:16:15.836  1081  1081 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-31 11:16:15.836  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:16:15.836  1081  1375 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:16:15.836  1081  1081 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-31 11:16:15.837  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:16:15.837  1081  1375 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:16:15.838  1081  1375 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:16:15.838  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-31 11:16:15.838  1081  1375 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 11:16:15.839  1081  1375 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138831  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:16:15.840  1081  1375 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138832  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:16:15.840  1081  1375 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138833  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 11:16:15.842  1081  1375 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14459] from screen [on:0 period:-538806686] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 11:16:15.843  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-538806685] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 11:16:15.843  1081  1375 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 11:16:15.846  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:16:15.848  1081  1427 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-31 11:16:15.848  1081  1375 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:16:15.849  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:16:15.849  1081  1375 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:16:15.849  1081  1375 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:16:15.850  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:16:15.850  1081  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:16:15.851  1081  1427 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 11:16:15.851  1081  1375 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=106,0,0
08-31 11:16:15.851  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=106,0,0
,08-31 11:16:15.851  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 11:16:15.852  8106  8106 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-31 11:16:15.853  1081  1375 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 11:16:15.853  1081  1375 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 11:16:15.853  1081  1375 D WifiNative-wlan0: SET ps 0: returned true
08-31 11:16:15.853  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-31 11:16:15.853  8106  8106 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 11:16:15.854  1081  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 11:16:15.854  1081  1375 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 11:16:15.854  1081  1375 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 11:16:15.854  1081  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3304e01d target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.854  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3304e01d target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.854  1081  1375 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 11:16:15.855   318   912 D CommandListener: Setting iface cfg
08-31 11:16:15.855   318   912 D CommandListener: Trying to bring up wlan0
08-31 11:16:15.857  1081  1375 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,08-31 11:16:15.858  1081  8216 D DhcpStateMachine: WaitBeforeStartState{ when=-4ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.858  1081  8216 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 11:16:15.859  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:16:15.859  1081  1081 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 11:16:15.860  1081  1081 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 11:16:15.860  1081  1081 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 11:16:15.860  1081  1375 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:16:15.861  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:16:15.861  1081  1375 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:16:15.861  1081  1375 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:16:15.862  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:16:15.862  1081  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 11:16:15.863  1081  1427 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 11:16:15.863  1081  1375 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 11:16:15.864  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 11:16:15.864  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 11:16:15.864  8106  8106 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 11:16:15.864  1081  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.864  1081  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.865  1081  1375 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 11:16:15.865  1081  1375 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 11:16:15.865  8106  8106 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 11:16:15.865  1081  1375 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 11:16:15.865  1081  1375 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 11:16:15.882  1081  1375 D WifiNative-wlan0: SET ps 1: returned true
08-31 11:16:15.882  1081  1427 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 11:16:15.883  1081  1375 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 11:16:15.883  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 11:16:15.883  1081  1375 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 11:16:15.884  1081  1427 D ConnectivityService: ignoring duplicate network state non-change
,08-31 11:16:15.887  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:16:15.887  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:16:15.889  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:16:15.891  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.891  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.891  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 11:16:15.892  1081  1427 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 11:16:15.892  1081  1427 D ConnectivityService: Adding iface wlan0 to network 102
08-31 11:16:15.895  1081  1375 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 11:16:15.903  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.903  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.903  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 11:16:15.904  1081  1081 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-31 11:16:15.907  1951  1951 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-31 11:16:15.907  7843  7958 D UEI.SmartControl: Internal timer expired: 3
08-31 11:16:15.907  7843  7958 D UEI.SmartControl: unbind internal service
08-31 11:16:15.912  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:16:15.912  1585  1585 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 11:16:15.914  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:16:15.914  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.914  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.915  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 11:16:15.915  1081  1081 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 11:16:15.917  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:16:15.917  1585  1585 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,08-31 11:16:15.917  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:16:15.921  7843  7843 D UEI.SmartControl: Service.onUnbind: IControl
08-31 11:16:15.921  1081  1081 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:16:15.921  1081  1081 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:16:15.921  7843  7843 D UEI.SmartControl: Service.onDestroy
08-31 11:16:15.921  7843  7843 D UEI.SmartControl: Lock is in USE false
08-31 11:16:15.921  1081  1081 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-31 11:16:15.921  7843  7843 D UEI.SmartControl: unbind internal service
08-31 11:16:15.921  7843  7843 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@7675e84
08-31 11:16:15.921  7843  7843 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-31 11:16:15.921  7843  7843 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-31 11:16:15.921  7843  7843 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-31 11:16:15.921  7843  7843 W System.err: 	at com.uei.control.Service.c(Unknown Source)
,08-31 11:16:15.921  7843  7843 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-31 11:16:15.921  7843  7843 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-31 11:16:15.922  7843  7843 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-31 11:16:15.922  7843  7843 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-31 11:16:15.922  7843  7843 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:15.922  7843  7843 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:16:15.922  7843  7843 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:16:15.922  7843  7843 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:15.922  7843  7843 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-31 11:16:15.922  7843  7843 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:16:15.922  7843  7843 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:16:15.922  7843  7843 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@7675e84
08-31 11:16:15.922  7843  7843 D serial_port: close(fd = 24)
,08-31 11:16:15.925  7843  7843 I UEI.SmartControl: Serial port is closed.
08-31 11:16:15.925  7843  7843 I UEI.SmartControl: Serial port is closed.
08-31 11:16:15.925  7843  7843 D UEI.SmartControl: Blaster closed
,08-31 11:16:15.925  7843  7843 D UEI.SmartControl: Shut down QS...
08-31 11:16:15.925  7843  7843 D UEI.SmartControl: Stopping QS lib
08-31 11:16:15.925  7843  7843 D UEI.SmartControl: QS lib stop result = true
08-31 11:16:15.925  7843  7843 D UEI.SmartControl: Stopped QS lib
08-31 11:16:15.925  7843  7843 D UEI.SmartControl: QS shutdown complete
08-31 11:16:15.927  1081  1427 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 11:16:15.927  1081  1427 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-31 11:16:15.928  1081  1427 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-31 11:16:15.929   318   912 E Netd    : netlink response contains error (File exists)
08-31 11:16:15.929  1081  1427 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-31 11:16:15.930  1081  1427 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-31 11:16:15.930  1081  1427 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-31 11:16:15.930  1081  1427 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-31 11:16:15.931  1081  1427 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 11:16:15.931  1081  1427 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-31 11:16:15.931  1081  1427 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-31 11:16:15.931  1081  1427 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-31 11:16:15.931  1081  1427 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:16:15.931  1081  8211 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.931  1081  8211 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 11:16:15.931  1081  1427 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:16:15.931  1081  1427 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 11:16:15.931  1081  1427 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:16:15.931  1081  8211 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:16:15.931  1081  1427 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 11:16:15.931  1081  1427 D ConnectivityService: currentScore = 0, newScore = 20
08-31 11:16:15.931  1081  1427 D ConnectivityService:    accepting network in place of null
08-31 11:16:15.931  1081  8211 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 11:16:15.931  1081  1427 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:16:15.931  1081  1375 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:16:15.931  1081  1375 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:16:15.934   318  8221 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-31 11:16:15.934  1862  1862 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capa,bilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:16:15.935  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 11:16:15.937  1081  1427 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 11:16:15.937  1081  1427 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-31 11:16:15.937  1081  1427 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:16:15.937  1081  1427 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:15.937  1081  1427 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 11:16:15.937  1585  1585 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 11:16:15.937  1585  1585 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 11:16:15.937  1081  1427 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 11:16:15.937  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:16:15.938  1081  1427 D ConnectivityService: validation of new default Network = false
08-31 11:16:15.938  1081  1427 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 11:16:15.938  1081  1427 D DSQN    : enableDataServiceNotify 
08-31 11:16:15.938  1081  1427 D DSQN    : start dsqn bin
08-31 11:16:15.939  1081  1081 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 11:16:15.939  1081  1081 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 11:16:15.939  1081  1081 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 11:16:15.939  1081  1081 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 11:16:15.947  1081  1427 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-31 11:16:15.947  1081  1373 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-31 11:16:15.947  1081  1427 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:16:15.947  1081  1427 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:16:15.948  1081  1427 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:16:15.948  1585  1795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 11:16:15.945  8223  8223 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 11:16:15.945  8223  8223 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:15.956  6631  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:16:15.956  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:15.956  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:16:15.956  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:15.956  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:15.956  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:15.956  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:15.956  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:16:15.957  6631  6712 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:15.960  6631  6712 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-31 11:16:15.961  6631  6712 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-31 11:16:15.962  6631  6712 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@32f6eb33 Bundle[{}]
08-31 11:16:15.963  6631  6712 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 11:16:15.963  6631  6712 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-31 11:16:15.963  6631  6712 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-31 11:16:15.964  6631  6712 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 11:16:15.964  8223  8223 E DSQN    : DSQN ssw
08-31 11:16:15.964  6631  6712 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-31 11:16:15.964  6631  6712 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-31 11:16:15.969  6631  6712 I System.out: Running OutgoingSocketThread
08-31 11:16:15.971  6631  8227 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 876)
08-31 11:16:15.972  6631  8227 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54714
08-31 11:16:15.972  6631  8227 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-31 11:16:15.974  1585  1585 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 11:16:15.975  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:16:15.976  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 11:16:16.062  1081  8216 D DhcpStateMachine: DHCPV4 request on wlan0
,08-31 11:16:16.062  1081  8216 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-31 11:16:16.062  1081  8216 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-31 11:16:16.065  8228  8228 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:16.065  8228  8228 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 11:16:16.091  8228  8228 I dhcpcd  : version 5.5.6 starting
08-31 11:16:16.093  8228  8228 E dhcpcd  : get_duid: m
08-31 11:16:16.093  8228  8228 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 11:16:16.093  8228  8228 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-31 11:16:16.103  8194  8194 W ExternalStrings: load override strings
08-31 11:16:16.103  8194  8194 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:16:16.103  8194  8194 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:16:16.105  8194  8194 D StatusProvider: onCreate
08-31 11:16:16.142  8194  8194 V Signer  : override build config not found
08-31 11:16:16.142  8194  8194 D Signer  : value of property debug is false
,08-31 11:16:16.165  8194  8194 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-31 11:16:16.165  8194  8194 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,08-31 11:16:16.165  8194  8194 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,08-31 11:16:16.165  8194  8194 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-31 11:16:16.166  8194  8194 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-31 11:16:16.166  8194  8194 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-31 11:16:16.166  8194  8194 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-31 11:16:16.166  8194  8194 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-31 11:16:16.166  8194  8194 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-31 11:16:16.166  8194  8194 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-31 11:16:16.166  8194  8194 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-31 11:16:16.167  8194  8194 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-31 11:16:16.167  8194  8194 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-31 11:16:16.174  8194  8194 V LGMDMManager: Create singleton instance
08-31 11:16:16.205  8228  8228 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 11:16:16.205  8228  8228 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 11:16:16.205  8228  8228 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 11:16:16.205  8228  8228 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,08-31 11:16:16.205  8228  8228 D dhcpcd  : wlan0: sending REQUEST (xid 0x61b80ea7), next in 4.75 seconds
,08-31 11:16:16.209  8194  8194 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-31 11:16:16.220  8228  8228 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-31 11:16:16.249  8228  8228 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 11:16:16.249  8228  8228 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-31 11:16:16.249  8228  8228 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 11:16:16.249  8228  8228 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-31 11:16:16.249  8228  8228 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-31 11:16:16.250  8228  8228 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 11:16:16.250  8228  8228 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 11:16:16.250  8228  8228 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-31 11:16:16.291  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:16:16.298  8194  8243 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 11:16:16.302  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:16.310  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:16.354  1081  2310 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8250 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-31 11:16:16.355  1081  2310 I ActivityManager: Killing 7308:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-31 11:16:16.514  8194  8242 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-31 11:16:16.597  1081  1927 W libprocessgroup: failed to open /acct/uid_10093/pid_7308/cgroup.procs: No such file or directory
08-31 11:16:16.620  8250  8250 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 11:16:16.643  8250  8250 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-31 11:16:16.666  1081  8216 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-31 11:16:16.669  1081  8216 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-31 11:16:16.669  8250  8250 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-31 11:16:16.669  1081  8216 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 11:16:16.669  8250  8250 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-31 11:16:16.669  1081  8216 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-31 11:16:16.669  1081  8216 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-31 11:16:16.670  1081  8216 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 11:16:16.670  1081  8216 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-31 11:16:16.670  1081  8216 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 11:16:16.670  8250  8250 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-31 11:16:16.670  1081  8216 D DhcpStateMachine: RunningState
08-31 11:16:16.670  8250  8250 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-31 11:16:16.670  8250  8250 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-31 11:16:16.671  8250  8250 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-31 11:16:16.682  8250  8250 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-31 11:16:16.693  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:16.697  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:16:16.710  8250  8250 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 11:16:16.711  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-31 11:16:16.712  8250  8250 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-31 11:16:16.713  6909  6909 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 11:16:16.715  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:16.715  8194  8243 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:16:16.715  8250  8250 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-31 11:16:16.718  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:16:16.721  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:16:16.725  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:16.725  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:16.726  8250  8250 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 11:16:16.728  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:16.729  8194  8243 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:16:16.733  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:16:16.736  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:16.740  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:16.740  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:16.741  8250  8250 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 11:16:16.742  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:16.742  8194  8243 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:16:16.746  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 11:16:16.750  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:16.755  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:16.755  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:16.755  8250  8250 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 11:16:16.758  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 11:16:16.758  6909  6909 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 11:16:16.758  6909  6909 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 11:16:16.758  6909  6909 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 11:16:16.759  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 11:16:16.759  6909  6909 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 11:16:16.759  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 11:16:16.759  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 11:16:16.759  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 11:16:16.759  6909  6909 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 11:16:16.759  6909  6909 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 11:16:16.759  6909  6909 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 11:16:16.761  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:16.762  8194  8243 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:16:16.766  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:16.769  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:16.773  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:16.774  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:16.774  8250  8250 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:16:16.776  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:16.776  8194  8243 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:16:16.780  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:16.784  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:16.788  8194  8242 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:16:16.789  8194  8242 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:16:16.790  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:16.790  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:16.790  8250  8250 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:16:16.793  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:16.793  8194  8243 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 11:16:16.799  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:16.805  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:16:16.811  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:16.811  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:16.812  8250  8250 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:16:16.820  8194  8243 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 11:16:16.820  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:16.834  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:16.846  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:16:16.853  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:16.854  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:16.861  8250  8250 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 11:16:16.865  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:16.865  8194  8243 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:16:16.872  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:16.883  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:16.891  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 11:16:16.892  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:16.893  8250  8250 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 11:16:16.898  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:16.899  8194  8243 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:16:16.902  8146  8146 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 11:16:16.906  8146  8146 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:16:16.911  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:16.919  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 11:16:16.927  8194  8242 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-31 11:16:16.930  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:16.930  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 11:16:16.932  8250  8250 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-31 11:16:16.934  8250  8250 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 11:16:16.935  8250  8250 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 11:16:16.941  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:16.942  8194  8243 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 11:16:16.948  8146  8146 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 11:16:16.949  8146  8146 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 11:16:16.953  8194  8242 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-31 11:16:16.958  6909  6909 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 11:16:16.966  6909  6909 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 11:16:16.970  8194  8242 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-31 11:16:16.972  6631  6712 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 877)
08-31 11:16:16.972  6631  6712 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 877)
08-31 11:16:16.972  8194  8242 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-31 11:16:16.973  8194  8242 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-31 11:16:16.975  8194  8242 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-31 11:16:16.975  8194  8242 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,08-31 11:16:16.980  8250  8250 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 11:16:16.981  8250  8250 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 11:16:16.982  8250  8250 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 11:16:16.982  6631  6712 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 882)
08-31 11:16:16.983  8194  8242 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-31 11:16:16.983  8250  8250 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 11:16:16.984  8250  8250 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 11:16:16.984  6631  6712 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-31 11:16:16.984  6631  6712 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 883)
08-31 11:16:16.987  8194  8242 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-31 11:16:16.989  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 11:16:16.990  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:16.990  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20fe9b9e added. We now have 2 listener(s)
,08-31 11:16:16.994  1081  2060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:16.997  8250  8250 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 11:16:16.997  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:16:16.997  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:16.997  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:16.998  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:16.998  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a06967f added. We now have 9 listener(s)
08-31 11:16:16.998  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 11:16:16.998  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:16.998  8250  8250 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-31 11:16:16.999  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:16:17.002  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:16:17.010  6631  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:17.010  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:17.010  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:16:17.010  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:17.010  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:17.010  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:17.010  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:17.010  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:16:17.012  6631  6712 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:17.012  6631  6712 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:16:17.012  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:17.012  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31763695 added. We now have 3 listener(s)
08-31 11:16:17.013  1081  1695 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:17.015  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:17.016  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:16:17.016  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:17.016  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:17.016  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:17.016  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2034d3aa added. We now have 10 listener(s)
08-31 11:16:17.016  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:17.016  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:17.016  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:17.016  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:17.016  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:17.016  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.017  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:17.017  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:17.017  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20fe9b9e removed from the list
08-31 11:16:17.017  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:17.017  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a06967f removed from the list
08-31 11:16:17.018  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:17.018  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:17.018  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.019  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.019  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.020  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:17.020  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:17.020  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:17.020  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a06967f not in the list
08-31 11:16:17.020  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.020  6631  6712 D org.thaliproject.p2p.btconne,ctorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.022  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:17.022  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:17.022  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:17.022  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2034d3aa removed from the list
08-31 11:16:17.022  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:17.022  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.022  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.022  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:17.022  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31763695 removed from the list
08-31 11:16:17.023  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:17.023  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e781b9b added. We now have 2 listener(s)
08-31 11:16:17.023  1081  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:17.026  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:16:17.026  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:17.026  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:17.026  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:17.026  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@166f2b38 added. We now have 9 listener(s)
08-31 11:16:17.026  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:16:17.027  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-31 11:16:17.030  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:17.034  6631  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:17.034  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-31 11:16:17.034  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:16:17.034  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:17.034  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:17.034  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:17.034  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:17.034  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:16:17.035  6631  6712 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:17.035  6631  6712 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:16:17.035  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:16:17.036  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30e48076 added. We now have 3 listener(s)
08-31 11:16:17.036  1081  1695 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:17.039  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-31 11:16:17.041  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:16:17.041  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:16:17.041  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:17.041  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:17.041  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:17.041  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2d677 added. We now have 10 listener(s)
08-31 11:16:17.042  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:17.042  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:16:17.042  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:16:17.042  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:16:17.042  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:17.042  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:16:17.045  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:16:17.045  1081  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:17.049  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:16:17.050  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:16:17.051  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:16:17.052  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:17.053  6631  6712 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 11:16:17.053  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:17.053  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:16:17.055  8250  8250 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:16:17.055  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:17.055  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:17.055  8250  8250 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 11:16:17.055  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:17.056  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:17.056  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.056  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:17.056  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:17.056  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e781b9b removed from the list
08-31 11:16:17.056  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:17.056  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@166f2b38 removed from the list
08-31 11:16:17.056  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:17.056  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.057  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.057  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.058  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:17.058  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:17.058  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:17.058  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@166f2b38 not in the list
08-31 11:16:17.058  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.058  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.059  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:17.060  6631  6712 D BluetoothLeScanner: could not find callback wrapper
08-31 11:16:17.060  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:16:17.060  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:17.060  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:17.060  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2d677 removed from the list
08-31 11:16:17.060  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:17.060  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list, - probably already removed
08-31 11:16:17.060  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.060  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:17.060  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30e48076 removed from the list
08-31 11:16:17.061  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:17.061  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28102e02 added. We now have 2 listener(s)
08-31 11:16:17.061  1081  1558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:17.063  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:16:17.063  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:17.063  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:17.063  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:17.063  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14746313 added. We now have 9 listener(s)
08-31 11:16:17.064  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:17.064  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:16:17.066  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:16:17.071  6631  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:17.071  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:17.071  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:16:17.071  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:17.071  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:17.071  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:17.071  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:17.071  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:16:17.073  6631  6712 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:17.074  6631  6712 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:16:17.074  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:17.074  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13382749 added. We now have 3 listener(s)
08-31 11:16:17.074  1081  1986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:17.076  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:17.076  8250  8250 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-31 11:16:17.078  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:16:17.078  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:17.078  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:17.078  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:17.078  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3657284e added. We now have 10 listener(s)
08-31 11:16:17.078  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:17.078  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 11:16:17.079  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:17.079  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:16:17.079  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:16:17.079  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:16:17.079  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:17.080  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:16:17.080  8250  8250 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-31 11:16:17.080  8250  8250 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-31 11:16:17.080  8250  8250 V SoundPool: doLoad: loading sample sampleID=1
08-31 11:16:17.080  8250  8301 V SoundPool: Start decode
08-31 11:16:17.080  8250  8301 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-31 11:16:17.081   323   323 V MediaPlayerService: decode(23, 10857164, 17813)
08-31 11:16:17.082   323   323 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-31 11:16:17.082   323   323 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-31 11:16:17.082   323   323 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-31 11:16:17.082   323   323 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-31 11:16:17.082   323   323 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-31 11:16:17.082   323   323 V MediaPlayerService: player type = 3
08-31 11:16:17.082   323   323 V AwesomePlayer: AwesomePlayer create()
08-31 11:16:17.082  8250  8250 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 11:16:17.083   323   323 V AwesomePlayer: reset_l() 
08-31 11:16:17.083   323   323 V AwesomePlayer: cancelPlayerEvents
08-31 11:16:17.083   323   323 V AwesomePlayer: setAudioSink() 
08-31 11:16:17.083   323   323 V AwesomePlayer: reset_l() 
08-31 11:16:17.083   323   323 V AudioCache: notify(0xb5474900, 8, 0, 0)
08-31 11:16:17.083   323   323 V AudioCache: ignored
08-31 11:16:17.083   323   323 V AwesomePlayer: cancelPlayerEvents
08-31 11:16:17.083   323   323 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-31 11:16:17.083   323   323 V AwesomePlayer: setDataSource_l dataSource
08-31 11:16:17.083   323   323 V LGParserOSAL: SniffLGParser start
08-31 11:16:17.083   323   323 V LGParserOSAL: MainType:5, SubType=0
08-31 11:16:17.083   323   323 V LGParserOSAL: #### check Mime : application/ogg
08-31 11:16:17.083   323   323 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-31 11:16:17.083   323   323 E MediaExtractor: Use LGExtractor :application/ogg 
08-31 11:16:17.085  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:16:17.085  1081  1695 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:17.085  7843  7843 D UEI.SmartControl: QS Service created
08-31 11:16:17.089  8250  8250 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-31 11:16:17.092  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:16:17.092  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-,31 11:16:17.094  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:16:17.094  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:17.095  8250  8250 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 11:16:17.096  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 11:16:17.096  6631  6712 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 11:16:17.096  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:17.096  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:17.096  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:17.096  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:17.096  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.096  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:17.096  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:17.096  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28102e02 removed from the list
08-31 11:16:17.096  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:17.096  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14746313 removed from the list
08-31 11:16:17.096  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:17.096  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.099  7843  7843 I UEI.SmartControl: Service initServices...
08-31 11:16:17.099  7843  7843 D UEI.SmartControl: QS start get config
,08-31 11:16:17.108  8250  8250 V LGMDMManager: Create singleton instance
08-31 11:16:17.109  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.109  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.110  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:17.110  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:17.110  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:17.110  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14746313 not in the list
08-31 11:16:17.110  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.110  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.113  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:16:17.115  6631  6712 D BluetoothLeScanner: could not find callback wrapper
08-31 11:16:17.115  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:16:17.115  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:17.115  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:17.115  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3657284e removed from the list
08-31 11:16:17.115  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:17.115  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.115  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.115  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:17.115  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13382749 removed from the list
08-31 11:16:17.116  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:17.116  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@252ef05 added. We now have 2 listener(s)
08-31 11:16:17.116  1081  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:17.119  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:16:17.119  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:17.119  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:17.119  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:17.119  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25017b5a added. We now have 9 listener(s)
08-31 11:16:17.119  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:17.119  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:16:17.121  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:17.124  6631  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:17.124  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:17.124  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:16:17.124  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:17.124  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:17.124  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:17.124  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:17.124  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - active network t,ype is Wi-Fi: true
,08-31 11:16:17.128  6631  6712 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:17.128  6631  6712 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:16:17.129  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:17.129  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@289fd268 added. We now have 3 listener(s)
08-31 11:16:17.129  1081  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:17.130  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:17.131  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:17.131  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:16:17.131  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:17.131  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:17.132  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:17.132  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22987681 added. We now have 10 listener(s)
08-31 11:16:17.132  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:17.132  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:16:17.132  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:16:17.132  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:16:17.132  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:17.132  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:16:17.134  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:16:17.134  1081  2310 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:17.138  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:16:17.138  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:16:17.140  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:16:17.140  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:17.141  6631  6712 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 11:16:17.143  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activi,ties and killing connections
08-31 11:16:17.143  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:17.143  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:17.143  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:17.143  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.143  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:17.143  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:17.143  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@252ef05 removed from the list
08-31 11:16:17.143  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:17.143  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25017b5a removed from the list
08-31 11:16:17.143  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:17.143  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.144  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.144   323   323 V LGParserOSAL: supported mime: application/ogg
08-31 11:16:17.144  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.144   323   323 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-31 11:16:17.144   323   323 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-31 11:16:17.144   323   323 V AwesomePlayer: mBitrate = -1 bits/sec
08-31 11:16:17.144   323   323 V AwesomePlayer: AudioTrack Setting
08-31 11:16:17.144   323   323 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-31 11:16:17.144   323   323 V AwesomePlayer: setAudioSource() 
08-31 11:16:17.144   323   323 V MediaPlayerService: prepare
08-31 11:16:17.144   323   323 V AwesomePlayer: prepareAsync_l() 
08-31 11:16:17.144   323   323 V MediaPlayerService: wait for prepare
08-31 11:16:17.145  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:17.145  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:17.145  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:17.145  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25017b5a not in the list
08-31 11:16:17.145  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.145  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.146  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:16:17.146  6631  6712 D BluetoothLeScanner: could not find callback wrapper
08-31 11:16:17.146  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:16:17.146  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:17.146  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:17.146  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22987681 removed from the list
08-31 11:16:17.146  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:17.146  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.146  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.146  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:17.146  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@289fd268 removed from the list
08-31 11:16:17.147  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:17.147  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30d3ad14 added. We now have 2 listener(s)
08-31 11:16:17.147  1081  2310 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:17.149   323  8302 V AwesomePlayer: onPrepareAsyncEvent() 
08-31 11:16:17.149   323  8302 V AwesomePlayer: initAudioDecoder() 
08-31 11:16:17.149   323  8302 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 11:16:17.149   323  8302 V AudioSystem: isOffloadSupported()
08-31 11:16:17.149   323  8302 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 11:16:17.149   323  8302 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 11:16:17.149   323  8302 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 11:16:17.149   323  8302 V AwesomePlayer: getUseOffload() = 0 
08-31 11:16:17.149   323  8302 V OMXCodec: OMXCodec::Create
08-31 11:16:17.149   323  8302 V OMXCodec: findMatchingCodecs()
08-31 11:16:17.149   323  8302 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-31 11:16:17.150   323  8302 V OMXCodec: matchingCodecs.size()=1
08-31 11:16:17.150   323  8302 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-31 11:16:17.150  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:16:17.150  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:17.150  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:17.150  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:17.150  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a54f9bd added. We now have 9 listener(s)
08-31 11:16:17.150  6631  6712 D org.thaliproject.p2p.btcon,nectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:17.151  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:16:17.151   323  8302 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-31 11:16:17.151   323  8302 V LGCodecAdapter: LG Codec Adapter start
08-31 11:16:17.151   323  8302 V OMXCodec: OMXCodec Createtor
08-31 11:16:17.151   323  8302 V OMXCodec: setComponentRole
08-31 11:16:17.151   323  8302 V OMXCodec: configureCodec protected=0
08-31 11:16:17.151   323  8302 V LGCodecAdapter: called getLGCodecSpecificData
08-31 11:16:17.151   323  8302 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-31 11:16:17.151   323  8302 V LGCodecOSAL: Called LGconfigureCodecMETA
08-31 11:16:17.151   323  8302 V LGCodecOSAL: Called LGconfigureCodecMSG
08-31 11:16:17.151   323  8302 V LGCodecOSAL: Not support LGCodec
08-31 11:16:17.151   323  8302 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 11:16:17.152   323  8302 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-31 11:16:17.152   323  8302 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-31 11:16:17.152   323  8302 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-31 11:16:17.152   323  8302 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 11:16:17.152  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:16:17.152   323  8302 V AudioSystem: isOffloadSupported()
08-31 11:16:17.152   323  8302 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 11:16:17.152   323  8302 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 11:16:17.152   323  8302 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-31 11:16:17.152   323  8302 V OMXCodec: init()
08-31 11:16:17.153   323  8302 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-31 11:16:17.153   323  8302 V OMXCodec: allocateBuffers
08-31 11:16:17.153   323  8302 V OMXCodec: allocateBuffersOnPort portIndex=0
08-31 11:16:17.153   323  8302 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-31 11:16:17.153   323  8302 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434240 on input port
08-31 11:16:17.153   323  8302 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on input port
08-31 11:16:17.153   323  8302 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
08-31 11:16:17.153   323  8302 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b81f0 on input port
08-31 11:16:17.153   323  8302 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 11:16:17.153   323  8302 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 11:16:17.153   323  8302 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8240 on output port
08-31 11:16:17.153   323  8302 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8920 on output port
08-31 11:16:17.153   323  8302 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8970 on output port
08-31 11:16:17.153   323  8302 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b89c0 on output port
08-31 11:16:17.153   323  8302 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 11:16:17.153   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 11:16:17.153   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
0,8-31 11:16:17.153   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-31 11:16:17.153   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-31 11:16:17.153   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-31 11:16:17.153   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-31 11:16:17.153   323  8302 V OMXCodec: init() mAsyncCompletion wait free! 
08-31 11:16:17.153   323  8302 V AwesomePlayer: finishAsyncPrepare_l() 
08-31 11:16:17.153   323  8302 V AudioCache: notify(0xb5474900, 5, 0, 0)
08-31 11:16:17.153   323  8302 V AudioCache: ignored
08-31 11:16:17.153   323  8302 V AudioCache: notify(0xb5474900, 1, 0, 0)
08-31 11:16:17.153   323  8302 V AudioCache: prepared
08-31 11:16:17.153   323   323 V AudioCache: wait - success
08-31 11:16:17.153   323   323 V MediaPlayerService: start
08-31 11:16:17.153   323   323 V AwesomePlayer: play_l() 
08-31 11:16:17.153   323   323 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-31 11:16:17.154   323   323 V AwesomePlayer: createAudioPlayer_l
08-31 11:16:17.154   323   323 V AwesomePlayer: seekAudioIfNecessary_l() 
08-31 11:16:17.154   323   323 V AwesomePlayer: startAudioPlayer_l() 
08-31 11:16:17.154   323   323 D AudioPlayer: start of Playback, useOffload 0
08-31 11:16:17.154   323   323 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 11:16:17.154   323   323 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 11:16:17.155   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-31 11:16:17.155   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-31 11:16:17.155   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-31 11:16:17.155   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-31 11:16:17.155   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-31 11:16:17.155   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 11:16:17.155   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974515776
08-31 11:16:17.155   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517536
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517616
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517696
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-31 11:16:17.156   323  8304 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8970 on output port
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8920 on output port
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8240 on output port
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8e20 on output port
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-31 11:16:17.156   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-31 11:16:17.157   323   323 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-31 11:16:17.157   323   323 V AudioCache: notify(0xb5474900, 6, 0, 0)
08-31 11:16:17.157   323   323 V AudioCache: ignored
08-31 11:16:17.157  6631  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:16:17.157  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:16:17.157  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 11:16:17.157  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:16:17.157  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:16:17.157  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:17.157  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:16:17.157  6631  6712 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:16:17.157   323   323 V MediaPlayerService: wait for playback complete
08-31 11:16:17.158  6631  6712 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:16:17.159  6631  6712 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:16:17.159  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:16:17.159  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@228c3703 added. We now have 3 listener(s)
08-31 11:16:17.160  1081  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 11:16:17.160  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:17.162   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.162   323  8306 V AudioCache: memcpy(0xac200000, 0xb57e2000, 4096)
08-31 11:16:17.162  6631  6631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:16:17.165  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 11:16:17.165  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:16:17.165  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:16:17.165  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:16:17.165  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc88680 added. We now have 10 listener(s)
08-31 11:16:17.165  6631  6712 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:16:17.165  6631  6712 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:16:17.165  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:17.165  6631  6712 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:16:17.167  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:17.167  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.167  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:16:17.168  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:17.168  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30d3ad14 removed from the list
08-31 11:16:17.168  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:17.168  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a54f9bd removed from the list
08-31 11:16:17.168  6631  6712 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:16:17.168  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.168  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.168  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.169  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:17.169  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:17.169  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:17.169  6631  6712 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a54f9bd not in the list
08-31 11:16:17.169  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.169  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.170  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:16:17.170  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:16:17.170  6631  6712 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:16:17.170  6631  6712 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc88680 removed from the list
08-31 11:16:17.170  6631  6712 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:16:17.170   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.170   323  8306 V AudioCache: memcpy(0xac201000, 0xb57e2000, 4096)
08-31 11:16:17.171   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.171   323  8306 V AudioCache: memcpy(0xac202000, 0xb57e2000, 4096)
08-31 11:16:17.171   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.171   323  8306 V AudioCache: memcpy(0xac203000, 0xb57e2000, 4096)
08-31 11:16:17.171   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.171   323  8306 V AudioCache: memcpy(0xac204000, 0xb57e2000, 4096)
08-31 11:16:17.172   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.172   323  8306 V AudioCache: memcpy(0xac205000, 0xb57e2000, 4096)
08-31 11:16:17.172  6631  6712 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:16:17.172  6631  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:16:17.172  6631  6712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:16:17.172  6631  6712 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@228c3703 removed from the list
08-31 11:16:17.172   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.172   323  8306 V AudioCache: memcpy(0xac206000, 0xb57e2000, 4096)
08-31 11:16:17.172   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.173   323  8306 V AudioCache: memcpy(0xac207000, 0xb57e2000, 4096)
08-31 11:16:17.173  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 11:16:17.173  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 11:16:17.173  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 11:16:17.173   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.173   323  8306 V AudioCache: memcpy(0xac208000, 0xb57e2000, 4096)
08-31 11:16:17.173  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:16:17.173  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 11:16:17.173  6631  6712 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:16:17.173   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.173   323  8306 V AudioCache: memcpy(0xac209000, 0xb57e2000, 4096)
08-31 11:16:17.174   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.174   323  8306 V AudioCache: memcpy(0xac20a000, 0xb57e2000, 4096)
08-31 11:16:17.174   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.174   323  8306 V AudioCache: memcpy(0xac20b000, 0xb57e2000, 4096)
08-31 11:16:17.174   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.174   323  8306 V AudioCache: memcpy(0xac20c000, 0xb57e2000, 4096)
08-31 11:16:17.175   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.175   323  8306 V AudioCache: memcpy(0xac20d000, 0xb57e2000, 4096)
08-31 11:16:17.175   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.175   323  8306 V AudioCache: memcpy(0xac20e000, 0xb57e2000, 4096)
08-31 11:16:17.175   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.175   323  8306 V AudioCache: memcpy(0xac20f000, 0xb57e2000, 4096)
08-31 11:16:17.175   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.175   323  8306 V AudioCache: memcpy(0xac210000, 0xb57e2000, 4096)
08-31 11:16:17.176   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.176   323  8306 V AudioCache: memcpy(0xac211000, 0xb57e2000, 4096)
08-31 11:16:17.176   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.176   323  8306 V AudioCache: memcpy(0xac212000, 0xb57e2000, 4096)
08-31 11:16:17.176   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.176   323  8306 V AudioCache: memcpy(0xac213000, 0xb57e2000, 4096)
08-31 11:16:17.177   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.177   323  8306 V AudioCache: memcpy(0xac214000, 0xb57e2000, 4096)
08-31 11:16:17.177   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.177   323  8306 V AudioCache: memcpy(0xac215000, 0xb57e2000, 4096)
08-31 11:16:17.177   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.177   323  8306 V AudioCache: memcpy(0xac216000, 0xb57e2000, 4096)
08-31 11:16:17.178   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.178   323  8306 V AudioCache: memcpy(0xac217000, 0xb57e2000, 4096)
08-31 11:16:17.178   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.178   323  8306 V AudioCache: memcpy(0xac218000, 0xb57e2000, 4096)
08-31 11:16:17.178   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.178   323  8306 V AudioCache: memcpy(0xac219000, 0xb57e2000, 4096)
08-31 11:16:17.179   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.179   323  8306 V AudioCache: memcpy(0xac21a000, 0xb57e2000, 4096)
08-31 11:16:17.179   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.179   323  8306 V AudioCache: memcpy(0xac21b000, 0xb57e2000, 4096)
08-31 11:16:17.179  6631  8308 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 890, name: My test thread name)
08-31 11:16:17.180   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.180   323  8306 V AudioCache: memcpy(0xac21c000, 0xb57e2000, 4096)
08-31 11:16:17.180  6631  8308 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 890, thread name: My test thread name)
08-31 11:16:17.180  6631  8308 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 890, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 11:16:17.180   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.180   323  8306 V AudioCache: memcpy(0xac21d000, 0xb57e2000, 4096)
08-31 11:16:17.181   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.181   323  8306 V AudioCache: memcpy(0xac21e000, 0xb57e2000, 4096)
,08-31 11:16:17.182  6631  8309 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 892, name: My test thread name)
08-31 11:16:17.182  6631  8309 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 892, thread name: My test thread name)
08-31 11:16:17.182  6631  8309 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 892, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 11:16:17.182   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.182   323  8306 V AudioCache: memcpy(0xac21f000, 0xb57e2000, 4096)
08-31 11:16:17.183   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.183   323  8306 V AudioCache: memcpy(0xac220000, 0xb57e2000, 4096)
08-31 11:16:17.183   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.183   323  8306 V AudioCache: memcpy(0xac221000, 0xb57e2000, 4096)
08-31 11:16:17.184   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.184   323  8306 V AudioCache: memcpy(0xac222000, 0xb57e2000, 4096)
08-31 11:16:17.184   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.184   323  8306 V AudioCache: memcpy(0xac223000, 0xb57e2000, 4096)
08-31 11:16:17.185   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.185   323  8306 V AudioCache: memcpy(0xac224000, 0xb57e2000, 4096)
08-31 11:16:17.185   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.185   323  8306 V AudioCache: memcpy(0xac225000, 0xb57e2000, 4096)
08-31 11:16:17.185  6631  6712 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-31 11:16:17.185  6631  6712 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 11:16:17.185  6631  6712 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 11:16:17.186  6631  6712 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-31 11:16:17.186  6631  6712 D com.test.thalitest.ThaliTestRunner: Total duration: 23894 ms
08-31 11:16:17.186   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.186   323  8306 V AudioCache: memcpy(0xac226000, 0xb57e2000, 4096)
08-31 11:16:17.186   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.186   323  8306 V AudioCache: memcpy(0xac227000, 0xb57e2000, 4096)
08-31 11:16:17.187   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.187   323  8306 V AudioCache: memcpy(0xac228000, 0xb57e2000, 4096)
08-31 11:16:17.187  6631  6712 I jxcore-log: Total number of executed tests:  80
08-31 11:16:17.187  6631  6712 I jxcore-log: 
08-31 11:16:17.187  6631  6712 I jxcore-log: Number of passed tests:  80
08-31 11:16:17.187  6631  6712 I jxcore-log: 
08-31 11:16:17.187  6631  6712 I jxcore-log: Number of failed tests:  0
08-31 11:16:17.187  6631  6712 I jxcore-log: 
08-31 11:16:17.187   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.187   323  8306 V AudioCache: memcpy(0xac229000, 0xb57e2000, 4096)
08-31 11:16:17.188  6631  6712 I jxcore-log: Number of ignored tests:  0
08-31 11:16:17.188  6631  6712 I jxcore-log: 
08-31 11:16:17.188   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.188  6631  6712 I jxcore-log: Total duration:  23894
08-31 11:16:17.188  6631  6712 I jxcore-log: 
08-31 11:16:17.188   323  8306 V AudioCache: memcpy(0xac22a000, 0xb57e2000, 4096)
08-31 11:16:17.188   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.188   323  8306 V AudioCache: memcpy(0xac22b000, 0xb57e2000, 4096)
08-31 11:16:17.189   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.189   323  8306 V AudioCache: memcpy(0xac22c000, 0xb57e2000, 4096)
08-31 11:16:17.190   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.190   323  8306 V AudioCache: memcpy(0xac22d000, 0xb57e2000, 4096)
08-31 11:16:17.190  6631  6712 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 11:16:17.190  6631  6712 I jxcore-log: 
08-31 11:16:17.190   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.190   323  8306 V AudioCache: memcpy(0xac22e000, 0xb57e2000, 4096)
08-31 11:16:17.190  6631  6712 I jxcore-log: My device name is: LGE-LG-D855
08-31 11:16:17.190  6631  6712 I jxcore-log: 
08-31 11:16:17.190   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.190   323  8306 V AudioCache: memcpy(0xac22f000, 0xb57e2000, 4096)
08-31 11:16:17.191   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.191   323  8306 V AudioCache: memcpy(0xac230000, 0xb57e2000, 4096)
08-31 11:16:17.191   323  8306 V AudioCache: write(0xb57e2000, 4096)
08-31 11:16:17.191   323  8306 V AudioCache: memcpy(0xac231000, 0xb57e2000, 4096)
08-31 11:16:17.191   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-31 11:16:17.192   323  8306 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 11:16:17.192   323  8306 V AwesomePlayer: postAudioEOS() 
08-31 11:16:17.192   323  8306 V AudioCache: write(0xb57e2000, 280)
08-31 11:16:17.192   323  8306 V AudioCache: memcpy(0xac232000, 0xb57e2000, 280)
08-31 11:16:17.193  6631  6712 I jxcore-log: WARN testUtils: myNameCallback not set!
08-31 11:16:17.193  6631  6712 I jxcore-log: 
08-31 11:16:17.199   323  8302 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-31 11:16:17.199   323  8302 V AwesomePlayer: onStreamDone
08-31 11:16:17.199   323  8302 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-31 11:16:17.199   323  8302 V AudioCache: notify(0xb5474900, 2, 0, 0)
08-31 11:16:17.199   323  8302 V AudioCache: playback complete
08-31 11:16:17.199   323  8302 V AwesomePlayer: pause_l() 
08-31 11:16:17.199   323  8302 V AudioCache: notify(0xb5474900, 7, 0, 0)
08-31 11:16:17.199   323  8302 V AudioCache: ignored
08-31 11:16:17.199   323  8302 V AwesomePlayer: cancelPlayerEvents
08-31 11:16:17.199   323   323 V AudioCache: wait - success
08-31 11:16:17.199   323   323 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-31 11:16:17.199   323  8302 D AudioPlayer: Pause Playback at 1068125
,08-31 11:16:17.199   323   323 V AwesomePlayer: reset_l() 
08-31 11:16:17.199   323   323 V AudioCache: notify(0xb5474900, 8, 0, 0)
08-31 11:16:17.199   323   323 V AudioCache: ignored
08-31 11:16:17.199   323   323 V AwesomePlayer: cancelPlayerEvents
08-31 11:16:17.199   323   323 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-31 11:16:17.199   323   323 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-31 11:16:17.199   323   323 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-31 11:16:17.199   323   323 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-31 11:16:17.199   323   323 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 11:16:17.199   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 11:16:17.199   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 11:16:17.199   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b81f0 on port 0
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 0
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434240 on port 0
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8e20 on port 1
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8240 on port 1
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8920 on port 1
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8970 on port 1
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-31 11:16:17.200   323  8304 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-31 11:16:17.201   323   323 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 11:16:17.201   323   323 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-31 11:16:17.201   323   323 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-31 11:16:17.202   323   323 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-31 11:16:17.202   323   323 D AudioPlayer: AudioPlayer releasing audio source
08-31 11:16:17.202   323   323 D AudioPlayer: AudioPlayer done releasing audio source
08-31 11:16:17.202   323   323 V AwesomePlayer: reset_l() 
08-31 11:16:17.202   323   323 V AwesomePlayer: cancelPlayerEvents
08-31 11:16:17.202   323   323 V AwesomePlayer: ~AwesomePlayer call
08-31 11:16:17.202   323   323 V AwesomePlayer: reset_l() 
08-31 11:16:17.202   323   323 V AwesomePlayer: cancelPlayerEvents
08-31 11:16:17.202  8250  8301 V SoundPool: close(31)
08-31 11:16:17.202  8250  8301 V SoundPool: pointer = 0xa0018000, size = 205080, sampleRate = 48000, numChannels = 2
08-31 11:16:17.203  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:17.203  6631  6712 I jxcore-log: 
08-31 11:16:17.204  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:17.204  6631  6712 I jxcore-log: 
08-31 11:16:17.205  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:17.205  6631  6712 I jxcore-log: 
08-31 11:16:17.206  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:17.206  6631  6712 I jxcore-log: 
08-31 11:16:17.207  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 11:16:17.207  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:17.207  6631  6712 I jxcore-log: 
08-31 11:16:17.208  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-31 11:16:17.208  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:17.208  6631  6712 I jxcore-log: 
08-31 11:16:17.209  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:16:17.209  6631  6712 I jxcore-log: 
08-31 11:16:17.209  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9516
08-31 11:16:17.210  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:16:17.210  6631  6712 I jxcore-log: 
08-31 11:16:17.210  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:16:17.210  6631  6712 I jxcore-log: 
08-31 11:16:17.211  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:16:17.211  6631  6712 I jxcore-log: 
08-31 11:16:17.212  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 11:16:17.212  6631  6712 I jxcore-log: 
08-31 11:16:17.212  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:16:17.212  6631  6712 I jxcore-log: 
08-31 11:16:17.213  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:16:17.213  6631  6712 I jxcore-log: 
08-31 11:16:17.213  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:16:17.213  6631  6712 I jxcore-log: 
08-31 11:16:17.214  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":,"doNotCare"}
08-31 11:16:17.214  6631  6712 I jxcore-log: 
08-31 11:16:17.214  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:16:17.214  6631  6712 I jxcore-log: 
08-31 11:16:17.214  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:16:17.214  6631  6712 I jxcore-log: 
08-31 11:16:17.215  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:16:17.215  6631  6712 I jxcore-log: 
08-31 11:16:17.215  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:16:17.215  6631  6712 I jxcore-log: 
08-31 11:16:17.216  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:16:17.216  6631  6712 I jxcore-log: 
08-31 11:16:17.216  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:16:17.216  6631  6712 I jxcore-log: 
08-31 11:16:17.217  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:16:17.217  6631  6712 I jxcore-log: 
08-31 11:16:17.217  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:17.217  6631  6712 I jxcore-log: 
08-31 11:16:17.218  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:17.218  6631  6712 I jxcore-log: 
08-31 11:16:17.218  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:17.218  6631  6712 I jxcore-log: 
08-31 11:16:17.218  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:17.218  6631  6712 I jxcore-log: 
08-31 11:16:17.219  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:17.219  6631  6712 I jxcore-log: 
08-31 11:16:17.219  6631  6712 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:16:17.219  6631  6712 I jxcore-log: 
08-31 11:16:17.221  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:17.241  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:17.244  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:17.246  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:17.248  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:17.249  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:17.252  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 11:16:17.254  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:17.256  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:17.258  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 11:16:17.309  1081  1375 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:16:17.310  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:16:17.310  1081  1375 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-31 11:16:17.310  1081  1375 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:16:17.310  1081  1375 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:16:17.310  1081  1375 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 11:16:17.311  1081  1427 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-31 11:16:17.311  1081  1427 D ConnectivityService: identical MTU - not setting
08-31 11:16:17.311  1081  1427 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 11:16:17.311  1081  1427 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-31 11:16:17.311  1081  1427 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:16:17.311  1081  1427 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:16:17.311  1081  1427 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 11:16:17.312  1585  1795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-31 11:16:17.367  7843  7843 I UEI.SmartControl: Supports setup maps: true
,08-31 11:16:17.374  7843  7843 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 11:16:17.375  7843  7843 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 11:16:17.375  7843  7843 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 11:16:17.375  7843  7843 I UEI.SmartControl: ### init IR Blaster...
08-31 11:16:17.378  7843  7843 D serial_port: Configuring serial port
08-31 11:16:17.378  7843  7843 E UEI.SmartControl: UEIBLaster setting for 616
08-31 11:16:17.378  7843  7843 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 11:16:17.378  7843  7843 I UEI.SmartControl: configuring settings for MAXQ616
08-31 11:16:17.378  7843  7843 I UEI.SmartControl: Get version...
08-31 11:16:17.394  7843  8314 D UEI.SmartControl: serial port data available: 21
,08-31 11:16:17.427  7843  7843 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 11:16:17.427  7843  7843 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 11:16:17.427  7843  7843 I UEI.SmartControl: QS saving settings...
08-31 11:16:17.428  7843  7843 D UEI.SmartControl: IR Blaster version: 25672567
,08-31 11:16:17.445  7843  8314 D UEI.SmartControl: serial port data available: 4
,08-31 11:16:17.477  8312  8312 D AndroidRuntime: 
08-31 11:16:17.477  8312  8312 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-31 11:16:17.480  8312  8312 D AndroidRuntime: CheckJNI is OFF
08-31 11:16:17.485  7843  8317 I UEI.SmartControl: Device manager: loading config....
08-31 11:16:17.486  7843  8317 D UEI.SmartControl: ----------- loading internal config...
08-31 11:16:17.490  7843  7843 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 11:16:17.493  7843  7843 E UEI.SmartControl: Services init done
08-31 11:16:17.493  7843  7843 D UEI.SmartControl: QS Service init finished
,08-31 11:16:17.499  7843  7843 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 11:16:17.499  7843  7843 D UEI.SmartControl: QS Service version code: 201091
08-31 11:16:17.500  7843  7843 D UEI.SmartControl: Service requested: Control
08-31 11:16:17.501  7843  8317 E UEI.SmartControl: Loading SETTINGS...
08-31 11:16:17.505  7843  7843 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 11:16:17.508  8250  8250 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-31 11:16:17.508  7843  7843 D UEI.SmartControl: Internal service binding...
08-31 11:16:17.510  7843  7858 I UEI.SmartControl: ------ IControl API: 11
08-31 11:16:17.510  7843  7858 D UEI.SmartControl: File observer start...
08-31 11:16:17.510  7843  7858 E UEI.SmartControl: IR Port is disabled: false
08-31 11:16:17.510  7843  7858 D UEI.SmartControl: Starting file observer...
08-31 11:16:17.511  7843  7858 I UEI.SmartControl: Registering callback...
,08-31 11:16:17.512  7843  7859 I UEI.SmartControl: ------ IControl API: 19
08-31 11:16:17.514  7843  8317 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 11:16:17.515  7843  7859 I UEI.SmartControl: Registering Services Ready callback...
08-31 11:16:17.538  7843  8316 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 11:16:17.538  7843  8316 D UEI.SmartControl: -----service ready thread exits
08-31 11:16:17.538  8250  8269 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-31 11:16:17.539  8250  8299 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-31 11:16:17.539  8250  8299 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-31 11:16:17.539  8250  8250 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-31 11:16:17.540  8250  8250 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-31 11:16:17.540  7843  7858 I UEI.SmartControl: ------ IControl API: 8
,08-31 11:16:17.544  8250  8250 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,08-31 11:16:17.545  8250  8250 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-31 11:16:17.545  8250  8250 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-31 11:16:17.546  8250  8250 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-31 11:16:17.547  8250  8250 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-31 11:16:17.548  8250  8250 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-31 11:16:17.549  8250  8250 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-31 11:16:17.553  8250  8250 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-31 11:16:17.554  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 11:16:17.556  8250  8250 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 11:16:17.557  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 11:16:17.557  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 11:16:17.558  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-31 11:16:17.559  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-31 11:16:17.560  8250  8250 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472634977559]
08-31 11:16:17.562  8250  8250 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-31 11:16:17.563  1081  2037 I ActivityManager: Killing 7327:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-31 11:16:17.581  8250  8329 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-31 11:16:17.587  8312  8312 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 11:16:17.660  1081  2010 W libprocessgroup: failed to open /acct/uid_10005/pid_7327/cgroup.procs: No such file or directory
08-31 11:16:17.667  1081  1172 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-31 11:16:17.667  1081  1172 I ActivityManager: Killing 6631:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-31 11:16:17.734  1081  1558 I WindowState: WIN DEATH: Window{25dbc70f u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 11:16:17.735  1081  1424 D WifiService: Client connection lost with reason: 4
,08-31 11:16:17.744  1081  1558 D InputDispatcher: Window went away: Window{25dbc70f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 11:16:17.907  1081  1172 I ActivityManager:   Force finishing activity ActivityRecord{2f0e70c2 u0 com.test.thalitest/.MainActivity t6}
,08-31 11:16:17.955   342   377 E GBMv2   : DFP En is all cleared set to be enabled
,08-31 11:16:17.972  1081  1896 W ActivityManager: Spurious death for ProcessRecord{1a1cd36d 6631:com.test.thalitest/u0a118}, curProc for 6631: null
,08-31 11:16:17.972  8250  8250 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-31 11:16:17.977  8250  8250 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 11:16:17.977  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-31 11:16:17.977  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-31 11:16:17.978  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-31 11:16:17.978  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,08-31 11:16:17.978  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-31 11:16:17.983  1081  1191 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-31 11:16:17.986  1081  1191 I ActivityManager:   Force finishing activity ActivityRecord{2f0e70c2 u0 com.test.thalitest/.MainActivity t6 f}
08-31 11:16:17.987  1081  1191 W ActivityManager: Duplicate finish request for ActivityRecord{2f0e70c2 u0 com.test.thalitest/.MainActivity t6 f}
,08-31 11:16:18.016  2061  2061 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-31 11:16:18.018  2061  2061 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-31 11:16:18.019  1951  1967 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-31 11:16:18.020  1951  1967 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2e833f3c co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 11:16:18.021  1951  4409 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-31 11:16:18.022  1951  4409 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2f8e64c5 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 11:16:18.022  8250  8250 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-31 11:16:18.029  1585  1585 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-31 11:16:18.038  1081  1364 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-31 11:16:18.061  2014  2014 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-31 11:16:18.063  3753  3753 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-31 11:16:18.066  7735  7735 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-31 11:16:18.066  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 11:16:18.068  4922  4922 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-31 11:16:18.069  2061  2061 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-31 11:16:18.069  4922  4922 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-31 11:16:18.069  4922  4922 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-31 11:16:18.069  4922  4922 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-31 11:16:18.069  4922  4922 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:16:18.069  4922  4922 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:16:18.069  4922  4922 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 11:16:18.069  4922  4922 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 11:16:18.069  4922  4922 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:16:18.069  4922  4922 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:16:18.069  4922  4922 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 11:16:18.070  4922  4922 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 11:16:18.070  2061  2163 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-31 11:16:18.089  2441  2586 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 11:16:18.098  5019  5019 I art     : Explicit concurrent mark sweep GC freed 8191(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 653us total 99.706ms
08-31 11:16:18.113  2061  2061 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-31 11:16:18.114  1914  1914 D ActionManagerService: notifyUserLog: 1000003
08-31 11:16:18.115  3753  4916 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-31 11:16:18.116  2061  2061 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-31 11:16:18.116  1585  1585 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-31 11:16:18.119  2061  2061 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-31 11:16:18.121  2061  2061 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-31 11:16:18.129  8194  8194 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-31 11:16:18.132  1585  1585 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-31 11:16:18.133  1585  1585 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-31 11:16:18.160  1081  2032 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:16:18.173  1081  1171 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-31 11:16:18.188  1879  1879 D SplitUIManager: split_name #11 / not available #0
,08-31 11:16:18.189  1879  1879 D SplitUIService: removed split : 
,08-31 11:16:18.199  1081  1081 I art     : Explicit concurrent mark sweep GC freed 78484(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.795ms total 175.545ms
08-31 11:16:18.199  1081  2037 I art     : WaitForGcToComplete blocked for 79.785ms for cause Explicit
08-31 11:16:18.228  1879  1879 D SplitUIManager: split_name #11 / not available #0
08-31 11:16:18.228  1879  1879 I SplitUIService: split app #11
,08-31 11:16:18.243  1081  2309 V SIM_STK : Menu title from STK is T-Mobile
08-31 11:16:18.243  1081  2309 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:16:18.275  1081  2037 I art     : Explicit concurrent mark sweep GC freed 2972(315KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.509ms total 74.825ms
,08-31 11:16:18.276  1081  1191 I art     : WaitForGcToComplete blocked for 140.368ms for cause Explicit
08-31 11:16:18.280  1802  1802 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-31 11:16:18.284  1914  1914 D ActionManagerService: notifyUserLog: 1000004
08-31 11:16:18.285  3753  4916 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-31 11:16:18.285  2061  2061 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-31 11:16:18.285  1585  1631 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 11:16:18.285  1585  1631 D KeyguardModel: createShortcutInfo...
08-31 11:16:18.289  3753  3769 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-31 11:16:18.295  2246  2246 I ConfigService: onCreate
08-31 11:16:18.297  2246  2246 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-31 11:16:18.300  1585  1631 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 11:16:18.301  1585  1631 D KeyguardModel: createShortcutInfo...
,08-31 11:16:18.302  1802  1802 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , create_time: 1430832262123
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , expire_time: 0
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , display: false
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , animation: false }
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , create_time: 1430832262287
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , expire_time: 0
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , display: false
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , animation: false }
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , create_time: 1472216588858
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , expire_time: 0
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , display: false
08-31 11:16:18.302  2061  2061 I GBoardWebViewUtils: , animation: false }
08-31 11:16:18.308  1585  1631 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 11:16:18.308  1585  1631 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:16:18.309  1081  1986 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-31 11:16:18.309  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 11:16:18.309  1585  1631 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-31 11:16:18.309  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 11:16:18.309  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 11:16:18.309  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 11:16:18.309  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 11:16:18.309  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:16:18.309  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 11:16:18.309  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 11:16:18.309  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 11:16:18.309  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 11:1,6:18.309  7735  7735 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 11:16:18.311  2061  8353 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-31 11:16:18.312  1585  1631 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-31 11:16:18.315  1585  1631 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:16:18.315  1585  1631 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 11:16:18.315  1585  1631 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 11:16:18.315  1585  1631 D KeyguardModel: createShortcutInfo...
08-31 11:16:18.316  2246  2246 I ConfigService: onBind returning update interface
08-31 11:16:18.316  2246  2246 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-31 11:16:18.316  2246  2246 I ConfigService: onBind returning config service
08-31 11:16:18.322  1585  1631 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 11:16:18.322  1585  1631 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:16:18.322  1585  1631 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:16:18.322  1585  1631 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 11:16:18.324  1585  1631 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 11:16:18.324  1585  1631 D KeyguardModel: createShortcutInfo...
,08-31 11:16:18.326  1081  1081 D administrator: Handling package changes for user 0
08-31 11:16:18.328  1585  1631 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:16:18.328  1585  1631 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 11:16:18.328  1585  1631 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-31 11:16:18.328  1585  1631 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 11:16:18.330  1585  1631 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:16:18.330  1585  1631 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 11:16:18.331  1585  1631 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 11:16:18.331  1585  1631 D KeyguardModel: createShortcutInfo...
08-31 11:16:18.335  2061  2061 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 11:16:18.336  2061  2061 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-31 11:16:18.337  1585  1585 D KeyguardModel: handleShortcutListChanged...
08-31 11:16:18.337  1585  1585 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 11:16:18.342  1585  1631 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 11:16:18.342  1585  1631 D KeyguardModel: createShortcutInfo...
,08-31 11:16:18.347  1585  1631 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
,08-31 11:16:18.347  1585  1631 D KeyguardModel: createShortcutInfo...
08-31 11:16:18.349  1585  1631 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:16:18.349  1585  1631 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 11:16:18.352  1585  1631 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 11:16:18.352  1585  1631 D KeyguardModel: createShortcutInfo...
08-31 11:16:18.354  1081  2037 V SIM_STK : Menu title from STK is T-Mobile
,08-31 11:16:18.357  1585  1631 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:16:18.357  1585  1631 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 11:16:18.358  1585  1631 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 11:16:18.358  1585  1631 D KeyguardModel: createShortcutInfo...
08-31 11:16:18.359  1585  1631 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 11:16:18.359  1585  1631 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 11:16:18.371  1585  1631 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 11:16:18.371  1585  1631 D KeyguardModel: createShortcutInfo...
,08-31 11:16:18.377  2246  2246 I ConfigService: onDestroy
08-31 11:16:18.382  1802  8355 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-31 11:16:18.386  1585  1585 D KeyguardModel: handleShortcutListChanged...
08-31 11:16:18.386  1585  1585 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 11:16:18.403  2061  2061 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-31 11:16:18.412  5748  8360 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-31 11:16:18.438  1802  8362 I PeopleContactsSync: CP2 sync disabled
,08-31 11:16:18.438  1802  5159 I Icing   : doRemovePackageData com.test.thalitest
08-31 11:16:18.451  1802  8361 W GmsApplication: Using Auth Proxy for data requests.
,08-31 11:16:18.469  7125  7125 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-31 11:16:18.490  1081  1081 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-31 11:16:18.490  1081  1081 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-31 11:16:18.490  1081  1081 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 11:16:18.495  2167  8366 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-31 11:16:18.499  2246  2328 I art     : Explicit concurrent mark sweep GC freed 6286(375KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 1.023ms total 41.453ms
08-31 11:16:18.515  2061  2061 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-31 11:16:18.518  1081  1747 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8367 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-31 11:16:18.521  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:16:18.523  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-31 11:16:18.524  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-31 11:16:18.526  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-31 11:16:18.528  1081  1561 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-31 11:16:18.528  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-31 11:16:18.533  1802  8361 W GmsApplication: Using Auth Proxy for data requests.
,08-31 11:16:18.539  1081  1177 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{abf2dcc u0 com.lge.launcher2/.Launcher t5} time:141540
08-31 11:16:18.559  8367  8367 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:16:18.559  8367  8367 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 11:16:18.560  8367  8367 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-31 11:16:18.560  8367  8367 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 11:16:18.564  2061  2061 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-31 11:16:18.564  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:16:18.566  2061  2245 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-31 11:16:18.566  2061  2245 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-31 11:16:18.578  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-31 11:16:18.579  2061  2061 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 11:16:18.579  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 11:16:18.587  2061  2061 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-31 11:16:18.588  2621  2621 D [Concierge]Service: onStartCommand(). Type : 8
08-31 11:16:18.588  2621  2621 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-31 11:16:18.589  2621  2621 D [Concierge]Service: Update widget ID : 11
08-31 11:16:18.590  2061  2061 D [Concierge]WidgetView: change position of spinner
08-31 11:16:18.591  2061  2061 I [Concierge]WidgetView: initWebView(). Time : 1472634978591
08-31 11:16:18.592  2621  2621 D [Concierge]Service: onStartCommand(). Type : 0
,08-31 11:16:18.602  1081  1191 I art     : Explicit concurrent mark sweep GC freed 10072(607KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 3.018ms total 323.223ms
08-31 11:16:18.611  2061  2061 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 503783812
08-31 11:16:18.611  2061  2061 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-31 11:16:18.611  2061  2061 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-31 11:16:18.615  2061  2061 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1fdd5f41
08-31 11:16:18.615  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-31 11:16:18.616  2061  2061 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 11:16:18.617  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 11:16:18.624  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-31 11:16:18.625  2061  2061 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-31 11:16:18.625  2061  2061 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 11:16:18.626  2061  2061 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472634865140, New one : 1472634978591
08-31 11:16:18.626  2061  2061 D [Concierge]WidgetView: Unregister all receivers
08-31 11:16:18.626  2061  2061 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 11:16:18.626  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:16:18.630  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-31 11:16:18.631  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-31 11:16:18.633  8367  8367 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-31 11:16:18.633  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,08-31 11:16:18.635  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-31 11:16:18.637  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-31 11:16:18.640  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:16:18.640  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:16:18.648  8367  8367 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-31 11:16:18.673  2061  2061 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-31 11:16:18.683  2061  2061 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-31 11:16:18.687  2061  2061 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-31 11:16:18.691  2061  2061 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 11:16:18.699  8312  8312 D AndroidRuntime: Shutting down VM
,08-31 11:16:18.713  8367  8367 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 11:16:18.722  2061  2061 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@5e1fa29 time:141723
08-31 11:16:18.725  1081  1171 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:16:18.733  1081  1171 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-31 11:16:18.738  1081  1191 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8388 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-31 11:16:18.750  2061  2061 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-31 11:16:18.759  8367  8367 D LgDataFeature: LgDataFeature() Constructor: none
08-31 11:16:18.759  8367  8367 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 11:16:18.801  1081  1695 I ActivityManager: Killing 7775:com.google.android.talk/u0a72 (adj 15): empty #17
08-31 11:16:18.842  2061  2061 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-31 11:16:18.849  1081  1375 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=53.0, 0.0, 0.0  rx=64.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-538803679] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 11:16:18.850  1081  1375 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=53.0, 0.0, 0.0  rx=64.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-538803678] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 11:16:18.850  1081  1375 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 11:16:18.870   318  8221 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-31 11:16:18.878  2061  2861 I GBoardtInterface: onReloaded()
08-31 11:16:18.880  2061  2061 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-31 11:16:18.891  1081  1927 W libprocessgroup: failed to open /acct/uid_10072/pid_7775/cgroup.procs: No such file or directory
,08-31 11:16:18.895  3753  3769 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 11:16:18.896  1585  1585 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 11:16:18.900  3753  3768 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 11:16:18.907  1081  1380 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-31 11:16:18.911  1914  1914 D ActionManagerService: notifyUserLog: 1000001
08-31 11:16:18.912  3753  4916 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-31 11:16:18.912  3753  4916 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-31 11:16:18.923  1914  1914 D ActionManagerService: notifyUserLog: 1000001
,08-31 11:16:18.925  3753  4916 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,08-31 11:16:18.925  3753  4916 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-31 11:16:18.925  3753  4916 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-31 11:16:18.925  3753  4916 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-31 11:16:18.928  3753  3769 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 11:16:18.930  8367  8367 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-31 11:16:18.934  2061  2061 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-31 11:16:18.934  2061  2061 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,08-31 11:16:18.937  2061  2061 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-31 11:16:18.937  2061  2061 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-31 11:16:18.939  1081  1427 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:16:18.939  2061  2061 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-31 11:16:18.939  2061  2061 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-31 11:16:18.942  1081  1747 I ActivityManager: Killing 7887:com.android.vending/u0a44 (adj 15): empty #17
08-31 11:16:18.942  5706  5706 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-31 11:16:18.943  1081  1176 D Tethering: MasterInitialState.processMessage what=3
,08-31 11:16:18.947  1081  1171 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:16:18.951  1081  1171 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:16:18.990  2014  2014 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-31 11:16:18.990  2014  2014 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-31 11:16:18.992  1081  1927 W libprocessgroup: failed to open /acct/uid_10044/pid_7887/cgroup.procs: No such file or directory
08-31 11:16:18.997  2014  2014 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-31 11:16:19.023  8194  8194 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-31 11:16:19.030  7547  7547 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-31 11:16:19.033  6909  6909 D PackageIntentReceiver: Not supported Hotkey customization function 
08-31 11:16:19.038  6909  6909 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-31 11:16:19.039  6909  6909 D HideNavigationAppsReceiver: replacing : false
,08-31 11:16:19.041  6909  6909 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-31 11:16:19.043  6909  6909 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-31 11:16:19.043  6909  6909 D ButtonCombinationReceiver: replacing : false
08-31 11:16:19.072  1081  1695 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8412 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:16:19.134   282   783 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
