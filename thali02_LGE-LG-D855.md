#### Test 83268893665f77c_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-06 16:55:38.434  6590  6590 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
--------- beginning of system
09-06 16:55:38.496  1033  1049 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6624 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
09-06 16:55:38.497  1033  1049 I ActivityManager: Killing 6105:com.android.vending/u0a44 (adj 15): empty #17
09-06 16:55:38.561  1033  1977 W libprocessgroup: failed to open /acct/uid_10044/pid_6105/cgroup.procs: No such file or directory
09-06 16:55:38.592  6624  6624 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 16:55:38.592  6624  6624 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-06 16:55:38.592  6624  6624 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-06 16:55:38.593  6624  6624 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 16:55:38.696  6624  6624 I AppConfig: Total System Memory = 2995761152
09-06 16:55:38.707  6624  6624 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-06 16:55:38.738  1033  1048 I ActivityManager: Killing 6154:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-06 16:55:38.770  1996  1996 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
09-06 16:55:38.770  1996  1996 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-06 16:55:38.771  1033  1905 W libprocessgroup: failed to open /acct/uid_10080/pid_6154/cgroup.procs: No such file or directory
09-06 16:55:38.775  1996  1996 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-06 16:55:38.805  6457  6457 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-06 16:55:38.811  6457  6457 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
09-06 16:55:38.854  1033  1049 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6644 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 16:55:39.127  6644  6644 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
09-06 16:55:39.211  6644  6644 D LgDataFeature: LgDataFeature() Constructor: none
09-06 16:55:39.212  6644  6644 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 16:55:39.238   332   423 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-06 16:55:39.241  3273  6677 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-06 16:55:39.271  6644  6644 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
09-06 16:55:39.291  6644  6644 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-06 16:55:39.292  6644  6644 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-06 16:55:39.310  6644  6644 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-06 16:55:39.310  6644  6644 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-06 16:55:39.323  1033  1574 I ActivityManager: Killing 5528:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-06 16:55:39.382  1033  2014 W libprocessgroup: failed to open /acct/uid_10085/pid_5528/cgroup.procs: No such file or directory
,09-06 16:55:39.392  5048  6682 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-06 16:55:39.438  1033  1742 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6683 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 16:55:39.444  1033  1713 V SIM_STK : Menu title from STK is T-Mobile
09-06 16:55:39.465   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 25.439ms
09-06 16:55:39.480  2855  2870 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-06 16:55:39.486   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 367us total 19.817ms
09-06 16:55:39.516   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 419us total 28.710ms
09-06 16:55:39.526  2855  2870 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@98a7a82 on behalf of 6644
09-06 16:55:39.547  6644  6644 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-06 16:55:39.577  6644  6644 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-06 16:55:39.620  1818  2508 I art     : Explicit concurrent mark sweep GC freed 33514(2MB) AllocSpace objects, 13(208KB) LOS objects, 51% free, 29MB/61MB, paused 1.901ms total 56.427ms
09-06 16:55:39.640  6683  6683 D DocsApplication: Installing DEX configuration.
09-06 16:55:39.649  6700  6700 D AndroidRuntime: 
09-06 16:55:39.649  6700  6700 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 16:55:39.652  6700  6700 D AndroidRuntime: CheckJNI is OFF
09-06 16:55:39.660  5048  6682 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 268 ms] updated apps [took 268 ms] 
09-06 16:55:39.661  6683  6683 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-06 16:55:39.663  6683  6683 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{14a8567d com.google.android.apps.docs}
09-06 16:55:39.678  6683  6683 D TAG     : onCreate()
09-06 16:55:39.692  6683  6683 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
09-06 16:55:39.789  6700  6700 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-06 16:55:39.793  1033  1049 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-06 16:55:39.802  1942  4414 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-06 16:55:39.804  1033  1049 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-06 16:55:39.805  1033  1049 D ActivityManager: setTaskToReturnTo : TaskRecord{567746d #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-06 16:55:39.805  1033  1049 D ActivityManager: setTaskToReturnTo : TaskRecord{567746d #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-06 16:55:39.806  1033  1049 D WindowStateEx: AppWindowTokenEx init.. 
09-06 16:55:39.807   346   371 E GBMv2   : DFP En is all cleared set to be enabled
09-06 16:55:39.833  1033  1049 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6729 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-06 16:55:39.834  6700  6700 D AndroidRuntime: Shutting down VM
09-06 16:55:39.907  1942  4414 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-06 16:55:39.908  1942  4414 D SplitWindowPolicy: topRunningActivity=ActivityInfo{feb5b89 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-06 16:55:39.909  1942  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-06 16:55:39.909  1942  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{120fe78e co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
,09-06 16:55:39.967  6729  6729 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-06 16:55:40.064  6729  6729 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-06 16:55:40.072  6729  6729 I LibraryLoader: Loading: webviewchromium
09-06 16:55:40.075  6729  6729 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5473-5477)
,09-06 16:55:40.075  6729  6729 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 16:55:40.094  6729  6729 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {29abb71f}
,09-06 16:55:40.098  6729  6729 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 16:55:40.099  6729  6729 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 16:55:40.123  6729  6729 I BrowserStartupController: Initializing chromium process, renderers=0
,09-06 16:55:40.124  6729  6729 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 16:55:40.141   323  1383 V AudioPolicyService: registerClient() client 0xb0410ac0, uid 10118
,09-06 16:55:40.141  6729  6729 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-06 16:55:40.142  6729  6729 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-06 16:55:40.142  6729  6729 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-06 16:55:40.145  1033  1095 D BluetoothManagerService: Message: 20
09-06 16:55:40.146  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10fc658f:true
09-06 16:55:40.166  6729  6729 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 16:55:40.166  6729  6729 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 16:55:40.166  6729  6729 I Adreno-EGL: Build Date: 12/12/14 금
09-06 16:55:40.166  6729  6729 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 16:55:40.166  6729  6729 I Adreno-EGL: Remote Branch: 
09-06 16:55:40.166  6729  6729 I Adreno-EGL: Local Patches: 
09-06 16:55:40.166  6729  6729 I Adreno-EGL: Reconstruct Branch: 
,09-06 16:55:40.246  6729  6766 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-06 16:55:40.250  6729  6729 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-06 16:55:40.264  6729  6729 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 16:55:40.268  6729  6729 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-06 16:55:40.270  6729  6729 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-06 16:55:40.273  6729  6729 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-06 16:55:40.273  6729  6729 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-06 16:55:40.284  6729  6729 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-06 16:55:40.290  6729  6729 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 16:55:40.290  6729  6729 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 16:55:40.318  6729  6778 D OpenGLRenderer: Render dirty regions requested: true
,09-06 16:55:40.320  6729  6778 I OpenGLRenderer: Initialized EGL, version 1.4
09-06 16:55:40.338  6729  6778 D OpenGLRenderer: Enabling debug mode 0
,09-06 16:55:40.354  6729  6729 D Atlas   : Validating map...
,09-06 16:55:40.356  6729  6776 D LgDataFeature: LgDataFeature() Constructor: none
09-06 16:55:40.356  6729  6776 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 16:55:40.359  1033  1905 D SplitWindow: check instance of lgWin Window{e381111 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 16:55:40.477  6729  6729 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@326d947a time:105879
09-06 16:55:40.477  1033  1096 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +572ms (total +669ms)
09-06 16:55:40.478  1033  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{bd3f8a2 u0 com.test.thalitest/.MainActivity t6} time:105879
,09-06 16:55:40.609  6729  6729 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-06 16:55:40.609  6729  6729 I chromium: 
,09-06 16:55:40.663  1818  5224 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
09-06 16:55:40.667  6729  6729 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 16:55:40.705  1818  5224 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,09-06 16:55:40.729  6729  6776 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-06 16:55:40.729  6729  6776 I chromium: 
,09-06 16:55:40.767  1818  5224 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,09-06 16:55:40.792  6729  6790 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435044352
,09-06 16:55:40.801  6729  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 16:55:40.801  6729  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 16:55:40.801  6729  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 16:55:40.801  6729  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 16:55:40.801  6729  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-06 16:55:40.802  6729  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb101e added. We now have 1 listener(s)
09-06 16:55:40.808  1033  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 16:55:40.813  6729  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-06 16:55:40.815  6729  6790 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 16:55:40.816  6729  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:55:40.816  6729  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:55:40.824  6729  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 16:55:40.824  6729  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 16:55:40.824  6729  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 16:55:40.824  6729  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-06 16:55:40.824  6729  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 16:55:40.824  6729  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 16:55:40.824  6729  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 16:55:40.824  6729  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 16:55:40.824  6729  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 16:55:40.824  6729  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 16:55:40.824  6729  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 16:55:40.824  6729  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 16:55:40.824  6729  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 16:55:40.824  6729  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-06 16:55:40.824  6729  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35129515 added. We now have 1 listener(s)
09-06 16:55:40.824  6729  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:55:40.832  1033  1542 D WifiService: New client listening to asynchronous messages
09-06 16:55:40.836  6729  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 16:55:40.836  6729  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-06 16:55:40.838  6729  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 16:55:40.838  6729  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 16:55:40.838  6729  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-06 16:55:40.842  6729  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:40.843  1033  1713 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:55:40.845  6729  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-06 16:55:40.861  6729  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-06 16:55:40.863  6729  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:40.863  6729  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:40.863  6729  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:40.863  6729  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:40.863  6729  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:40.863  6729  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:40.863  6729  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:40.863  6729  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:40.863  6729  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 16:55:40.863  6729  6790 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:55:40.865  6729  6790 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 16:55:40.867  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:40.869  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:40.894  6729  6729 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 16:55:41.047  6683  6683 D LgDataFeature: LgDataFeature() Constructor: none
09-06 16:55:41.047  6683  6683 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 16:55:41.236  6683  6683 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-06 16:55:41.270  1033  2071 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6807 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-06 16:55:41.332  6807  6807 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-06 16:55:41.353  6807  6807 I LockScreenSettings: New app installed broadcast received ..
09-06 16:55:41.356  6807  6807 I LockScreenSettings: Number of installed packages  1
,09-06 16:55:41.521  1033  1713 I art     : Explicit concurrent mark sweep GC freed 28521(1387KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.976ms total 157.363ms
,09-06 16:55:41.536   346   373 E GBMv2   : DFP En is all cleared set to be enabled
09-06 16:55:41.536   346   373 E GBMv2   : Set value is all cleared set the max
09-06 16:55:41.537   346   373 I GBMv2   : DFP Enabled. Ignore VFP set
09-06 16:55:41.572  1033  1977 V SIM_STK : Menu title from STK is T-Mobile
,09-06 16:55:41.576  6729  6793 W jxcore-log: Initializing JXcore engine
09-06 16:55:41.576  6729  6793 W jxcore-log: JXcore engine is ready
09-06 16:55:41.603  6793  6793 W Thread-797: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7624]" dev="sockfs" ino=7624 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-06 16:55:41.603  6793  6793 W Thread-797: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-06 16:55:41.603  6793  6793 W Thread-797: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7876]" dev="sockfs" ino=7876 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-06 16:55:41.603  6793  6793 W Thread-797: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-06 16:55:41.603  6793  6793 W Thread-797: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31533]" dev="sockfs" ino=31533 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-06 16:55:41.616  1033  1742 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6831 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 16:55:41.619  1033  1742 I ActivityManager: Killing 5658:com.lge.bnr/1000 (adj 15): empty #17
09-06 16:55:41.623  6729  6793 W jxcore-log: Starting JXcore engine
,09-06 16:55:41.696  6729  6793 W jxcore-log: Platform android
09-06 16:55:41.696  6729  6793 W jxcore-log: 
,09-06 16:55:41.696  6729  6793 W jxcore-log: Process ARCH arm
09-06 16:55:41.696  6729  6793 W jxcore-log: 
,09-06 16:55:41.700  1033  1741 W libprocessgroup: failed to open /acct/uid_1000/pid_5658/cgroup.procs: No such file or directory
09-06 16:55:41.770  6831  6831 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-06 16:55:41.770  6831  6831 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,09-06 16:55:41.848  1033  1742 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6848 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-06 16:55:41.852  1033  1742 I ActivityManager: Killing 5779:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-06 16:55:41.872  5759  5759 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-06 16:55:41.872  5759  5759 W System.err: android.os.DeadObjectException
09-06 16:55:41.872  5759  5759 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,09-06 16:55:41.872  5759  5759 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 16:55:41.872  5759  5759 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-06 16:55:41.872  5759  5759 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-06 16:55:41.872  5759  5759 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 16:55:41.872  5759  5759 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 16:55:41.872  5759  5759 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 16:55:41.873  5759  5759 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 16:55:41.873  5759  5759 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:55:41.873  5759  5759 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 16:55:41.873  5759  5759 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:41.873  5759  5759 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:41.873  5759  5759 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 16:55:41.873  5759  5759 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 16:55:41.873  5759  5759 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-06 16:55:41.873  5759  5759 W System.err: android.os.DeadObjectException
09-06 16:55:41.873  5759  5759 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 16:55:41.873  5759  5759 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 16:55:41.874  5759  5759 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-06 16:55:41.874  5759  5759 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-06 16:55:41.874  5759  5759 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 16:55:41.874  5759  5759 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 16:55:41.874  5759  5759 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 16:55:41.874  5759  5759 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 16:55:41.874  5759  5759 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:55:41.874  5759  5759 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 16:55:41.874  5759  5759 W System.err: ,	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:41.874  5759  5759 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:41.874  5759  5759 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 16:55:41.874  5759  5759 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 16:55:41.874  5759  5759 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-06 16:55:41.874  5759  5759 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-06 16:55:41.902  6729  6793 I jxcore-log: JXcore Cordova bridge is ready!
09-06 16:55:41.902  6729  6793 I jxcore-log: 
09-06 16:55:41.902  6729  6793 W jxcore-log: JXcore engine is started
,09-06 16:55:41.906  6729  6790 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-06 16:55:41.909  6729  6729 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-06 16:55:42.090  1033  1995 W libprocessgroup: failed to open /acct/uid_1000/pid_5779/cgroup.procs: No such file or directory
,09-06 16:55:42.091  1033  1995 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
09-06 16:55:42.100  5759  5759 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-06 16:55:42.101  5759  5759 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-06 16:55:42.182  1033  1940 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6868 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 16:55:42.183  5759  5759 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-06 16:55:42.189  6848  6848 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,09-06 16:55:42.225  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,09-06 16:55:42.228  6848  6848 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-06 16:55:42.252  1033  1959 I ActivityManager: Killing 5759:com.lge.qremote/u0a112 (adj 15): empty #17
,09-06 16:55:42.263  6868  6868 D UEI.SmartControl: Quickset Services start...
09-06 16:55:42.267  6868  6868 I UEI.SmartControl: Manufacture = LGE
,09-06 16:55:42.268  6868  6868 D UEI.SmartControl: Id = LGNevo
09-06 16:55:42.271  6868  6868 D UEI.SmartControl: File observer start...
09-06 16:55:42.272  6868  6868 E UEI.SmartControl: IR Port is disabled: false
,09-06 16:55:42.273  6868  6868 D UEI.SmartControl: Starting file observer...
09-06 16:55:42.273  6868  6868 D UEI.SmartControl: Extracting JNI libs...
09-06 16:55:42.273  6868  6868 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,09-06 16:55:42.355  6868  6868 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-06 16:55:42.355  6868  6868 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,09-06 16:55:42.355  6868  6868 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-06 16:55:42.359  1033  1741 W libprocessgroup: failed to open /acct/uid_10112/pid_5759/cgroup.procs: No such file or directory
09-06 16:55:42.382  6868  6868 I UEI.SmartControl: --- Selecting new region: 6
,09-06 16:55:42.385  6868  6868 I UEI.SmartControl: Model = LG-D855
,09-06 16:55:42.386  6868  6868 D UEI.SmartControl: QS Service created
09-06 16:55:42.397  6868  6868 I UEI.SmartControl: Service initServices...
,09-06 16:55:42.401  6868  6868 D UEI.SmartControl: QS start get config
,09-06 16:55:42.443  6868  6868 D UEI.SmartControl: Loading JNI Libs...
,09-06 16:55:42.692  6868  6868 I UEI.SmartControl: Supports setup maps: true
09-06 16:55:42.695  6868  6868 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 16:55:42.695  6868  6868 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 16:55:42.695  6868  6868 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 16:55:42.696  6868  6868 I UEI.SmartControl: ### init IR Blaster...
,09-06 16:55:42.710  6868  6868 D serial_port: Configuring serial port
09-06 16:55:42.713  6868  6868 E UEI.SmartControl: UEIBLaster setting for 616
09-06 16:55:42.713  6868  6868 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 16:55:42.717  6868  6868 I UEI.SmartControl: configuring settings for MAXQ616
09-06 16:55:42.717  6868  6868 I UEI.SmartControl: Get version...
,09-06 16:55:42.733  6868  6896 D UEI.SmartControl: serial port data available: 21
,09-06 16:55:42.761  6868  6868 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-06 16:55:42.761  6868  6868 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 16:55:42.762  6868  6868 I UEI.SmartControl: QS saving settings...
09-06 16:55:42.764  6868  6868 D UEI.SmartControl: IR Blaster version: 25672567
09-06 16:55:42.781  6868  6896 D UEI.SmartControl: serial port data available: 4
,09-06 16:55:42.821  6868  6899 I UEI.SmartControl: Device manager: loading config....
09-06 16:55:42.822  6868  6899 D UEI.SmartControl: ----------- loading internal config...
,09-06 16:55:42.829  6868  6868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-06 16:55:42.831  6868  6868 E UEI.SmartControl: Services init done
09-06 16:55:42.831  6868  6868 D UEI.SmartControl: QS Service init finished
09-06 16:55:42.832  6868  6868 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 16:55:42.832  6868  6868 D UEI.SmartControl: QS Service version code: 201091
09-06 16:55:42.839  6868  6868 D UEI.SmartControl: Service requested: Control
,09-06 16:55:42.844  6868  6899 E UEI.SmartControl: Loading SETTINGS...
09-06 16:55:42.845  6868  6868 D UEI.SmartControl: Request IControl service: devices are loaded...
09-06 16:55:42.846  6868  6868 D UEI.SmartControl: Service.onUnbind: IControl
09-06 16:55:42.848  6868  6868 D UEI.SmartControl: Service.onDestroy
09-06 16:55:42.848  6868  6868 D UEI.SmartControl: Lock is in USE false
09-06 16:55:42.848  6868  6868 D UEI.SmartControl: unbind internal service
09-06 16:55:42.852  6868  6899 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 16:55:42.853  6868  6868 D serial_port: close(fd = 25)
,09-06 16:55:42.858  6868  6868 I UEI.SmartControl: Serial port is closed.
09-06 16:55:42.858  6868  6868 I UEI.SmartControl: Serial port is closed.
09-06 16:55:42.858  6868  6898 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 16:55:42.858  6868  6898 D UEI.SmartControl: -----service ready thread exits
09-06 16:55:42.859  6868  6868 D UEI.SmartControl: Blaster closed
09-06 16:55:42.859  6868  6868 D UEI.SmartControl: Shut down QS...
09-06 16:55:42.859  6868  6868 D UEI.SmartControl: Stopping QS lib
09-06 16:55:42.859  6868  6868 D UEI.SmartControl: QS lib stop result = true
09-06 16:55:42.859  6868  6868 D UEI.SmartControl: Stopped QS lib
09-06 16:55:42.860  6868  6868 D UEI.SmartControl: Stopped file observer...
09-06 16:55:42.860  6868  6868 D UEI.SmartControl: QS shutdown complete
09-06 16:55:42.860  6868  6868 D UEI.SmartControl: QS Service created
09-06 16:55:42.884  6868  6868 I UEI.SmartControl: Service initServices...
,09-06 16:55:42.884  6868  6868 D UEI.SmartControl: QS start get config
09-06 16:55:43.201  6868  6868 I UEI.SmartControl: Supports setup maps: true
,09-06 16:55:43.204  6868  6868 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 16:55:43.204  6868  6868 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 16:55:43.204  6868  6868 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 16:55:43.204  6868  6868 I UEI.SmartControl: ### init IR Blaster...
09-06 16:55:43.207  6868  6868 D serial_port: Configuring serial port
09-06 16:55:43.208  6868  6868 E UEI.SmartControl: UEIBLaster setting for 616
09-06 16:55:43.208  6868  6868 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 16:55:43.208  6868  6868 I UEI.SmartControl: configuring settings for MAXQ616
09-06 16:55:43.208  6868  6868 I UEI.SmartControl: Get version...
09-06 16:55:43.226  6868  6902 D UEI.SmartControl: serial port data available: 21
,09-06 16:55:43.252  6868  6868 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 16:55:43.253  6868  6868 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 16:55:43.253  6868  6868 I UEI.SmartControl: QS saving settings...
09-06 16:55:43.254  6868  6868 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 16:55:43.271  6868  6902 D UEI.SmartControl: serial port data available: 4
,09-06 16:55:43.302  6868  6868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-06 16:55:43.303  6868  6905 I UEI.SmartControl: Device manager: loading config....
09-06 16:55:43.303  6868  6905 D UEI.SmartControl: ----------- loading internal config...
,09-06 16:55:43.304  6868  6868 E UEI.SmartControl: Services init done
09-06 16:55:43.304  6868  6868 D UEI.SmartControl: QS Service init finished
09-06 16:55:43.306  6868  6868 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 16:55:43.306  6868  6868 D UEI.SmartControl: QS Service version code: 201091
09-06 16:55:43.306  6868  6868 D UEI.SmartControl: Service requested: Control
,09-06 16:55:43.312  6868  6868 D UEI.SmartControl: Request IControl service: devices are loaded...
09-06 16:55:43.312  6868  6905 E UEI.SmartControl: Loading SETTINGS...
09-06 16:55:43.316  1033  1740 I ActivityManager: Killing 6207:com.google.android.gm/u0a64 (adj 15): empty #17
09-06 16:55:43.329  6868  6905 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-06 16:55:43.342  6868  6904 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 16:55:43.342  6868  6904 D UEI.SmartControl: -----service ready thread exits
09-06 16:55:43.482  1033  1049 W libprocessgroup: failed to open /acct/uid_10064/pid_6207/cgroup.procs: No such file or directory
,09-06 16:55:43.489  6868  6868 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@275ea63b that was originally bound here
09-06 16:55:43.489  6868  6868 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@275ea63b that was originally bound here
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 16:55:43.489  6868  6868 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-06 16:55:43.493  6868  6868 D UEI.SmartControl: Internal service binding...
09-06 16:55:43.848  6868  6901 D UEI.SmartControl: Internal timer expired: 2
,09-06 16:55:45.154  6683  6683 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,09-06 16:55:45.164  1033  1713 I ActivityManager: Killing 5998:com.google.android.talk/u0a72 (adj 15): empty #17
09-06 16:55:45.270  1033  1940 W libprocessgroup: failed to open /acct/uid_10072/pid_5998/cgroup.procs: No such file or directory
,09-06 16:55:45.855  2797  2797 I MusicWidget: mDelayedStopHandler : unbind
,09-06 16:55:45.858  2146  2146 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
09-06 16:55:45.858  2146  2146 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
09-06 16:55:45.858  2146  2146 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
09-06 16:55:45.860  2146  2146 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-06 16:55:45.860  2146  2146 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-06 16:55:45.860  2146  2146 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
09-06 16:55:45.877  2146  2146 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-06 16:55:45.878  2146  2146 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,09-06 16:55:45.883  1033  1977 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@df7769ccom.lge.music.MediaPlaybackService$5@312938a5
09-06 16:55:45.886  2146  2146 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-06 16:55:45.887  2146  2146 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 16:55:45.888  2146  2146 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 16:55:45.889  2146  2146 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 16:55:45.889  2146  2146 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@275ea63b
09-06 16:55:45.890  2146  2146 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 16:55:45.890  2146  2146 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-06 16:55:45.891  2146  2146 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 16:55:45.891  2146  2146 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-06 16:55:45.891  2146  2146 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-06 16:55:45.891  2146  2146 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 16:55:45.893  2146  2146 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 16:55:45.893  2146  2146 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 16:55:45.894  2146  2146 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 16:55:45.894  2146  2146 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-06 16:55:45.896  2146  2146 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-06 16:55:45.897  2146  2146 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
09-06 16:55:45.897  2146  2146 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-06 16:55:45.897  2146  2146 V MediaPlayer[Native]: reset
,09-06 16:55:45.908  2146  2146 V MediaPlayer[Native]: setListener
09-06 16:55:45.908  2146  2146 V MediaPlayer[Native]: disconnect
09-06 16:55:45.908  2146  2146 V MediaPlayer[Native]: destructor
09-06 16:55:45.909   323  1383 V AudioFlinger: releasing 18 from 2146 for -1
09-06 16:55:45.909   323  1383 V AudioFlinger:  decremented refcount to 0
09-06 16:55:45.909   323  1383 V AudioFlinger: purging stale effects
09-06 16:55:45.909  2146  2146 V MediaPlayer[Native]: disconnect
09-06 16:55:45.910  2146  2146 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
09-06 16:55:45.912  2146  2146 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
,09-06 16:55:45.914  2146  2146 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-06 16:55:45.915  2146  2146 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-06 16:55:45.916  2146  2146 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-06 16:55:45.916  2146  2146 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
09-06 16:55:45.916  2146  2146 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 846042234
09-06 16:55:45.916  2146  2146 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 846042234
09-06 16:55:45.922  2146  2146 I SmartShareClient: [SmartShareManagerClient] terminate service: 2146/MediaPlaybackService/896064889
09-06 16:55:45.926  2146  2146 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-06 16:55:45.926  2146  2146 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@2c41942b
,09-06 16:55:45.930  2146  2146 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
,09-06 16:55:45.930  2146  2146 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-06 16:55:45.931  2146  2146 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-06 16:55:45.931  2146  2146 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
09-06 16:55:45.933  1033  1049 I ActivityManager: Killing 5709:com.android.calendar/u0a13 (adj 15): empty #17
09-06 16:55:45.934  2146  2146 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
09-06 16:55:46.020  1033  1941 W libprocessgroup: failed to open /acct/uid_10013/pid_5709/cgroup.procs: No such file or directory
,09-06 16:55:46.133  6683  6797 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-06 16:55:47.246  6868  6879 E UEI.SmartControl: file observer is disposed!
,09-06 16:55:48.301  6868  6906 D UEI.SmartControl: Internal timer expired: 3
,09-06 16:55:48.301  6868  6906 D UEI.SmartControl: unbind internal service
,09-06 16:55:48.313  6868  6868 D UEI.SmartControl: Service.onUnbind: IControl
09-06 16:55:48.315  6868  6903 D serial_port: close(fd = 24)
,09-06 16:55:48.319  6868  6868 D UEI.SmartControl: Service.onDestroy
,09-06 16:55:48.319  6868  6868 D UEI.SmartControl: Lock is in USE false
09-06 16:55:48.319  6868  6868 D UEI.SmartControl: unbind internal service
09-06 16:55:48.322  6868  6903 I UEI.SmartControl: Serial port is closed.
09-06 16:55:48.323  6868  6868 I UEI.SmartControl: Serial port is closed.
09-06 16:55:48.323  6868  6868 I UEI.SmartControl: Serial port is closed.
09-06 16:55:48.323  6868  6868 D UEI.SmartControl: Blaster closed
09-06 16:55:48.323  6868  6868 D UEI.SmartControl: Shut down QS...
09-06 16:55:48.323  6868  6868 D UEI.SmartControl: Stopping QS lib
09-06 16:55:48.323  6868  6868 D UEI.SmartControl: QS lib stop result = true
09-06 16:55:48.323  6868  6868 D UEI.SmartControl: Stopped QS lib
09-06 16:55:48.323  6868  6868 D UEI.SmartControl: QS shutdown complete
,09-06 16:55:51.814  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 16:55:51.814  6729  6793 I jxcore-log: 
,09-06 16:55:51.818  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 16:55:51.818  6729  6793 I jxcore-log: 
09-06 16:55:51.822  6729  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:51.822  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:51.822  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:51.822  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:51.822  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:51.822  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:51.822  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:51.822  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:51.824  6729  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:51.826  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 16:55:51.826  6729  6793 I jxcore-log: 
09-06 16:55:51.828  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 16:55:51.828  6729  6793 I jxcore-log: 
,09-06 16:55:52.334  6729  6793 D executeNativeTests: Running unit tests
,09-06 16:55:52.415  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 16:55:52.415  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e added. We now have 2 listener(s)
09-06 16:55:52.415  1033  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 16:55:52.417  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 16:55:52.417  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:55:52.417  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-06 16:55:52.417  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:55:52.417  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f added. We now have 2 listener(s)
,09-06 16:55:52.417  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:55:52.418  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 16:55:52.420  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:55:52.423  6729  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:52.423  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:52.423  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:52.423  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:52.423  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:52.423  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:52.423  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:52.423  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:55:52.424  6729  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:52.424  6729  6793 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:55:52.425  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:52.427  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:52.430  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 16:55:52.431  6729  6793 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 16:55:52.431  6729  6793 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 16:55:52.437  6729  6793 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-06 16:55:52.437  6729  6793 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 16:55:52.437  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 16:55:52.437  6729  6793 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 16:55:52.437  6729  6793 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 16:55:52.438  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.440  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.440  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.440  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.440  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.441  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:52.441  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:55:52.441  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e removed from the list
09-06 16:55:52.441  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.441  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f removed from the list
09-06 16:55:52.441  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.441  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.442  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.442  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.443  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.443  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.443  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.443  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.444  6729  6793 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-06 16:55:52.445  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.445  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.445  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation,, skipping...
,09-06 16:55:52.445  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.445  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.445  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.445  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.445  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.445  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.445  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.445  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.445  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.445  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.445  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.447  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.447  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.447  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.447  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-,06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 16:55:52.451  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 16:55:52.451  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 16:55:52.451  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.451  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.452  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.452  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.452  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.452  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.452  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.452  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.452  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.452  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.452  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.452  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.452  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.452  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-06 16:55:52.452  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.452  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.452  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.453  6729  6793 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 16:55:52.454  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:52.456  6729  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:52.456  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:52.456  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:52.456  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:52.456  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:52.456  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:52.456  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:52.456  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:52.457  6729  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:52.457  6729  6793 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 16:55:52.458  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-06 16:55:52.459  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:52.459  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:55:52.459  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 16:55:52.459  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:55:52.459  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:52.459  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 16:55:52.462  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 16:55:52.462  1033  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:55:52.465  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 16:55:52.469  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
09-06 16:55:52.470  6729  6793 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-06 16:55:52.471  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 16:55:52.472  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:52.473  6729  6793 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 16:55:52.473  6729  6793 I io.jxcore.node.ConnectionHelper: start: OK
09-06 16:55:52.475  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.475  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.475  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.475  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.475  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-06 16:55:52.475  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:52.475  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.475  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.475  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.475  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.475  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.475  6729  6793 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 16:55:52.477  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:52.479  6729  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:52.479  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:52.479  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:52.479  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:52.479  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:52.479  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:52.479  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:52.479  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
,09-06 16:55:52.480  6729  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-06 16:55:52.480  6729  6793 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:55:52.481  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:52.482  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:52.482  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:55:52.482  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 16:55:52.482  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:55:52.482  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:52.482  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 16:55:52.485  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 16:55:52.485  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:52.486  6729  6793 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 16:55:52.486  6729  6793 I io.jxcore.node.ConnectionHelper: start: OK
09-06 16:55:52.487  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.487  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.487  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.487  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.487  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.487  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:52.487  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.487  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.487  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
,09-06 16:55:52.487  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.488  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.488  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.488  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.489  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.489  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.490  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:55:52.490  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:52.490  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.490  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.490  6729  6793 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 16:55:52.492  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:52.493  6729  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:52.493  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:52.493  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:52.493  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:52.493  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:52.493  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:52.493  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:52.493  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:52.494  6729  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:52.494  6729  6793 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:55:52.495  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:52.495  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:55:52.495  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 16:55:52.496  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:55:52.496  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:52.496  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 16:55:52.497  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:52.498  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 16:55:52.499  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:52.499  6729  6793 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 16:55:52.500  6729  6793 I io.jxcore.node.ConnectionHelper: start: OK
09-06 16:55:52.500  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.500  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.500  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.500  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.500  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.500  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.500  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.500  6729  6793 W ,org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.500  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:52.501  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.501  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.501  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.501  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.501  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.501  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.501  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.501  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.501  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.502  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:55:52.502  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:52.502  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.502  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.502  6729  6793 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 16:55:52.502  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.502  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.502  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.503  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.503  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.503  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.503  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.503  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.503  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.503  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.503  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.503  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.503  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.503  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.506  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.506  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.506  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:55:52.506  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:52.506  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.506  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.507  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 16:55:52.507  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.507  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.507  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.508  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.508  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.508  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.508  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.508  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.508  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.508  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.508  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.508  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.508  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.508  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.509  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.509  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.509  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:55:52.509  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:52.509  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.509  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.510  6729  6793 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-06 16:55:52.510  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.510  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.510  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.510  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.510  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.510  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.510  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.510  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.510  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.510  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.510  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.510  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.510  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.510  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.511  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.511  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.511  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:55:52.511  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:52.511  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.511  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.512  6729  6793 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 16:55:52.512  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.512  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.512  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.512  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.512  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.512  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.512  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.512  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.512  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.512  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.512  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.512  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.512  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.512  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.513  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.513  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.513  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:55:52.513  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:52.513  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.513  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.514  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 16:55:52.515  6729  6793 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 16:55:52.515  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 16:55:52.515  6729  6793 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 16:55:52.515  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 16:55:52.515  6729  6793 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 16:55:52.515  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.515  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.515  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.516  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.516  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.516  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.516  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.516  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.516  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.516  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.516  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.516  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.516  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.516  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.516  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.516  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.517  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:55:52.517  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:52.517  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.517  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.518  6729  6793 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 16:55:52.518  6729  6793 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 16:55:52.518  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 16:55:52.521  6729  6793 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 16:55:52.521  6729  6793 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 16:55:52.521  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 16:55:52.521  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 16:55:52.521  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 16:55:52.521  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 16:55:52.521  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 16:55:52.521  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 16:55:52.521  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 16:55:52.522  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 16:55:52.522  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 16:55:52.522  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 16:55:52.522  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 16:55:52.522  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 16:55:52.522  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 16:55:52.522  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 16:55:52.522  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 16:55:52.522  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 16:55:52.522  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 16:55:52.522  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 16:55:52.522  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 16:55:52.522  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 16:55:52.522  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 16:55:52.522  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 16:55:52.523  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 16:55:52.523  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 16:55:52.523  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-06 16:55:52.523  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 16:55:52.523  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 16:55:52.523  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 16:55:52.523  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 16:55:52.523  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 16:55:52.523  6729  6793 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 16:55:52.523  6729  6793 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 16:55:52.524  6729  6793 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 16:55:52.524  6729  6793 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 16:55:52.524  6729  6793 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 16:55:52.524  6729  6793 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 16:55:52.524  6729  6793 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 16:55:52.524  6729  6793 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 16:55:52.524  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 16:55:52.525  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 16:55:52.526  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 16:55:52.526  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 16:55:52.527  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 16:55:52.527  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 16:55:52.527  6729  6793 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 16:55:52.527  6729  6793 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 16:55:52.527  6729  6793 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 16:55:52.527  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.527  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.527  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.528  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.528  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.528  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.528  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 16:55:52.528  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.528  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.528  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.528  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.528  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.528  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.528  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.528  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.529  6729  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 861)
09-06 16:55:52.538  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.538  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.539  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:55:52.539  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:52.539  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.539  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.539  6729  6793 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 16:55:52.540  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.540  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.540  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.541  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.541  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.541  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.541  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.541  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.541  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.541  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.541  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.541  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.541  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.541  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.541  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.541  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.542  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:55:52.542  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:52.542  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.542  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.542  6729  6793 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 16:55:52.543  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.543  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.543  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.544  6729  6921 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 861
09-06 16:55:52.544  6729  6921 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 861)
09-06 16:55:52.544  6729  6921 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 861)
09-06 16:55:52.544  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.544  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.544  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.544  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.544  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.544  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.544  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.544  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.544  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.544  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.544  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.545  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.545  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.545  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:55:52.545  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:52.545  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.545  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.546  6729  6793 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 16:55:52.546  6729  6793 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 16:55:52.546  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 16:55:52.546  6729  6793 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 16:55:52.546  6729  6793 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 16:55:52.546  6729  6793 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 16:55:52.546  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 16:55:52.546  6729  6793 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 16:55:52.546  6729  6793 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 16:55:52.546  6729  6793 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 16:55:52.546  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 16:55:52.546  6729  6793 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 16:55:52.547  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.547  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.547  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.547  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.547  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.547  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.547  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.547  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.547  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.547  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.547  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.547  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.547  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.547  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.548  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.548  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.549  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:55:52.549  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:52.549  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.549  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.549  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.549  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.549  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.549  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.549  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.549  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.549  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.549  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.549  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.549  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.549  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.549  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.549  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.549  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.549  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.549  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.549  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.549  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.550  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.550  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.550  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.550  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.550  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.550  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.550  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.550  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.550  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.550  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.550  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.551  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.551  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.558  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:55:52.558  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:52.558  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.558  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.560  6729  6793 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 16:55:52.560  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:52.564  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 16:55:52.565  6729  6793 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 16:55:52.565  6729  6793 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 16:55:52.565  6729  6729 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 16:55:52.565  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 16:55:52.565  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 16:55:52.566  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.567  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 16:55:52.567  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 16:55:52.567  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 16:55:52.567  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.567  6729  6793 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 16:55:52.567  6729  6926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 16:55:52.567  6729  6926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 16:55:52.567  6729  6729 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 16:55:52.567  6729  6729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 16:55:52.568  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.568  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.568  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 16:55:52.568  6729  6793 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 16:55:52.568  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 16:55:52.569  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 16:55:52.569  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:55:52.569  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:52.569  6729  6793 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 16:55:52.569  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.569  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.570  6729  6793 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:55:52.570  6729  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:55:52.570  6729  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:55:52.570  6729  6729 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:55:52.571  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.571  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.571  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.571  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.571  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.571  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.571  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.571  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.571  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.571  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.571  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.571  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.572  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.572  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.572  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.572  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.572  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.572  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.572  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.573  6729  6793 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 16:55:52.573  6729  6793 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 16:55:52.573  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 16:55:52.573  6729  6793 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 16:55:52.573  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.573  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.573  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.573  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.573  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.573  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothMana,ger: release: 1 listener(s) left
09-06 16:55:52.573  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.573  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.573  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.573  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.573  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.573  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.573  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.573  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.574  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.574  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.574  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.574  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.575  1033  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:55:52.575  1033  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:55:52.576  1033  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:55:52.576  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.576  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.576  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.576  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.576  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.576  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.576  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.576  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.576  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.576  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.576  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.576  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.576  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.576  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.577  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.577  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.577  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.577  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.578  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:52.578  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:52.578  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:52.578  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:52.578  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.578  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.578  6729  6793 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8ca36e not in the list
09-06 16:55:52.578  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.578  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.578  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:52.578  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.578  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.578  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:52.578  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:52.579  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:52.579  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:52.579  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:52.579  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c14a0f not in the list
09-06 16:55:52.580  6729  6793 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 16:55:52.580  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 16:55:52.580  6729  6793 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 16:55:52.580  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 16:55:52.580  6729  6793 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 16:55:52.580  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 16:55:52.582  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 16:55:52.582  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 16:55:52.582  6729  6793 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 16:55:52.582  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 16:55:52.582  6729  6793 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 16:55:52.583  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 16:55:52.583  6729  6793 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 16:55:52.583  6729  6793 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-06 16:55:52.583  6729  6793 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 16:55:52.583  6729  6793 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 16:55:52.584  6729  6793 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 16:55:52.584  6729  6793 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 16:55:52.584  6729  6793 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 16:55:52.584  6729  6793 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-06 16:55:52.584  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:55:52.584  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e285134 added. We now have 2 listener(s)
09-06 16:55:52.584  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:55:52.586  6729  6793 D BluetoothAdapter: enable(): BT is already enabled..!
09-06 16:55:52.587  1033  1905 D WifiServiceImplEx: setWifiEnabled: true pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 16:55:52.587  1033  1905 D WifiService: setWifiEnabled: true pid=6729, uid=10118
09-06 16:55:52.587  1033  1905 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 16:55:52.588  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:55:52.588  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12209b5d added. We now have 3 listener(s)
09-06 16:55:52.588  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:55:52.590  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:55:52.591  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e26acd2 added. We now have 4 listener(s)
09-06 16:55:52.591  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:55:52.592  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:55:52.592  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b8bc1a3 added. We now have 5 listener(s)
09-06 16:55:52.592  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:55:52.593  1033  1741 D WifiServiceImplEx: setWifiEnabled: false pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 16:55:52.593  1033  1741 D WifiService: setWifiEnabled: false pid=6729, uid=10118
09-06 16:55:52.593  1033  1741 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 16:55:52.600  1033  1091 I ActivityManager: Waited long enough for: ServiceRecord{33473f92 u0 com.google.android.gms/.wearable.service.WearableService}
09-06 16:55:52.604  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 16:55:52.605  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 16:55:52.605  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-06 16:55:52.605  1033  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 16:55:52.606  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 16:55:52.606  1033  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-06 16:55:52.606  1033  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-06 16:55:52.606  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-06 16:55:52.606  1033  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 16:55:52.606  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 16:55:52.606  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 16:55:52.607  1033  2071 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:55:52.607  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 16:55:52.607  1033  2071 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@196ab774 mBinding = false
09-06 16:55:52.607  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 16:55:52.615  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 16:55:52.615  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 16:55:52.615  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:52.615  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:52.615  2641  2641 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,09-06 16:55:52.616  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 16:55:52.616  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 16:55:52.617  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
09-06 16:55:52.617  1033  2796 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:52.618  6729  6920 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-06 16:55:52.618  6729  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 861)
09-06 16:55:52.619  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 16:55:52.619  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 16:55:52.619  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-06 16:55:52.619  1033  1095 D BluetoothManagerService: Message: 2
09-06 16:55:52.620   318   893 D CommandListener: Clearing all IP addresses on wlan0
09-06 16:55:52.620  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:52.621  1033  1095 D BluetoothManagerService: Sending off request.
09-06 16:55:52.621  4301  4319 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-06 16:55:52.622  4301  4393 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-06 16:55:52.622  4301  4393 D BluetoothAdapterProperties: Setting state to 13
09-06 16:55:52.622  4301  4393 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 16:55:52.622  6729  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:52.622  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:52.622  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:52.622  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:52.622  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:52.622  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:52.622  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:52.622  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:52.622  4301  4393 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 16:55:52.623  4301  4393 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-06 16:55:52.623  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:52.623  6729  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:52.623  4301  4397 D BluetoothAdapterProperties: Scan Mode:20
09-06 16:55:52.623  6729  6793 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:55:52.623  4301  4393 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 16:55:52.624  4301  4393 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 16:55:52.625  4301  4709 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-06 16:55:52.625  4301  4709 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 16:55:52.625  4301  4709 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(Blu,etoothSocket.java:586)
09-06 16:55:52.625  4301  4709 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-06 16:55:52.625  4301  4709 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-06 16:55:52.625  4301  4709 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-06 16:55:52.625  4301  4709 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-06 16:55:52.625  4301  4709 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-06 16:55:52.625  4301  4712 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 16:55:52.625  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:52.625  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:52.625  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:52.625  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:52.625  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:52.625  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:52.625  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:52.625  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:52.625  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:52.625  4301  4748 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 16:55:52.625  4301  4751 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 16:55:52.626  4301  4757 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 16:55:52.626  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:52.626  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:52.627  1033  1095 D BluetoothManagerService: Message: 60
09-06 16:55:52.627  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-06 16:55:52.627  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-06 16:55:52.631  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:52.634  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:52.634  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:52.634  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:52.634  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:52.634  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:52.634  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:52.634  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:52.634  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:52.634  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:52.635  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:52.635  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:52.636  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-06 16:55:52.636  4301  4508 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-06 16:55:52.636  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 16:55:52.636  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-06 16:55:52.637  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:52.637  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:52.637  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:52.637  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:52.637  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:52.637  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:52.637  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:52.637  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:52.637  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:52.638  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 16:55:52.638  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 16:55:52.638  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 16:55:52.638  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 16:55:52.638  4301  4508 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:55:52.638  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 16:55:52.638  4301  4508 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:55:52.638  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 16:55:52.638  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Che,cking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:52.638  4301  4508 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 16:55:52.638  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-06 16:55:52.638  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:55:52.638  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-06 16:55:52.638  4301  4508 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 16:55:52.648  1033  1048 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-06 16:55:52.649  1033  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:52.649  1033  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:52.649  1033  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-06 16:55:52.649  1033  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:52.649  1033  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,09-06 16:55:52.669  1033  1091 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6942 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-06 16:55:52.670   318  6952 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-06 16:55:52.670  1033  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-06 16:55:52.670  1033  1543 D DSQN    : disableDataServiceNotify
09-06 16:55:52.670  1033  1543 D DSQN    : stop dsqn bin
09-06 16:55:52.671  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-06 16:55:52.671  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:52.671  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:52.672  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:52.672  1033  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1b2ed4d5
09-06 16:55:52.672  1033  1536 D LGWifiP2pService: P2pDisablingState
09-06 16:55:52.672  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:52.672  1033  1536 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:52.672  1033  1536 D LGWifiP2pService: p2p socket connection lost
09-06 16:55:52.672  1033  1536 D LGWifiP2pService: P2pDisabledState
09-06 16:55:52.672  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:52.672  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:52.673  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:52.673  1033  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-06 16:55:52.673  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:52.673  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:52.673  1033  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 16:55:52.674  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:52.674  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:52.674  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:52.674  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 16:55:52.675  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-06 16:55:52.675  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:52.675  1033  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:52.675  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 16:55:52.675  2641  2641 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 16:55:52.676  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 16:55:52.676  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 16:55:52.676  4301  4301 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:52.676  4301  4301 D BluetoothMapService: STATE_TURNING_OFF
09-06 16:55:52.676  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
09-06 16:55:52.676  4301  4301 V BluetoothMapService: Handler(): got msg=4
09-06 16:55:52.676  4301  4301 D BluetoothMapService: MAP Service closeService in
09-06 16:55:52.676   318   893 D CommandListener: Clearing all IP addresses on wlan0
09-06 16:55:52.676  4301  4301 D BluetoothMapMasInstance: MAP Service shutdown
09-06 16:55:52.676  1033  1543 D ConnectivityService: notifyTy,pe LOST for NetworkAgentInfo [WIFI () - 100]
09-06 16:55:52.676  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:52.676  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:55:52.676  4301  4301 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 16:55:52.676  4301  4301 V BluetoothMapService: MAP Service closeService out
09-06 16:55:52.677  1033  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:55:52.677  1033  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-06 16:55:52.677  1033  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-06 16:55:52.677  1033  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-06 16:55:52.677  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 16:55:52.677  1033  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:52.678  1033  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:52.678  1033  2794 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-06 16:55:52.678  1600  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 16:55:52.678  4301  4301 V BtOppService: Receiver DISABLED_ACTION 
09-06 16:55:52.678  4301  4301 I BtOppRfcommListener: stopping Accept Thread
09-06 16:55:52.679  4301  4301 V BtOppRfcommListener: close mBtServerSocket
09-06 16:55:52.679  4301  4301 V BtOppRfcommListener: waiting for thread to terminate
09-06 16:55:52.679  4301  4748 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 16:55:52.679  4301  4301 V BtOppRfcommListener: done waiting for thread to terminate
09-06 16:55:52.708  1033  1091 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6960 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 16:55:52.709  1033  1537 D WifiNative-p2p0: doBoolean: TERMINATE
09-06 16:55:52.709  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:52.709  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 16:55:52.709  1033  1537 D WifiNative-p2p0: TERMINATE: returned true
,09-06 16:55:52.709  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 16:55:52.709  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
09-06 16:55:52.709  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-06 16:55:52.711  4301  4301 V BtOppService: onDestroy
09-06 16:55:52.712  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:52.712  1033  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:52.712  1033  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:52.712  1033  1543 D NetworkManagementService: Removing idletimer
09-06 16:55:52.712  1033  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:52.713  1033  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-06 16:55:52.713  1854  1854 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:52.713  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 16:55:52.715  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-06 16:55:52.715  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-06 16:55:52.716  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:52.716  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:52.716  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 16:55:52.716  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-06 16:55:52.717  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:52.717  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:52.717  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 16:55:52.717  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 16:55:52.717  1033  1033 D RttService: SCAN_AVAILABLE : 1
09-06 16:55:52.717  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 16:55:52.717  1942  1942 D WfdsService: WifiP2pState is changed : false
09-06 16:55:52.717  1942  2350 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-06 16:55:52.717  1942  2350 D WfdsService: Set the WFDS Monitor: false
09-06 16:55:52.718  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-06 16:55:52.718  1033  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:52.718  1942  2350 D WfdsMonitor: WFDS Monitor is stopped
09-06 16:55:52.718  1942  2350 D WfdsService: STATE : WfdsDisabledState - enter
09-06 16:55:52.718  1942  2698 D CtrlSupplicant: Received on exit socket, terminate
09-06 16:55:52.718  1942  2698 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-06 16:55:52.718  1942  2351 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-06 16:55:52.718  1942  2698 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-06 16:55:52.718  1942  2698 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-06 16:55:52.718  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to ,android.provider.Settings.Global, returning read-only value.
09-06 16:55:52.718  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:52.718  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 16:55:52.719  1033  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 16:55:52.719  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 16:55:52.719  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 16:55:52.719  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 16:55:52.719  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 16:55:52.719  1033  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 16:55:52.719  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 16:55:52.719  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 16:55:52.719  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 16:55:52.719  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 16:55:52.720  1033  1556 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:52.720  1033  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:52.720  4301  4301 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-06 16:55:52.720  1033  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 16:55:52.721  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:52.721  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:52.721  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:52.721  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:52.721  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:52.721  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:52.721  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:52.721  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:52.721  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:52.722  1942  2350 W WfdsService: DefaultState - msg [9445378] is not handled
09-06 16:55:52.722  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:52.722  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:55:52.723  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored va,lue
09-06 16:55:52.723  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:52.723  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:52.723  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:52.723  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:52.723  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:52.723  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:52.723  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:52.723  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:55:52.724  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:52.724  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:55:52.724  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-06 16:55:52.724  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:52.724  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:55:52.725  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:52.727  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:52.727  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:52.727  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:52.727  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:52.727  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:52.727  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:52.727  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:52.727  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:52.727  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:55:52.727  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-06 16:55:52.728  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:52.728  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 16:55:52.728  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-06 16:55:52.746  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:52.746  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:55:52.747  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 16:55:52.748  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 16:55:52.748  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:55:52.749  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 16:55:52.765  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 16:55:52.766  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:52.766  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:52.768  6960  6960 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 16:55:52.770  6960  6960 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-06 16:55:52.770  6960  6960 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 16:55:52.770  6960  6960 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-06 16:55:52.771  6960  6960 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 16:55:52.771  6960  6960 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-06 16:55:52.772  6942  6942 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-06 16:55:52.773  6942  6942 W LG Account v2.2: No ProfileInfo entries
09-06 16:55:52.773  6942  6942 I LG Account v2.2: isEnabled: false
09-06 16:55:52.773  6942  6942 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-06 16:55:52.773  6942  6942 I Feature : [Lifetracker]Country: EU
09-06 16:55:52.773  6942  6942 I Feature : [Lifetracker]Operator: OPEN
09-06 16:55:52.773  6942  6942 I Feature : [Lifetracker]Ranking support: false
09-06 16:55:52.773  6942  6942 I Feature : [Lifetracker]Comfort support: false
09-06 16:55:52.773  6942  6942 I Feature : [Lifetracker]Accessory: true
09-06 16:55:52.773  6942  6942 I Feature : [Lifetracker]Health device: true
09-06 16:55:52.774  6942  6942 I Feature : [Lifetracker]Extra Pedometer: false
09-06 16:55:52.774  6942  6942 I Feature : [Lifetracker]Blood glucose device: false
09-06 16:55:52.774  6942  6942 I Feature : [Lifetracker]Device Number: 3
09-06 16:55:52.778  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 16:55:52.779  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:52.779  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:52.779  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 16:55:52.782  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:55:52.799  2641  2641 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-06 16:55:52.799  2641  2641 I wpa_supplicant: monitor socket send errors count : 1
09-06 16:55:52.799  2641  2641 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-2\x00 that cannot receive messages
09-06 16:55:52.800  1033  2691 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-06 16:55:52.800  1033  2691 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-06 16:55:52.811  1033  1995 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6979 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 16:55:52.812  1033  1995 I ActivityManager: Killing 6271:com.android.providers.calendar/u0a14 (adj 15): empty #17
,09-06 16:55:52.828  1033  2796 D DhcpStateMachine: StoppedState
09-06 16:55:52.829  1033  2796 D DhcpStateMachine: StoppedState{ when=-152ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 16:55:52.837  2641  2641 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 16:55:52.837  1033  2691 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-06 16:55:52.837  1033  2691 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 16:55:52.837  1033  2691 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 16:55:52.837  1033  2691 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-06 16:55:52.838  1033  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118226
09-06 16:55:52.838  1033  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=118227
09-06 16:55:52.839  1033  2691 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 16:55:52.839  2641  2641 W wpa_supplicant: USIM:  scard_deinit function
09-06 16:55:52.839  1033  2691 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 16:55:52.839  1033  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118228  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 16:55:52.839  1033  1095 D Tethering: InitialState.processMessage what=4
09-06 16:55:52.840  1033  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=118228  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,09-06 16:55:52.849  1033  1742 W libprocessgroup: failed to open /acct/uid_10014/pid_6271/cgroup.procs: No such file or directory
,09-06 16:55:52.855  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 16:55:52.856  1033  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-06 16:55:52.856  1033  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-06 16:55:52.856  1033  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:55:52.857  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:55:52.895  6960  6960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-06 16:55:52.897  6979  6979 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 16:55:52.899  4301  4301 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 16:55:52.899  4301  4301 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:52.899  4301  4301 V BluetoothPbapReceiver: ***********state = 13
09-06 16:55:52.900  4301  4301 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-06 16:55:52.901  4301  4301 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:52.901  4301  4301 V BluetoothPbapService: state: 13
09-06 16:55:52.901  4301  4301 V BluetoothPbapService: Pbap Service closeService in
09-06 16:55:52.903  4301  4301 V BluetoothPbapService: successfully stopped pbap service
09-06 16:55:52.903  4301  4301 V BluetoothPbapService: Pbap Service closeService out
09-06 16:55:52.903  1033  1095 D BluetoothManagerService: Message: 20
09-06 16:55:52.903  4301  4301 V BluetoothPbapService: Pbap Service onDestroy
09-06 16:55:52.903  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e41943f:true
09-06 16:55:52.903  4301  4301 V BluetoothPbapService: Pbap Service closeService in
09-06 16:55:52.903  4301  4301 V BluetoothPbapService: Pbap Service closeService out
09-06 16:55:52.903  4301  4301 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-06 16:55:52.903  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 16:55:52.905  6979  6979 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 16:55:52.905  6979  6979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:55:52.918  1033  1959 I ActivityManager: Killing 6335:com.android.defcontainer/u0a4 (adj 15): empty #17
,09-06 16:55:52.921  1033  1095 D BluetoothManagerService: Message: 30
09-06 16:55:52.930  2641  2641 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-06 16:55:52.930  1033  2691 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-06 16:55:52.930  1033  2691 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
,09-06 16:55:52.931  1033  2691 D WifiMonitor: Disconnecting from the supplicant, no more events
,09-06 16:55:52.931  1033  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-06 16:55:52.960  1033  2014 W libprocessgroup: failed to open /acct/uid_10004/pid_6335/cgroup.procs: No such file or directory
,09-06 16:55:52.964  1033  1095 D BluetoothManagerService: Message: 30
09-06 16:55:52.965  6960  6960 D LocalBluetoothProfileManager: Adding local MAP profile
09-06 16:55:52.967  6960  6960 D BluetoothMap: Create BluetoothMap proxy object
09-06 16:55:52.968  1033  1095 D BluetoothManagerService: Message: 30
09-06 16:55:52.975  1033  1095 D BluetoothManagerService: Message: 30
,09-06 16:55:52.978  6960  6960 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-06 16:55:52.980  6960  6960 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-06 16:55:53.000  6960  6960 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-06 16:55:53.004  6960  6960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-06 16:55:53.019  6960  6960 D DockEventReceiver: finishStartingService: stopping service
,09-06 16:55:53.032  1033  1537 D WifiOffDelayIfNotUsed: stopMonitoring
,09-06 16:55:53.032  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 16:55:53.032  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
09-06 16:55:53.032  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 16:55:53.036  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-06 16:55:53.036  1942  1942 D WfdsService: Supplicant Connection state is changed : false
09-06 16:55:53.037  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 16:55:53.037  1942  2350 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-06 16:55:53.037  1942  2350 D WfdsService: Set the WFDS Monitor: false
09-06 16:55:53.037  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-06 16:55:53.037  1942  2350 D WfdsMonitor: WFDS Monitor is stopped
09-06 16:55:53.037  2469  2469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:53.037  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-06 16:55:53.039  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:53.039  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:53.041  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:53.043  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 16:55:53.070  6729  6729 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 16:55:53.085  6960  6960 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 16:55:53.086  6960  6960 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 16:55:53.097  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:55:53.107  6960  6960 D BluetoothInputDevice: Proxy object connected
09-06 16:55:53.108  6960  6960 D HidProfile: Bluetooth service connected
09-06 16:55:53.111  6960  6960 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 16:55:53.112  6960  6960 D PanProfile: Bluetooth service connected
,09-06 16:55:53.113  6960  6960 D BluetoothMap: Proxy object connected
09-06 16:55:53.114  6960  6960 D MapProfile: Bluetooth service connected
09-06 16:55:53.114  6960  6960 D BluetoothMap: getConnectedDevices()
09-06 16:55:53.115  6960  6960 D BluetoothMap: Bluetooth is Not enabled
09-06 16:55:53.115  6960  6960 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-06 16:55:53.117  6960  6960 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-06 16:55:53.122  6960  6960 D BluetoothPermissionRequest: onReceive
09-06 16:55:53.126  6960  6960 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-06 16:55:53.137  6960  6960 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 16:55:53.138  1033  1959 I ActivityManager: Killing 6523:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-06 16:55:53.235  4301  4301 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-06 16:55:53.236  4301  4301 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-06 16:55:53.239  4301  4301 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-06 16:55:53.241  1033  1048 W libprocessgroup: failed to open /acct/uid_10008/pid_6523/cgroup.procs: No such file or directory
09-06 16:55:53.353  1033  1959 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7009 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-06 16:55:53.357  4301  4301 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:53.357  4301  4301 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 16:55:53.360  4301  4301 V BluetoothFtpService: Ftp Service onStartCommand
09-06 16:55:53.360  4301  4301 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:53.361  4301  4301 V BluetoothFtpService: Ftp Service closeService
09-06 16:55:53.361  4301  4301 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-06 16:55:53.363  4301  4301 V BluetoothFtpService: successfully stopped ftp service
09-06 16:55:53.363  4301  4301 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 16:55:53.364  4301  4301 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 16:55:53.364  4301  4301 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 16:55:53.364  4301  4301 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:53.364  4301  4301 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-06 16:55:53.364  4301  4301 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-06 16:55:53.368  4301  4301 V BluetoothFtpService: Ftp Service onDestroy
09-06 16:55:53.368  4301  4301 V BluetoothFtpService: Ftp Service closeService
09-06 16:55:53.431  1033  1941 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7026 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 16:55:53.439  4301  4301 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:53.439  4301  4301 V BluetoothSapService: state: 13
09-06 16:55:53.439  4301  4301 V BluetoothSapService: Stopping SAP server process
09-06 16:55:53.440  4301  4301 V BluetoothSapService: Sap Service closeSapService in
09-06 16:55:53.440  4301  4301 V BluetoothSapService: Close listen Socket : 
09-06 16:55:53.441  4301  4301 V BluetoothSapService: Close rfcomm Socket : 
09-06 16:55:53.441  4301  4301 V BluetoothSapService: Close sapd  Socket : 
09-06 16:55:53.442  4301  4301 V BluetoothSapService: Sap Service closeSapService out
09-06 16:55:53.443  4301  4301 V BluetoothSapService: Sap Service onDestroy
09-06 16:55:53.443  4301  4301 V BluetoothSapService: Sap Service closeSapService in
09-06 16:55:53.443  4301  4301 V BluetoothSapService: Close listen Socket : 
09-06 16:55:53.443  4301  4301 V BluetoothSapService: Close rfcomm Socket : 
09-06 16:55:53.443  4301  4301 V BluetoothSapService: Close sapd  Socket : 
09-06 16:55:53.443  4301  4301 V BluetoothSapService: Sap Service closeSapService out
09-06 16:55:53.463  7009  7009 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 16:55:53.516  7009  7009 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-06 16:55:53.519  7026  7026 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 16:55:53.535  1033  1574 I ActivityManager: Killing 6560:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-06 16:55:53.563  7009  7009 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-06 16:55:53.563  7009  7009 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-06 16:55:53.563  7009  7009 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-06 16:55:53.564  7009  7009 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-06 16:55:53.564  7009  7009 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-06 16:55:53.566  7009  7009 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-06 16:55:53.571  7009  7009 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-06 16:55:53.591  1033  1713 W libprocessgroup: failed to open /acct/uid_10011/pid_6560/cgroup.procs: No such file or directory
,09-06 16:55:53.616  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 16:55:53.623  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 16:55:53.643  4301  4397 D bt_hci_bdroid: cleanup
,09-06 16:55:53.644  4301  4686 I bt_userial_mct: exiting userial_read_thread
09-06 16:55:53.645  4301  4686 D bt_userial_mct: Leaving userial_evt_read_thread()
,09-06 16:55:53.645  4301  4397 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 16:55:53.646  4301  4510 I bt_lpm  : LPM is already off!!!
09-06 16:55:53.646  4301  4510 I bt_vendor: hw_epilog_process
09-06 16:55:53.647  4301  4397 D bt_hci_bdroid: cleanup Finalizing cleanup
09-06 16:55:53.647  4301  4397 D bt_userial_mct: userial_close
09-06 16:55:53.647  4301  4397 E bt_userial_mct: pthread_join() FAILED result:3
09-06 16:55:53.648  4301  4397 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-06 16:55:53.649  4301  4508 W bt-btif : ag scb idx 1 not allocated
09-06 16:55:53.649  4301  4508 E bt-btif : BTA AG is already disabled, ignoring ...
,09-06 16:55:53.649  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 16:55:53.649  4301  4508 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:55:53.649  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 16:55:53.649  4301  4508 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:55:53.649  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 16:55:53.649  4301  4508 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 16:55:53.649  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 16:55:53.649  4301  4508 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:55:53.649  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 16:55:53.649  4301  4508 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:55:53.650  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 16:55:53.650  4301  4508 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 16:55:53.650  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 16:55:53.650  4301  4508 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:55:53.650  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 16:55:53.650  4301  4508 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:55:53.650  4301  4508 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 16:55:53.650  4301  4508 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 16:55:53.650  4301  4508 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 16:55:53.662  7009  7009 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 16:55:53.666  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:55:53.671  7009  7009 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-06 16:55:53.672  6979  6979 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 16:55:53.673  6979  6979 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 16:55:53.673  6979  6979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:55:53.676  7009  7009 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-06 16:55:53.682  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:55:53.688  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:55:53.698  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:55:53.698  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:55:53.700  7009  7009 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 16:55:53.704  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:55:53.710  6979  6979 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 16:55:53.710  6979  6979 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 16:55:53.710  6979  6979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:55:53.716  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:55:53.719  4301  4397 D bt_hci_bdroid: set_power 0
09-06 16:55:53.719  4301  4397 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 16:55:53.719  4301  4397 I bt_vendor: bluetooth satus is on
09-06 16:55:53.719  4301  4397 I bt_vendor: bt-vendor : resetting BT status
09-06 16:55:53.719  4301  4397 I bt_vendor: Starting hciattach daemon
09-06 16:55:53.719  4301  4397 I bt_vendor: try to set false
09-06 16:55:53.720  4301  4397 I bt_vendor: Starting hciattach daemon
09-06 16:55:53.720  4301  4397 I bt_vendor: try to set false
09-06 16:55:53.721  4301  4397 I bt_vendor: cleanup
09-06 16:55:53.722  4301  4508 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-06 16:55:53.723  4301  4397 I GKI_LINUX: GKI_exit_task 0 done
09-06 16:55:53.723  4301  4397 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 16:55:53.723  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:55:53.725  4301  4393 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 16:55:53.728  4301  4301 D HeadsetService: Received stop request...Stopping profile...
09-06 16:55:53.729  4301  4301 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 16:55:53.729  4301  4301 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 16:55:53.729  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10e29a6c
09-06 16:55:53.729  4301  4457 D HeadsetStateMachine: Exit Disconnected: -1
,09-06 16:55:53.732  1854  1854 D BluetoothHeadset: Proxy object disconnected
09-06 16:55:53.732  1854  1854 D BluetoothHeadset: Proxy object disconnected
09-06 16:55:53.732  1854  1854 D BluetoothHeadset: Proxy object disconnected
09-06 16:55:53.733  1033  1033 D BluetoothHeadset: Proxy object disconnected
09-06 16:55:53.733  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 16:55:53.736  4301  4301 D A2dpService: Received stop request...Stopping profile...
09-06 16:55:53.736  4301  4486 D A2dpStateMachine: Exit Disconnected: -1
09-06 16:55:53.738  4301  4301 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-06 16:55:53.740  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 16:55:53.743  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:55:53.744  4301  4393 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 16:55:53.745  4301  4301 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-06 16:55:53.745  4301  4301 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 16:55:53.745  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10e29a6c
09-06 16:55:53.746  1033  1033 D BluetoothA2dp: Proxy object disconnected
09-06 16:55:53.746  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 16:55:53.747  7009  7009 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 16:55:53.747  4301  4301 D HidService: Received stop request...Stopping profile...
09-06 16:55:53.747  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10e29a6c
09-06 16:55:53.809  1033  1049 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7050 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-06 16:55:53.812  6960  6960 D BluetoothInputDevice: Proxy object disconnected
09-06 16:55:53.813  6960  6960 D HidProfile: Bluetooth service disconnected
09-06 16:55:53.813  4301  4301 D HeadsetStateMachine: Unbinding service...
09-06 16:55:53.815  4301  4301 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 16:55:53.815  4301  4301 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 16:55:53.815  4301  4301 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 16:55:53.815  4301  4301 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 16:55:53.815  4301  4301 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 16:55:53.815  4301  4301 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 16:55:53.815  4301  4301 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 16:55:53.817  4301  4301 D HealthService: Received stop request...Stopping profile...
09-06 16:55:53.817  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10e29a6c
09-06 16:55:53.819  4301  4301 D PanService: Received stop request...Stopping profile...
09-06 16:55:53.821  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10e29a6c
09-06 16:55:53.825  4301  4301 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 16:55:53.827  4301  4301 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 16:55:53.827  4301  4301 D BtGatt.GattService: stop()
09-06 16:55:53.827  4301  4301 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 16:55:53.829   350   350 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 475us total 23.444ms
09-06 16:55:53.829  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10e29a6c
09-06 16:55:53.831  4301  4301 D BluetoothMapService: Received stop request...Stopping profile...
09-06 16:55:53.831  4301  4301 D BluetoothMapService: stop()
09-06 16:55:53.831  4301  4301 D BluetoothMapEmailAppObserver: deinitObservers()
09-06 16:55:53.831  4301  4301 D BluetoothMapEmailAppObserver: removeReceiver()
09-06 16:55:53.832  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10e29a6c
,09-06 16:55:53.833  4301  4301 I BluetoothA2dpServiceJni: cleanupNative
09-06 16:55:53.833  4301  4487 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 16:55:53.834  4301  4301 I GKI_LINUX: GKI_exit_task 2 done
09-06 16:55:53.834  4301  4301 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 16:55:53.834  4301  4301 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 16:55:53.834  4301  4301 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 16:55:53.834  4301  4301 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 16:55:53.834  4301  4301 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 16:55:53.834  4301  4301 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 16:55:53.835  4301  4301 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 16:55:53.835  4301  4301 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 16:55:53.837  4301  4301 V BluetoothMapService: Handler(): got msg=4
09-06 16:55:53.837  4301  4301 D BluetoothMapService: MAP Service closeService in
09-06 16:55:53.837  4301  4301 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 16:55:53.837  4301  4301 V BluetoothMapService: MAP Service closeService out
09-06 16:55:53.838  4301  4393 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-06 16:55:53.838  4301  4393 D BluetoothAdapterProperties: Setting state to 10
09-06 16:55:53.838  4301  4393 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 16:55:53.838  4301  4301 D BluetoothMapService: cleanup()
09-06 16:55:53.838  4301  4301 D BluetoothMapService: MAP Service closeService in
09-06 16:55:53.838  4301  4301 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 16:55:53.838  4301  4301 V BluetoothMapService: MAP Service closeService out
09-06 16:55:53.839  4301  4393 I BluetoothAdapterState: Entering OffState
09-06 16:55:53.839  1033  1095 D BluetoothManagerService: Message: 60
09-06 16:55:53.839  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-06 16:55:53.839  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-06 16:55:53.839  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 16:55:53.839  1854  2414 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 16:55:53.840  1854  4637 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 16:55:53.841  6960  7000 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 16:55:53.841  6960  6976 D BluetoothMap: onBluetoothStateChange: up=false
09-06 16:55:53.842  1854  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 16:55:53.843  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 16:55:53.843  6960  6975 D BluetoothPan: onBluetoothStateChange on: false
09-06 16:55:53.843  6960  6960 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 16:55:53.843  6960  6960 D PanProfile: Bluetooth service disconnected
,09-06 16:55:53.848  6960  7000 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 16:55:53.849  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-06 16:55:53.849  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-06 16:55:53.852   350   350 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 450us total 21.575ms
09-06 16:55:53.852  1033  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-06 16:55:53.853  1033  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-06 16:55:53.853  1033  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@196ab774 mBinding = false
09-06 16:55:53.853  1033  1095 D BluetoothManagerService: Sending unbind request.
09-06 16:55:53.854  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-06 16:55:53.862  4301  4397 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-06 16:55:53.862  4301  4301 I GKI_LINUX: GKI_exit_task 1 done
09-06 16:55:53.862  4301  4301 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 16:55:53.863  4301  4301 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 16:55:53.863  4301  4301 I art     : --- WEIRD: removing null entry 246
09-06 16:55:53.863  4301  4301 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-06 16:55:53.863  4301  4301 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-06 16:55:53.864  4301  4301 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-06 16:55:53.865  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:53.866  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 16:55:53.867  1942  2142 D LGBluetoothAPIService: Message: 2
09-06 16:55:53.867  1942  2142 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2f270baf mBinding = false
09-06 16:55:53.867  1942  2142 D LGBluetoothAPIService: Sending unbind request.
09-06 16:55:53.869  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:53.870  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:53.871  1600  1600 D BluetoothAdapter: 269373847: getState() :  mService = null. Returning STATE_OFF
09-06 16:55:53.871  1600  1600 D BluetoothAdapter: 269373847: getState() :  mService = null. Returning STATE_OFF
09-06 16:55:53.873  4301  4301 I art     : System.exit called, status: 0
09-06 16:55:53.873  4301  4301 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-06 16:55:53.874   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 443us total 21.846ms
09-06 16:55:53.874  6960  6960 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-06 16:55:53.875  6960  6960 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-06 16:55:53.875  6960  6960 D LGBluetoothEventManager: [BTUI] clear device connection state
09-06 16:55:53.879  6960  6960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 16:55:53.888  6960  6960 D DockEventReceiver: finishStartingService: stopping service
,09-06 16:55:53.894   323   323 V AudioFlinger: 4301 died, releasing its sessions
09-06 16:55:53.894   323   323 V AudioFlinger:  pid 1854 @ 0
09-06 16:55:53.894   323   323 V AudioFlinger:  pid 3175 @ 1
09-06 16:55:53.894   323   323 V AudioFlinger:  pid 3175 @ 2
09-06 16:55:53.895  6960  6960 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-06 16:55:53.909  1033  1941 I ActivityManager: Process com.android.bluetooth (pid 4301) has died
,09-06 16:55:53.909  1033  1941 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
09-06 16:55:53.913  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 16:55:53.923  6960  6960 D BluetoothPermissionRequest: onReceive
,09-06 16:55:53.925  6960  6960 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 16:55:53.926  6960  6960 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-06 16:55:53.928  6960  6960 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 16:55:53.980  1033  1995 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7074 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-06 16:55:53.995  6979  6979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 16:55:53.999  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:55:54.015  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:55:54.047  7050  7094 W FormManager: Network not available. Please check & try again.
,09-06 16:55:54.053  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 16:55:54.053  6960  6960 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 16:55:54.053  6960  6960 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 16:55:54.053  6960  6960 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 16:55:54.061  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-06 16:55:54.076  7074  7074 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-06 16:55:54.077  7074  7074 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 16:55:54.077  7074  7074 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-06 16:55:54.078  7074  7074 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-06 16:55:54.083  7050  7095 V FormManager: Network unavailable.
09-06 16:55:54.088  6960  6960 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 16:55:54.088  7050  7095 V FormManager: Network unavailable.
09-06 16:55:54.088  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 16:55:54.088  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 16:55:54.089  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 16:55:54.089  6960  6960 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 16:55:54.090  6960  6960 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-06 16:55:54.097  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 16:55:54.098  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 16:55:54.099  7074  7074 D BluetoothAdapterApp: Loading JNI Library
09-06 16:55:54.103  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 16:55:54.107  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 16:55:54.114  6979  6979 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-06 16:55:54.114  6979  6979 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 16:55:54.114  6979  6979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:55:54.118  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 16:55:54.118  4759  7098 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 16:55:54.123  4759  7099 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 16:55:54.123  4759  7099 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 16:55:54.128  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:55:54.133  7050  7101 W FormManager: Network not available. Please check & try again.
,09-06 16:55:54.139  7050  7102 V FormManager: Network unavailable.
09-06 16:55:54.142  7050  7102 V FormManager: Network unavailable.
09-06 16:55:54.145  7074  7074 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@14a8567d Instance Count = 1
,09-06 16:55:54.147  1033  1740 I ActivityManager: Killing 6060:com.android.contacts/u0a19 (adj 15): empty #17
09-06 16:55:54.148  7009  7009 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-06 16:55:54.149  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-06 16:55:54.150  7009  7009 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-06 16:55:54.187  7009  7009 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 16:55:54.187  7009  7009 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 16:55:54.196  7009  7009 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-06 16:55:54.197  7009  7009 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-06 16:55:54.197  7009  7009 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-06 16:55:54.197  7009  7009 V SoundPool: doLoad: loading sample sampleID=1
09-06 16:55:54.197  7009  7009 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-06 16:55:54.200  7009  7105 V SoundPool: Start decode
,09-06 16:55:54.200  7009  7105 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-06 16:55:54.201   323  1383 V MediaPlayerService: decode(23, 10857164, 17813)
09-06 16:55:54.201   323  1383 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-06 16:55:54.201   323  1383 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-06 16:55:54.201   323  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-06 16:55:54.201   323  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-06 16:55:54.201   323  1383 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-06 16:55:54.201   323  1383 V MediaPlayerService: player type = 3
09-06 16:55:54.201   323  1383 V AwesomePlayer: AwesomePlayer create()
09-06 16:55:54.202   323  1383 V AwesomePlayer: reset_l() 
09-06 16:55:54.202   323  1383 V AwesomePlayer: cancelPlayerEvents
09-06 16:55:54.202   323  1383 V AwesomePlayer: setAudioSink() 
09-06 16:55:54.202   323  1383 V AwesomePlayer: reset_l() 
09-06 16:55:54.202   323  1383 V AudioCache: notify(0xb1023380, 8, 0, 0)
09-06 16:55:54.202   323  1383 V AudioCache: ignored
09-06 16:55:54.202   323  1383 V AwesomePlayer: cancelPlayerEvents
09-06 16:55:54.202   323  1383 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-06 16:55:54.202   323  1383 V AwesomePlayer: setDataSource_l dataSource
09-06 16:55:54.202   323  1383 V LGParserOSAL: SniffLGParser start
09-06 16:55:54.202   323  1383 V LGParserOSAL: MainType:5, SubType=0
09-06 16:55:54.202   323  1383 V LGParserOSAL: #### check Mime : application/ogg
09-06 16:55:54.202   323  1383 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-06 16:55:54.202   323  1383 E MediaExtractor: Use LGExtractor :application/ogg 
09-06 16:55:54.205  1033  1574 W libprocessgroup: failed to open /acct/uid_10019/pid_6060/cgroup.procs: No such file or directory
09-06 16:55:54.205  7074  7074 D BluetoothAdapterApp: onCreate
09-06 16:55:54.212  7009  7009 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-06 16:55:54.212  6868  6868 D UEI.SmartControl: QS Service created
,09-06 16:55:54.225  7009  7009 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 16:55:54.226  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 16:55:54.228  6868  6868 I UEI.SmartControl: Service initServices...
09-06 16:55:54.229  6868  6868 D UEI.SmartControl: QS start get config
09-06 16:55:54.234  7074  7074 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-06 16:55:54.235  7074  7074 D ProfileConfigQcom: Adding HeadsetService
09-06 16:55:54.235  7074  7074 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-06 16:55:54.235  7074  7074 D ProfileConfigQcom: Adding A2dpService
09-06 16:55:54.235  7074  7074 D ProfileConfigQcom: [BTUI] HidService is supported
09-06 16:55:54.236  7074  7074 D ProfileConfigQcom: Adding HidService
09-06 16:55:54.236  7074  7074 D ProfileConfigQcom: [BTUI] HealthService is supported
09-06 16:55:54.236  7074  7074 D ProfileConfigQcom: Adding HealthService
09-06 16:55:54.236  7074  7074 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-06 16:55:54.237  7074  7074 D ProfileConfigQcom: [BTUI] PanService is supported
09-06 16:55:54.237  7074  7074 D ProfileConfigQcom: Adding PanService
09-06 16:55:54.238  7074  7074 D ProfileConfigQcom: [BTUI] GattService is supported
09-06 16:55:54.238  7074  7074 D ProfileConfigQcom: Adding GattService
09-06 16:55:54.238  7074  7074 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-06 16:55:54.238  7074  7074 D ProfileConfigQcom: Adding BluetoothMapService
09-06 16:55:54.239  7074  7074 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-06 16:55:54.241  7074  7074 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-06 16:55:54.248  6960  6960 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-06 16:55:54.251  7074  7074 V LGMDMManagerInternal: Create singleton instance
09-06 16:55:54.252   323  1383 V LGParserOSAL: supported mime: application/ogg
09-06 16:55:54.253   323  1383 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-06 16:55:54.253   323  1383 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-06 16:55:54.253   323  1383 V AwesomePlayer: mBitrate = -1 bits/sec
09-06 16:55:54.253   323  1383 V AwesomePlayer: AudioTrack Setting
09-06 16:55:54.253   323  1383 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-06 16:55:54.253   323  1383 V AwesomePlayer: setAudioSource() 
09-06 16:55:54.253   323  1383 V MediaPlayerService: prepare
09-06 16:55:54.253   323  1383 V AwesomePlayer: prepareAsync_l() 
09-06 16:55:54.253   323  1383 V MediaPlayerService: wait for prepare
09-06 16:55:54.253   323  7107 V AwesomePlayer: onPrepareAsyncEvent() 
09-06 16:55:54.253   323  7107 V AwesomePlayer: initAudioDecoder() 
09-06 16:55:54.253   323  7107 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 16:55:54.253   323  7107 V AudioSystem: isOffloadSupported()
09-06 16:55:54.253   323  7107 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 16:55:54.253   323  7107 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 16:55:54.253   323  7107 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 16:55:54.253   323  7107 V AwesomePlayer: getUseOffload() = 0 
09-06 16:55:54.253   323  7107 V OMXCodec: OMXCodec::Create
09-06 16:55:54.253   323  7107 V OMXCodec: findMatchingCodecs()
09-06 16:55:54.253   323  7107 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-06 16:55:54.253   323  7107 V OMXCodec: matchingCodecs.size()=1
09-06 16:55:54.253   323  7107 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-06 16:55:54.255   323  7107 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-06 16:55:54.255   323  7107 V LGCodecAdapter: LG Codec Adapter start
09-06 16:55:54.255   323  7107 V OMXCodec: OMXCodec Createtor
09-06 16:55:54.255   323  7107 V OMXCodec: setComponentRole
09-06 16:55:54.255   323  7107 V OMXCodec: configureCodec protected=0
09-06 16:55:54.255   323  7107 V LGCodecAdapter: called getLGCodecSpecificData
09-06 16:55:54.255   323  7107 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-06 16:55:54.255   323  7107 V LGCodecOSAL: Called LGconfigureCodecMETA
09-06 16:55:54.256   323  7107 V LGCodecOSAL: Called LGconfigureCodecMSG
09-06 16:55:54.256   323  7107 V LGCodecOSAL: Not support LGCodec
09-06 16:55:54.256   323  7107 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 16:55:54.256   323  7107 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-06 16:55:54.256   323  7107 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-06 16:55:54.256   323  7107 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-06 16:55:54.256   323  7107 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 16:55:54.256   323  7107 V AudioSystem: isOffloadSupported()
09-06 16:55:54.256   323  7107 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 16:55:54.256   323  7107 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 16:55:54.256   323  7107 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-06 16:55:54.256   323  7107 V OMXCodec: ,init()
09-06 16:55:54.256   323  7107 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-06 16:55:54.256   323  7107 V OMXCodec: allocateBuffers
09-06 16:55:54.256   323  7107 V OMXCodec: allocateBuffersOnPort portIndex=0
09-06 16:55:54.256   323  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-06 16:55:54.256   323  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
09-06 16:55:54.256   323  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on input port
09-06 16:55:54.256   323  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on input port
09-06 16:55:54.256   323  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on input port
09-06 16:55:54.256   323  7107 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 16:55:54.256   323  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 16:55:54.257   323  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fbf0 on output port
09-06 16:55:54.257   323  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on output port
09-06 16:55:54.257   323  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1546060 on output port
09-06 16:55:54.257   323  7107 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1546150 on output port
09-06 16:55:54.257   323  7107 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 16:55:54.257   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 16:55:54.257   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 16:55:54.257   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-06 16:55:54.257   323  7107 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 16:55:54.257   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-06 16:55:54.257   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-06 16:55:54.257   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-06 16:55:54.257   323  7107 V OMXCodec: init() mAsyncCompletion wait free! 
09-06 16:55:54.257   323  7107 V AwesomePlayer: finishAsyncPrepare_l() 
09-06 16:55:54.257   323  7107 V AudioCache: notify(0xb1023380, 5, 0, 0)
09-06 16:55:54.257   323  7107 V AudioCache: ignored
09-06 16:55:54.257   323  7107 V AudioCache: notify(0xb1023380, 1, 0, 0)
09-06 16:55:54.257   323  7107 V AudioCache: prepared
09-06 16:55:54.257   323  1383 V AudioCache: wait - success
09-06 16:55:54.257   323  1383 V MediaPlayerService: start
09-06 16:55:54.257   323  1383 V AwesomePlayer: play_l() 
09-06 16:55:54.257   323  1383 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-06 16:55:54.257   323  1383 V AwesomePlayer: createAudioPlayer_l
09-06 16:55:54.257   323  1383 V AwesomePlayer: seekAudioIfNecessary_l() 
09-06 16:55:54.257   323  1383 V AwesomePlayer: startAudioPlayer_l() 
09-06 16:55:54.257   323  1383 D AudioPlayer: start of Playback, useOffload 0
09-06 16:55:54.257   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 16:55:54.257   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 16:55:54.260   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-06 16:55:54.260   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-06 16:55:54.260   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-06 16:55:54.260   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-06 16:55:54.260   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-06 16:55:54.260   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 16:55:54.260   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048816
09-06 16:55:54.260   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975584
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975096928
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975097168
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-06 16:55:54.261   323  7109 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1546060 on output port
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on output port
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fbf0 on output port
09-06 16:55:54.261   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on output port
09-06 16:55:54.262   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-06 16:55:54.262   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-06 16:55:54.264  7009  7009 V LGMDMManager: Create singleton instance
09-06 16:55:54.268   323  1383 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-06 16:55:54.269   323  1383 V AudioCache: notify(0xb1023380, 6, 0, 0)
09-06 16:55:54.269   323  1383 V AudioCache: ignored
09-06 16:55:54.270   323  1383 V MediaPlayerService: wait for playback complete
09-06 16:55:54.270   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.270   323  7110 V AudioCache: memcpy(0xaf006000, 0xb1011000, 4096)
09-06 16:55:54.273   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.273   323  7110 V AudioCache: memcpy(0xaf007000, 0xb1011000, 4096)
09-06 16:55:54.274   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.274   323  7110 V AudioCache: memcpy(0xaf008000, 0xb1011000, 4096)
09-06 16:55:54.275   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.275   323  7110 V AudioCache: memcpy(0xaf009000, 0xb1011000, 4096)
09-06 16:55:54.276   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.276   323  7110 V AudioCache: memcpy(0xaf00a000, 0xb1011000, 4096)
09-06 16:55:54.276   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.276   323  7110 V AudioCache: memcpy(0xaf00b000, 0xb1011000, 4096)
09-06 16:55:54.277   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.277   323  7110 V AudioCache: memcpy(0xaf00c000, 0xb1011000, 4096)
09-06 16:55:54.278   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.278   323  7110 V AudioCache: memcpy(0xaf00d000, 0xb1011000, 4096)
09-06 16:55:54.279   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.279   323  7110 V AudioCache: memcpy(0xaf00e000, 0xb1011000, 4096)
09-06 16:55:54.280   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.280   323  7110 V AudioCache: memcpy(0xaf00f000, 0xb1011000, 4096)
09-06 16:55:54.281   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.281   323  7110 V AudioCache: memcpy(0xaf010000, 0xb1011000, 4096)
09-06 16:55:54.281   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.281   323  7110 V AudioCache: memcpy(0xaf011000, 0xb1011000, 4096)
09-06 16:55:54.282   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.282   323  7110 V AudioCache: memcpy(0xaf012000, 0xb1011000, 4096)
09-06 16:55:54.283   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.283   323  7110 V AudioCache: memcpy(0xaf013000, 0xb1011000, 4096)
09-06 16:55:54.284   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.284   323  7110 V AudioCache: memcpy(0xaf014000, 0xb1011000, 4096)
09-06 16:55:54.284   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.284   323  7110 V AudioCache: memcpy(0xaf015000, 0xb1011000, 4096)
09-06 16:55:54.285   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.285   323  7110 V AudioCache: memcpy(0xaf016000, 0xb1011000, 4096)
09-06 16:55:54.286   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.286   323  7110 V AudioCache: memcpy(0xaf017000, 0xb1011000, 4096)
09-06 16:55:54.287   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.287   323  7110 V AudioCache: memcpy(0xaf018000, 0xb1011000, 4096)
09-06 16:55:54.288   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.288   323  7110 V AudioCache: memcpy(0xaf019000, 0xb1011000, 4096)
09-06 16:55:54.288   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.288   323  7110 V AudioCache: memcpy(0xaf01a000, 0xb1011000, 4096)
09-06 16:55:54.288   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.288   323  7110 V AudioCache: memcpy(0xaf01b000, 0xb1011000, 4096)
09-06 16:55:54.288   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.288   323  7110 V AudioCache: memcpy(0xaf01c000, 0xb1011000, 4096)
,09-06 16:55:54.289   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.289   323  7110 V AudioCache: memcpy(0xaf01d000, 0xb1011000, 4096)
09-06 16:55:54.289   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.289   323  7110 V AudioCache: memcpy(0xaf01e000, 0xb1011000, 4096)
09-06 16:55:54.294   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.294   323  7110 V AudioCache: memcpy(0xaf01f000, 0xb1011000, 4096)
09-06 16:55:54.294   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.295   323  7110 V AudioCache: memcpy(0xaf020000, 0xb1011000, 4096)
09-06 16:55:54.295   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.295   323  7110 V AudioCache: memcpy(0xaf021000, 0xb1011000, 4096)
09-06 16:55:54.295   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.295   323  7110 V AudioCache: memcpy(0xaf022000, 0xb1011000, 4096)
09-06 16:55:54.295   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.295   323  7110 V AudioCache: memcpy(0xaf023000, 0xb1011000, 4096)
09-06 16:55:54.296   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.296   323  7110 V AudioCache: memcpy(0xaf024000, 0xb1011000, 4096)
09-06 16:55:54.296   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.296   323  7110 V AudioCache: memcpy(0xaf025000, 0xb1011000, 4096)
09-06 16:55:54.297   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.297   323  7110 V AudioCache: memcpy(0xaf026000, 0xb1011000, 4096)
09-06 16:55:54.297   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.297   323  7110 V AudioCache: memcpy(0xaf027000, 0xb1011000, 4096)
09-06 16:55:54.298   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.298   323  7110 V AudioCache: memcpy(0xaf028000, 0xb1011000, 4096)
09-06 16:55:54.298   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.298   323  7110 V AudioCache: memcpy(0xaf029000, 0xb1011000, 4096)
09-06 16:55:54.299   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.299   323  7110 V AudioCache: memcpy(0xaf02a000, 0xb1011000, 4096)
09-06 16:55:54.300   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.300   323  7110 V AudioCache: memcpy(0xaf02b000, 0xb1011000, 4096)
09-06 16:55:54.300   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.300   323  7110 V AudioCache: memcpy(0xaf02c000, 0xb1011000, 4096)
09-06 16:55:54.301   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.301   323  7110 V AudioCache: memcpy(0xaf02d000, 0xb1011000, 4096)
09-06 16:55:54.302   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.302   323  7110 V AudioCache: memcpy(0xaf02e000, 0xb1011000, 4096)
09-06 16:55:54.302   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.302   323  7110 V AudioCache: memcpy(0xaf02f000, 0xb1011000, 4096)
09-06 16:55:54.303   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.303   323  7110 V AudioCache: memcpy(0xaf030000, 0xb1011000, 4096)
09-06 16:55:54.304   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.304   323  7110 V AudioCache: memcpy(0xaf031000, 0xb1011000, 4096)
09-06 16:55:54.304   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.304   323  7110 V AudioCache: memcpy(0xaf032000, 0xb1011000, 4096)
09-06 16:55:54.305   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.305   323  7110 V AudioCache: memcpy(0xaf033000, 0xb1011000, 4096)
09-06 16:55:54.306   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.306   323  7110 V AudioCache: memcpy(0xaf034000, 0xb1011000, 4096)
09-06 16:55:54.306   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.306   323  7110 V AudioCache: memcpy(0xaf035000, 0xb1011000, 4096)
09-06 16:55:54.307   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.307   323  7110 V AudioCache: memcpy(0xaf036000, 0xb1011000, 4096)
09-06 16:55:54.308   323  7110 V AudioCache: write(0xb1011000, 4096)
09-06 16:55:54.308   323  7110 V AudioCache: memcpy(0xaf037000, 0xb1011000, 4096)
09-06 16:55:54.308   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-06 16:55:54.308   323  7110 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 16:55:54.308   323  7110 V AwesomePlayer: postAudioEOS() 
09-06 16:55:54.308   323  7110 V AudioCache: write(0xb1011000, 280)
09-06 16:55:54.308   323  7110 V AudioCache: memcpy(0xaf038000, 0xb1011000, 280)
09-06 16:55:54.310   323  7107 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-06 16:55:54.310   323  7107 V AwesomePlayer: onStreamDone
09-06 16:55:54.310   323  7107 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-06 16:55:54.310   323  7107 V AudioCache: notify(0xb1023380, 2, 0, 0)
09-06 16:55:54.310   323  7107 V AudioCache: playback complete
09-06 16:55:54.310   323  7107 V AwesomePlayer: pause_l() 
09-06 16:55:54.310   323  7107 V AudioCache: notify(0xb1023380, 7, 0, 0)
09-06 16:55:54.310   323  7107 V AudioCache: ignored
09-06 16:55:54.310   323  7107 V AwesomePlayer: cancelPlayerEvents
09-06 16:55:54.310   323  1383 V AudioCache: wait - success
09-06 16:55:54.310   323  1383 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-06 16:55:54.310   323  7107 D AudioPlayer: Pause Playback at 1068125
09-06 16:55:54.311   323  1383 V AwesomePlayer: reset_l() 
09-06 16:55:54.311   323  1383 V AudioCache: notify(0xb1023380, 8, 0, 0)
09-06 16:55:54.311   323  1383 V AudioCache: ignored
09-06 16:55:54.311   323  1383 V AwesomePlayer: cancelPlayerEvents
09-06 16:55:54.311   323  1383 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-06 16:55:54.311   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-06 16:55:54.311   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-06 16:55:54.311   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-06 16:55:54.311   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 16:55:54.317  1033  1376 V AlarmManager: RTC_WAKEUP set : Alarm{3e4af1b1 type 0 when 1473173754315 com.android.vending} when 1473173754315
09-06 16:55:54.318   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 16:55:54.318   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 16:55:54.318   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-06 16:55:54.318   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 0
09-06 16:55:54.318   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-06 16:55:54.318   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 0
09-06 16:55:54.318   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 0
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 1
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fbf0 on port 1
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 1
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1546060 on port 1
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-06 16:55:54.319   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 16:55:54.319   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-06 16:55:54.319   323  7109 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-06 16:55:54.319   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 16:55:54.319   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-06 16:55:54.320   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-06 16:55:54.320   323  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-06 16:55:54.321   323  1383 D AudioPlayer: AudioPlayer releasing audio source
09-06 16:55:54.321   323  1383 D AudioPlayer: AudioPlayer done releasing audio source
09-06 16:55:54.321   323  1383 V AwesomePlayer: reset_l() 
09-06 16:55:54.321   323  1383 V AwesomePlayer: cancelPlayerEvents
09-06 16:55:54.321   323  1383 V AwesomePlayer: ~AwesomePlayer call
09-06 16:55:54.321   323  1383 V AwesomePlayer: reset_l() 
09-06 16:55:54.321   323  1383 V AwesomePlayer: cancelPlayerEvents
09-06 16:55:54.321  7009  7105 V SoundPool: close(31)
09-06 16:55:54.321  7009  7105 V SoundPool: pointer = 0xa0006000, size = 205080, sampleRate = 48000, numChannels = 2
,09-06 16:55:54.354  7074  7074 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:54.357  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 16:55:54.357  7074  7074 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 16:55:54.357  7074  7074 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 16:55:54.357  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-06 16:55:54.358  7074  7074 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 16:55:54.359  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7380
09-06 16:55:54.359  7074  7074 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:54.359  7074  7074 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-06 16:55:54.367  7026  7026 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-06 16:55:54.375  1033  1995 V SIM_STK : Menu title from STK is T-Mobile
09-06 16:55:54.386  4945  7112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,09-06 16:55:54.505  6644  6644 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-06 16:55:54.650  6868  6868 I UEI.SmartControl: Supports setup maps: true
,09-06 16:55:54.656  6868  6868 D UEI.SmartControl: QS start statue = true Error code = 0
,09-06 16:55:54.656  6868  6868 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 16:55:54.656  6868  6868 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 16:55:54.657  6868  6868 I UEI.SmartControl: ### init IR Blaster...
09-06 16:55:54.660  6868  6868 D serial_port: Configuring serial port
09-06 16:55:54.660  6868  6868 E UEI.SmartControl: UEIBLaster setting for 616
09-06 16:55:54.660  6868  6868 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 16:55:54.660  6868  6868 I UEI.SmartControl: configuring settings for MAXQ616
09-06 16:55:54.660  6868  6868 I UEI.SmartControl: Get version...
09-06 16:55:54.678  6868  7121 D UEI.SmartControl: serial port data available: 21
,09-06 16:55:54.706  6868  6868 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-06 16:55:54.706  6868  6868 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 16:55:54.706  6868  6868 I UEI.SmartControl: QS saving settings...
09-06 16:55:54.708  6868  6868 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 16:55:54.729  6868  7121 D UEI.SmartControl: serial port data available: 4
,09-06 16:55:54.762  6868  7127 I UEI.SmartControl: Device manager: loading config....
,09-06 16:55:54.765  6868  6868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-06 16:55:54.768  6868  7127 D UEI.SmartControl: ----------- loading internal config...
09-06 16:55:54.769  6868  6868 E UEI.SmartControl: Services init done
,09-06 16:55:54.769  6868  6868 D UEI.SmartControl: QS Service init finished
09-06 16:55:54.771  6868  6868 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 16:55:54.771  6868  6868 D UEI.SmartControl: QS Service version code: 201091
09-06 16:55:54.772  6868  6868 D UEI.SmartControl: Service requested: Control
09-06 16:55:54.783  6868  7127 E UEI.SmartControl: Loading SETTINGS...
,09-06 16:55:54.796  6868  6868 D UEI.SmartControl: Request IControl service: devices are loaded...
09-06 16:55:54.801  6868  6868 D UEI.SmartControl: Internal service binding...
,09-06 16:55:54.803  7009  7009 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-06 16:55:54.805  6868  6884 I UEI.SmartControl: ------ IControl API: 11
09-06 16:55:54.805  6868  6884 D UEI.SmartControl: File observer start...
09-06 16:55:54.806  6868  6884 E UEI.SmartControl: IR Port is disabled: false
09-06 16:55:54.807  6868  6884 D UEI.SmartControl: Starting file observer...
09-06 16:55:54.809  6868  7127 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 16:55:54.809  6868  6884 I UEI.SmartControl: Registering callback...
09-06 16:55:54.810  6868  6883 I UEI.SmartControl: ------ IControl API: 19
09-06 16:55:54.812  6868  6883 I UEI.SmartControl: Registering Services Ready callback...
,09-06 16:55:54.822  6868  7126 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 16:55:54.824  7009  7025 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,09-06 16:55:54.825  7009  7103 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-06 16:55:54.825  7009  7103 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-06 16:55:54.825  7009  7009 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-06 16:55:54.826  7009  7009 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-06 16:55:54.826  6868  6883 I UEI.SmartControl: ------ IControl API: 8
09-06 16:55:54.826  6868  7126 D UEI.SmartControl: -----service ready thread exits
09-06 16:55:54.828  7009  7009 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-06 16:55:54.829  7009  7009 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-06 16:55:54.829  7009  7009 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-06 16:55:54.829  7009  7009 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-06 16:55:54.830  7009  7009 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-06 16:55:54.831  7009  7009 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-06 16:55:54.832  7009  7009 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-06 16:55:54.838  7009  7009 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-06 16:55:54.839  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 16:55:54.840  7009  7009 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 16:55:54.840  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 16:55:54.841  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 16:55:54.842  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-06 16:55:54.843  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-06 16:55:54.844  7009  7009 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473173754844]
09-06 16:55:54.848  7009  7009 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-06 16:55:54.851  1033  1905 I ActivityManager: Killing 6624:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-06 16:55:54.868  7009  7132 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-06 16:55:54.888  1033  1905 I ActivityManager: Killing 6590:com.lge.email/u0a23 (adj 15): empty #18
,09-06 16:55:54.923  1033  1995 W libprocessgroup: failed to open /acct/uid_10023/pid_6590/cgroup.procs: No such file or directory
,09-06 16:55:54.925  7009  7009 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-06 16:55:54.926  7009  7009 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 16:55:54.927  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-06 16:55:54.927  1033  1977 W libprocessgroup: failed to open /acct/uid_10027/pid_6624/cgroup.procs: No such file or directory
09-06 16:55:54.927  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-06 16:55:54.929  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-06 16:55:54.930  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-06 16:55:54.932  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-06 16:55:54.944  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-06 16:55:55.629  1033  1049 D WifiServiceImplEx: setWifiEnabled: true pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 16:55:55.630  1033  1049 D WifiService: setWifiEnabled: true pid=6729, uid=10118
09-06 16:55:55.631  1033  1049 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 16:55:55.661  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-06 16:55:55.661  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-06 16:55:55.661  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,09-06 16:55:55.663  1033  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-06 16:55:55.663  1033  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-06 16:55:55.665  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-06 16:55:55.665  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 16:55:55.665  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,09-06 16:55:55.665  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 16:55:55.666  1033  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-06 16:55:55.666  1033  1537 E WifiHW  : unknown target_country: EU , set to default
,09-06 16:55:55.666  1033  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-06 16:55:55.666  1033  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-06 16:55:55.666  1033  1537 I WifiUtil: gEnableBmps=1
09-06 16:55:55.714  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:55:55.735  1033  1095 D Tethering: MasterInitialState.processMessage what=3
09-06 16:55:55.740  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:55.747  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:55.754  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:55.754  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:55.759  1033  1095 D Tethering: MasterInitialState.processMessage what=3
,09-06 16:55:55.767  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:55.769  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:55.771  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-06 16:55:55.776  6457  6497 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 16:55:55.778  5836  5836 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 16:55:55.799  5836  5836 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-06 16:55:55.824  2188  2188 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:55:55.887  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:55:55.916  1033  1740 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7151 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-06 16:55:55.919  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:55.919  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:55.938  2146  2146 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19993
,09-06 16:55:56.034  7151  7151 I AppUp4:AppBoxCP: onCreate
,09-06 16:55:56.035  7151  7151 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-06 16:55:56.045  7151  7151 I AppUp4:DB:  setFingerPrint start
09-06 16:55:56.046  7151  7151 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-06 16:55:56.054  7151  7151 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-06 16:55:56.055  7151  7151 I AppUp4:DB:  SDK version = 21
09-06 16:55:56.055  7151  7151 I AppUp4:DB:  beforefinger == newfinger no write in DB
,09-06 16:55:56.057  7151  7151 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-06 16:55:56.059  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 16:55:56.059  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:56.061  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 16:55:56.062  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 16:55:56.069  7151  7151 I AppUp4:CustModeStarterReceiver: onReceive
,09-06 16:55:56.113  7151  7151 D LgDataFeature: LgDataFeature() Constructor: none,
09-06 16:55:56.113  7151  7151 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 16:55:56.122  7151  7151 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@29abb71f
09-06 16:55:56.122  7151  7151 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 16:55:56.122  7151  7151 D AppUp4:CustFacade: isPhone : true
09-06 16:55:56.123  7151  7151 D AppUp4:CustModeStarterReceiver: begin check event
09-06 16:55:56.124  7151  7151 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-06 16:55:56.124  7151  7151 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-06 16:55:56.125  7151  7170 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-06 16:55:56.125  7151  7170 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-06 16:55:56.126  7151  7170 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,09-06 16:55:56.134  1033  1574 I ActivityManager: Killing 6683:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-06 16:55:56.214  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:55:56.218  1033  1376 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1f6bf7ed type 2 when 121553 com.google.android.gms} when 121553
09-06 16:55:56.218  1033  1049 W libprocessgroup: failed to open /acct/uid_10061/pid_6683/cgroup.procs: No such file or directory
09-06 16:55:56.222  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 16:55:56.226  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 16:55:56.231  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 16:55:56.249  4759  7181 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 16:55:56.254  4759  7183 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:56.255  4759  7183 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 16:55:56.286  1033  1740 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7184 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-06 16:55:56.380  7184  7184 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 16:55:56.381  7184  7184 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 16:55:56.383  7184  7184 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 16:55:56.383  7184  7184 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 16:55:56.405  1033  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-06 16:55:56.410  1033  1095 D Tethering: InitialState.processMessage what=4
09-06 16:55:56.411  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 16:55:56.424   318   893 D SoftapController: Softap fwReload - Ok
,09-06 16:55:56.424  1033  1537 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (751ms)
09-06 16:55:56.428   318   893 D CommandListener: Setting iface cfg
09-06 16:55:56.429   318   893 D CommandListener: Trying to bring down wlan0
09-06 16:55:56.429   318   893 D CommandListener: Clearing all IP addresses on wlan0
09-06 16:55:56.431  1033  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-06 16:55:56.433  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 16:55:56.433  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
09-06 16:55:56.433  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 16:55:56.434  1033  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-06 16:55:56.434  1033  1537 D WifiMonitor: connecting to supplicant
09-06 16:55:56.434  1033  1537 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
09-06 16:55:56.423  7202  7202 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:55:56.437  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-06 16:55:56.423  7202  7202 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 16:55:56.440  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:56.442  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-06 16:55:56.443  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:56.444  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:56.463  7202  7202 I wpa_supplicant: Successfully initialized wpa_supplicant
09-06 16:55:56.512  7202  7202 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 16:55:56.512  7202  7202 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-06 16:55:56.513  7184  7184 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-06 16:55:56.527  7184  7184 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-06 16:55:56.567  7184  7184 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-06 16:55:56.585  7202  7202 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 16:55:56.593  7184  7184 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 16:55:56.593  7184  7184 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 16:55:56.639  7202  7202 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-06 16:55:56.657  7202  7202 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-06 16:55:56.657  7202  7202 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-06 16:55:56.682  7184  7184 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-06 16:55:56.708  3175  3175 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 16:55:56.708  3175  3175 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:56.708  3175  3175 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-06 16:55:56.750  1033  2014 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7217 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-06 16:55:56.754  7050  7214 W FormManager: Network not available. Please check & try again.
09-06 16:55:56.759  7184  7184 I HubEmail: JNI_OnLoad()
,09-06 16:55:56.759  7184  7184 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 16:55:56.759  7184  7184 I HubEmail: registerNatives()
09-06 16:55:56.759  7184  7184 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 16:55:56.759  7184  7184 I HubEmail: registerNativeMethods()
09-06 16:55:56.759  7184  7184 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 16:55:56.759  7184  7184 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-06 16:55:56.764  7050  7216 V FormManager: Network unavailable.
09-06 16:55:56.766  7050  7216 V FormManager: Network unavailable.
,09-06 16:55:56.776  1033  1740 I ActivityManager: Killing 6807:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-06 16:55:56.838  7184  7230 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 16:55:56.851  1033  1049 W libprocessgroup: failed to open /acct/uid_10080/pid_6807/cgroup.procs: No such file or directory
,09-06 16:55:56.950  7217  7217 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 16:55:56.951  7217  7217 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 16:55:56.955  7217  7217 D PhoneMonitor: Register our PhoneStateListener
09-06 16:55:56.981  7217  7217 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-06 16:55:56.985  7217  7217 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-06 16:55:57.017  7217  7217 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-06 16:55:57.020  7217  7217 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-06 16:55:57.022  7217  7217 D TelephonyAutoProfiling: [parse] Load xml
09-06 16:55:57.028  7217  7217 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-06 16:55:57.029  7217  7217 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,09-06 16:55:57.029  7217  7217 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-06 16:55:57.029  7217  7217 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-06 16:55:57.029  7217  7217 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-06 16:55:57.029  7217  7217 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-06 16:55:57.029  7217  7217 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-06 16:55:57.029  7217  7217 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-06 16:55:57.029  7217  7217 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-06 16:55:57.029  7217  7217 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-06 16:55:57.029  7217  7217 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-06 16:55:57.029  7217  7217 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-06 16:55:57.029  7217  7217 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-06 16:55:57.029  7217  7217 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-06 16:55:57.030  7217  7217 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-06 16:55:57.030  7217  7217 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-06 16:55:57.030  7217  7217 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-06 16:55:57.042  7217  7217 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-06 16:55:57.059  1033  2071 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7240 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 16:55:57.060  1033  2071 I ActivityManager: Killing 6176:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-06 16:55:57.109  1033  1995 W libprocessgroup: failed to open /acct/uid_10097/pid_6176/cgroup.procs: No such file or directory
,09-06 16:55:57.352  7202  7202 E wpa_supplicant: USIM:  scard_init function
09-06 16:55:57.353  7202  7202 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-06 16:55:57.360  1033  1713 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7261 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-06 16:55:57.370  1033  1713 I ActivityManager: Killing 6831:com.lge.eula/1000 (adj 15): empty #17
,09-06 16:55:57.437  1033  1941 W libprocessgroup: failed to open /acct/uid_1000/pid_6831/cgroup.procs: No such file or directory
09-06 16:55:57.438  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-06 16:55:57.441  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,09-06 16:55:57.442  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-06 16:55:57.442  1033  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-06 16:55:57.444  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:55:57.445  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:55:57.446  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:55:57.446  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:55:57.447  1033  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-06 16:55:57.447  1033  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-06 16:55:57.448  1033  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-06 16:55:57.449  1033  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-06 16:55:57.449  1033  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-06 16:55:57.449  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 16:55:57.449  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
09-06 16:55:57.449  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 16:55:57.450  1033  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
09-06 16:55:57.452  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:57.452  1033  1537 D WifiNative-wlan0: SET update_config 1: returned true
09-06 16:55:57.452  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:57.452  1033  1537 D WifiConfigStore: Loading config and enabling all networks 
09-06 16:55:57.452  1033  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-06 16:55:57.452  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:57.452  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:57.452  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 16:55:57.453  1942  1942 D WfdService: Waiting for WifiP2p enabling
09-06 16:55:57.453  1033  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
,09-06 16:55:57.457  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:57.462  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-06 16:55:57.463  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-06 16:55:57.463  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:57.463  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:57.463  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:57.463  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:57.463  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:57.463  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:57.463  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:57.463  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:57.463  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:55:57.463  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:57.463  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:55:57.464  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:57.464  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:57.464  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:57.464  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:57.464  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:57.464  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:57.464  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:57.464  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:57.464  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:55:57.464  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:57.464  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:55:57.472  1033  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-06 16:55:57.481  7202  7202 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-06 16:55:57.484  1033  7278 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-06 16:55:57.485  1033  7278 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-06 16:55:57.485  1033  7278 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-06 16:55:57.485  1033  7278 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-06 16:55:57.485  1033  7278 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 16:55:57.485  1033  7278 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-06 16:55:57.491  7202  7202 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 16:55:57.491  7202  7202 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 16:55:57.492  1033  7278 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 16:55:57.492  1033  7278 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 16:55:57.493  1033  7278 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-06 16:55:57.493  1033  7278 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 16:55:57.493  1033  7278 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 16:55:57.493  1033  7278 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-06 16:55:57.493  1033  7278 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 16:55:57.493  1033  7278 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 16:55:57.493  1033  7278 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 16:55:57.493  1033  7278 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 16:55:57.495  1033  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-06 16:55:57.503  1033  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-06 16:55:57.503  1033  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-06 16:55:57.504  1033  1537 D WifiStateMachine: enableVerboseLogging : level 2
09-06 16:55:57.504  1033  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-06 16:55:57.504  1033  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-06 16:55:57.504  1033  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-06 16:55:57.506  1033  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-06 16:55:57.506  1033  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-06 16:55:57.508  1033  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-06 16:55:57.508  1033  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-06 16:55:57.509  1033  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-06 16:55:57.509  1033  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-06 16:55:57.509  1033  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-06 16:55:57.509  1033  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-06 16:55:57.510  1033  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-06 16:55:57.510  1033  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-06 16:55:57.510  1033  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-06 16:55:57.542  1033  1741 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7285 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 16:55:57.543  1033  1741 I ActivityManager: Killing 6848:com.lge.bnr/1000 (adj 15): empty #17
,09-06 16:55:57.589  1033  1537 D WifiStateMachine: Setting OUI to DA-A1-19
,09-06 16:55:57.590  1033  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-06 16:55:57.590  1942  1942 D WfdsService: Supplicant Connection state is changed : true
09-06 16:55:57.591  1942  2350 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-06 16:55:57.591  1942  2350 D WfdsService: Set the WFDS Monitor: true
09-06 16:55:57.591  1942  2350 D WfdsMonitor: WfdsMonitorThread create
09-06 16:55:57.591  1942  2350 D WfdsMonitor: WFDS Monitor is created and started
09-06 16:55:57.591  1942  2350 D WfdsService: WiFi: Supplicant connection re-established
09-06 16:55:57.591  1033  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-06 16:55:57.591  1033  1537 D WifiNative-HAL: Setting external_sim to 1
09-06 16:55:57.591  1033  2014 W libprocessgroup: failed to open /acct/uid_1000/pid_6848/cgroup.procs: No such file or directory
09-06 16:55:57.591  1033  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-06 16:55:57.592  1033  1537 D WifiNative-wlan0: SET external_sim 1: returned true
09-06 16:55:57.592  1033  1537 I WifiNative-HAL: startHal
09-06 16:55:57.592  1033  1537 D wifi    : setting scan oui 0x957c5060
09-06 16:55:57.592  1033  1537 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 16:55:57.593  1033  1537 I WifiNative-HAL: startHal
09-06 16:55:57.593  1033  1537 D wifi    : setting scan oui 0x957c5060
09-06 16:55:57.593  1033  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-06 16:55:57.594  1033  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-06 16:55:57.594  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-06 16:55:57.594  7202  7202 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-06 16:55:57.594  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-06 16:55:57.595  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 16:55:57.595  7202  7202 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 16:55:57.595  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 16:55:57.595  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-06 16:55:57.595  1942  7302 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-06 16:55:57.596  7202  7202 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-06 16:55:57.596  1942  7302 E CtrlSupplicant: Succeed to open control connection
09-06 16:55:57.596  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-06 16:55:57.596  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 16:55:57.596  7202  7202 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 16:55:57.596  1942  7302 E CtrlSupplicant: Succeed to open monitor connection
09-06 16:55:57.596  1942  7302 D WfdsMonitor: Supplicant connection established
09-06 16:55:57.597  1942  2350 D WfdsService: Connected to the supplicant for wfds
09-06 16:55:57.597  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 16:55:57.597  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 16:55:57.597  7202  7202 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 16:55:57.598  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 16:55:57.598  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-06 16:55:57.598  7202  7202 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-06 16:55:57.599  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-06 16:55:57.599  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 16:55:57.599  7202  7202 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 16:55:57.600  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 16:55:57.601  1033  1537 E WifiNative: : [122,989,158 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-06 16:55:57.601  1033  1537 D WifiNative-wlan0: do,Boolean: RECONNECT
09-06 16:55:57.602  1033  1537 D WifiNative-wlan0: RECONNECT: returned true
09-06 16:55:57.602  1033  1537 D WifiNative-wlan0: doString: [STATUS]
09-06 16:55:57.603  1033  7278 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 16:55:57.603  1033  7278 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-06 16:55:57.609  1033  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 16:55:57.609  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 16:55:57.610  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
09-06 16:55:57.610  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.613  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 16:55:57.613  1033  1033 D RttService: SCAN_AVAILABLE : 3
09-06 16:55:57.614  1033  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.614  1033  1555 I WifiNative-HAL: startHal
09-06 16:55:57.614  1033  1556 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.614  1033  1555 D wifi    : getting scan capabilities on interface[1] = 0x957c5060
09-06 16:55:57.614  1033  1555 D wifi    : failed to get capabilities : -3
09-06 16:55:57.614  1033  1555 E WifiScanningService: could not get scan capabilities
09-06 16:55:57.615  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-06 16:55:57.615   318   893 D CommandListener: Setting iface cfg
09-06 16:55:57.615   318   893 D CommandListener: Trying to bring up p2p0
09-06 16:55:57.616  1033  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 16:55:57.616  1033  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-06 16:55:57.616  1033  1536 D LGWifiP2pService: P2pEnablingState
09-06 16:55:57.616  1033  1536 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.616  1033  1536 D LGWifiP2pService: P2p socket connection successful
09-06 16:55:57.616  1033  1536 D LGWifiP2pService: P2pEnabledState
09-06 16:55:57.616  1033  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-06 16:55:57.617  1033  1536 D LGWifiP2pService: sending p2p connection changed broadcast
,09-06 16:55:57.620  1033  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-06 16:55:57.621  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-06 16:55:57.621  1942  1942 D WfdsService: WifiP2pState is changed : true
09-06 16:55:57.621  1942  2350 D WfdsService: Receive the WFDS_ENABLE Method
09-06 16:55:57.622  1942  2350 D WfdsService: Set the WFDS Monitor: true
09-06 16:55:57.622  1942  2350 D WfdsService: Connected to the supplicant for wfds
09-06 16:55:57.622  1942  2350 D WfdsJNI : doCommand: WFDS_SET TRUE
09-06 16:55:57.622  7202  7202 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-06 16:55:57.623  1942  2350 D WfdsService: selectPreferredScanChannel [36]
09-06 16:55:57.623  1942  2350 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-06 16:55:57.623  1033  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-06 16:55:57.623  1033  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
09-06 16:55:57.627  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-06 16:55:57.628  1942  1942 D WfdsService: isConnected: false
09-06 16:55:57.628  1033  1536 D WifiNative-p2p0: SET device_name G3: returned true
09-06 16:55:57.628  1033  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-06 16:55:57.628  1033  1536 D LGWifiP2pService: before postfix = G3
09-06 16:55:57.628  1033  1536 D WifiServerServiceExt: postfix byte check : 2
09-06 16:55:57.628  1033  1536 D LGWifiP2pService: after postfix = G3
09-06 16:55:57.628  1033  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-06 16:55:57.630  1033  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-06 16:55:57.630  1033  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-06 16:55:57.630  1033  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-06 16:55:57.631  1033  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-06 16:55:57.631  1033  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-06 16:55:57.635  1033  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
,09-06 16:55:57.638  1033  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-06 16:55:57.638  7202  7202 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-06 16:55:57.639  1033  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-06 16:55:57.639  1033  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-06 16:55:57.639  1033  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-06 16:55:57.639  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-06 16:55:57.640  1033  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-06 16:55:57.640  1033  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-06 16:55:57.640  1033  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-06 16:55:57.640  1033  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-06 16:55:57.641  7202  7202 E wpa_supplicant: disconnect_rssi_lvl: -100
09-06 16:55:57.643  1033  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-06 16:55:57.643  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress
09-06 16:55:57.643  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=123032  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 16:55:57.643  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-06 16:55:57.644  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=123033  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 16:55:57.644  1033  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-06 16:55:57.644  1033  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-06 16:55:57.645  1033  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 23 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123033
09-06 16:55:57.645  1033  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
09-06 16:55:57.645  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-06 16:55:57.645  1033  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 23 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123034
09-06 16:55:57.645  1033  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-06 16:55:57.645  1033  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-06 16:55:57.646  1033  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 23 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123034
,09-06 16:55:57.646  1033  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-06 16:55:57.646  1033  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-06 16:55:57.646  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 23 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123035
09-06 16:55:57.646  1033  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 23 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=123035
09-06 16:55:57.647  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=123036  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 16:55:57.650  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=123038  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 16:55:57.650  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=123039  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 16:55:57.653  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=123040  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 16:55:57.653  1033  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123042
09-06 16:55:57.654  1033  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=123043
09-06 16:55:57.655  1033  1537 D WifiNative-wlan0: doString: [STATUS]
09-06 16:55:57.663  7285  7285 I art     : Almond Protected OAT
,09-06 16:55:57.675  1033  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-06 16:55:57.675  1033  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-06 16:55:57.676  1033  1536 D LGWifiP2pService: InactiveState
09-06 16:55:57.676  1033  1536 D LGWifiP2pService: InactiveState{ when=-30ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.676  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-30ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.676  1033  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-06 16:55:57.676  1033  7278 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 16:55:57.676  1033  7278 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 16:55:57.676  1033  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 16:55:57.677  7202  7202 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-06 16:55:57.679  1033  1537 I WifiServiceExtension: setVHTCapabilityType  : false
09-06 16:55:57.680  7202  7202 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 16:55:57.680  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:57.680  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:55:57.680  7202  7202 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 16:55:57.680  7202  7202 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:55:57.681  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:57.681  7202  7202 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:55:57.682  1033  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-06 16:55:57.682  1033  1536 D LGWifiP2pService: InactiveState{ when=-10ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.682  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.683  1033  1536 D LGWifiP2pService: DefaultState{ when=-10ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.683  1033  1536 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.683  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.683  1033  1536 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.683  1033  1536 D LGWifiP2pService: InactiveState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.683  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.683  1033  1536 D LGWifiP2pService: DefaultState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.684  1942  7302 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 16:55:57.684  1942  7302 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 16:55:57.684  1942  7302 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 16:55:57.685  1033  7278 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 16:55:57.685  1033  7278 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 16:55:57.685  1033  7278 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 16:55:57.685  1033  7278 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 16:55:57.685  1033  7278 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 16:55:57.685  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:57.685  1033  7278 E WifiMonitor: WifiMonitor:p2p0 cnt=32 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:55:57.685  1033  7278 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:55:57.685  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:57.685  1033  7278 E WifiMonitor: handleEvent unknown,: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:55:57.685  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 16:55:57.685  1033  7278 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 16:55:57.685  1033  7278 E WifiMonitor: WifiMonitor:p2p0 cnt=33 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:55:57.685  1033  7278 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:55:57.685  1033  7278 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:55:57.686  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.686  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.686  1033  1536 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.687  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
09-06 16:55:57.687  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.687  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.687  1033  1536 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.687  1942  2350 W WfdsService: DefaultState - msg [9441285] is not handled
09-06 16:55:57.687  1033  1033 E WifiServerServiceExt: No p2p device connected
09-06 16:55:57.687  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-06 16:55:57.688  1942  1942 D WfdsService: Update P2p Interface State: 3
,09-06 16:55:57.693  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:57.693  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:57.693  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 16:55:57.698  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:57.698  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:57.698  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-06 16:55:57.698  1033  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-06 16:55:57.698  1033  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-06 16:55:57.705  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:57.705  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:57.705  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 16:55:57.706  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:57.706  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:55:57.709  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:57.710  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:57.710  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:57.710  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 16:55:57.710  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:57.710  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:55:57.712  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:57.713  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:57.713  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:55:57.714  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:57.716  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:57.716  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 16:55:57.720  1033  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-06 16:55:57.720  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:57.720  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 16:55:57.720  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 16:55:57.720  1033  1543 D ConnectivityService: Got NetworkAgent Messenger
09-06 16:55:57.720  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-06 16:55:57.720  1033  1543 D ConnectivityService: NetworkAgent connected
09-06 16:55:57.721  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 16:55:57.721  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 16:55:57.726  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 16:55:57.726  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 16:55:57.726  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 16:55:57.727  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 16:55:57.727  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-06 16:55:57.734  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 16:55:57.735   318   893 D CommandListener: Setting iface cfg
09-06 16:55:57.738  1033  7309 D DhcpStateMachine: StoppedState
09-06 16:55:57.738  1033  1537 E WifiStateMachine: Start Dhcp Watchdog 2
09-06 16:55:57.738  1033  7309 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:57.738  1033  7309 D DhcpStateMachine: WaitBeforeStartState
09-06 16:55:57.739  1033  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=123128  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 16:55:57.740  1033  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=123128  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 16:55:57.741  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=123129  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 16:55:57.741  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:55:57.742  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:55:57.743  1033  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:55:57.743  1033  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:55:57.744  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:55:57.744  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:55:57.745  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 16:55:57.745  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 2 0 cz
,09-06 16:55:57.746  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_SET_FREQUENCY_BAND 0 0
09-06 16:55:57.747  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_SET_FREQUENCY_BAND 0 0
09-06 16:55:57.747  1033  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-06 16:55:57.748  1033  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-06 16:55:57.750  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-06 16:55:57.751  7202  7202 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-06 16:55:57.751  7202  7202 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 16:55:57.751  1033  7278 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-06 16:55:57.751  1033  7278 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 16:55:57.752  1033  7278 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 16:55:57.752  1033  7278 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 16:55:57.752  1033  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-06 16:55:57.752  1033  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-06 16:55:57.753  1033  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-06 16:55:57.753  1033  1537 D WifiNative-wlan0: doBoolean: SCAN
09-06 16:55:57.753  7202  7202 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-06 16:55:57.754  1033  7278 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-06 16:55:57.754  1033  7278 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-06 16:55:57.754  1033  7278 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-06 16:55:57.754  1033  7278 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-06 16:55:57.754  1033  1537 D WifiNative-wlan0: SCAN: returned true
09-06 16:55:57.755  1033  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=123143  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 16:55:57.755  1033  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=123144  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 16:55:57.756  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=123144  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 16:55:57.756  1033  1537 E WifiStateMachine:  ObtainingIpState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 16:55:57.757  1033  1537 E WifiStateMachine:  L2ConnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 16:55:57.757  1033  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 16:55:57.758  1033  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 16:55:57.759  1033  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 16:55:57.759  1033  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 16:55:57.760  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 16:55:57.760  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,09-06 16:55:57.761  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-06 16:55:57.761  1033  1033 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-06 16:55:57.762  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 16:55:57.762  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-06 16:55:57.762  1033  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=123151  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 16:55:57.763  1033  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=123151  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 16:55:57.763  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=123152  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 16:55:57.764  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 16:55:57.765  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 16:55:57.765  1033  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 16:55:57.765  1033  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 16:55:57.766  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 16:55:57.766  1033  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 16:55:57.768  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:76587] from screen [on:0 period:-24761] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 16:55:57.769  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-24759] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 16:55:57.770  1033  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-06 16:55:57.787  7285  7285 D WeatherApplication: removeAccount
09-06 16:55:57.788  7285  7285 D WeatherApplication: Account.length = 0
09-06 16:55:57.789  7285  7285 E WeatherApplication: OPERATOR:OPEN
,09-06 16:55:57.794  7285  7285 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:55:57
09-06 16:55:57.797  7285  7285 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 16:55:57.797  7285  7285 D Weather.Utils: 2 : All the weather widget is gone.
09-06 16:55:57.799  7285  7285 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-06 16:55:57.802  7285  7285 D WeatherAncestor: connectivity changed - connection : true
09-06 16:55:57.803  7285  7285 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-06 16:55:57.816  7285  7285 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 16:55:57.816  7285  7285 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 16:55:57.817  7285  7285 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,09-06 16:55:57.852  7285  7285 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,09-06 16:55:57.852  7285  7285 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:55:57
09-06 16:55:57.937  1033  1977 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7312 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 16:55:57.939  1033  1977 I ActivityManager: Killing 2146:com.lge.music/u0a34 (adj 15): empty #17
09-06 16:55:57.974   323   323 V AudioFlinger: 2146 died, releasing its sessions
,09-06 16:55:57.974   323   323 V AudioFlinger:  pid 1854 @ 0
09-06 16:55:57.974   323   323 V AudioFlinger:  pid 3175 @ 1
09-06 16:55:57.974   323   323 V AudioFlinger:  pid 3175 @ 2
09-06 16:55:58.021  1033  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-06 16:55:58.021  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-06 16:55:58.022  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.022  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:58.022  1033  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.023  1033  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.023  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.023  1033  1940 W libprocessgroup: failed to open /acct/uid_10034/pid_2146/cgroup.procs: No such file or directory
09-06 16:55:58.023  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.024  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-06 16:55:58.025  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=182,0,0
09-06 16:55:58.025  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=182,0,0
09-06 16:55:58.025  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-06 16:55:58.026  7202  7202 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-06 16:55:58.026  1033  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-06 16:55:58.026  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 0
09-06 16:55:58.027  1033  1537 D WifiNative-wlan0: SET ps 0: returned true
09-06 16:55:58.027  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-06 16:55:58.027  7202  7202 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-06 16:55:58.030  1942  7302 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
09-06 16:55:58.030  1942  7302 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
09-06 16:55:58.031  1033  7278 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-06 16:55:58.031  1033  7278 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-06 16:55:58.031  1033  7278 E WifiMonitor: WifiMonitor:p2p0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-06 16:55:58.031  1033  7278 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,09-06 16:55:58.031  1033  7278 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
09-06 16:55:58.031  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.031  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.031  1033  1536 D LGWifiP2pService: DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.031  1033  7278 E WifiMonitor: WifiMonitor:p2p0 cnt=38 dispatchEvent: WPS-AP-AVAILABLE 
09-06 16:55:58.032  1033  7278 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-06 16:55:58.032  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-06 16:55:58.032  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2efa94e2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.032  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2efa94e2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.033  1033  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-06 16:55:58.033  1033  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 16:55:58.033  1033  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 16:55:58.035  1033  7309 D DhcpStateMachine: WaitBeforeStartState{ when=-2ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.035  1033  7309 D DhcpStateMachine: DHCP Start wake lock is acquired.
,09-06 16:55:58.039   318   893 D CommandListener: Setting iface cfg
09-06 16:55:58.040   318   893 D CommandListener: Trying to bring up wlan0
09-06 16:55:58.043  1033  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-06 16:55:58.049  1033  1537 E WifiStateMachine:  ObtainingIpState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
,09-06 16:55:58.050  1033  1537 E WifiStateMachine:  L2ConnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 16:55:58.050  1033  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 16:55:58.051  1033  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 16:55:58.051  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 16:55:58.051  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 16:55:58.051  1033  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-06 16:55:58.051  1033  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-06 16:55:58.059  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.059  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.060  1033  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.060  1033  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.060  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.061  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.062  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-06 16:55:58.062  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 16:55:58.063  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 16:55:58.063  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 16:55:58.063  7202  7202 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,09-06 16:55:58.063  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.063  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.064  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 16:55:58.065  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-06 16:55:58.065  7202  7202 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-06 16:55:58.065  1033  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-06 16:55:58.066  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 16:55:58.082  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
09-06 16:55:58.083  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 16:55:58.083  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 16:55:58.083  1033  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,09-06 16:55:58.085  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-06 16:55:58.085  1033  1543 D ConnectivityService: ignoring duplicate network state non-change
09-06 16:55:58.088  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:58.088  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:55:58.090  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:58.092  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:58.092  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:58.092  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 16:55:58.097  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-06 16:55:58.097  1033  1543 D ConnectivityService: Adding iface wlan0 to network 101
09-06 16:55:58.101  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:58.101  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:58.101  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 16:55:58.106  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 16:55:58.107  1033  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 16:55:58.109  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:58.109  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:58.109  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,09-06 16:55:58.109  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 16:55:58.118  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:58.118  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:55:58.120  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:58.121  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-06 16:55:58.124  1033  1537 E WifiStateMachine:  ConnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 16:55:58.125  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 16:55:58.125  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:58.125  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 16:55:58.125  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 16:55:58.125  1033  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 16:55:58.125  1033  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-06 16:55:58.126  1033  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-06 16:55:58.127   318   893 E Netd    : netlink response contains error (File exists)
09-06 16:55:58.128  1033  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-06 16:55:58.129  1033  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-06 16:55:58.129  1033  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-06 16:55:58.129  1033  1543 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-06 16:55:58.130  1033  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 16:55:58.131  1033  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-06 16:55:58.131  1033  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-06 16:55:58.131  1033  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-06 16:55:58.131  1033  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 16:55:58.131  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:55:58.132  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 16:55:58.132  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:58.132  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-06 16:55:58.132  1033  1543 D ConnectivityService: currentScore = 0, newScore = 20
09-06 16:55:58.132  1033  1543 D ConnectivityService:    accepting network in place of null
09-06 16:55:58.132  1033  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:58.132  1033  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:58.133  1033  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 16:55:58.134  1033  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 16:55:58.134  1033  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-06 16:55:58.134  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 16:55:58.134  1033  7308 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.134  1033  7308 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-06 16:55:58.134  1033  7308 D NetworkMonitor, NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.134  1033  7308 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-06 16:55:58.134  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:58.134  1033  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-06 16:55:58.135  1033  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-06 16:55:58.136  1033  1543 D ConnectivityService: validation of new default Network = false
09-06 16:55:58.136  1033  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-06 16:55:58.136  1033  1543 D DSQN    : enableDataServiceNotify 
09-06 16:55:58.136  1033  1543 D DSQN    : start dsqn bin
09-06 16:55:58.138   318  7339 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-06 16:55:58.139   318  7339 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-06 16:55:58.142  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:58.143  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 16:55:58.143  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:58.145  1033  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-06 16:55:58.145  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:58.145  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:55:58.146  1033  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:55:58.147  1854  1854 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:58.148  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 16:55:58.133  7340  7340 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:55:58.133  7340  7340 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:55:58.151  1600  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 16:55:58.153  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-06 16:55:58.153  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 16:55:58.153  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 16:55:58.153  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 16:55:58.156  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:58.156  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 16:55:58.156  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:58.165  7340  7340 E DSQN    : DSQN ssw
,09-06 16:55:58.185  1033  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-06 16:55:58.189  1818  7345 I CheckinService: active receiver: enabled
,09-06 16:55:58.201  1818  7345 I CheckinService: Preparing to send checkin request
09-06 16:55:58.201  1818  7345 I EventLogService: Accumulating logs since 1473173678908
09-06 16:55:58.202   318  7339 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-06 16:55:58.214  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 16:55:58.215  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:58.215  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:58.238  1033  7309 D DhcpStateMachine: DHCPV4 request on wlan0
09-06 16:55:58.239  1033  7309 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-06 16:55:58.239  1033  7309 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-06 16:55:58.241   318   892 D LGDataListener: argv[0]=dsqncommand
09-06 16:55:58.241   318   892 D LGDataListener: argv[1]=wlan0
09-06 16:55:58.241   318   892 D LGDataListener: argv[2]=1
09-06 16:55:58.241   318   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-06 16:55:58.241  1033  1093 D DSQN    : DSQM DsqnNotification wlan0  1
,09-06 16:55:58.241  1033  1093 D DSQN    : start to monitor internet connection
09-06 16:55:58.233  7348  7348 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:55:58.233  7348  7348 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:55:58.250  7348  7348 I dhcpcd  : version 5.5.6 starting
09-06 16:55:58.252  7348  7348 E dhcpcd  : get_duid: m
09-06 16:55:58.252  7348  7348 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-06 16:55:58.252  7348  7348 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-06 16:55:58.254  1818  7345 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-06 16:55:58.275  1033  7308 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 14:55:58 GMT], X-Android-Received-Millis=[1473173758274], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473173758240]}
,09-06 16:55:58.275  1033  7308 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-06 16:55:58.275  1033  7308 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-06 16:55:58.275  1033  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-06 16:55:58.275  1033  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-06 16:55:58.275  1033  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 16:55:58.275  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:55:58.275  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 16:55:58.275  1033  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-06 16:55:58.276  1033  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-06 16:55:58.276  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:58.276  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:55:58.276  1033  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:55:58.276  1033  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:58.276  1600  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
09-06 16:55:58.277  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 16:55:58.277  1033  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:58.277  1033  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 16:55:58.278  1854  1854 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:58.278  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-06 16:55:58.297  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-06 16:55:58.298  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:58.299  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:58.325  7348  7348 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 16:55:58.325  7348  7348 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 16:55:58.325  7348  7348 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-06 16:55:58.325  7348  7348 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-06 16:55:58.325  7348  7348 D dhcpcd  : wlan0: sending REQUEST (xid 0xa15774a5), next in 3.65 seconds
09-06 16:55:58.360  1033  2071 I art     : Explicit concurrent mark sweep GC freed 106303(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/64MB, paused 1.966ms total 158.272ms
,09-06 16:55:58.376   281   341 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,09-06 16:55:58.376   281   341 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-06 16:55:58.376   281   341 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 16:55:58.377  7348  7348 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-06 16:55:58.379  1033  1740 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7360 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
09-06 16:55:58.388  7312  7358 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-06 16:55:58.390   281   341 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 16:55:58.390   281   341 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-06 16:55:58.390   281   341 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 16:55:58.390  7312  7358 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-06 16:55:58.394   281   341 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 16:55:58.394   281   341 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-06 16:55:58.394   281   341 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 16:55:58.395  7312  7380 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-06 16:55:58.396   281   341 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 16:55:58.396   281   341 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-06 16:55:58.396   281   341 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 16:55:58.396  7312  7380 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-06 16:55:58.408  7348  7348 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-06 16:55:58.408  7348  7348 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-06 16:55:58.408  7348  7348 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-06 16:55:58.408  7348  7348 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-06 16:55:58.409  7348  7348 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 16:55:58.409  7348  7348 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 16:55:58.409  7348  7348 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 16:55:58.409  7348  7348 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-06 16:55:58.428  7360  7360 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-06 16:55:58.428  7360  7360 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-06 16:55:58.458  7360  7360 I MultiDex: VM with version 2.1.0 has multidex support
09-06 16:55:58.458  7360  7360 I MultiDex: install
09-06 16:55:58.458  7360  7360 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-06 16:55:58.467  7360  7360 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-06 16:55:58.597  7312  7312 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-06 16:55:58.605  7312  7312 I LibraryLoader: Loading: webviewchromium
09-06 16:55:58.608  7312  7312 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4006-4009)
09-06 16:55:58.608  7312  7312 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 16:55:58.614  7312  7312 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {33307e46}
,09-06 16:55:58.617  7312  7312 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 16:55:58.618  7312  7312 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 16:55:58.641  1033  7309 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-06 16:55:58.642  7312  7312 I BrowserStartupController: Initializing chromium process, renderers=0
,09-06 16:55:58.643  7312  7312 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 16:55:58.647  1033  7309 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-06 16:55:58.647  1033  7309 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 16:55:58.647  1033  7309 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-06 16:55:58.648  1033  7309 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-06 16:55:58.648  1033  7309 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 16:55:58.648  1033  7309 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-06 16:55:58.648  1033  7309 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-06 16:55:58.650  1033  7309 D DhcpStateMachine: RunningState
09-06 16:55:58.655  7312  7312 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-06 16:55:58.655  7312  7312 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-06 16:55:58.656  7312  7312 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-06 16:55:58.660   323  1384 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10093
09-06 16:55:58.661  7312  7423 W AudioManagerAndroid: Requires BLUETOOTH permission
09-06 16:55:58.665  1033  2014 D WifiServiceImplEx: setWifiEnabled: false pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 16:55:58.665  1033  2014 D WifiService: setWifiEnabled: false pid=6729, uid=10118
09-06 16:55:58.665  1033  2014 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 16:55:58.681  1033  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 16:55:58.682  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 16:55:58.682  1033  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-06 16:55:58.682  1033  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-06 16:55:58.683  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 16:55:58.683  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-06 16:55:58.683  1033  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 16:55:58.683  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 16:55:58.683  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,09-06 16:55:58.684  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,09-06 16:55:58.684  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 16:55:58.684  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-06 16:55:58.684  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-06 16:55:58.687  7312  7312 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 16:55:58.687  7312  7312 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 16:55:58.687  7312  7312 I Adreno-EGL: Build Date: 12/12/14 금
09-06 16:55:58.687  7312  7312 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 16:55:58.687  7312  7312 I Adreno-EGL: Remote Branch: 
09-06 16:55:58.687  7312  7312 I Adreno-EGL: Local Patches: 
09-06 16:55:58.687  7312  7312 I Adreno-EGL: Reconstruct Branch: 
,09-06 16:55:58.696  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-06 16:55:58.696  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,09-06 16:55:58.696  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.696  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.696  7202  7202 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 16:55:58.697  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 16:55:58.697  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 16:55:58.697  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
09-06 16:55:58.698  1033  7309 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.702   318   893 D CommandListener: Clearing all IP addresses on wlan0
09-06 16:55:58.737  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 16:55:58.737  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,09-06 16:55:58.739  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-06 16:55:58.741  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:58.741  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:58.742  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 16:55:58.742  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:58.742  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 16:55:58.742  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:55:58.742  1033  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.742  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.742  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.742  1033  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1b2ed4d5
09-06 16:55:58.742  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.742  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-06 16:55:58.743  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.743  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:58.743  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.744  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.745  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:55:58.745  1033  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 16:55:58.745  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:58.745  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:58.745  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 16:55:58.746  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 16:55:58.746  1033  1033 D RttService: SCAN_AVAILABLE : 1
09-06 16:55:58.746  1033  1536 D LGWifiP2pService: P2pDisablingState
09-06 16:55:58.746  1033  1536 D LGWifiP2pService: P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.746  1033  1536 D LGWifiP2pService: p2p socket connection lost
09-06 16:55:58.746  1033  1536 D LGWifiP2pService: P2pDisabledState
09-06 16:55:58.746  1033  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.746  1033  1556 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.747  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-06 16:55:58.747  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 16:55:58.747  1942  1942 D WfdsService: WifiP2pState is changed : false
09-06 16:55:58.747  1942  2350 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-06 16:55:58.747  1942  2350 D WfdsService: Set the WFDS Monitor: false
09-0,6 16:55:58.748  1942  2350 D WfdsMonitor: WFDS Monitor is stopped
09-06 16:55:58.748  1942  2350 D WfdsService: STATE : WfdsDisabledState - enter
09-06 16:55:58.748  1942  7302 D CtrlSupplicant: Received on exit socket, terminate
09-06 16:55:58.748  1942  2351 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-06 16:55:58.748  1942  7302 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-06 16:55:58.748  1942  7302 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
,09-06 16:55:58.748  1942  7302 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-06 16:55:58.749  1942  2350 W WfdsService: DefaultState - msg [9445378] is not handled
09-06 16:55:58.750  1033  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-06 16:55:58.751  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.751  1033  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.751  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 16:55:58.752  7202  7202 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 16:55:58.752  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 16:55:58.752  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 16:55:58.752  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
09-06 16:55:58.764  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:58.764  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:55:58.765  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:58.767  7312  7312 I NSApplication: Starting up...
,09-06 16:55:58.782  7360  7379 D LgDataFeature: LgDataFeature() Constructor: none
09-06 16:55:58.782  7360  7379 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 16:55:58.786   318   893 D CommandListener: Clearing all IP addresses on wlan0
09-06 16:55:58.787  1033  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-06 16:55:58.787  1033  1543 D DSQN    : disableDataServiceNotify
09-06 16:55:58.787  1033  1543 D DSQN    : stop dsqn bin
09-06 16:55:58.796  1033  1977 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7441 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-06 16:55:58.797  1033  1977 I ActivityManager: Killing 6942:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-06 16:55:58.802  1033  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-06 16:55:58.802  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:58.802  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:55:58.802  1033  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:55:58.802  1033  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-06 16:55:58.802  1600  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 16:55:58.803  1033  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-06 16:55:58.803  1033  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-06 16:55:58.803  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 16:55:58.803  1033  7308 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.803  1033  7308 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:58.803  1033  7308 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,09-06 16:55:58.907  1033  7309 D DhcpStateMachine: StoppedState
09-06 16:55:58.907  1033  7309 D DhcpStateMachine: StoppedState{ when=-154ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 16:55:58.932  1033  1537 D WifiNative-p2p0: doBoolean: TERMINATE
,09-06 16:55:58.933  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:58.933  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-06 16:55:58.934  1033  1905 W libprocessgroup: failed to open /acct/uid_10037/pid_6942/cgroup.procs: No such file or directory
09-06 16:55:58.936  1033  1537 D WifiNative-p2p0: TERMINATE: returned true
09-06 16:55:58.936  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 16:55:58.936  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
09-06 16:55:58.936  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 16:55:58.948  1033  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,09-06 16:55:58.950  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-06 16:55:58.950  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:58.950  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:58.950  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 16:55:58.950  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 16:55:58.950  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 16:55:58.950  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:58.951  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 16:55:58.951  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 16:55:58.951  1033  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:58.954  1033  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:58.954  1033  1537 E WifiStateMachine:  SupplicantStoppingState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 16:55:58.954  1033  1543 D NetworkManagementService: Removing idletimer
09-06 16:55:58.954  1033  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:58.954  1854  1854 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:58.954  1033  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:58.954  1033  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 16:55:58.954  1033  1543 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-06 16:55:58.954  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 16:55:58.957  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 16:55:58.957  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:55:58.959  1033  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-06 16:55:58.961  1033  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-06 16:55:58.961  1033  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,09-06 16:55:58.966  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:58.969  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 16:55:58.970  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-06 16:55:58.970  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:58.970  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:58.970  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:58.970  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:58.970  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:58.970  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:58.970  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:58.970  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:58.970  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:55:58.970  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:58.970  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:55:58.971  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-06 16:55:58.971  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:58.971  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:58.971  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:58.971  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:55:58.971  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:58.971  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:58.971  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:58.971  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:58.971  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:55:58.971  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:58.971  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:55:58.973  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 16:55:58.973  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-06 16:55:58.973  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 16:55:58.973  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 16:55:58.973  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-06 16:55:58.993  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 16:55:58.994  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:58.994  7441  7441 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 16:55:58.995  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:59.014  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-06 16:55:59.015  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:59.015  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:59.016  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:59.051  7202  7202 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-06 16:55:59.051  7202  7202 I wpa_supplicant: monitor socket send errors count : 1
09-06 16:55:59.051  7202  7202 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-4\x00 that cannot receive messages
,09-06 16:55:59.054  1033  7278 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-06 16:55:59.054  1033  7278 D WifiMonitor: Dropping event because (p2p0) is stopped
09-06 16:55:59.076  7202  7202 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 16:55:59.077  1033  1095 D Tethering: InitialState.processMessage what=4
09-06 16:55:59.078  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-06 16:55:59.079  7202  7202 W wpa_supplicant: USIM:  scard_deinit function
,09-06 16:55:59.079  1033  7278 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-06 16:55:59.079  1033  7278 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 16:55:59.080  1033  7278 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 16:55:59.080  1033  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:55:59.081  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:55:59.083  1033  7278 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-06 16:55:59.083  1033  7278 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 16:55:59.083  1033  7278 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 16:55:59.084  1033  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124473
09-06 16:55:59.084  1033  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124473
09-06 16:55:59.085  1033  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=124474  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 16:55:59.085  1033  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=124474  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 16:55:59.115  7461  7461 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-06 16:55:59.145  1033  1543 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-06 16:55:59.172  7461  7461 I dex2oat : dex2oat took 56.915ms (threads: 4)
,09-06 16:55:59.187  7360  7379 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 16:55:59.187  7360  7379 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 16:55:59.187  7360  7379 I Adreno-EGL: Build Date: 12/12/14 금
09-06 16:55:59.187  7360  7379 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 16:55:59.187  7360  7379 I Adreno-EGL: Remote Branch: 
09-06 16:55:59.187  7360  7379 I Adreno-EGL: Local Patches: 
09-06 16:55:59.187  7360  7379 I Adreno-EGL: Reconstruct Branch: 
,09-06 16:55:59.188  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-06 16:55:59.191  6457  6497 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 16:55:59.202  2188  2188 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:55:59.209  7202  7202 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-06 16:55:59.209  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 16:55:59.210  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:59.210  1033  7278 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-06 16:55:59.210  1033  7278 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-TERMINATING 
09-06 16:55:59.210  1033  7278 D WifiMonitor: Disconnecting from the supplicant, no more events
09-06 16:55:59.211  1033  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 41 0
09-06 16:55:59.217  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 16:55:59.217  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 16:55:59.219  7151  7151 I AppUp4:CustModeStarterReceiver: onReceive
,09-06 16:55:59.223  7151  7151 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@29abb71f
09-06 16:55:59.223  7151  7151 D AppUp4:CustFacade: isCustomizationCompleted : false
,09-06 16:55:59.223  7151  7151 D AppUp4:CustFacade: isPhone : true
09-06 16:55:59.223  7151  7151 D AppUp4:CustModeStarterReceiver: begin check event
09-06 16:55:59.223  7151  7151 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 16:55:59.226  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:59.226  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 16:55:59.228  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 16:55:59.229  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 16:55:59.233  4759  7474 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 16:55:59.234  7184  7184 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 16:55:59.237  4759  7475 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:59.237  4759  7475 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 16:55:59.255  3175  3175 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 16:55:59.255  3175  3175 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:59.255  3175  3175 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-06 16:55:59.257  7184  7477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:59.258  7050  7478 W FormManager: Network not available. Please check & try again.
09-06 16:55:59.261  7217  7217 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 16:55:59.261  7217  7217 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 16:55:59.262  7050  7481 V FormManager: Network unavailable.
09-06 16:55:59.273  7285  7285 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:55:59
,09-06 16:55:59.274  7050  7481 V FormManager: Network unavailable.
09-06 16:55:59.274  7285  7285 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-06 16:55:59.274  7285  7285 D Weather.Utils: 2 : All the weather widget is gone.
09-06 16:55:59.275  7285  7285 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 16:55:59.275  7285  7285 D WeatherAncestor: connectivity changed - connection : true
09-06 16:55:59.275  7285  7285 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1710d835
09-06 16:55:59.276  7285  7285 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 16:55:59.276  7285  7285 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 16:55:59.276  7285  7285 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 16:55:59.276  7285  7285 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 16:55:59.276  7285  7285 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:55:59
09-06 16:55:59.302   318  7486 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-06 16:55:59.302  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-06 16:55:59.305  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 16:55:59.305  6960  6960 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 16:55:59.305  6960  6960 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 16:55:59.305  6960  6960 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 16:55:59.306  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 16:55:59.306  6960  6960 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 16:55:59.306  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 16:55:59.306  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,09-06 16:55:59.306  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 16:55:59.306  6960  6960 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 16:55:59.306  6960  6960 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 16:55:59.311  1033  1537 D WifiOffDelayIfNotUsed: stopMonitoring
09-06 16:55:59.312  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 16:55:59.312  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
09-06 16:55:59.312  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 16:55:59.312  1942  1942 D WfdsService: Supplicant Connection state is changed : false
09-06 16:55:59.312  1942  2350 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-06 16:55:59.312  1942  2350 D WfdsService: Set the WFDS Monitor: false
09-06 16:55:59.312  1942  2350 D WfdsMonitor: WFDS Monitor is stopped
09-06 16:55:59.313  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 16:55:59.313  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:55:59.314  2469  2469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:59.316  6979  6979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:55:59.317  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-06 16:55:59.317  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-06 16:55:59.317  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-06 16:55:59.318  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:59.318  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:59.322  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 16:55:59.323  7050  7488 W FormManager: Network not available. Please check & try again.
09-06 16:55:59.328  7360  7379 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 16:55:59.328  7360  7379 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 16:55:59.328  7360  7379 I Adreno-EGL: Build Date: 12/12/14 금
09-06 16:55:59.328  7360  7379 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 16:55:59.328  7360  7379 I Adreno-EGL: Remote Branch: 
09-06 16:55:59.328  7360  7379 I Adreno-EGL: Local Patches: 
09-06 16:55:59.328  7360  7379 I Adreno-EGL: Reconstruct Branch: 
,09-06 16:55:59.332  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:55:59.337  7050  7489 V FormManager: Network unavailable.
09-06 16:55:59.343  7050  7489 V FormManager: Network unavailable.
,09-06 16:55:59.350  6979  6979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:55:59.352  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:55:59.356  7050  7491 V FormManager: Network unavailable.
09-06 16:55:59.357  7050  7490 W FormManager: Network not available. Please check & try again.
09-06 16:55:59.357  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:55:59.358  7050  7491 V FormManager: Network unavailable.
09-06 16:55:59.369  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 16:55:59.370  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 16:55:59.371  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 16:55:59.372  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 16:55:59.376  4759  7492 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 16:55:59.380  4759  7493 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 16:55:59.380  4759  7493 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 16:55:59.385  7360  7379 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 16:55:59.385  7360  7379 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 16:55:59.385  7360  7379 I Adreno-EGL: Build Date: 12/12/14 금
09-06 16:55:59.385  7360  7379 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 16:55:59.385  7360  7379 I Adreno-EGL: Remote Branch: 
09-06 16:55:59.385  7360  7379 I Adreno-EGL: Local Patches: 
09-06 16:55:59.385  7360  7379 I Adreno-EGL: Reconstruct Branch: 
,09-06 16:55:59.399  1033  2014 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7494 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-06 16:55:59.413   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 275us total 12.120ms
,09-06 16:55:59.425   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 11.657ms
,09-06 16:55:59.437   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 229us total 11.337ms
,09-06 16:55:59.482  7494  7494 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 16:55:59.482  7494  7494 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-06 16:55:59.484   318  7513 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-06 16:55:59.484  1818  7345 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-06 16:55:59.485  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-06 16:55:59.488  7494  7494 V [BNRBootReceiver]: Boot Receiver Return
09-06 16:55:59.489  7494  7494 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-06 16:55:59.491  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:55:59.495  1818  7345 I CheckinService: active receiver: disabled
,09-06 16:55:59.509  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 16:55:59.515  1033  1537 E WifiStateMachine:  InitialState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 16:55:59.515  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:55:59.516  1033  1537 E WifiStateMachine:  DefaultState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 16:55:59.524  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:55:59.525  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:55:59.526  7009  7009 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 16:55:59.531  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 16:55:59.538  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:55:59.545  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:55:59.553  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 16:55:59.553  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:55:59.554  7009  7009 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 16:55:59.557  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:55:59.567  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:55:59.578  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:55:59.592  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:55:59.593  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 16:55:59.594  7009  7009 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 16:55:59.599  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 16:55:59.613  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:55:59.623  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 16:55:59.635  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:55:59.636  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 16:55:59.637  7009  7009 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 16:55:59.644  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:55:59.660  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:55:59.673  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:55:59.690  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 16:55:59.691  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 16:55:59.696  7009  7009 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 16:55:59.705  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-06 16:55:59.710  6960  6960 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-06 16:55:59.722  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 16:55:59.739  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:55:59.749  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:55:59.760  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 16:55:59.760  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:55:59.763  6868  7128 D UEI.SmartControl: Internal timer expired: 4
09-06 16:55:59.763  6868  7128 D UEI.SmartControl: unbind internal service
09-06 16:55:59.770  7009  7009 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 16:55:59.778  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 16:55:59.797  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:55:59.809  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:55:59.820  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:55:59.820  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:55:59.821  7009  7009 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 16:55:59.828  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 16:55:59.840  6979  6979 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-06 16:55:59.853  1033  1542 D WifiService: New client listening to asynchronous messages
09-06 16:55:59.853  6979  6979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:55:59.862  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:55:59.875  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:55:59.890  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:55:59.890  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:55:59.893  7009  7009 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-06 16:55:59.897  6868  7122 D serial_port: close(fd = 24)
09-06 16:55:59.900  7009  7009 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 16:55:59.900  6868  7122 I UEI.SmartControl: Serial port is closed.
09-06 16:55:59.901  7009  7009 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 16:55:59.912  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 16:55:59.922  6979  6979 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-06 16:55:59.925  6979  6979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:55:59.933  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:55:59.946  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:55:59.961  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 16:55:59.963  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 16:55:59.964  7009  7009 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-06 16:55:59.966  7009  7009 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 16:55:59.967  7009  7009 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 16:55:59.973  1033  1995 I ActivityManager: Killing 6644:com.android.vending/u0a44 (adj 15): empty #17
09-06 16:56:00.036  1600  1600 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-06 16:56:00.036  1600  1600 I KeyguardUpdateMonitor: called onTimeUpdated()
09-06 16:56:00.036  1600  1600 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-06 16:56:00.037  1600  1600 I [SystemUI]Clock: called onTimeUpdated()
09-06 16:56:00.037  1033  1376 D PowerManagerServiceEx: acquireWakeLockInternal: lock=445733117, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
09-06 16:56:00.039  1600  1600 I LgeClockWidgetControlView: called onTimeUpdated()
09-06 16:56:00.039  1600  1600 I [SystemUI]DateView: called onTimeUpdated()
09-06 16:56:00.040  1033  1940 W libprocessgroup: failed to open /acct/uid_10044/pid_6644/cgroup.procs: No such file or directory
09-06 16:56:00.041  1600  1600 I [SystemUI]DateView: called onTimeUpdated()
09-06 16:56:00.044  1600  1600 D KeyguardUpdateMonitor: handleTimeUpdate
,09-06 16:56:00.049  2188  2188 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-06 16:56:00.057  2188  2188 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-06 16:56:00.057  2188  2188 D c       : Getting all permits...
09-06 16:56:00.057  2188  2188 D a       : Opening database...
09-06 16:56:00.065  2188  2188 D a       : Opening database auth.proximity.permit_store...
09-06 16:56:00.066  2188  2188 D a       : Closing database...
09-06 16:56:00.077  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 16:56:00.083  6979  6979 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 16:56:00.083  6979  6979 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 16:56:00.083  6979  6979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:56:00.086  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:56:00.093  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:00.099  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:56:00.100  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:56:00.101  7009  7009 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 16:56:00.105  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:56:00.113  6979  6979 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 16:56:00.113  6979  6979 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 16:56:00.113  6979  6979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:56:00.116  2681  2681 D [Concierge]Service: onStartCommand(). Type : 9
,09-06 16:56:00.127  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:56:00.139  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:00.152  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:56:00.152  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 16:56:00.155  7009  7009 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 16:56:00.160  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:56:00.165  6979  6979 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 16:56:00.165  6979  6979 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-06 16:56:00.166  6979  6979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:56:00.171  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 16:56:00.176  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:00.183  7009  7009 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:56:00.184  7009  7009 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:56:00.185  7009  7009 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 16:56:00.194  6979  6979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:56:00.197  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:56:00.201  7050  7521 W FormManager: Network not available. Please check & try again.
,09-06 16:56:00.204  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:00.205  7050  7522 V FormManager: Network unavailable.
09-06 16:56:00.221  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-06 16:56:00.222  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-06 16:56:00.223  7050  7522 V FormManager: Network unavailable.
09-06 16:56:00.224  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 16:56:00.226  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 16:56:00.235  4759  7523 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 16:56:00.237  6979  6979 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-06 16:56:00.237  6979  6979 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 16:56:00.237  6979  6979 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:56:00.239  4759  7524 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 16:56:00.240  4759  7524 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 16:56:00.241  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:56:00.251  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:00.256  7050  7526 W FormManager: Network not available. Please check & try again.
09-06 16:56:00.261  7050  7527 V FormManager: Network unavailable.
,09-06 16:56:00.264  7050  7527 V FormManager: Network unavailable.
,09-06 16:56:00.269  2188  2188 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-06 16:56:00.284  7009  7009 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,09-06 16:56:00.286  7009  7009 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7380
,09-06 16:56:00.286  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=445733117 [*alarm*], flags=0x0
09-06 16:56:01.022  1033  1537 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-21506] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 16:56:01.023  1033  1537 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-21505] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-06 16:56:01.136  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:56:01.150  1033  1095 D Tethering: MasterInitialState.processMessage what=3
,09-06 16:56:01.166  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:01.172  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:01.175  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:01.177  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 16:56:01.179  6457  6497 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 16:56:01.190  5836  5836 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 16:56:01.208  2188  2188 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:56:01.225  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 16:56:01.225  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:01.226  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 16:56:01.226  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-06 16:56:01.233  7151  7151 I AppUp4:CustModeStarterReceiver: onReceive
09-06 16:56:01.237  7151  7151 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@29abb71f
09-06 16:56:01.237  7151  7151 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 16:56:01.237  7151  7151 D AppUp4:CustFacade: isPhone : true
09-06 16:56:01.237  7151  7151 D AppUp4:CustModeStarterReceiver: begin check event
09-06 16:56:01.238  7151  7151 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,09-06 16:56:01.244  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:01.245  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 16:56:01.246  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 16:56:01.250  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 16:56:01.259  7184  7184 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 16:56:01.281  4759  7536 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 16:56:01.289  7184  7535 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:01.297  4759  7537 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:01.297  4759  7537 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 16:56:01.315  3175  3175 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 16:56:01.316  3175  3175 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:01.316  3175  3175 I LgeMiscReceiver: networkInfo.isConnected() = true
09-06 16:56:01.316  3175  3175 D PhoneState: setPdpRejectCasuse : false
,09-06 16:56:01.321  7217  7217 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 16:56:01.321  7217  7217 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 16:56:01.343  7285  7285 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:1
,09-06 16:56:01.349  7285  7285 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 16:56:01.349  7285  7285 D Weather.Utils: 2 : All the weather widget is gone.
09-06 16:56:01.350  7285  7285 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 16:56:01.350  7285  7285 D WeatherAncestor: connectivity changed - connection : true
09-06 16:56:01.350  7285  7285 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1710d835
09-06 16:56:01.351  7285  7285 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 16:56:01.351  7285  7285 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 16:56:01.351  7285  7285 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 16:56:01.351  7285  7285 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 16:56:01.351  7285  7285 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:1
09-06 16:56:01.356  7050  7538 W FormManager: Network not available. Please check & try again.
,09-06 16:56:01.362  7050  7539 V FormManager: Network unavailable.
09-06 16:56:01.376  7050  7539 V FormManager: Network unavailable.
,09-06 16:56:01.396  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 16:56:01.683  1033  1742 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:01.683  1033  1742 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-06 16:56:01.710  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 16:56:01.710  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 16:56:01.710  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,09-06 16:56:01.714  1033  1095 D BluetoothManagerService: Message: 1
09-06 16:56:01.714  1033  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-06 16:56:01.740  1033  1095 D BluetoothManagerService: Message: 20
09-06 16:56:01.740  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@162f4833:true
,09-06 16:56:01.741  7074  7074 D BluetoothAdapterState: make
09-06 16:56:01.747  7074  7074 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-06 16:56:01.747  7074  7074 I bluedroid-qcom: init
09-06 16:56:01.749  7074  7074 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 16:56:01.749  7074  7565 I BluetoothAdapterState: Entering OffState
09-06 16:56:01.750  7074  7074 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 16:56:01.750  7074  7074 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 16:56:01.750  7074  7074 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 16:56:01.750  7074  7074 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-06 16:56:01.752  7074  7074 I bluedroid-qcom: get_profile_interface socket
09-06 16:56:01.752  7074  7074 I bluedroid-qcom: get_profile_interface map_client
09-06 16:56:01.743  7568  7568 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:01.743  7568  7568 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:01.757  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-06 16:56:01.757  1033  1095 D BluetoothManagerService: Message: 40
09-06 16:56:01.758  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-06 16:56:01.759  7074  7091 I bluedroid-qcom: config_hci_snoop_log
09-06 16:56:01.760  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-06 16:56:01.761  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,09-06 16:56:01.766  7568  7568 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-06 16:56:01.767  7074  7565 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-06 16:56:01.767  7568  7568 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-06 16:56:01.767  7568  7568 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-06 16:56:01.767  7074  7565 D BluetoothAdapterProperties: Setting state to 11
09-06 16:56:01.767  7074  7565 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 16:56:01.770  1033  1095 D BluetoothManagerService: Message: 60
09-06 16:56:01.771  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-06 16:56:01.771  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-06 16:56:01.771  7074  7565 I LGBluetoothServiceJni: classInitNative: succeeds
09-06 16:56:01.771  7568  7568 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-06 16:56:01.774  7074  7569 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-06 16:56:01.776  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:01.778  6960  6960 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-06 16:56:01.779  7074  7569 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-06 16:56:01.779  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-06 16:56:01.782  7074  7569 D BluetoothAdapterProperties: Name is: G3
09-06 16:56:01.784  7568  7568 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-06 16:56:01.784  7568  7568 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-06 16:56:01.785  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:01.787  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:01.790  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 16:56:01.790  7074  7074 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 16:56:01.790  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 16:56:01.791  7074  7074 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:01.791  7074  7074 V BluetoothPbapReceiver: ***********state = 11
,09-06 16:56:01.795  7074  7565 D BluetoothBondStateMachine: make
,09-06 16:56:01.803  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 16:56:01.804  7074  7565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:01.804  7074  7565 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-06 16:56:01.804  7074  7565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:01.804  7074  7565 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-06 16:56:01.805  7074  7565 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-06 16:56:01.807  7074  7571 I BluetoothBondStateMachine: StableState(): Entering Off State
09-06 16:56:01.816  7074  7565 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 16:56:01.842  1033  1713 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7578 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-06 16:56:01.847  7074  7565 E BluetoothAdapterService: File transfer profiles supported!!
09-06 16:56:01.852  7074  7074 D HeadsetService: Received start request. Starting profile...
,09-06 16:56:01.854  7074  7074 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 16:56:01.854  7074  7074 D LGBluetoothHfpAdapter: Version 1.6
09-06 16:56:01.857  7074  7565 E BluetoothAdapterService: File transfer profiles supported!!
09-06 16:56:01.862  7074  7074 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 16:56:01.865  7074  7565 E BluetoothAdapterService: File transfer profiles supported!!
09-06 16:56:01.865  7074  7074 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 16:56:01.867  7074  7074 D HeadsetStateMachine: make
09-06 16:56:01.872  7074  7565 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 16:56:01.878  7074  7565 E BluetoothAdapterService: File transfer profiles supported!!
09-06 16:56:01.883  7074  7565 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 16:56:01.899  7074  7565 V LGMDMManager: Create singleton instance
,09-06 16:56:01.908  7074  7565 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-06 16:56:01.912  7074  7074 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 16:56:01.913  7074  7074 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 16:56:01.918  7074  7074 D HeadsetStateMachine: max_hf_connections = 1
09-06 16:56:01.918  7074  7074 I bluedroid-qcom: get_profile_interface handsfree
09-06 16:56:01.920  7074  7074 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-06 16:56:01.921   323   323 V AudioPolicyService: registerClient() client 0xb57c70c0, uid 1002
09-06 16:56:01.921   323  1384 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-06 16:56:01.922   323  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 16:56:01.922   323  1384 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 16:56:01.922  7074  7074 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 16:56:01.922   323  1765 V AudioFlinger: registerClient() client 0xb5581b08, pid 7074
09-06 16:56:01.923   323  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 16:56:01.923   323  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 16:56:01.923  7074  7074 V ToneGenerator: Create Track: 0xb4928a80
,09-06 16:56:01.923  7074  7074 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-06 16:56:01.923  7074  7074 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-06 16:56:01.923   323   323 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 16:56:01.923   323   323 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-06 16:56:01.923   323   323 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 16:56:01.923   323   323 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 16:56:01.924  7074  7074 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 16:56:01.924   323  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 16:56:01.924   323  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 16:56:01.924   323  1383 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 16:56:01.924  3175  3191 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 16:56:01.924  3175  3191 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 16:56:01.924   323  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 16:56:01.924   323  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-06 16:56:01.924  3175  3191 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 16:56:01.924   323  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 16:56:01.924   323  1383 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 16:56:01.924  3175  3191 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 16:56:01.925  1033  1742 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 16:56:01.925  1033  1742 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 16:56:01.925  1033  1742 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 16:56:01.925  1033  1742 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 16:56:01.925  7074  7074 V AudioSystem: getLatency() output 2, latency 50
09-06 16:56:01.925  1600  3204 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 16:56:01.925  1600  3204 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 16:56:01.925  7074  7074 V AudioSystem: getFrameCount() output 2, frameCount 960
09-06 16:56:01.925  1600  3204 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 16:56:01.925  7074  7074 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 16:56:01.925  1600  3204 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 16:56:01.925  1854  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 16:56:01.925  1854  1870 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 16:56:01.925  7074  7074 V AudioTrack: createTrack_l() output 2 afLatency 50
09-06 16:56:01.925  1854  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 16:56:01.925  1854  1870 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 16:56:01.925  7074  7091 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 16:56:01.925  7074  7091 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-06 16:56:01.925  7074  7091 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 16:56:01.925  7074  7091 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-06 16:56:01.925   323  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 16:56:01.925   323  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 16:56,:01.925   323  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 16:56:01.925   323  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 16:56:01.925   323  1383 V AudioFlinger: createTrack() lSessionId: 22
09-06 16:56:01.927  7074  7074 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-06 16:56:01.927   323  1384 V AudioFlinger: acquiring 22 from 7074, for 7074
09-06 16:56:01.927   323  1384 V AudioFlinger:  added new entry for 22
09-06 16:56:01.927  7074  7074 V ToneGenerator: ToneGenerator INIT OK, time: 127329
09-06 16:56:01.927  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:01.928  7074  7592 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-06 16:56:01.928  7074  7592 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 16:56:01.928  7074  7592 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 16:56:01.928  7074  7592 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-06 16:56:01.929  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:01.929   323  1765 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7074
09-06 16:56:01.929   323  1765 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-06 16:56:01.930   323  1765 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-06 16:56:01.930   323  1765 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-06 16:56:01.930   323  1765 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-06 16:56:01.930   323  1765 V voice   : voice_set_parameters: exit with code(0)
09-06 16:56:01.930   323  1765 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-06 16:56:01.930   323  1765 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-06 16:56:01.930   323  1765 V msm8974_platform: platform_set_parameters: exit with code(0)
09-06 16:56:01.930   323  1765 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-06 16:56:01.930   323  1765 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-06 16:56:01.930   323  1765 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-06 16:56:01.931  7074  7592 V ToneGenerator: ToneGenerator destructor
09-06 16:56:01.931  7074  7592 V ToneGenerator: stopTone
09-06 16:56:01.931  7074  7592 V ToneGenerator: Delete Track: 0xb4928a80
09-06 16:56:01.931  7074  7074 D A2dpService: Received start request. Starting profile...
09-06 16:56:01.932  7074  7074 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 16:56:01.933  7074  7074 V Avrcp   : make
09-06 16:56:01.933  7074  7592 V AudioTrack: ~AudioTrack, releasing session id from 7074 on behalf of 7074
09-06 16:56:01.933   323  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
09-06 16:56:01.933   323  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-06 16:56:01.933   323  1384 V AudioFlinger: PlaybackThread::Track destructor
09-06 16:56:01.933   323  1226 V AudioPolicyService: AudioCommandThread() waking up
09-06 16:56:01.933   323  1384 V AudioFlinger: removeClient_l() pid 7074, calling pid 323
09-06 16:56:01.933   323  1226 V AudioPolicyService: AudioCommandThread() processing release output 2
09-06 16:56:01.933   323  1226 V AudioPolicyManager: releaseOutput() 2
09-06 16:56:01.933   323  1226 V AudioPolicyService: AudioCommandThread() going to sleep
09-06 16:56:01.933   323  1384 V AudioFlinger: releasing 22 from 7074 for 7074
09-06 16:56:01.933   323  1384 V AudioFlinger:  decremented refcount to 0
09-06 16:56:01.933   323  1384 V AudioFlinger: purging stale effects
09-06 16:56:01.933  7074  7074 D Avrcp   : [BTUI] ,Use Native AVRCP : init jni
09-06 16:56:01.933  7074  7074 I bluedroid-qcom: get_profile_interface avrcp
09-06 16:56:01.934  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:01.934  1033  1049 W Process : Unable to open /proc/7601/status
09-06 16:56:01.937  1033  1095 D Tethering: MasterInitialState.processMessage what=3
09-06 16:56:01.940  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:01.942  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:01.949  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:01.950  7074  7074 V AudioManager: registerRemoteController: size of Media player list: 0
09-06 16:56:01.951  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 16:56:01.951  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:01.952  6457  6497 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 16:56:01.953  7074  7074 E AudioManager: No RCC entry present to update
09-06 16:56:01.953  7074  7074 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-06 16:56:01.957  7074  7074 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-06 16:56:01.959  7074  7074 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-06 16:56:01.959  7074  7074 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-06 16:56:01.962  1033  1095 D Tethering: MasterInitialState.processMessage what=3
09-06 16:56:01.969  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:01.973  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:01.974  7074  7074 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-06 16:56:01.975  5836  5836 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 16:56:02.029  5836  5836 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 16:56:02.036  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:02.037  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:56:02.038  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:56:02.052  2188  2188 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:56:02.066  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 16:56:02.066  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:02.067  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 16:56:02.067  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-06 16:56:02.070  7151  7151 I AppUp4:CustModeStarterReceiver: onReceive
09-06 16:56:02.074  7151  7151 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@29abb71f
09-06 16:56:02.074  7151  7151 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 16:56:02.074  7151  7151 D AppUp4:CustFacade: isPhone : true
09-06 16:56:02.074  7151  7151 D AppUp4:CustModeStarterReceiver: begin check event
09-06 16:56:02.075  7151  7151 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 16:56:02.078  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:02.078  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-06 16:56:02.080  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 16:56:02.082  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 16:56:02.087  4759  7605 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 16:56:02.092  7184  7184 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-06 16:56:02.092  1033  1049 V SIM_STK : Menu title from STK is T-Mobile
09-06 16:56:02.092  1033  1049 V SIM_STK : Menu title from STK is T-Mobile
09-06 16:56:02.095  4759  7606 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:02.095  4759  7606 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 16:56:02.103  7578  7578 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-06 16:56:02.103  7578  7578 W LG Account v2.2: No ProfileInfo entries
09-06 16:56:02.103  7578  7578 I LG Account v2.2: isEnabled: false
09-06 16:56:02.103  7578  7578 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-06 16:56:02.103  7578  7578 I Feature : [Lifetracker]Country: EU
09-06 16:56:02.103  7578  7578 I Feature : [Lifetracker]Operator: OPEN
09-06 16:56:02.103  7578  7578 I Feature : [Lifetracker]Ranking support: false
09-06 16:56:02.103  7578  7578 I Feature : [Lifetracker]Comfort support: false
09-06 16:56:02.103  7578  7578 I Feature : [Lifetracker]Accessory: true
09-06 16:56:02.103  7578  7578 I Feature : [Lifetracker]Health device: true
09-06 16:56:02.103  7578  7578 I Feature : [Lifetracker]Extra Pedometer: false
09-06 16:56:02.103  7578  7578 I Feature : [Lifetracker]Blood glucose device: false
09-06 16:56:02.103  7578  7578 I Feature : [Lifetracker]Device Number: 3
,09-06 16:56:02.111  7184  7609 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:02.122  7050  7611 W FormManager: Network not available. Please check & try again.
,09-06 16:56:02.122  7050  7612 V FormManager: Network unavailable.
,09-06 16:56:02.127  7050  7612 V FormManager: Network unavailable.
09-06 16:56:02.127  6960  6960 D BluetoothPermissionRequest: onReceive
09-06 16:56:02.130  3175  3175 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 16:56:02.130  3175  3175 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:02.130  3175  3175 I LgeMiscReceiver: networkInfo.isConnected() = false
09-06 16:56:02.134  7217  7217 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 16:56:02.135  7217  7217 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-06 16:56:02.139  6960  6960 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 16:56:02.151  7285  7285 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:2
,09-06 16:56:02.152  7285  7285 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 16:56:02.152  7285  7285 D Weather.Utils: 2 : All the weather widget is gone.
09-06 16:56:02.152  7285  7285 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 16:56:02.152  7285  7285 D WeatherAncestor: connectivity changed - connection : true
09-06 16:56:02.152  7285  7285 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1710d835
09-06 16:56:02.154  7285  7285 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 16:56:02.154  7285  7285 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 16:56:02.154  7285  7285 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 16:56:02.154  7285  7285 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 16:56:02.154  7285  7285 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:2
09-06 16:56:02.169  1033  2071 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-06 16:56:02.171  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 16:56:02.175  7074  7074 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-06 16:56:02.176  6457  6497 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 16:56:02.180  7074  7074 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-06 16:56:02.181  7074  7074 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,09-06 16:56:02.181  7074  7074 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 16:56:02.181  7074  7074 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 16:56:02.181  7074  7074 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 16:56:02.181  7074  7074 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 16:56:02.181  7074  7074 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 16:56:02.181  7074  7074 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 16:56:02.181  7074  7074 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 16:56:02.181  7074  7074 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 16:56:02.182  7074  7074 I BluetoothA2dpServiceJni: classInitNative
09-06 16:56:02.182  7074  7074 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 16:56:02.182  7074  7074 D A2dpStateMachine: make
09-06 16:56:02.184  7074  7074 I bluedroid-qcom: get_profile_interface a2dp
09-06 16:56:02.184  7074  7615 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 16:56:02.187  7074  7074 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-06 16:56:02.187  7074  7074 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-06 16:56:02.189  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:02.189  2188  2188 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:02.190  7074  7614 D A2dpStateMachine: Enter Disconnected: -2
09-06 16:56:02.190  7074  7074 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 16:56:02.194  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 16:56:02.194  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:02.194  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 16:56:02.194  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 16:56:02.196  7074  7074 D HidService: Received start request. Starting profile...
09-06 16:56:02.196  7074  7074 I bluedroid-qcom: get_profile_interface hidhost
09-06 16:56:02.196  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:02.196  7151  7151 I AppUp4:CustModeStarterReceiver: onReceive
09-06 16:56:02.196  7074  7074 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 16:56:02.200  7074  7074 D HealthService: Received start request. Starting profile...
09-06 16:56:02.201  7074  7074 I bluedroid-qcom: get_profile_interface health
09-06 16:56:02.201  7074  7074 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-06 16:56:02.201  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:02.202  7151  7151 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@29abb71f
09-06 16:56:02.202  7074  7074 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-06 16:56:02.202  7151  7151 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 16:56:02.202  7151  7151 D AppUp4:CustFacade: isPhone : true
09-06 16:56:02.202  7151  7151 D AppUp4:CustModeStarterReceiver: begin check event
09-06 16:56:02.203  7151  7151 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 16:56:02.204  7074  7074 D PanService: Received start request. Starting profile...
09-06 16:56:02.204  7074  7074 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 16:56:02.204  7074  7074 I bluedroid-qcom: get_profile_interface pan
09-06 16:56:02.205  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:02.205  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 16:56:02.206  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 16:56:02.209  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 16:56:02.209  7074  7074 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,09-06 16:56:02.209  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:02.210  7074  7074 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-06 16:56:02.215  4759  7621 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:02.215  4759  7621 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 16:56:02.215  7074  7074 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 16:56:02.216  7074  7074 D BtGatt.GattService: Received start request. Starting profile...
09-06 16:56:02.216  7074  7074 D BtGatt.GattService: start()
09-06 16:56:02.216  7074  7074 I bluedroid-qcom: get_profile_interface gatt
09-06 16:56:02.216  4759  7620 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 16:56:02.216  7184  7184 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 16:56:02.217  7074  7074 D BtGatt.AdvertiseManager: advertise manager created
09-06 16:56:02.222  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:02.223  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
,09-06 16:56:02.224  7074  7074 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-06 16:56:02.225  7074  7074 V BluetoothMapService: BluetoothMapBinder()
09-06 16:56:02.226  7074  7074 D BluetoothMapService: Received start request. Starting profile...
09-06 16:56:02.226  7074  7074 D BluetoothMapService: start()
09-06 16:56:02.230  7074  7074 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-06 16:56:02.230  7074  7074 D BluetoothMapEmailAppObserver: createReceiver()
09-06 16:56:02.233  7074  7074 D BluetoothMapEmailAppObserver: initObservers()
09-06 16:56:02.233  7074  7074 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-06 16:56:02.241  7184  7624 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 16:56:02.244  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:02.244  7074  7074 D HeadsetStateMachine: Proxy object connected
09-06 16:56:02.245  7074  7074 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-06 16:56:02.245  7074  7074 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-06 16:56:02.250  7074  7074 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 16:56:02.250  7074  7592 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-06 16:56:02.251  7074  7592 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 16:56:02.251  3175  3175 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 16:56:02.251  3175  3175 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:02.251  7074  7592 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-06 16:56:02.252  3175  3175 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-06 16:56:02.254  7074  7074 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 16:56:02.259  7074  7074 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 16:56:02.260  7050  7626 W FormManager: Network not available. Please check & try again.
09-06 16:56:02.262  7217  7217 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-06 16:56:02.263  7074  7074 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 16:56:02.263  7074  7074 V PanService: [BTUI] SIM Extra State :ABSENT
09-06 16:56:02.263  7217  7217 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 16:56:02.265  7050  7627 V FormManager: Network unavailable.
,09-06 16:56:02.266  7074  7074 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 16:56:02.270  7074  7074 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,09-06 16:56:02.270  7074  7074 V BluetoothMapService: Handler(): got msg=1
09-06 16:56:02.271  7074  7565 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-06 16:56:02.271  7074  7565 I bluedroid-qcom: enable
09-06 16:56:02.272  7074  7629 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-06 16:56:02.272  7074  7565 I bt_hci_bdroid: init
09-06 16:56:02.273  7050  7627 V FormManager: Network unavailable.
09-06 16:56:02.274  7074  7565 I bt_vendor: bt-vendor : init
09-06 16:56:02.274  7074  7565 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 16:56:02.274  7074  7565 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 16:56:02.274  7074  7565 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-06 16:56:02.274  7074  7565 D bt_userial_mct: userial_init
09-06 16:56:02.272  7074  7629 I bt-btu  : btu_task pending for preload complete event
09-06 16:56:02.274  7074  7565 D bt_hci_bdroid: set_power 1
09-06 16:56:02.275  7074  7565 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 16:56:02.275  7074  7565 I bt_vendor: Starting hciattach daemon
09-06 16:56:02.275  7074  7565 I bt_vendor: try to set true
09-06 16:56:02.275  7285  7285 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:2
09-06 16:56:02.277  7074  7074 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:02.263  7632  7632 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:02.263  7632  7632 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:02.280  7285  7285 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 16:56:02.280  7285  7285 D Weather.Utils: 2 : All the weather widget is gone.
09-06 16:56:02.280  7074  7074 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 16:56:02.280  7074  7074 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 16:56:02.280  7074  7074 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 16:56:02.280  7074  7074 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:02.280  7074  7074 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-06 16:56:02.280  7285  7285 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 16:56:02.280  7285  7285 D WeatherAncestor: connectivity changed - connection : true
09-06 16:56:02.280  7285  7285 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1710d835
09-06 16:56:02.282  7285  7285 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 16:56:02.282  7285  7285 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 16:56:02.282  7285  7285 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 16:56:02.282  7285  7285 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 16:56:02.282  7285  7285 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:2
09-06 16:56:02.304  7633  7633 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-06 16:56:02.390  7639  7639 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 16:56:02.407  7640  7640 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 16:56:02.441  7642  7642 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 16:56:02.455  7643  7643 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-06 16:56:02.469  7644  7644 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 16:56:02.496  7645  7645 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-06 16:56:02.523  7647  7647 I libmdmdetect: ESOC framework not supported
09-06 16:56:02.525  7647  7647 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-06 16:56:02.537  7647  7647 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-06 16:56:02.537  7647  7647 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-06 16:56:02.537  7647  7647 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-06 16:56:02.537  7647  7647 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,09-06 16:56:02.537  7647  7647 D bthci_qcomm_common: [BTUI]     LE: Class 2
,09-06 16:56:02.537  7647  7647 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,09-06 16:56:02.537  7647  7647 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-06 16:56:02.585  7647  7648 E QC-QMI  : qmi_client [7647] 14: failed to locate client data
,09-06 16:56:02.586   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-06 16:56:02.587   484   484 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-06 16:56:02.649  7652  7652 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-06 16:56:02.662  7656  7656 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-06 16:56:02.694  7074  7565 I bt_vendor: bluetooth satus is on
09-06 16:56:02.694  7074  7565 D bt_hci_bdroid: preload
,09-06 16:56:02.695  7074  7631 D bt_userial_mct: userial_open(port:0)
09-06 16:56:02.695  7074  7631 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-06 16:56:02.698  7074  7631 I bt_vendor: Done intiailizing UART
,09-06 16:56:02.701  7074  7631 I bt_vendor: Done intiailizing UART
09-06 16:56:02.701  7074  7631 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-06 16:56:02.701  7074  7631 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 16:56:02.701  7074  7629 I bt-btu  : btu_task received preload complete event
09-06 16:56:02.702  7074  7658 D bt_userial_mct: Entering userial_read_thread()
09-06 16:56:02.702  7074  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-06 16:56:02.702  7074  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-06 16:56:02.704  7074  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_HCI
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 16:56:02.707  7074  7629 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 16:56:02.759  7074  7629 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-06 16:56:02.761  7074  7629 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0214061 
09-06 16:56:02.761  7074  7629 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0214061 
,09-06 16:56:02.785  7074  7569 E bt-btif : Calling BTA_HhEnable
09-06 16:56:02.785  7074  7569 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,09-06 16:56:02.786  7074  7569 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-06 16:56:02.787  7074  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,09-06 16:56:02.787  7074  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-06 16:56:02.787  7074  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-06 16:56:02.788  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 16:56:02.790  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 16:56:02.790  7074  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-06 16:56:02.790  7074  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-06 16:56:02.791  7074  7569 D BluetoothAdapterProperties: Name is: G3
,09-06 16:56:02.795  7074  7569 D BluetoothAdapterProperties: Scan Mode:20
09-06 16:56:02.795  7074  7569 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 16:56:02.796  7074  7569 D bt_hci_bdroid: postload
09-06 16:56:02.797  7074  7569 D bte_conf: Device ID record 1 : primary
09-06 16:56:02.797  7074  7569 D bte_conf:   vendorId            = 00c4
09-06 16:56:02.797  7074  7569 D bte_conf:   vendorIdSource      = 0001
09-06 16:56:02.797  7074  7569 D bte_conf:   product             = 13a1
09-06 16:56:02.797  7074  7569 D bte_conf:   version             = 1000
09-06 16:56:02.798  7074  7569 D bte_conf:   clientExecutableURL = 
09-06 16:56:02.798  7074  7569 D bte_conf:   serviceDescription  = 
09-06 16:56:02.798  7074  7569 D bte_conf:   documentationURL    = 
09-06 16:56:02.798  7074  7569 D bte_conf: bte_load_did_conf no section named DID2.
09-06 16:56:02.804  7074  7565 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-06 16:56:02.807  7074  7565 D BluetoothAdapterProperties: ScanMode =  20
,09-06 16:56:02.807  7074  7565 D BluetoothAdapterProperties: State =  11
09-06 16:56:02.807  7074  7565 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-06 16:56:02.807  7074  7565 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-06 16:56:02.808  7074  7565 D BluetoothAdapterProperties: Setting state to 12
09-06 16:56:02.808  7074  7565 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 16:56:02.793  7660  7660 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:02.803  7660  7660 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:02.811  7074  7569 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 16:56:02.814  1033  1095 D BluetoothManagerService: Message: 60
09-06 16:56:02.814  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-06 16:56:02.814  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-06 16:56:02.814  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 16:56:02.815  7074  7658 E bt_mct  : hci lib postload completed
09-06 16:56:02.821  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:02.821  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:02.821  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:56:02.821  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:02.821  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:02.821  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:02.821  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:02.821  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:02.826  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:56:02.827  7074  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-06 16:56:02.827  7074  7565 I BluetoothAdapterState: Entering On State
09-06 16:56:02.831  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:02.831  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:02.831  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:56:02.831  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:02.831  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:02.831  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:02.831  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:02.831  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:56:02.833  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:56:02.839  1033  1033 D BluetoothA2dp: Proxy object connected
09-06 16:56:02.842  7074  7629 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 16:56:02.842  7074  7629 W bt-smp  : Plain text(LSB ~ MSB) = 15 9b 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 16:56:02.842  7074  7629 W bt-smp  : Encrypted text(LSB ~ MSB) = 23 98 cb 18 5a 9c e6 02 bb d9 5d 54 0e e8 33 00 
09-06 16:56:02.842  7074  7629 W bt-btm  : Stopping oneshot timer
09-06 16:56:02.846  1854  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 16:56:02.847  7074  7565 D LGBluetoothServiceAdapter: [BTUI] OnState
09-06 16:56:02.847  7074  7565 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-06 16:56:02.847  7074  7565 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-06 16:56:02.848  7074  7565 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,09-06 16:56:02.857  7074  7569 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 16:56:02.859  7074  7569 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-06 16:56:02.859  7074  7569 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 16:56:02.859  1854  1854 D BluetoothHeadset: Proxy object connected
09-06 16:56:02.860  1854  1870 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 16:56:02.862  1854  1854 D BluetoothHeadset: Proxy object connected
09-06 16:56:02.864  6960  6975 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 16:56:02.870  6960  6976 D BluetoothMap: onBluetoothStateChange: up=true
09-06 16:56:02.874  7074  7629 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 16:56:02.874  7074  7629 W bt-smp  : Plain text(LSB ~ MSB) = 99 8d 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 16:56:02.874  7074  7629 W bt-smp  : Encrypted text(LSB ~ MSB) = 76 c4 eb 25 29 b1 02 b5 3b 42 d5 32 9b c7 f9 00 
09-06 16:56:02.875  1854  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 16:56:02.875  7074  7629 W bt-btm  : Stopping oneshot timer
,09-06 16:56:02.879  1854  1854 D BluetoothHeadset: Proxy object connected
09-06 16:56:02.879  7074  7565 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-06 16:56:02.882  6960  6960 D BluetoothInputDevice: Proxy object connected
09-06 16:56:02.882  6960  6960 D HidProfile: Bluetooth service connected
09-06 16:56:02.882  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 16:56:02.884  1033  1033 D BluetoothHeadset: Proxy object connected
09-06 16:56:02.884  6960  6975 D BluetoothPan: onBluetoothStateChange on: true
09-06 16:56:02.884  6960  6975 D BluetoothPan: onBluetoothStateChange call bindService
09-06 16:56:02.889  6960  6976 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 16:56:02.891  6960  6960 D BluetoothMap: Proxy object connected
09-06 16:56:02.891  6960  6960 D MapProfile: Bluetooth service connected
09-06 16:56:02.891  6960  6960 D BluetoothMap: getConnectedDevices()
,09-06 16:56:02.892  7074  7663 V BluetoothMapService: getConnectedDevices()
09-06 16:56:02.893  6960  6960 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 16:56:02.893  6960  6960 D PanProfile: Bluetooth service connected
09-06 16:56:02.897  1033  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-06 16:56:02.897  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-06 16:56:02.899  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-06 16:56:02.899  1033  1095 D BluetoothManagerService: Message: 40
09-06 16:56:02.899  7666  7666 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-06 16:56:02.900  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-06 16:56:02.903  7074  7629 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 16:56:02.903  7074  7629 W bt-smp  : Plain text(LSB ~ MSB) = 4f 76 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 16:56:02.903  7074  7629 W bt-smp  : Encrypted text(LSB ~ MSB) = d2 9b d0 ad be 63 21 3e c4 35 4d 7f ff 5b 52 5c 
09-06 16:56:02.903  7074  7629 W bt-btm  : Stopping oneshot timer
09-06 16:56:02.904  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 16:56:02.904  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:02.905  1942  2142 D LGBluetoothAPIService: Message: 1
09-06 16:56:02.905  1942  2142 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,09-06 16:56:02.911  6729  6729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-06 16:56:02.913  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:02.914  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:02.916  7074  7629 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 16:56:02.916  7074  7629 W bt-smp  : Plain text(LSB ~ MSB) = a6 e0 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 16:56:02.916  7074  7629 W bt-smp  : Encrypted text(LSB ~ MSB) = 5b 26 c5 dd cc d1 46 8b b1 58 f2 36 ff f0 6e f8 
09-06 16:56:02.916  7074  7629 W bt-btm  : Stopping oneshot timer
09-06 16:56:02.919  7074  7074 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:02.919  7074  7074 D BluetoothMapService: STATE_ON
09-06 16:56:02.923  1942  2142 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-06 16:56:02.923  6960  6960 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-06 16:56:02.928  1033  1095 D BluetoothManagerService: Message: 30
09-06 16:56:02.930  6960  6960 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-06 16:56:02.932  7074  7629 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 16:56:02.932  7074  7629 W bt-smp  : Plain text(LSB ~ MSB) = be 10 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 16:56:02.932  7074  7629 W bt-smp  : Encrypted text(LSB ~ MSB) = 35 d8 07 c2 c4 39 bd 97 63 0e 4a 6f 80 bb 9e 21 
09-06 16:56:02.932  7074  7629 W bt-btm  : Stopping oneshot timer
09-06 16:56:02.933  1033  1095 D BluetoothManagerService: Message: 30
09-06 16:56:02.937  6960  6960 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,09-06 16:56:02.939  6960  6960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 16:56:02.942  6960  6960 D BluetoothA2dp: Proxy object connected
09-06 16:56:02.942  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:02.942  7074  7074 V BluetoothPbapService: Pbap Service onCreate
09-06 16:56:02.942  7074  7074 V BluetoothPbapService: Starting PBAP service
09-06 16:56:02.943  6960  6960 D A2dpProfile: Bluetooth service connected
09-06 16:56:02.944  7074  7074 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-06 16:56:02.944  7074  7074 V BluetoothMapService: Handler(): got msg=1
09-06 16:56:02.944  7074  7074 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-06 16:56:02.945  7074  7074 V BluetoothPbapService: Pbap Service onBind
09-06 16:56:02.946  7074  7074 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:02.946  7074  7074 V BluetoothPbapService: state: 12
09-06 16:56:02.946  6960  6960 D BluetoothHeadset: Proxy object connected
09-06 16:56:02.947  6960  6960 D HeadsetProfile: Bluetooth service connected
09-06 16:56:02.947  7074  7074 D LGBluetoothAPIServer: [BTUI] onCreate()
09-06 16:56:02.948  7074  7074 D LGBluetoothAPIServer: [BTUI] onBind()
09-06 16:56:02.948  7074  7679 D BluetoothMapMasInstance: MAS initSocket()
09-06 16:56:02.949  7074  7679 D BluetoothMapMasInstance:   masId = 00
09-06 16:56:02.949  7074  7679 D BluetoothMapMasInstance:   msgTypes = 0e
09-06 16:56:02.949  7074  7679 D BluetoothMapMasInstance:   masName = SMS/MMS
09-06 16:56:02.949  7074  7679 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-06 16:56:02.955  1033  1713 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 16:56:02.958  7074  7679 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 16:56:02.959  7074  7679 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-06 16:56:02.959  7074  7679 V BluetoothMapMasInstance: Succeed to create listening socket 
09-06 16:56:02.959  7074  7679 D BluetoothMapMasInstance: Accepting socket connection...
09-06 16:56:03.069  1033  1940 I art     : Explicit concurrent mark sweep GC freed 94017(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 4.317ms total 120.862ms
,09-06 16:56:03.070  7074  7074 V BluetoothPbapService: Handler(): got msg=1
09-06 16:56:03.070  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-06 16:56:03.070  1942  2142 D LGBluetoothAPIService: Message: 100
09-06 16:56:03.070  1942  2142 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-06 16:56:03.072  7074  7569 D BluetoothAdapterProperties: Scan Mode:21
09-06 16:56:03.072  7074  7569 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-06 16:56:03.075  7074  7074 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-06 16:56:03.076  7074  7074 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 16:56:03.076  7074  7681 V BluetoothPbapService: Pbap Service initSocket
09-06 16:56:03.076  7074  7074 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:03.076  7074  7074 V BluetoothPbapReceiver: ***********state = 12
09-06 16:56:03.077  1033  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:03.081  7074  7681 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 16:56:03.084  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 16:56:03.084  7074  7681 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-06 16:56:03.084  7074  7681 V BluetoothPbapService: Succeed to create listening socket 
09-06 16:56:03.084  7074  7681 V BluetoothPbapService: Accepting socket connection...
09-06 16:56:03.084  2188  2188 D c       : Getting all permits...
09-06 16:56:03.084  2188  2188 D a       : Opening database...
09-06 16:56:03.088  6960  6960 D DockEventReceiver: finishStartingService: stopping service
09-06 16:56:03.088  2188  2188 D a       : Opening database auth.proximity.permit_store...
09-06 16:56:03.089  6960  6960 D BluetoothPbap: Proxy object connected
09-06 16:56:03.089  6960  6960 D PbapServerProfile: Bluetooth service connected
09-06 16:56:03.089  2188  2188 D a       : Closing database...
09-06 16:56:03.092  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:03.093  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:03.100  6960  6960 D BluetoothPermissionRequest: onReceive
,09-06 16:56:03.101  6960  6960 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 16:56:03.102  6960  6960 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 16:56:03.107  7074  7074 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-06 16:56:03.108  7074  7074 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-06 16:56:03.113  7074  7074 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-06 16:56:03.132  7074  7074 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 16:56:03.132  7074  7074 V BtOppService: onCreate
,09-06 16:56:03.136  7074  7074 V BluetoothOppNotification: send message
09-06 16:56:03.139  7074  7074 V BtOppService: Starting RfcommListener
09-06 16:56:03.148  7074  7074 D BluetoothOppPreference: Dumping Names:  
09-06 16:56:03.149  7074  7074 D BluetoothOppPreference: {}
09-06 16:56:03.149  7074  7074 D BluetoothOppPreference: Dumping Channels:  
09-06 16:56:03.149  7074  7074 D BluetoothOppPreference: {}
,09-06 16:56:03.154  7074  7074 V BtOppService: onStartCommand
,09-06 16:56:03.155  7074  7684 V BtOppService: Deleted complete outbound shares, number =  0
09-06 16:56:03.157  7074  7684 V BtOppService: Deleted complete inbound failed shares, number = 0
09-06 16:56:03.158  7074  7074 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:03.158  7074  7074 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 16:56:03.159  7074  7684 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-06 16:56:03.160  7074  7684 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c0c97a6 on behalf of 
09-06 16:56:03.161  7074  7074 V BluetoothOppNotification: new notify threadi!
09-06 16:56:03.161  7074  7687 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 16:56:03.162  7074  7074 V BluetoothOppNotification: send delay message
09-06 16:56:03.162  7074  7687 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-06 16:56:03.164  7074  7074 V BtOppService: start RfcommListener
09-06 16:56:03.166  7074  7687 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7f555e7 on behalf of 
09-06 16:56:03.166  7074  7688 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-06 16:56:03.167  7074  7687 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-06 16:56:03.167  7074  7074 V BtOppService: RfcommListener started
09-06 16:56:03.168  7074  7074 V BtOppService: ContentObserver received notification
09-06 16:56:03.169  7074  7689 V BtOppRfcommListener: Starting RFCOMM listener....
09-06 16:56:03.169  7074  7688 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b4c2594 on behalf of 
09-06 16:56:03.169  7074  7074 V BtOppService: ContentObserver received notification
09-06 16:56:03.170  1033  1742 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:03.171  7074  7689 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 16:56:03.171  7074  7688 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 16:56:03.172  7074  7689 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-06 16:56:03.172  7074  7689 V BtOppRfcommListener: Started RFCOMM listener....
09-06 16:56:03.173  7074  7689 I BtOppRfcommListener: Accept thread started.
09-06 16:56:03.173  7074  7689 V BtOppRfcommListener: Accepting connection...
09-06 16:56:03.173  7074  7688 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 16:56:03.173  7074  7690 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 16:56:03.174  7074  7690 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-06 16:56:03.177  7074  7690 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1757483d on behalf of 
09-06 16:56:03.177  7074  7688 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@245a8832 on behalf of 
09-06 16:56:03.179  7074  7690 V BluetoothOppNotification: update too frequent, put in queue
09-06 16:56:03.180  7074  7688 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 16:56:03.181  7074  7690 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-06 16:56:03.182  7074  7688 V BluetoothOppNotification: outbound notification was removed.
09-06 16:56:03.182  7074  7688 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 16:56:03.184  7074  7688 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18b76983 on behalf of 
09-06 16:56:03.185  7074  7688 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 16:56:03.186  7074  7688 V BluetoothOppNotification: inbound notification was removed.
09-06 16:56:03.186  7074  7688 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-06 16:56:03.187  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:03.187  7074  7074 V BluetoothFtpService: Ftp Service onCreate
09-06 16:56:03.187  7074  7074 I BluetoothFtpService: Ftp Service onCreate
09-06 16:56:03.187  7074  7074 V BluetoothFtpService: Ftp Service onStartCommand
09-06 16:56:03.187  7074  7074 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:03.188  7074  7074 V BluetoothFtpService: Starting Listening on sockets
09-06 16:56:03.188  7074  7074 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 16:56:03.188  7074  7074 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 16:56:03.188  7074  7074 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 16:56:03.188  7074  7074 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:03.188  7074  7688 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17752b39 on behalf of 
09-06 16:56:03.188  7074  7074 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-06 16:56:03.189  7074  7074 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 16:56:03.191  7074  7074 V BluetoothFtpService: Handler(): got msg=1
09-06 16:56:03.192  7074  7074 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-06 16:56:03.192  7074  7074 V BluetoothFtpService: Ftp Service initSocket
09-06 16:56:03.196  1033  1713 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:03.197  7074  7074 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 16:56:03.198  7074  7074 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
,09-06 16:56:03.198  7074  7074 V BluetoothFtpService: Succeed to create listening socket on channel 20
,09-06 16:56:03.200  7074  7691 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-06 16:56:03.224  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:03.224  7074  7074 V BluetoothSapService: Sap Service onCreate
,09-06 16:56:03.226  7074  7074 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:03.226  7074  7074 V BluetoothSapService: state: 12
09-06 16:56:03.226  7074  7074 V BluetoothSapService: Starting SAP server process
09-06 16:56:03.229  7074  7074 V BluetoothSapService: SAP Service startRfcommListenerThread
09-06 16:56:03.223  7693  7693 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:03.231  7074  7694 V BluetoothSapService: Sap Service initRfcommSocket
,09-06 16:56:03.232  1033  1742 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:03.223  7693  7693 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:03.233  7074  7694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 16:56:03.235  7074  7694 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-06 16:56:03.235  7074  7694 V BluetoothSapService: Succeed to create listening socket 
09-06 16:56:03.235  7074  7694 V BluetoothSapService: Accepting socket connection...
09-06 16:56:03.244  7693  7693 V BT_SAP  : Event pipe created
09-06 16:56:03.244  7693  7693 V BT_SAP  : create_server_socket qcom.sap.server
,09-06 16:56:03.244  7693  7693 V BT_SAP  : created socket fd 6
,09-06 16:56:03.413  7312  7372 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-06 16:56:03.752  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 16:56:03.752  1033  1536 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 16:56:03.941  1033  1537 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-06 16:56:03.942  1033  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-06 16:56:04.164  7074  7074 V BluetoothOppNotification: new notify threadi!
,09-06 16:56:04.164  7074  7074 V BluetoothOppNotification: send delay message
,09-06 16:56:04.179  7074  7706 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-06 16:56:04.181  7074  7706 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6f441f5 on behalf of 
09-06 16:56:04.183  7074  7706 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 16:56:04.193  1033  1941 I ActivityManager: Killing 7494:com.lge.bnr/1000 (adj 15): empty #17
,09-06 16:56:04.207  7074  7706 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-06 16:56:04.218  7074  7706 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a96eb8a on behalf of 
09-06 16:56:04.219  7074  7706 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-06 16:56:04.223  7074  7706 V BluetoothOppNotification: outbound notification was removed.
09-06 16:56:04.223  7074  7706 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 16:56:04.225  7074  7706 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4c285fb on behalf of 
09-06 16:56:04.225  7074  7706 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 16:56:04.227  7074  7706 V BluetoothOppNotification: inbound notification was removed.
09-06 16:56:04.227  7074  7706 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 16:56:04.230  7074  7706 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26c7b618 on behalf of 
09-06 16:56:04.233  1033  1741 W libprocessgroup: failed to open /acct/uid_1000/pid_7494/cgroup.procs: No such file or directory
,09-06 16:56:04.477  1033  1742 I ActivityManager: Killing 6979:com.lge.sync/1000 (adj 15): empty #17
,09-06 16:56:04.500  1033  1542 D WifiService: Client connection lost with reason: 4
,09-06 16:56:04.511  1033  1740 W libprocessgroup: failed to open /acct/uid_1000/pid_6979/cgroup.procs: No such file or directory
,09-06 16:56:04.722  1033  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 16:56:04.722  1033  1941 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1e985a2f mBinding = false
,09-06 16:56:04.748  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-06 16:56:04.750  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 16:56:04.750  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-06 16:56:04.752  1033  1095 D BluetoothManagerService: Message: 2
09-06 16:56:04.752  1033  1095 D BluetoothManagerService: Sending off request.
09-06 16:56:04.753  7074  7092 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-06 16:56:04.754  7074  7565 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-06 16:56:04.754  7074  7565 D BluetoothAdapterProperties: Setting state to 13
09-06 16:56:04.754  7074  7565 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 16:56:04.755  7074  7565 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 16:56:04.755  7074  7565 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-06 16:56:04.757  7074  7569 D BluetoothAdapterProperties: Scan Mode:20
09-06 16:56:04.759  7074  7565 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 16:56:04.761  7074  7565 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 16:56:04.765  7074  7681 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 16:56:04.766  7074  7689 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 16:56:04.766  7074  7691 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 16:56:04.767  7074  7694 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 16:56:04.767  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-06 16:56:04.767  7074  7629 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-06 16:56:04.769  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 16:56:04.769  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 16:56:04.769  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 16:56:04.769  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 16:56:04.769  7074  7629 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:56:04.769  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 16:56:04.769  7074  7629 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:56:04.769  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 16:56:04.769  7074  7629 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 16:56:04.769  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-06 16:56:04.769  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-06 16:56:04.769  7074  7629 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 16:56:04.770  7074  7679 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-06 16:56:04.770  7074  7679 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 16:56:04.770  7074  7679 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-06 16:56:04.770  7074  7679 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-06 16:56:04.770  7074  7679 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-06 16:56:04.770  7074  7679 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-06 16:56:04.770  7074  7679 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-06 16:56:04.770  7074  7679 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-06 16:56:04.776  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:56:04.776  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:04.776  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:04.776  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:56:04.776  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:04.776  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:56:04.776  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:04.776  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:04.776  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:04.787  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 16:56:04.787  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:56:04.793  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:56:04.793  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:04.793  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:04.793  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:56:04.793  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:04.793  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:56:04.793  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:04.793  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:04.793  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:04.799  6729  6729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:56:04.799  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:56:04.800  1033  1095 D BluetoothManagerService: Message: 60
09-06 16:56:04.800  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-06 16:56:04.800  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-06 16:56:04.802  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:04.804  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 16:56:04.811  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:04.815  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:04.817  7074  7074 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:04.817  7074  7074 D BluetoothMapService: STATE_TURNING_OFF
09-06 16:56:04.817  7074  7074 V BluetoothMapService: Handler(): got msg=4
09-06 16:56:04.818  7074  7074 D BluetoothMapService: MAP Service closeService in
09-06 16:56:04.818  7074  7074 D BluetoothMapMasInstance: MAP Service shutdown
09-06 16:56:04.818  7074  7074 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 16:56:04.819  7074  7074 V BluetoothMapService: MAP Service closeService out
09-06 16:56:04.820  7074  7074 V BtOppService: Receiver DISABLED_ACTION 
09-06 16:56:04.820  7074  7074 I BtOppRfcommListener: stopping Accept Thread
09-06 16:56:04.820  7074  7074 V BtOppRfcommListener: close mBtServerSocket
09-06 16:56:04.820  7074  7689 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 16:56:04.821  7074  7074 V BtOppRfcommListener: waiting for thread to terminate
09-06 16:56:04.821  7074  7074 V BtOppRfcommListener: done waiting for thread to terminate
09-06 16:56:04.828  6960  6960 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,09-06 16:56:04.835  6960  6960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 16:56:04.836  7074  7074 V BtOppService: onDestroy
09-06 16:56:04.838  7074  7074 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-06 16:56:04.843  7074  7074 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 16:56:04.843  7074  7074 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:04.843  7074  7074 V BluetoothPbapReceiver: ***********state = 13
,09-06 16:56:04.847  7074  7074 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-06 16:56:04.849  7074  7074 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:04.849  7074  7074 V BluetoothPbapService: state: 13
09-06 16:56:04.849  7074  7074 V BluetoothPbapService: Pbap Service closeService in
09-06 16:56:04.852  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 16:56:04.855  7074  7074 V BluetoothPbapService: successfully stopped pbap service
09-06 16:56:04.855  7074  7074 V BluetoothPbapService: Pbap Service closeService out
,09-06 16:56:04.858  7074  7074 V BluetoothPbapService: Pbap Service onDestroy
09-06 16:56:04.858  7074  7074 V BluetoothPbapService: Pbap Service closeService in
09-06 16:56:04.858  7074  7074 V BluetoothPbapService: Pbap Service closeService out
09-06 16:56:04.858  7074  7074 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-06 16:56:04.873  6960  6960 D DockEventReceiver: finishStartingService: stopping service
,09-06 16:56:04.876  6960  6960 D BluetoothPbap: Proxy object disconnected
09-06 16:56:04.876  6960  6960 D PbapServerProfile: Bluetooth service disconnected
09-06 16:56:04.882  6960  6960 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-06 16:56:04.893  6960  6960 D BluetoothPermissionRequest: onReceive
09-06 16:56:04.893  6960  6960 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-06 16:56:04.899  6960  6960 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-06 16:56:04.905  7074  7074 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-06 16:56:04.905  7074  7074 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-06 16:56:04.906  7074  7074 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-06 16:56:04.921  7074  7074 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:04.921  7074  7074 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 16:56:04.923  7074  7074 V BluetoothFtpService: Ftp Service onStartCommand
09-06 16:56:04.923  7074  7074 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:04.924  7074  7074 V BluetoothFtpService: Ftp Service closeService
09-06 16:56:04.924  7074  7074 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-06 16:56:04.929  7074  7074 V BluetoothFtpService: successfully stopped ftp service
09-06 16:56:04.930  7074  7074 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 16:56:04.930  7074  7074 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 16:56:04.930  7074  7074 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 16:56:04.930  7074  7074 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:04.930  7074  7074 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-06 16:56:04.931  7074  7074 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-06 16:56:04.935  7074  7074 V BluetoothFtpService: Ftp Service onDestroy,
09-06 16:56:04.935  7074  7074 V BluetoothFtpService: Ftp Service closeService
09-06 16:56:04.941  7074  7074 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:04.941  7074  7074 V BluetoothSapService: state: 13
09-06 16:56:04.941  7074  7074 V BluetoothSapService: Stopping SAP server process
09-06 16:56:04.944  7074  7074 V BluetoothSapService: Sap Service closeSapService in
09-06 16:56:04.946  7074  7074 V BluetoothSapService: Close listen Socket : 
09-06 16:56:04.946  7074  7074 V BluetoothSapService: Close rfcomm Socket : 
09-06 16:56:04.946  7074  7074 V BluetoothSapService: Close sapd  Socket : 
,09-06 16:56:04.949  7074  7074 V BluetoothSapService: Sap Service closeSapService out
,09-06 16:56:04.949  7074  7074 V BluetoothSapService: Sap Service onDestroy
,09-06 16:56:04.949  7074  7074 V BluetoothSapService: Sap Service closeSapService in
,09-06 16:56:04.949  7074  7074 V BluetoothSapService: Close listen Socket : 
,09-06 16:56:04.949  7074  7074 V BluetoothSapService: Close rfcomm Socket : 
,09-06 16:56:04.949  7074  7074 V BluetoothSapService: Close sapd  Socket : ,
09-06 16:56:04.950  7074  7074 V BluetoothSapService: Sap Service closeSapService out,
09-06 16:56:05.712  7074  7569 D bt_hci_bdroid: cleanup,
,09-06 16:56:05.729  7074  7658 I bt_userial_mct: exiting userial_read_thread
09-06 16:56:05.729  7074  7658 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 16:56:05.731  7074  7631 I bt_lpm  : LPM is already off!!!
09-06 16:56:05.731  7074  7629 W bt-btif : ag scb idx 1 not allocated
09-06 16:56:05.731  7074  7629 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 16:56:05.731  7074  7629 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 16:56:05.731  7074  7629 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 16:56:05.732  7074  7569 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 16:56:05.732  7074  7631 I bt_vendor: hw_epilog_process
09-06 16:56:05.733  7074  7569 D bt_hci_bdroid: cleanup Finalizing cleanup
09-06 16:56:05.733  7074  7569 D bt_userial_mct: userial_close
09-06 16:56:05.733  7074  7569 E bt_userial_mct: pthread_join() FAILED result:3
09-06 16:56:05.733  7074  7569 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-06 16:56:05.739  7074  7569 D bt_hci_bdroid: set_power 0
09-06 16:56:05.739  7074  7569 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 16:56:05.739  7074  7569 I bt_vendor: bluetooth satus is on
09-06 16:56:05.739  7074  7569 I bt_vendor: bt-vendor : resetting BT status
09-06 16:56:05.739  7074  7569 I bt_vendor: Starting hciattach daemon
09-06 16:56:05.739  7074  7569 I bt_vendor: try to set false
,09-06 16:56:05.746  7074  7569 I bt_vendor: Starting hciattach daemon
09-06 16:56:05.746  7074  7569 I bt_vendor: try to set false
09-06 16:56:05.748  7074  7569 I bt_vendor: cleanup
09-06 16:56:05.749  7074  7629 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-06 16:56:05.750  7074  7569 I GKI_LINUX: GKI_exit_task 0 done
09-06 16:56:05.750  7074  7569 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 16:56:05.751  7074  7565 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 16:56:05.757  7074  7074 D HeadsetService: Received stop request...Stopping profile...
,09-06 16:56:05.764  7074  7565 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 16:56:05.765  7074  7074 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 16:56:05.765  7074  7074 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 16:56:05.765  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:05.766  7074  7592 D HeadsetStateMachine: Exit Disconnected: -1
09-06 16:56:05.769  1033  1033 D BluetoothHeadset: Proxy object disconnected
09-06 16:56:05.769  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 16:56:05.769  1854  1854 D BluetoothHeadset: Proxy object disconnected
09-06 16:56:05.769  1854  1854 D BluetoothHeadset: Proxy object disconnected
09-06 16:56:05.769  1854  1854 D BluetoothHeadset: Proxy object disconnected
,09-06 16:56:05.773  7074  7074 D A2dpService: Received stop request...Stopping profile...
09-06 16:56:05.774  7074  7614 D A2dpStateMachine: Exit Disconnected: -1
09-06 16:56:05.776  7074  7074 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-06 16:56:05.778  7074  7074 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-06 16:56:05.778  7074  7074 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 16:56:05.778  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:05.780  1033  1033 D BluetoothA2dp: Proxy object disconnected
09-06 16:56:05.780  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 16:56:05.780  7074  7074 D HidService: Received stop request...Stopping profile...
09-06 16:56:05.780  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:05.783  7074  7074 D HealthService: Received stop request...Stopping profile...
09-06 16:56:05.783  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
,09-06 16:56:05.788  7074  7074 D PanService: Received stop request...Stopping profile...
09-06 16:56:05.789  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:05.790  7074  7074 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 16:56:05.791  7074  7074 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 16:56:05.791  7074  7074 D BtGatt.GattService: stop()
09-06 16:56:05.791  7074  7074 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 16:56:05.793  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:05.794  7074  7074 D BluetoothMapService: Received stop request...Stopping profile...
09-06 16:56:05.794  7074  7074 D BluetoothMapService: stop()
09-06 16:56:05.795  7074  7074 D BluetoothMapEmailAppObserver: deinitObservers()
09-06 16:56:05.795  7074  7074 D BluetoothMapEmailAppObserver: removeReceiver()
,09-06 16:56:05.798  7074  7074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1710d835
09-06 16:56:05.799  7074  7074 D HeadsetStateMachine: Unbinding service...
09-06 16:56:05.801  7074  7074 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 16:56:05.801  7074  7074 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 16:56:05.801  7074  7074 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 16:56:05.801  7074  7074 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 16:56:05.801  7074  7074 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 16:56:05.801  7074  7074 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 16:56:05.801  7074  7074 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 16:56:05.802  7074  7074 I BluetoothA2dpServiceJni: cleanupNative
09-06 16:56:05.802  7074  7615 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 16:56:05.803  7074  7074 I GKI_LINUX: GKI_exit_task 2 done
09-06 16:56:05.803  7074  7074 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 16:56:05.803  7074  7074 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 16:56:05.803  7074  7074 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 16:56:05.803  7074  7074 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 16:56:05.804  7074  7074 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 16:56:05.804  7074  7074 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 16:56:05.804  7074  7074 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 16:56:05.804  7074  7074 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 16:56:05.807  7074  7074 V BluetoothMapService: Handler(): got msg=4
09-06 16:56:05.807  7074  7074 D BluetoothMapService: MAP Service closeService in
09-06 16:56:05.807  7074  7074 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 16:56:05.807  7074  7074 V BluetoothMapService: MAP Service closeService out
,09-06 16:56:05.812  7074  7565 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-06 16:56:05.812  7074  7565 D BluetoothAdapterProperties: Setting state to 10
09-06 16:56:05.812  7074  7565 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 16:56:05.814  7074  7074 D BluetoothMapService: cleanup()
09-06 16:56:05.814  7074  7074 D BluetoothMapService: MAP Service closeService in
09-06 16:56:05.814  7074  7074 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 16:56:05.814  7074  7074 V BluetoothMapService: MAP Service closeService out
09-06 16:56:05.816  1033  1095 D BluetoothManagerService: Message: 60
09-06 16:56:05.816  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-06 16:56:05.816  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-06 16:56:05.816  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 16:56:05.817  7074  7565 I BluetoothAdapterState: Entering OffState
09-06 16:56:05.817  1854  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 16:56:05.818  6960  6975 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 16:56:05.819  1854  4637 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 16:56:05.819  6960  6975 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 16:56:05.822  6960  6975 D BluetoothMap: onBluetoothStateChange: up=false
09-06 16:56:05.823  1854  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 16:56:05.824  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 16:56:05.825  6960  6975 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 16:56:05.825  6960  6975 D BluetoothPan: onBluetoothStateChange on: false
09-06 16:56:05.826  6960  6975 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 16:56:05.827  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-06 16:56:05.827  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-06 16:56:05.829  1033  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-06 16:56:05.829  1033  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-06 16:56:05.829  1033  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1e985a2f mBinding = false
09-06 16:56:05.830  1033  1095 D BluetoothManagerService: Sending unbind request.
09-06 16:56:05.834  7074  7569 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-06 16:56:05.837  7074  7074 I GKI_LINUX: GKI_exit_task 1 done
09-06 16:56:05.837  7074  7074 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 16:56:05.839  7074  7074 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 16:56:05.839  7074  7074 I art     : --- WEIRD: removing null entry 248
09-06 16:56:05.839  7074  7074 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-06 16:56:05.839  7074  7074 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-06 16:56:05.840  7074  7074 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-06 16:56:05.841  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-06 16:56:05.843  7074  7074 I art     : System.exit called, status: 0
09-06 16:56:05.843  7074  7074 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-06 16:56:05.863   323  1383 V AudioFlinger: 7074 died, releasing its sessions
09-06 16:56:05.863   323  1383 V AudioFlinger:  pid 1854 @ 0
09-06 16:56:05.863   323  1383 V AudioFlinger:  pid 3175 @ 1
09-06 16:56:05.863   323  1383 V AudioFlinger:  pid 3175 @ 2
,09-06 16:56:05.867  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-06 16:56:05.868  1942  2142 D LGBluetoothAPIService: Message: 101
09-06 16:56:05.868  1942  2142 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-06 16:56:05.870  1942  2142 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-06 16:56:05.871  1942  2142 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-06 16:56:05.873  6960  6960 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-06 16:56:06.019  1033  2014 I ActivityManager: Process com.android.bluetooth (pid 7074) has died,
,09-06 16:56:06.019  1033  2014 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
09-06 16:56:06.020  1033  2014 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
09-06 16:56:06.037  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:06.038  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-06 16:56:06.039  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:06.041  6960  6960 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-06 16:56:06.041  6960  6960 D LGBluetoothEventManager: [BTUI] clear device connection state
09-06 16:56:06.042  1942  2142 D LGBluetoothAPIService: Message: 2
09-06 16:56:06.042  1942  2142 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-06 16:56:06.042  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:06.051  6960  6960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-06 16:56:06.058  1600  1600 D BluetoothAdapter: 269373847: getState() :  mService = null. Returning STATE_OFF
09-06 16:56:06.058  1600  1600 D BluetoothAdapter: 269373847: getState() :  mService = null. Returning STATE_OFF
09-06 16:56:06.112  1033  1977 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7753 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-06 16:56:06.117  6960  6960 D DockEventReceiver: finishStartingService: stopping service
,09-06 16:56:06.204  7753  7753 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-06 16:56:06.205  7753  7753 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 16:56:06.205  7753  7753 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,09-06 16:56:06.206  7753  7753 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 16:56:06.228  7753  7753 D BluetoothAdapterApp: Loading JNI Library
,09-06 16:56:06.269  7753  7753 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@14a8567d Instance Count = 1
,09-06 16:56:06.277  7753  7753 D BluetoothAdapterApp: onCreate
,09-06 16:56:06.305  7753  7753 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,09-06 16:56:06.306  7753  7753 D ProfileConfigQcom: Adding HeadsetService
09-06 16:56:06.306  7753  7753 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-06 16:56:06.307  7753  7753 D ProfileConfigQcom: Adding A2dpService
09-06 16:56:06.307  7753  7753 D ProfileConfigQcom: [BTUI] HidService is supported
,09-06 16:56:06.308  7753  7753 D ProfileConfigQcom: Adding HidService
09-06 16:56:06.310  7753  7753 D ProfileConfigQcom: [BTUI] HealthService is supported
09-06 16:56:06.311  7753  7753 D ProfileConfigQcom: Adding HealthService
09-06 16:56:06.311  7753  7753 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,09-06 16:56:06.313  7753  7753 D ProfileConfigQcom: [BTUI] PanService is supported
,09-06 16:56:06.313  7753  7753 D ProfileConfigQcom: Adding PanService
,09-06 16:56:06.313  7753  7753 D ProfileConfigQcom: [BTUI] GattService is supported
09-06 16:56:06.314  7753  7753 D ProfileConfigQcom: Adding GattService
09-06 16:56:06.314  7753  7753 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,09-06 16:56:06.314  7753  7753 D ProfileConfigQcom: Adding BluetoothMapService
09-06 16:56:06.315  7753  7753 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-06 16:56:06.316  7753  7753 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-06 16:56:06.317  7753  7753 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:06.317  7753  7753 V BluetoothPbapReceiver: ***********state = 10
09-06 16:56:06.328  7753  7753 V LGMDMManagerInternal: Create singleton instance
,09-06 16:56:06.435  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 16:56:06.448  7753  7753 D LGBluetoothAPIServer: [BTUI] onCreate()
09-06 16:56:06.449  6960  6960 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-06 16:56:06.449  7753  7753 D LGBluetoothAPIServer: [BTUI] onBind()
,09-06 16:56:06.455  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-06 16:56:06.455  1942  2142 D LGBluetoothAPIService: Message: 100
09-06 16:56:06.455  1942  2142 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-06 16:56:06.462  6960  6960 D BluetoothPermissionRequest: onReceive
09-06 16:56:06.464  6960  6960 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 16:56:06.464  6960  6960 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,09-06 16:56:06.468  6960  6960 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 16:56:06.474  7753  7753 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-06 16:56:06.480  7753  7753 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:56:06.484  7753  7753 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-06 16:56:06.485  7753  7753 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,09-06 16:56:06.485  7753  7753 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 16:56:06.486  7753  7753 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:56:06.486  7753  7753 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-06 16:56:06.490  7026  7026 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-06 16:56:07.832  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop,
,09-06 16:56:07.832  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:56:08.283  1033  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 16:56:08.288  1600  1600 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
09-06 16:56:08.357  1033  1033 D administrator: Handling package changes for user 0
,09-06 16:56:08.376  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-06 16:56:08.394  1033  1091 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7782 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-06 16:56:08.401  1600  1600 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-06 16:56:08.402  1600  1600 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,09-06 16:56:08.484  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-06 16:56:08.491  7782  7782 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-06 16:56:08.533  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-06 16:56:08.533  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-06 16:56:08.585  7782  7782 D LgDataFeature: LgDataFeature() Constructor: none
09-06 16:56:08.586  7782  7782 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 16:56:08.593  1033  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 16:56:08.598  1033  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-06 16:56:08.605  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-06 16:56:08.605  2469  2469 V GmsNetworkLocationProvi: DISABLE
09-06 16:56:08.655  2469  2469 E GCoreFlp: Bound FusedProviderService with LocationManager
09-06 16:56:08.655  1033  1090 D LocationProviderProxy: applying state to connected service
,09-06 16:56:08.714  7782  7827 I Babel   : MmsConfig: mnc/mcc: 0/0
09-06 16:56:08.714  7782  7827 I Babel   : MmsConfig.loadMmsSettings
09-06 16:56:08.720  7782  7827 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-06 16:56:08.720  7782  7827 I Babel   : MmsConfig.loadFromDatabase
,09-06 16:56:08.737  7782  7827 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-06 16:56:08.737  7782  7827 I Babel   : MmsConfig.loadFromResources
09-06 16:56:08.739  7782  7827 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-06 16:56:08.739  7782  7827 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-06 16:56:08.754  7782  7782 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 16:56:08.775  7782  7825 W AudioCapabilities: Unsupported mime audio/evrc
09-06 16:56:08.778  7782  7825 W AudioCapabilities: Unsupported mime audio/qcelp
09-06 16:56:08.782  7782  7825 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-06 16:56:08.786  1818  7830 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-06 16:56:08.786  1818  7830 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-06 16:56:08.792  7151  7151 I AppUp4:CustModeStarterReceiver: onReceive
09-06 16:56:08.797  7151  7151 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@29abb71f
09-06 16:56:08.797  7151  7151 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 16:56:08.797  7151  7151 D AppUp4:CustFacade: isPhone : true
09-06 16:56:08.798  7151  7151 D AppUp4:CustModeStarterReceiver: begin check event
09-06 16:56:08.798  7151  7151 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,09-06 16:56:08.812  1818  5224 I Icing   : updateResources: need to parse e{com.google.android.gms}
,09-06 16:56:08.815  7782  7825 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-06 16:56:08.819  7782  7825 W AudioCapabilities: Unsupported mime audio/qcelp
09-06 16:56:08.821  7782  7825 W AudioCapabilities: Unsupported mime audio/evrc
09-06 16:56:08.835  1033  1741 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7833 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-06 16:56:08.838  7782  7825 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-06 16:56:08.841  1033  1574 I ActivityManager: Killing 6868:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-06 16:56:08.844  7782  7825 W VideoCapabilities: Unsupported mime video/divx
09-06 16:56:08.855  7009  7009 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,09-06 16:56:08.855  7009  7009 W System.err: android.os.DeadObjectException
09-06 16:56:08.855  7009  7009 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 16:56:08.855  7009  7009 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 16:56:08.855  7009  7009 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-06 16:56:08.855  7009  7009 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-06 16:56:08.855  7009  7009 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 16:56:08.855  7009  7009 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 16:56:08.855  7009  7009 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 16:56:08.855  7009  7009 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 16:56:08.855  7009  7009 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:56:08.855  7009  7009 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 16:56:08.855  7009  7009 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:56:08.855  7009  7009 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:56:08.856  7009  7009 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 16:56:08.856  7009  7009 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 16:56:08.856  7009  7009 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-06 16:56:08.856  7009  7009 W System.err: android.os.DeadObjectException
09-06 16:56:08.856  7009  7009 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 16:56:08.857  7009  7009 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 16:56:08.857  7009  7009 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-06 16:56:08.857  7009  7009 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-06 16:56:08.857  7009  7009 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 16:56:08.857  7009  7009 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 16:56:08.857  7009  7009 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 16:56:08.857  7009  7009 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 16:56:08.857  7009  7009 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:56:08.857  7009  7009 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 16:56:08.857  7009  7009 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:56:08.857  7009  7009 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:56:08.857  7009  7009 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 16:56:08.857  7009  7009 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 16:56:08.857  7009  7009 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-06 16:56:08.857  7009  7009 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-06 16:56:08.858  7782  7825 W VideoCapabilities: Unsupported mime video/divx311
09-06 16:56:08.860  7782  7825 W VideoCapabilities: Unsupported mime video/divx4
09-06 16:56:08.863  7782  7825 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-06 16:56:08.873  7782  7825 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-06 16:56:08.875  7782  7825 W AudioCapabilities: Unsupported mime audio/eac3
,09-06 16:56:08.876  7782  7825 W AudioCapabilities: Unsupported mime audio/ac3
09-06 16:56:08.876  7782  7825 W AudioCapabilities: Unsupported mime audio/g726
09-06 16:56:08.877  7782  7825 W AudioCapabilities: Unsupported mime audio/wma-voice
09-06 16:56:08.877  7782  7825 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-06 16:56:08.878  7782  7825 W AudioCapabilities: Unsupported mime audio/adpcm
09-06 16:56:08.879  7782  7825 W VideoCapabilities: Unsupported mime video/theora
09-06 16:56:08.880  7782  7825 W VideoCapabilities: Unsupported mime video/mjpg
09-06 16:56:09.048  1033  1574 E libprocessgroup: failed to kill 1 processes for processgroup 6868
,09-06 16:56:09.137  1033  1940 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-06 16:56:09.143  7009  7009 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,09-06 16:56:09.145  7009  7009 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-06 16:56:09.181  1033  1905 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7853 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 16:56:09.182  7009  7009 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-06 16:56:09.184  7833  7833 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 16:56:09.184  7833  7833 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 16:56:09.185  7833  7833 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-06 16:56:09.187  7833  7833 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-06 16:56:09.193  7833  7833 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-06 16:56:09.260  7853  7853 D UEI.SmartControl: Quickset Services start...
09-06 16:56:09.262  7853  7853 I UEI.SmartControl: Manufacture = LGE
09-06 16:56:09.262  7853  7853 D UEI.SmartControl: Id = LGNevo
09-06 16:56:09.263  7853  7853 D UEI.SmartControl: File observer start...
09-06 16:56:09.263  7853  7853 E UEI.SmartControl: IR Port is disabled: false
09-06 16:56:09.264  7853  7853 D UEI.SmartControl: Starting file observer...
09-06 16:56:09.264  7853  7853 D UEI.SmartControl: Extracting JNI libs...
09-06 16:56:09.264  7853  7853 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,09-06 16:56:09.275  7833  7833 I SystemConfig: BUILD Country: EU
09-06 16:56:09.275  7833  7833 I SystemConfig: BUILD Operator: OPEN
09-06 16:56:09.324  1033  1049 I ActivityManager: Killing 7009:com.lge.qremote/u0a112 (adj 15): empty #17
,09-06 16:56:09.356  7853  7853 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,09-06 16:56:09.356  7853  7853 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,09-06 16:56:09.356  7853  7853 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-06 16:56:09.396  7853  7853 I UEI.SmartControl: --- Selecting new region: 6
,09-06 16:56:09.398  7853  7853 I UEI.SmartControl: Model = LG-D855
09-06 16:56:09.400  7853  7853 D UEI.SmartControl: QS Service created
09-06 16:56:09.465  1033  1941 W libprocessgroup: failed to open /acct/uid_10112/pid_7009/cgroup.procs: No such file or directory
,09-06 16:56:09.486  7833  7876 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,09-06 16:56:09.486  7833  7876 I SystemConfig: existFile = false
09-06 16:56:09.486  7833  7876 I SystemConfig: canReadFile = false
09-06 16:56:09.487  7833  7876 I SystemConfig: systemFeature RCS result false
09-06 16:56:09.487  7833  7876 D SystemConfig: refreshRcsSupport() :false
,09-06 16:56:09.501  7853  7853 I UEI.SmartControl: Service initServices...
,09-06 16:56:09.506  7853  7853 D UEI.SmartControl: QS start get config
09-06 16:56:09.545  1033  1049 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7880 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-06 16:56:09.577  7853  7853 D UEI.SmartControl: Loading JNI Libs...
09-06 16:56:09.587  7880  7880 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 16:56:09.587  7880  7880 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-06 16:56:09.587  7880  7880 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-06 16:56:09.588  7880  7880 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 16:56:09.686  7880  7880 I AppConfig: Total System Memory = 2995761152
,09-06 16:56:09.696  7880  7880 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-06 16:56:09.799  1033  1740 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7899 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 16:56:09.800  1033  1740 I ActivityManager: Killing 7184:com.lge.email/u0a23 (adj 15): empty #17
,09-06 16:56:09.813  7853  7853 I UEI.SmartControl: Supports setup maps: true
,09-06 16:56:09.815  7853  7853 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 16:56:09.815  7853  7853 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 16:56:09.816  7853  7853 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 16:56:09.816  7853  7853 I UEI.SmartControl: ### init IR Blaster...
,09-06 16:56:09.821  7853  7853 D serial_port: Configuring serial port
09-06 16:56:09.826  7853  7853 E UEI.SmartControl: UEIBLaster setting for 616
09-06 16:56:09.827  7853  7853 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 16:56:09.827  7853  7853 I UEI.SmartControl: configuring settings for MAXQ616
09-06 16:56:09.827  7853  7853 I UEI.SmartControl: Get version...
09-06 16:56:09.844  7853  7914 D UEI.SmartControl: serial port data available: 21
,09-06 16:56:09.869  1033  1905 W libprocessgroup: failed to open /acct/uid_10023/pid_7184/cgroup.procs: No such file or directory
,09-06 16:56:09.872  7853  7853 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 16:56:09.872  7853  7853 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 16:56:09.873  7853  7853 I UEI.SmartControl: QS saving settings...
09-06 16:56:09.873  7853  7853 D UEI.SmartControl: IR Blaster version: 25672567
09-06 16:56:09.891  7853  7914 D UEI.SmartControl: serial port data available: 4
,09-06 16:56:09.929  7853  7920 I UEI.SmartControl: Device manager: loading config....
09-06 16:56:09.930  7853  7920 D UEI.SmartControl: ----------- loading internal config...
09-06 16:56:09.931  7853  7853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-06 16:56:09.939  7853  7853 E UEI.SmartControl: Services init done
09-06 16:56:09.939  7853  7853 D UEI.SmartControl: QS Service init finished
09-06 16:56:09.940  7853  7853 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 16:56:09.940  7853  7853 D UEI.SmartControl: QS Service version code: 201091
09-06 16:56:09.942  7853  7853 D UEI.SmartControl: Service requested: Control
09-06 16:56:09.944  7853  7920 E UEI.SmartControl: Loading SETTINGS...
,09-06 16:56:09.947  7853  7853 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-06 16:56:09.950  7853  7853 D UEI.SmartControl: Service.onUnbind: IControl
09-06 16:56:09.951  7853  7853 D UEI.SmartControl: Service.onDestroy
09-06 16:56:09.951  7853  7853 D UEI.SmartControl: Lock is in USE false
09-06 16:56:09.951  7853  7853 D UEI.SmartControl: unbind internal service
09-06 16:56:09.952  7853  7853 D serial_port: close(fd = 25)
09-06 16:56:09.956  7853  7853 I UEI.SmartControl: Serial port is closed.
09-06 16:56:09.958  7853  7853 I UEI.SmartControl: Serial port is closed.
09-06 16:56:09.958  7853  7853 D UEI.SmartControl: Blaster closed
09-06 16:56:09.960  7853  7853 D UEI.SmartControl: Shut down QS...
09-06 16:56:09.960  7853  7853 D UEI.SmartControl: Stopping QS lib
09-06 16:56:09.960  7853  7853 D UEI.SmartControl: QS lib stop result = true
09-06 16:56:09.960  7853  7853 D UEI.SmartControl: Stopped QS lib
09-06 16:56:09.962  7853  7920 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 16:56:09.964  7853  7853 D UEI.SmartControl: Stopped file observer...
09-06 16:56:09.964  7853  7853 D UEI.SmartControl: QS shutdown complete
09-06 16:56:09.965  7853  7853 D UEI.SmartControl: QS Service created
09-06 16:56:09.966  7853  7918 I UEI.SmartControl: Notify AllClients services are ready: 11
09-06 16:56:09.966  7853  7918 D UEI.SmartControl: -----service ready thread exits
,09-06 16:56:09.978  7853  7853 I UEI.SmartControl: Service initServices...
09-06 16:56:09.979  7853  7853 D UEI.SmartControl: QS start get config
09-06 16:56:10.030  7899  7899 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-06 16:56:10.083  7899  7899 D LgDataFeature: LgDataFeature() Constructor: none
09-06 16:56:10.083  7899  7899 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 16:56:10.119  7899  7899 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
09-06 16:56:10.133  7899  7899 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-06 16:56:10.133  7899  7899 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-06 16:56:10.143  7899  7899 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-06 16:56:10.143  7899  7899 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-06 16:56:10.157  1033  1941 I ActivityManager: Killing 7050:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-06 16:56:10.285  7853  7853 I UEI.SmartControl: Supports setup maps: true
,09-06 16:56:10.288  7853  7853 D UEI.SmartControl: QS start statue = true Error code = 0
,09-06 16:56:10.288  7853  7853 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 16:56:10.288  7853  7853 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 16:56:10.288  7853  7853 I UEI.SmartControl: ### init IR Blaster...
09-06 16:56:10.292  7853  7853 D serial_port: Configuring serial port
09-06 16:56:10.292  7853  7853 E UEI.SmartControl: UEIBLaster setting for 616
09-06 16:56:10.292  7853  7853 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 16:56:10.292  7853  7853 I UEI.SmartControl: configuring settings for MAXQ616
09-06 16:56:10.292  7853  7853 I UEI.SmartControl: Get version...
09-06 16:56:10.298  1033  1740 W libprocessgroup: failed to open /acct/uid_10026/pid_7050/cgroup.procs: No such file or directory
,09-06 16:56:10.309  7853  7945 D UEI.SmartControl: serial port data available: 21
09-06 16:56:10.313  5048  7946 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-06 16:56:10.314  2855  2870 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,09-06 16:56:10.318  2855  2870 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3d5f593 on behalf of 7899
09-06 16:56:10.336  7853  7853 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 16:56:10.336  7853  7853 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 16:56:10.336  7853  7853 I UEI.SmartControl: QS saving settings...
09-06 16:56:10.337  7853  7853 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 16:56:10.351  7853  7945 D UEI.SmartControl: serial port data available: 4
,09-06 16:56:10.382  7853  7853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-06 16:56:10.389  1033  1713 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7950 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
09-06 16:56:10.391  7853  7949 I UEI.SmartControl: Device manager: loading config....
09-06 16:56:10.391  7853  7949 D UEI.SmartControl: ----------- loading internal config...
09-06 16:56:10.397  7853  7949 E UEI.SmartControl: Loading SETTINGS...
,09-06 16:56:10.403  7853  7949 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 16:56:10.404  7853  7853 E UEI.SmartControl: Services init done
09-06 16:56:10.404  7853  7853 D UEI.SmartControl: QS Service init finished
09-06 16:56:10.408  7853  7853 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 16:56:10.408  7853  7853 D UEI.SmartControl: QS Service version code: 201091
09-06 16:56:10.409  7853  7853 D UEI.SmartControl: Service requested: Control
09-06 16:56:10.413  1033  2014 I ActivityManager: Killing 6457:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-06 16:56:10.414  7899  7899 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-06 16:56:10.429  7853  7948 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 16:56:10.429  7853  7948 D UEI.SmartControl: -----service ready thread exits
,09-06 16:56:10.464  7853  7853 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@275ea63b that was originally bound here
09-06 16:56:10.464  7853  7853 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@275ea63b that was originally bound here
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 16:56:10.464  7853  7853 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 16:56:10.466  1033  1049 W libprocessgroup: failed to open /acct/uid_1000/pid_6457/cgroup.procs: No such file or directory
,09-06 16:56:10.477  7853  7853 D UEI.SmartControl: Internal service binding...
09-06 16:56:10.493  7899  7899 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-06 16:56:10.509  7950  7950 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-06 16:56:10.532  7950  7950 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-06 16:56:10.532  7950  7950 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-06 16:56:10.532  7950  7950 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,09-06 16:56:10.532  7950  7950 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-06 16:56:10.532  7950  7950 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-06 16:56:10.532  7950  7950 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-06 16:56:10.553  1033  1941 I ActivityManager: Killing 7217:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-06 16:56:10.583  1033  1995 W libprocessgroup: failed to open /acct/uid_10046/pid_7217/cgroup.procs: No such file or directory
,09-06 16:56:10.831  1033  2071 V SIM_STK : Menu title from STK is T-Mobile
,09-06 16:56:10.852  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:10.852  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11d09059 added. We now have 6 listener(s)
09-06 16:56:10.852  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:56:10.856  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:10.856  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f9ec41e added. We now have 7 listener(s)
09-06 16:56:10.856  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:10.858  6729  6793 I System.out: IsBluetoothEnabled
09-06 16:56:10.859  1033  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:10.860  1033  1959 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-06 16:56:10.860  1033  1095 D BluetoothManagerService: Message: 2
09-06 16:56:10.864  6729  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:10.867  1033  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:10.867  1033  2014 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
09-06 16:56:10.878  5048  7946 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 565 ms] updated apps [took 565 ms] 
,09-06 16:56:10.896  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 16:56:10.896  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 16:56:10.896  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,09-06 16:56:10.900  1033  1095 D BluetoothManagerService: Message: 1
09-06 16:56:10.900  1033  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-06 16:56:10.925  1033  1095 D BluetoothManagerService: Message: 20
09-06 16:56:10.925  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e4c2866:true
,09-06 16:56:10.929  7753  7753 D BluetoothAdapterState: make
09-06 16:56:10.933  7753  7753 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-06 16:56:10.933  7753  7753 I bluedroid-qcom: init
09-06 16:56:10.934  7753  7981 I BluetoothAdapterState: Entering OffState
09-06 16:56:10.935  7753  7753 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 16:56:10.935  7753  7753 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 16:56:10.935  7753  7753 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 16:56:10.935  7753  7753 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 16:56:10.935  7753  7753 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-06 16:56:10.937  7753  7753 I bluedroid-qcom: get_profile_interface socket
09-06 16:56:10.937  7753  7753 I bluedroid-qcom: get_profile_interface map_client
,09-06 16:56:10.941  7753  7985 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-06 16:56:10.933  7984  7984 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:10.933  7984  7984 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:10.950  7753  7985 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-06 16:56:10.960  7984  7984 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-06 16:56:10.961  7984  7984 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-06 16:56:10.961  7984  7984 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-06 16:56:10.962  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-06 16:56:10.962  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 16:56:10.962  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 16:56:10.962  1033  1095 D BluetoothManagerService: Message: 40
09-06 16:56:10.963  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,09-06 16:56:10.965  7984  7984 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-06 16:56:10.967  7753  7770 I bluedroid-qcom: config_hci_snoop_log
09-06 16:56:10.969  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-06 16:56:10.969  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-06 16:56:10.970  7753  7985 D BluetoothAdapterProperties: Name is: G3
09-06 16:56:10.970  7853  7922 D UEI.SmartControl: Internal timer expired: 2
09-06 16:56:10.975  7753  7981 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-06 16:56:10.976  7753  7981 D BluetoothAdapterProperties: Setting state to 11
09-06 16:56:10.976  7753  7981 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-06 16:56:10.980  7753  7981 I LGBluetoothServiceJni: classInitNative: succeeds
09-06 16:56:10.982  1033  1095 D BluetoothManagerService: Message: 60
09-06 16:56:10.983  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-06 16:56:10.983  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-06 16:56:10.986  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:10.987  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 16:56:10.988  7984  7984 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-06 16:56:10.988  7984  7984 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-06 16:56:10.993  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:10.998  6960  6960 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-06 16:56:11.003  7753  7753 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 16:56:11.003  7753  7753 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:11.003  7753  7753 V BluetoothPbapReceiver: ***********state = 11
,09-06 16:56:11.013  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 16:56:11.020  7753  7981 D BluetoothBondStateMachine: make
,09-06 16:56:11.024  7753  7981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@220a64ca
09-06 16:56:11.024  7753  7981 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-06 16:56:11.025  7753  7981 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@220a64ca
09-06 16:56:11.025  7753  7981 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-06 16:56:11.025  7753  7994 I BluetoothBondStateMachine: StableState(): Entering Off State
09-06 16:56:11.027  7753  7981 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-06 16:56:11.035  6960  6960 D BluetoothPermissionRequest: onReceive
,09-06 16:56:11.040  7753  7981 E BluetoothAdapterService: File transfer profiles supported!!
09-06 16:56:11.041  6960  6960 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 16:56:11.051  7753  7753 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:56:11.055  7753  7981 E BluetoothAdapterService: File transfer profiles supported!!
09-06 16:56:11.055  7753  7753 D HeadsetService: Received start request. Starting profile...
09-06 16:56:11.056  7753  7753 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 16:56:11.056  7753  7753 D LGBluetoothHfpAdapter: Version 1.6
09-06 16:56:11.061  7753  7981 E BluetoothAdapterService: File transfer profiles supported!!
09-06 16:56:11.062  7753  7753 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 16:56:11.063  7753  7753 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 16:56:11.064  7753  7753 D HeadsetStateMachine: make
,09-06 16:56:11.071  7753  7981 E BluetoothAdapterService: File transfer profiles supported!!
09-06 16:56:11.079  7753  7981 E BluetoothAdapterService: File transfer profiles supported!!
09-06 16:56:11.084  7753  7981 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 16:56:11.093  7753  7981 E BluetoothAdapterService: File transfer profiles supported!!
09-06 16:56:11.107  7753  7753 D LgDataFeature: LgDataFeature() Constructor: none
09-06 16:56:11.107  7753  7753 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 16:56:11.110  7753  7981 V LGMDMManager: Create singleton instance
09-06 16:56:11.113  7753  7981 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-06 16:56:11.114  7753  7753 D HeadsetStateMachine: max_hf_connections = 1
09-06 16:56:11.114  7753  7753 I bluedroid-qcom: get_profile_interface handsfree
09-06 16:56:11.117  7753  7753 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-06 16:56:11.117   323  1765 V AudioPolicyService: registerClient() client 0xb0410160, uid 1002
09-06 16:56:11.118   323  1765 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-06 16:56:11.118   323  1765 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 16:56:11.118   323  1765 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 16:56:11.119  7753  7753 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 16:56:11.120   323  1384 V AudioFlinger: registerClient() client 0xb5581610, pid 7753
,09-06 16:56:11.120   323  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 16:56:11.120   323  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 16:56:11.121   323  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 16:56:11.121   323  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 16:56:11.121  1033  1995 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 16:56:11.121  1033  1995 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 16:56:11.121  1033  1995 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 16:56:11.121  1033  1995 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 16:56:11.121  1600  2536 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 16:56:11.121  1600  2536 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 16:56:11.121  1600  2536 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 16:56:11.121  1854  2414 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 16:56:11.121  1854  2414 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 16:56:11.122  1854  2414 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 16:56:11.122  1854  2414 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 16:56:11.122  3175  3190 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 16:56:11.122  3175  3190 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 16:56:11.122  1600  2536 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 16:56:11.122  3175  3190 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 16:56:11.122  3175  3190 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 16:56:11.122  7753  7770 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 16:56:11.122  7753  7770 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-06 16:56:11.122  7753  7753 V ToneGenerator: Create Track: 0xb4928a80
09-06 16:56:11.122  7753  7770 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 16:56:11.122  7753  7770 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-06 16:56:11.122  7753  7753 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-06 16:56:11.122  7753  7753 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-06 16:56:11.123   323  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 16:56:11.123   323  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-06 16:56:11.123   323  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 16:56:11.123   323  1383 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 16:56:11.124   323  1765 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 16:56:11.125   323  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 16:56:11.125   323  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-06 16:56:11.125   323  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 16:56:11.125   323  1384 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 16:56:11.125  7753  7753 V AudioSystem: getLatency() output 2, latency 50
09-06 16:56:11.125  7753  7753 V AudioSystem: getFrameCount() output 2, frameCount 960
09-06 16:56:11.125  7753  7753 V AudioTrack: createTrack_l() output 2 afLatency 50
09-06 16:56:11.128   323   323 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 16:56:11.128   323   323 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), ,curLvl = 31 
09-06 16:56:11.128   323   323 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 16:56:11.128   323   323 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 16:56:11.129   323   323 V AudioFlinger: createTrack() lSessionId: 23
09-06 16:56:11.131  7753  7753 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-06 16:56:11.132   323  1383 V AudioFlinger: acquiring 23 from 7753, for 7753
09-06 16:56:11.132   323  1383 V AudioFlinger:  added new entry for 23
09-06 16:56:11.132  7753  7753 V ToneGenerator: ToneGenerator INIT OK, time: 136534
09-06 16:56:11.133  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@220a64ca
09-06 16:56:11.134  7753  8002 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-06 16:56:11.134  7753  8002 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 16:56:11.135  7753  8002 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 16:56:11.135  7753  8002 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-06 16:56:11.136   323  1765 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7753
09-06 16:56:11.136   323  1765 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-06 16:56:11.136   323  1765 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-06 16:56:11.136   323  1765 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-06 16:56:11.136   323  1765 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-06 16:56:11.136   323  1765 V voice   : voice_set_parameters: exit with code(0)
09-06 16:56:11.136   323  1765 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-06 16:56:11.136   323  1765 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-06 16:56:11.136   323  1765 V msm8974_platform: platform_set_parameters: exit with code(0)
09-06 16:56:11.136   323  1765 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-06 16:56:11.137   323  1765 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-06 16:56:11.137   323  1765 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-06 16:56:11.137  7753  8002 V ToneGenerator: ToneGenerator destructor
09-06 16:56:11.137  7753  8002 V ToneGenerator: stopTone
09-06 16:56:11.137  7753  8002 V ToneGenerator: Delete Track: 0xb4928a80
09-06 16:56:11.137  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@220a64ca
09-06 16:56:11.138   323  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
09-06 16:56:11.138   323  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-06 16:56:11.138   323  1226 V AudioPolicyService: AudioCommandThread() waking up
09-06 16:56:11.138   323  1226 V AudioPolicyService: AudioCommandThread() processing release output 2
09-06 16:56:11.138   323  1226 V AudioPolicyManager: releaseOutput() 2
09-06 16:56:11.139   323  1226 V AudioPolicyService: AudioCommandThread() going to sleep
09-06 16:56:11.139   323  1384 V AudioFlinger: PlaybackThread::Track destructor
09-06 16:56:11.139   323  1384 V AudioFlinger: removeClient_l() pid 7753, calling pid 323
09-06 16:56:11.139  7753  8002 V AudioTrack: ~AudioTrack, releasing session id from 7753 on behalf of 7753
09-06 16:56:11.139   323  1765 V AudioFlinger: releasing 23 from 7753 for 7753
09-06 16:56:11.139   323  1765 V AudioFlinger:  decremented refcount to 0
09-06 16:56:11.139   323  1765 V AudioFlinger: purging stale effects
09-06 16:56:11.142  7753  7753 D A2dpService: Received start request. Starting profile...
09-06 16:56:11.144  7753  7753 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 16:56:11.146  7753  7753 V Avrcp   : make
09-06 16:56:11.147  7753  7753 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-06 16:56:11.148  7753  7753 I bluedroid-qcom: get_profile_interface avrcp
09-06 16:56:11.159  7753  7753 V AudioManager: registerRemoteController: size of Media player list: 0
,09-06 16:56:11.161  7753  7753 E AudioManager: No RCC entry present to update
,09-06 16:56:11.161  7753  7753 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-06 16:56:11.165  7753  7753 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-06 16:56:11.166  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-06 16:56:11.166  7753  7753 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-06 16:56:11.171  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-06 16:56:11.310  1033  1977 V SIM_STK : Menu title from STK is T-Mobile
09-06 16:56:11.310  1033  1977 V SIM_STK : Menu title from STK is T-Mobile
,09-06 16:56:11.439  1033  1941 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-06 16:56:11.455  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-06 16:56:11.463  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-06 16:56:11.464  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-06 16:56:11.464  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 16:56:11.464  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 16:56:11.464  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 16:56:11.465  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 16:56:11.465  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 16:56:11.465  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 16:56:11.465  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 16:56:11.465  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 16:56:11.465  7753  7753 I BluetoothA2dpServiceJni: classInitNative
09-06 16:56:11.466  7753  7753 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 16:56:11.466  7753  7753 D A2dpStateMachine: make
,09-06 16:56:11.469  7753  7753 I bluedroid-qcom: get_profile_interface a2dp
09-06 16:56:11.470  7753  8012 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 16:56:11.476  7753  7753 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-06 16:56:11.476  7753  7753 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,09-06 16:56:11.479  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@220a64ca
09-06 16:56:11.479  7753  8011 D A2dpStateMachine: Enter Disconnected: -2
09-06 16:56:11.483  7753  7753 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 16:56:11.488  7753  7753 D HidService: Received start request. Starting profile...
,09-06 16:56:11.488  7753  7753 I bluedroid-qcom: get_profile_interface hidhost
09-06 16:56:11.488  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@220a64ca
09-06 16:56:11.489  7753  7753 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 16:56:11.489  7753  7753 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 16:56:11.490  7753  7753 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 16:56:11.490  7753  7753 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:11.490  7753  7753 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-06 16:56:11.491  7753  7753 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 16:56:11.496  7753  7753 D HealthService: Received start request. Starting profile...
09-06 16:56:11.499  7753  7753 I bluedroid-qcom: get_profile_interface health
09-06 16:56:11.499  7753  7753 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-06 16:56:11.499  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@220a64ca
09-06 16:56:11.500  7753  7753 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 16:56:11.503  7753  7753 D PanService: Received start request. Starting profile...
09-06 16:56:11.503  7753  7753 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 16:56:11.503  7753  7753 I bluedroid-qcom: get_profile_interface pan
09-06 16:56:11.511  7753  7753 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-06 16:56:11.511  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@220a64ca
09-06 16:56:11.512  7753  7753 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-06 16:56:11.519  7753  7753 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 16:56:11.519  7753  7753 D BtGatt.GattService: Received start request. Starting profile...
,09-06 16:56:11.519  7753  7753 D BtGatt.GattService: start()
09-06 16:56:11.519  7753  7753 I bluedroid-qcom: get_profile_interface gatt
09-06 16:56:11.520  7753  7753 D BtGatt.AdvertiseManager: advertise manager created
09-06 16:56:11.670  1033  2014 I art     : Explicit concurrent mark sweep GC freed 27049(1334KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.064ms total 144.979ms
09-06 16:56:11.672  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@220a64ca
,09-06 16:56:11.677  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@220a64ca
09-06 16:56:11.678  7753  7753 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-06 16:56:11.679  7753  7753 V BluetoothMapService: BluetoothMapBinder()
09-06 16:56:11.679  7753  7753 D BluetoothMapService: Received start request. Starting profile...
09-06 16:56:11.679  7753  7753 D BluetoothMapService: start()
09-06 16:56:11.682  7753  7753 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-06 16:56:11.682  7753  7753 D BluetoothMapEmailAppObserver: createReceiver()
09-06 16:56:11.684  7753  7753 D BluetoothMapEmailAppObserver: initObservers()
09-06 16:56:11.684  7753  7753 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,09-06 16:56:11.693  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@220a64ca
09-06 16:56:11.693  7753  7753 D HeadsetStateMachine: Proxy object connected
09-06 16:56:11.694  7753  7753 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-06 16:56:11.694  7753  7753 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-06 16:56:11.697  7753  8002 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-06 16:56:11.697  7753  8002 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 16:56:11.698  7753  8002 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-06 16:56:11.702  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 16:56:11.704  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 16:56:11.706  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 16:56:11.708  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 16:56:11.709  7753  7753 V PanService: [BTUI] SIM Extra State :ABSENT
09-06 16:56:11.711  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 16:56:11.713  7753  7753 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-06 16:56:11.713  7753  7753 V BluetoothMapService: Handler(): got msg=1
09-06 16:56:11.714  7753  7981 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-06 16:56:11.714  7753  7981 I bluedroid-qcom: enable
,09-06 16:56:11.714  7753  7981 I bt_hci_bdroid: init
09-06 16:56:11.715  7753  7981 I bt_vendor: bt-vendor : init
09-06 16:56:11.715  7753  7981 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 16:56:11.715  7753  7981 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 16:56:11.715  7753  7981 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-06 16:56:11.715  7753  7981 D bt_userial_mct: userial_init
09-06 16:56:11.716  7753  8022 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-06 16:56:11.716  7753  8022 I bt-btu  : btu_task pending for preload complete event
09-06 16:56:11.716  7753  7981 D bt_hci_bdroid: set_power 1
09-06 16:56:11.716  7753  7981 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 16:56:11.716  7753  7981 I bt_vendor: Starting hciattach daemon
09-06 16:56:11.716  7753  7981 I bt_vendor: try to set true
09-06 16:56:11.703  8025  8025 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:11.703  8025  8025 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:11.741  8026  8026 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-06 16:56:11.787  8032  8032 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 16:56:11.795  8033  8033 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-06 16:56:11.812  8035  8035 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 16:56:11.836  8036  8036 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-06 16:56:11.848  8037  8037 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-06 16:56:11.856  8038  8038 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-06 16:56:11.877  8040  8040 I libmdmdetect: ESOC framework not supported
09-06 16:56:11.878  8040  8040 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-06 16:56:11.885  8040  8040 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-06 16:56:11.885  8040  8040 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,09-06 16:56:11.885  8040  8040 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-06 16:56:11.885  8040  8040 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-06 16:56:11.885  8040  8040 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-06 16:56:11.885  8040  8040 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-06 16:56:11.886  8040  8040 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-06 16:56:11.926  8040  8041 E QC-QMI  : qmi_client [8040] 15: failed to locate client data
09-06 16:56:11.928   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-06 16:56:11.928   484   484 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-06 16:56:11.968  8042  8042 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-06 16:56:11.993  8043  8043 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 16:56:12.017  7753  7981 I bt_vendor: bluetooth satus is on
09-06 16:56:12.017  7753  7981 D bt_hci_bdroid: preload
09-06 16:56:12.017  7753  8024 D bt_userial_mct: userial_open(port:0)
09-06 16:56:12.017  7753  8024 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-06 16:56:12.021  7753  8024 I bt_vendor: Done intiailizing UART
09-06 16:56:12.026  7753  8024 I bt_vendor: Done intiailizing UART
09-06 16:56:12.026  7753  8024 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-06 16:56:12.026  7753  8024 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 16:56:12.026  7753  8022 I bt-btu  : btu_task received preload complete event
09-06 16:56:12.027  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-06 16:56:12.027  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-06 16:56:12.028  7753  8045 D bt_userial_mct: Entering userial_read_thread()
09-06 16:56:12.029  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_HCI
09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_BTM
,09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_PAN
,09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 16:56:12.033  7753  8022 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 16:56:12.125  7753  8022 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-06 16:56:12.125  7753  8022 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0214061 ,
09-06 16:56:12.125  7753  8022 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0214061 ,
,09-06 16:56:12.185  7753  7985 E bt-btif : Calling BTA_HhEnable
,09-06 16:56:12.185  7753  7985 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,09-06 16:56:12.186  7753  7985 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-06 16:56:12.196  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,09-06 16:56:12.197  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 16:56:12.198  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,09-06 16:56:12.198  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-06 16:56:12.198  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-06 16:56:12.198  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-06 16:56:12.198  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-06 16:56:12.200  7753  7985 D BluetoothAdapterProperties: Name is: G3
09-06 16:56:12.204  7753  7985 D BluetoothAdapterProperties: Scan Mode:20
09-06 16:56:12.205  7753  7985 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 16:56:12.205  7753  7985 D bt_hci_bdroid: postload
,09-06 16:56:12.213  7753  8024 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 16:56:12.215  7753  8022 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-06 16:56:12.216  7753  7985 D bte_conf: Device ID record 1 : primary
09-06 16:56:12.216  7753  7985 D bte_conf:   vendorId            = 00c4
09-06 16:56:12.216  7753  7985 D bte_conf:   vendorIdSource      = 0001
09-06 16:56:12.216  7753  7985 D bte_conf:   product             = 13a1
09-06 16:56:12.216  7753  7985 D bte_conf:   version             = 1000
09-06 16:56:12.216  7753  7985 D bte_conf:   clientExecutableURL = 
09-06 16:56:12.216  7753  7985 D bte_conf:   serviceDescription  = 
09-06 16:56:12.216  7753  7985 D bte_conf:   documentationURL    = 
09-06 16:56:12.216  7753  7985 D bte_conf: bte_load_did_conf no section named DID2.
09-06 16:56:12.218  7753  8024 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 16:56:12.221  7753  7981 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-06 16:56:12.225  7753  7981 D BluetoothAdapterProperties: ScanMode =  20
09-06 16:56:12.225  7753  7981 D BluetoothAdapterProperties: State =  11
09-06 16:56:12.225  7753  7981 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-06 16:56:12.226  7753  7981 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-06 16:56:12.226  7753  7981 D BluetoothAdapterProperties: Setting state to 12
09-06 16:56:12.226  7753  7981 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 16:56:12.226  7753  7985 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 16:56:12.227  7753  7985 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 16:56:12.223  8050  8050 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 16:56:12.233  8050  8050 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:12.244  7753  7981 I BluetoothAdapterState: Entering On State
09-06 16:56:12.248  7753  8024 D bt_hci_bdroid: Used up Tx Cmd credits
,09-06 16:56:12.242  1033  1095 D BluetoothManagerService: Message: 60
09-06 16:56:12.250  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-06 16:56:12.250  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-06 16:56:12.250  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 16:56:12.257  7753  7981 D LGBluetoothServiceAdapter: [BTUI] OnState
09-06 16:56:12.257  7753  7981 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-06 16:56:12.257  7753  7981 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-06 16:56:12.258  7753  7981 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-06 16:56:12.258  7753  8022 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 16:56:12.258  7753  8022 W bt-smp  : Plain text(LSB ~ MSB) = 17 e2 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 16:56:12.258  7753  8022 W bt-smp  : Encrypted text(LSB ~ MSB) = bb e8 9c 81 5e 38 52 cb 0b 4b c2 9c 87 2b 23 d7 
09-06 16:56:12.259  7753  8024 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 16:56:12.259  7753  8022 W bt-btm  : Stopping oneshot timer
09-06 16:56:12.262  7753  8045 E bt_mct  : hci lib postload completed
,09-06 16:56:12.281  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:12.281  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:12.281  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:56:12.281  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:12.281  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:12.281  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:12.281  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:12.281  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:12.293  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:56:12.295  7753  7981 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-06 16:56:12.300  7753  8022 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 16:56:12.300  7753  8022 W bt-smp  : Plain text(LSB ~ MSB) = 9c cc 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 16:56:12.300  7753  8022 W bt-smp  : Encrypted text(LSB ~ MSB) = 82 99 42 d5 e7 aa 1a 68 f4 4d 43 50 05 fc 8b 88 
09-06 16:56:12.301  7753  8022 W bt-btm  : Stopping oneshot timer
09-06 16:56:12.320  1854  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 16:56:12.323  7753  8022 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 16:56:12.323  7753  8022 W bt-smp  : Plain text(LSB ~ MSB) = e6 01 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 16:56:12.323  7753  8022 W bt-smp  : Encrypted text(LSB ~ MSB) = 8d 10 4d 4e da d7 52 95 ce 23 43 cf 69 3a 9d d5 
09-06 16:56:12.323  7753  8022 W bt-btm  : Stopping oneshot timer
09-06 16:56:12.339  7753  8022 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 16:56:12.339  7753  8022 W bt-smp  : Plain text(LSB ~ MSB) = a2 23 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 16:56:12.339  7753  8022 W bt-smp  : Encrypted text(LSB ~ MSB) = c7 61 f7 61 84 0d 1c 25 aa e8 4a d4 ec fb fd 4e 
09-06 16:56:12.339  7753  8022 W bt-btm  : Stopping oneshot timer
09-06 16:56:12.340  1033  1033 D BluetoothA2dp: Proxy object connected
,09-06 16:56:12.360  1854  1854 D BluetoothHeadset: Proxy object connected
09-06 16:56:12.363  7753  8022 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,09-06 16:56:12.363  7753  8022 W bt-smp  : Plain text(LSB ~ MSB) = 9b 62 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 16:56:12.363  7753  8022 W bt-smp  : Encrypted text(LSB ~ MSB) = ea 57 40 e0 0e db 5a cb b1 03 63 41 8a 70 e2 ef 
09-06 16:56:12.364  7753  8022 W bt-btm  : Stopping oneshot timer
09-06 16:56:12.365  6960  6976 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 16:56:12.373  6960  6960 D BluetoothHeadset: Proxy object connected
09-06 16:56:12.374  6960  6960 D HeadsetProfile: Bluetooth service connected
09-06 16:56:12.376  1854  1870 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 16:56:12.377  8065  8065 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-06 16:56:12.378  7753  7985 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 16:56:12.378  7753  7985 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-06 16:56:12.380  1854  1854 D BluetoothHeadset: Proxy object connected
,09-06 16:56:12.382  6960  6976 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 16:56:12.385  6960  6976 D BluetoothMap: onBluetoothStateChange: up=true
09-06 16:56:12.389  1854  4637 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 16:56:12.389  6960  6960 D BluetoothInputDevice: Proxy object connected
09-06 16:56:12.389  6960  6960 D HidProfile: Bluetooth service connected
09-06 16:56:12.391  1854  1854 D BluetoothHeadset: Proxy object connected
09-06 16:56:12.391  6960  6960 D BluetoothMap: Proxy object connected
09-06 16:56:12.391  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 16:56:12.391  6960  6960 D MapProfile: Bluetooth service connected
09-06 16:56:12.391  6960  6960 D BluetoothMap: getConnectedDevices()
09-06 16:56:12.392  1033  1033 D BluetoothHeadset: Proxy object connected
09-06 16:56:12.392  7753  7771 V BluetoothMapService: getConnectedDevices()
09-06 16:56:12.394  6960  6976 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 16:56:12.397  6960  7000 D BluetoothPan: onBluetoothStateChange on: true
09-06 16:56:12.397  6960  7000 D BluetoothPan: onBluetoothStateChange call bindService
09-06 16:56:12.397  6960  6960 D BluetoothA2dp: Proxy object connected
09-06 16:56:12.397  6960  6960 D A2dpProfile: Bluetooth service connected
09-06 16:56:12.401  6960  6960 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 16:56:12.401  6960  6960 D PanProfile: Bluetooth service connected
09-06 16:56:12.402  6960  6976 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 16:56:12.406  1033  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-06 16:56:12.406  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-06 16:56:12.406  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-06 16:56:12.408  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:56:12.408  1600  1600 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 16:56:12.409  1942  2142 D LGBluetoothAPIService: Message: 1
09-06 16:56:12.409  1942  2142 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-06 16:56:12.409  1942  2142 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-06 16:56:12.409  1942  2142 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-06 16:56:12.413  1033  1095 D BluetoothManagerService: Message: 40
09-06 16:56:12.413  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-06 16:56:12.417  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:12.418  7753  7753 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:12.418  7753  7753 D BluetoothMapService: STATE_ON
09-06 16:56:12.422  6960  6960 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,09-06 16:56:12.425  6960  6960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 16:56:12.435  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@220a64ca
,09-06 16:56:12.436  7753  7753 V BluetoothPbapService: Pbap Service onCreate
09-06 16:56:12.436  7753  7753 V BluetoothPbapService: Starting PBAP service
09-06 16:56:12.437  7753  7753 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-06 16:56:12.437  7753  7753 V BluetoothMapService: Handler(): got msg=1
09-06 16:56:12.438  7753  7753 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-06 16:56:12.439  6960  6960 D DockEventReceiver: finishStartingService: stopping service
09-06 16:56:12.439  7753  7753 V BluetoothPbapService: Pbap Service onBind
09-06 16:56:12.440  7753  7753 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:12.440  7753  7753 V BluetoothPbapService: state: 12
09-06 16:56:12.440  6960  6960 D BluetoothPbap: Proxy object connected
09-06 16:56:12.440  6960  6960 D PbapServerProfile: Bluetooth service connected
09-06 16:56:12.440  7753  7753 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 16:56:12.440  7753  7753 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:12.440  7753  7753 V BluetoothPbapReceiver: ***********state = 12
09-06 16:56:12.441  7753  8075 D BluetoothMapMasInstance: MAS initSocket()
09-06 16:56:12.442  7753  8075 D BluetoothMapMasInstance:   masId = 00
09-06 16:56:12.442  7753  8075 D BluetoothMapMasInstance:   msgTypes = 0e
09-06 16:56:12.442  7753  8075 D BluetoothMapMasInstance:   masName = SMS/MMS
09-06 16:56:12.442  7753  8075 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-06 16:56:12.442  7753  7753 V BluetoothPbapService: Handler(): got msg=1
09-06 16:56:12.443  7753  7753 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-06 16:56:12.444  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 16:56:12.444  2188  2188 D c       : Getting all permits...
09-06 16:56:12.444  2188  2188 D a       : Opening database...
09-06 16:56:12.448  2188  2188 D a       : Opening database auth.proximity.permit_store...
09-06 16:56:12.449  1033  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:12.449  7753  8076 V BluetoothPbapService: Pbap Service initSocket
09-06 16:56:12.449  2188  2188 D a       : Closing database...
09-06 16:56:12.449  1033  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 16:56:12.452  7753  8075 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 16:56:12.455  7753  8076 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 16:56:12.461  7753  8076 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
,09-06 16:56:12.461  7753  8075 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=0
,09-06 16:56:12.462  7753  8076 V BluetoothPbapService: Succeed to create listening socket 
09-06 16:56:12.462  7753  8076 V BluetoothPbapService: Accepting socket connection...
09-06 16:56:12.462  7753  8075 V BluetoothMapMasInstance: Succeed to create listening socket 
09-06 16:56:12.462  7753  8075 D BluetoothMapMasInstance: Accepting socket connection...
09-06 16:56:12.463  7753  7985 D BluetoothAdapterProperties: Scan Mode:21
09-06 16:56:12.464  7753  7985 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-06 16:56:12.466  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:12.468  6960  6960 D BluetoothPermissionRequest: onReceive
09-06 16:56:12.472  6960  6960 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 16:56:12.474  6960  6960 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-06 16:56:12.477  7753  7753 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,09-06 16:56:12.478  7753  7753 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-06 16:56:12.484  7753  7753 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-06 16:56:12.505  7753  7753 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-06 16:56:12.505  7753  7753 V BtOppService: onCreate
09-06 16:56:12.511  7753  7753 V BluetoothOppNotification: send message
09-06 16:56:12.514  7753  7753 V BtOppService: Starting RfcommListener
09-06 16:56:12.523  7753  7753 D BluetoothOppPreference: Dumping Names:  
09-06 16:56:12.523  7753  7753 D BluetoothOppPreference: {}
09-06 16:56:12.523  7753  7753 D BluetoothOppPreference: Dumping Channels:  
09-06 16:56:12.523  7753  7753 D BluetoothOppPreference: {}
,09-06 16:56:12.526  7753  7753 V BtOppService: onStartCommand
09-06 16:56:12.529  7753  8083 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 16:56:12.530  7753  7753 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:12.530  7753  7753 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 16:56:12.534  7753  7753 V BluetoothOppNotification: new notify threadi!
09-06 16:56:12.535  7753  7753 V BluetoothOppNotification: send delay message
09-06 16:56:12.535  7753  8083 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 16:56:12.537  7753  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-06 16:56:12.538  7753  7753 V BtOppService: start RfcommListener
09-06 16:56:12.542  7753  8080 V BtOppService: Deleted complete outbound shares, number =  0
09-06 16:56:12.543  7753  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c0c97a6 on behalf of 
09-06 16:56:12.544  7753  8083 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7f555e7 on behalf of 
09-06 16:56:12.544  7753  8084 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 16:56:12.546  7753  8080 V BtOppService: Deleted complete inbound failed shares, number = 0
09-06 16:56:12.546  7753  7753 V BtOppService: RfcommListener started
09-06 16:56:12.547  7753  8080 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-06 16:56:12.548  7753  8085 V BtOppRfcommListener: Starting RFCOMM listener....
09-06 16:56:12.549  1033  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:12.550  7753  8085 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 16:56:12.551  7753  8080 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b4c2594 on behalf of 
,09-06 16:56:12.551  7753  8085 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
09-06 16:56:12.552  7753  8085 V BtOppRfcommListener: Started RFCOMM listener....
09-06 16:56:12.552  7753  8085 I BtOppRfcommListener: Accept thread started.
09-06 16:56:12.552  7753  8085 V BtOppRfcommListener: Accepting connection...
09-06 16:56:12.553  7753  8083 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-06 16:56:12.553  7753  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 16:56:12.557  7753  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1757483d on behalf of 
09-06 16:56:12.558  7753  8084 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 16:56:12.560  7753  8084 V BluetoothOppNotification: outbound notification was removed.
,09-06 16:56:12.560  7753  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 16:56:12.561  7753  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@245a8832 on behalf of 
09-06 16:56:12.562  7753  8084 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 16:56:12.563  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@220a64ca
09-06 16:56:12.563  7753  7753 V BluetoothFtpService: Ftp Service onCreate
09-06 16:56:12.563  7753  7753 I BluetoothFtpService: Ftp Service onCreate
09-06 16:56:12.564  7753  7753 V BluetoothFtpService: Ftp Service onStartCommand
,09-06 16:56:12.564  7753  7753 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:12.564  7753  7753 V BluetoothFtpService: Starting Listening on sockets
09-06 16:56:12.564  7753  8084 V BluetoothOppNotification: inbound notification was removed.
09-06 16:56:12.564  7753  7753 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 16:56:12.564  7753  7753 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 16:56:12.564  7753  7753 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 16:56:12.564  7753  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 16:56:12.565  7753  7753 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:12.565  7753  7753 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-06 16:56:12.565  7753  7753 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 16:56:12.567  7753  7753 V BtOppService: ContentObserver received notification
09-06 16:56:12.567  7753  7753 V BtOppService: ContentObserver received notification
09-06 16:56:12.567  7753  7753 V BluetoothFtpService: Handler(): got msg=1
09-06 16:56:12.569  7753  8086 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 16:56:12.569  7753  7753 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-06 16:56:12.569  7753  7753 V BluetoothFtpService: Ftp Service initSocket
09-06 16:56:12.569  7753  8086 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 16:56:12.570  7753  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6900700 on behalf of 
09-06 16:56:12.571  7753  8086 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17752b39 on behalf of 
09-06 16:56:12.572  1033  1740 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:12.572  7753  8086 V BluetoothOppNotification: update too frequent, put in queue
09-06 16:56:12.573  7753  8086 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-06 16:56:12.573  7753  7753 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
09-06 16:56:12.575  7753  7753 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-06 16:56:12.578  7753  8087 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-06 16:56:12.592  7753  7753 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@220a64ca
09-06 16:56:12.592  7753  7753 V BluetoothSapService: Sap Service onCreate
,09-06 16:56:12.594  7753  7753 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:12.594  7753  7753 V BluetoothSapService: state: 12
09-06 16:56:12.594  7753  7753 V BluetoothSapService: Starting SAP server process
,09-06 16:56:12.597  7753  7753 V BluetoothSapService: SAP Service startRfcommListenerThread
09-06 16:56:12.583  8088  8088 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:12.583  8088  8088 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:12.600  7753  8089 V BluetoothSapService: Sap Service initRfcommSocket
09-06 16:56:12.600  1033  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:12.601  7753  8089 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 16:56:12.602  7753  8089 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-06 16:56:12.602  7753  8089 V BluetoothSapService: Succeed to create listening socket 
09-06 16:56:12.603  7753  8089 V BluetoothSapService: Accepting socket connection...
09-06 16:56:12.619  8088  8088 V BT_SAP  : Event pipe created
09-06 16:56:12.619  8088  8088 V BT_SAP  : create_server_socket qcom.sap.server
09-06 16:56:12.619  8088  8088 V BT_SAP  : created socket fd 6
,09-06 16:56:12.944  6729  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:12.944  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:12.944  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:56:12.944  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:12.944  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:12.944  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:12.944  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:12.944  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:12.957  6729  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:56:12.961  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:12.961  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@238ed4ff added. We now have 8 listener(s)
09-06 16:56:12.961  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:56:12.968  1033  1049 D WifiServiceImplEx: setWifiEnabled: false pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 16:56:12.968  1033  1049 D WifiService: setWifiEnabled: false pid=6729, uid=10118
09-06 16:56:12.968  1033  1049 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 16:56:12.973  6729  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:12.974  1033  1048 D WifiServiceImplEx: setWifiEnabled: true pid=6729, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 16:56:12.975  1033  1048 D WifiService: setWifiEnabled: true pid=6729, uid=10118
09-06 16:56:12.975  1033  1048 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 16:56:12.994  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 16:56:12.995  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 16:56:12.995  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-06 16:56:12.996  1033  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-06 16:56:12.996  1033  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-06 16:56:12.999  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-06 16:56:12.999  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 16:56:12.999  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-06 16:56:12.999  1033  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 16:56:12.999  1033  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-06 16:56:12.999  1033  1537 E WifiHW  : unknown target_country: EU , set to default
09-06 16:56:12.999  1033  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-06 16:56:12.999  1033  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-06 16:56:12.999  1033  1537 I WifiUtil: gEnableBmps=1
09-06 16:56:13.549  7753  7753 V BluetoothOppNotification: new notify threadi!
09-06 16:56:13.549  7753  7753 V BluetoothOppNotification: send delay message
,09-06 16:56:13.572   318   893 D SoftapController: Softap fwReload - Ok
,09-06 16:56:13.602  1033  1537 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (599ms)
,09-06 16:56:13.607  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 16:56:13.607  1033  1095 D Tethering: InitialState.processMessage what=4
09-06 16:56:13.607  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-06 16:56:13.624   318   893 D CommandListener: Setting iface cfg
09-06 16:56:13.624   318   893 D CommandListener: Trying to bring down wlan0
09-06 16:56:13.626   318   893 D CommandListener: Clearing all IP addresses on wlan0
09-06 16:56:13.633  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 16:56:13.633  6960  6960 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,09-06 16:56:13.634  6960  6960 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 16:56:13.634  6960  6960 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 16:56:13.634  1033  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-06 16:56:13.635  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 16:56:13.642  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 16:56:13.642  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
09-06 16:56:13.642  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 16:56:13.643  8119  8119 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 16:56:13.643  8119  8119 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:13.654  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-06 16:56:13.655  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:13.659  1033  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-06 16:56:13.659  1033  1537 D WifiMonitor: connecting to supplicant
09-06 16:56:13.667  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-06 16:56:13.682  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:13.710  8119  8119 I wpa_supplicant: Successfully initialized wpa_supplicant
09-06 16:56:13.710  7753  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-06 16:56:13.709  6960  6960 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 16:56:13.711  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 16:56:13.711  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 16:56:13.711  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 16:56:13.711  6960  6960 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 16:56:13.711  6960  6960 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 16:56:13.717  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 16:56:13.717  6960  6960 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 16:56:13.717  6960  6960 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 16:56:13.717  6960  6960 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 16:56:13.719  7753  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6f441f5 on behalf of 
,09-06 16:56:13.720  7753  8108 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 16:56:13.721  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-06 16:56:13.723  6960  6960 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 16:56:13.723  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 16:56:13.723  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 16:56:13.723  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 16:56:13.723  6960  6960 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 16:56:13.723  6960  6960 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 16:56:13.731  7753  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 16:56:13.743  7753  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a96eb8a on behalf of 
09-06 16:56:13.744  7753  8108 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-06 16:56:13.758  8119  8119 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 16:56:13.758  8119  8119 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-06 16:56:13.759  7753  8108 V BluetoothOppNotification: outbound notification was removed.
09-06 16:56:13.759  7753  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-06 16:56:13.766  1033  1713 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8128 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-06 16:56:13.767  7753  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4c285fb on behalf of 
09-06 16:56:13.768  7753  8108 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 16:56:13.770  7753  8108 V BluetoothOppNotification: inbound notification was removed.
09-06 16:56:13.770  7753  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 16:56:13.771  7753  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26c7b618 on behalf of 
,09-06 16:56:13.818  8119  8119 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 16:56:13.861  1033  1049 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8150 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 16:56:13.869  8128  8148 W FormManager: Network not available. Please check & try again.
09-06 16:56:13.876  8128  8149 V FormManager: Network unavailable.
,09-06 16:56:13.878  8128  8149 V FormManager: Network unavailable.
09-06 16:56:13.883  8119  8119 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-06 16:56:13.893  8119  8119 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-06 16:56:13.894  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-06 16:56:13.895  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-06 16:56:13.895  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-06 16:56:13.896  1033  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-06 16:56:13.896  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-06 16:56:13.896  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-06 16:56:13.896  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-06 16:56:13.896  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-06 16:56:13.896  1033  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:56:13.897  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:56:13.897  1033  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-06 16:56:13.897  1033  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-06 16:56:13.898  1033  2071 I ActivityManager: Killing 7240:com.android.chrome/u0a57 (adj 15): empty #17
09-06 16:56:13.898  1033  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-06 16:56:13.898  1033  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-06 16:56:13.899  1033  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,09-06 16:56:13.921  8150  8150 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 16:56:13.941  1033  1977 W libprocessgroup: failed to open /acct/uid_10057/pid_7240/cgroup.procs: No such file or directory
09-06 16:56:13.941  1033  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 16:56:13.941  1033  1537 E WifiStateMachine: useWiFiOffloading() : false
09-06 16:56:13.941  1033  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-06 16:56:13.943  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:13.943  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:13.943  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:13.943  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:13.943  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 16:56:13.943  1033  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
09-06 16:56:13.944  1033  1537 D WifiNative-wlan0: SET update_config 1: returned true
09-06 16:56:13.944  1033  1537 D WifiConfigStore: Loading config and enabling all networks 
09-06 16:56:13.944  1033  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
,09-06 16:56:13.944  1033  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-06 16:56:13.945  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:13.945  1942  1942 D WfdService: Waiting for WifiP2p enabling
09-06 16:56:13.948  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-06 16:56:13.950  1033  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-06 16:56:13.950  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 16:56:13.951  1033  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-06 16:56:13.955  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:13.955  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:13.955  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:56:13.955  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:13.955  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:13.955  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:13.955  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:13.955  6729  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:56:13.957  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:13.958  1033  1977 I ActivityManager: Killing 7261:com.lge.drmservice/u0a62 (adj 15): empty #17
09-06 16:56:13.959  6729  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:56:13.962  1033  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-06 16:56:13.962  1033  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 16:56:13.987  1033  1049 W libprocessgroup: failed to open /acct/uid_10062/pid_7261/cgroup.procs: No such file or directory
,09-06 16:56:13.990  1033  1537 D WifiStateMachine: enableVerboseLogging : level 2
09-06 16:56:13.990  1033  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-06 16:56:13.991  1033  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-06 16:56:13.991  1033  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-06 16:56:13.991  1033  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-06 16:56:13.991  1033  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-06 16:56:13.991  1033  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-06 16:56:13.991  1033  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-06 16:56:13.991  1033  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-06 16:56:13.992  1033  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-06 16:56:13.992  1033  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-06 16:56:13.992  1033  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-06 16:56:13.992  1033  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-06 16:56:13.992  1033  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-06 16:56:13.993  1033  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-06 16:56:13.993  1033  1537 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 16:56:13.993  1033  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-06 16:56:13.994  1033  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-06 16:56:13.994  1942  1942 D WfdsService: Supplicant Connection state is changed : true
09-06 16:56:13.994  1033  1537 D WifiNative-HAL: Setting external_sim to 1
09-06 16:56:13.994  1033  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-06 16:56:13.994  1942  2350 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-06 16:56:13.994  1942  2350 D WfdsService: Set the WFDS Monitor: true
09-06 16:56:13.994  1942  2350 D WfdsMonitor: WfdsMonitorThread create
09-06 16:56:13.994  7782  7782 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:13.994  1942  2350 D WfdsMonitor: WFDS Monitor is created and started
09-06 16:56:13.994  1942  2350 D WfdsService: WiFi: Supplicant connection re-established
09-06 16:56:13.994  1033  1537 D WifiNative-wlan0: SET external_sim 1: returned true
09-06 16:56:13.994  1033  1537 I WifiNative-HAL: startHal
09-06 16:56:13.995  1033  1537 D wifi    : setting scan oui 0x957c5060
09-06 16:56:13.995  1033  1537 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 16:56:13.995  1033  1537 I WifiNative-HAL: startHal
09-06 16:56:13.995  1942  8171 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-06 16:56:13.995  1033  1537 D wifi    : setting scan oui 0x957c5060
09-06 16:56:13.995  1942  8171 E CtrlSupplicant: Succeed to open control connection
09-06 16:56:13.996  1033  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-06 16:56:13.996  1942  8171 E CtrlSupplicant: Succeed to open monitor connection
09-06 16:56:13.996  1033  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-06 16:56:13.996  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-06 16:56:13.996  8119  8119 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-06 16:56:13.996  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-06 16:56:13.997  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 16:56:13.997  8119  8119 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 16:56:13.997  1942  8171 D WfdsMonitor: Supplicant connection established
09-06 16:56:13.997  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 16:56:13.997  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-06 16:56:13.997  1942  2350, D WfdsService: Connected to the supplicant for wfds
09-06 16:56:13.997  8119  8119 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-06 16:56:13.997  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-06 16:56:13.997  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 16:56:13.997  8119  8119 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 16:56:13.998  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 16:56:13.998  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 16:56:13.998  8119  8119 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 16:56:13.998  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 16:56:13.998  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-06 16:56:13.998  8119  8119 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-06 16:56:13.998  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-06 16:56:13.998  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 16:56:13.999  8119  8119 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 16:56:13.999  1033  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 16:56:13.999  1033  1537 E WifiNative: : [139,387,905 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-06 16:56:14.000  1033  1537 D WifiNative-wlan0: doBoolean: RECONNECT
09-06 16:56:14.000  1033  1537 D WifiNative-wlan0: RECONNECT: returned true
09-06 16:56:14.000  1033  1537 D WifiNative-wlan0: doString: [STATUS]
09-06 16:56:14.000  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-06 16:56:14.000  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-06 16:56:14.000  1033  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 16:56:14.000  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 16:56:14.001  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
09-06 16:56:14.002  1033  1536 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 16:56:14.004   318   893 D CommandListener: Setting iface cfg
09-06 16:56:14.004   318   893 D CommandListener: Trying to bring up p2p0
09-06 16:56:14.005  1033  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 16:56:14.005  1033  1536 D LGWifiP2pService: P2pEnablingState
09-06 16:56:14.005  1033  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 16:56:14.005  1033  1536 D LGWifiP2pService: P2p socket connection successful
09-06 16:56:14.005  1033  1536 D LGWifiP2pService: P2pEnabledState
09-06 16:56:14.007  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 16:56:14.007  1033  1033 D RttService: SCAN_AVAILABLE : 3
09-06 16:56:14.007  1033  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.007  1033  1555 I WifiNative-HAL: startHal
09-06 16:56:14.008  1033  1556 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.008  1033  1555 D wifi    : getting scan capabilities on interface[1] = 0x957c5060
09-06 16:56:14.008  1033  1555 D wifi    : failed to get capabilities : -3
09-06 16:56:14.008  1033  1555 E WifiScanningService: could not get scan capabilities
09-06 16:56:14.009  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-06 16:56:14.010  8150  8150 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:56:14.010  1033  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-06 16:56:14.010  6729  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:14.010  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:14.010  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:56:14.010  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:14.010  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:14.010  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:14.010  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:14.010  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:56:14.010  1033  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-06 16:56:14.010  1033  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-06 16:56:14.011  1033  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-06 16:56:14.011  6729  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:56:14.011  1033  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-06 16:56:14.012  1033  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-06 16:56:14.012  1033  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-06 16:56:14.012  8119  8119 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-06 16:56:14.013  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 16:56:14.014  1033  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-06 16:56:14.014  1033  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-06 16:56:14.014  1033  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-06 16:56:14.014  1033  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-06 16:56:14.015  8119  8119 E wpa_supplicant: disconnect_rssi_lvl: -100
09-06 16:56:14.015  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 16:56:14.016  1033  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 16:56:14.016  1033  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 16:56:14.016  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-06 16:56:14.016  1033  1536 D LGWifiP2pService: sending p2p connection changed broadcast
09-06 16:56:14.017  8119  8119 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-06 16:56:14.017  8119  8119 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 16:56:14.018  8119  8119 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 16:56:14.018  8119  8119 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.018  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 16:56:14.018  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 16:56:14.018  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 16:56:14.018  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 16:56:14.018  1033  8168 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 16:56:14.018  8119  8119 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.018  1033  8168 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.018  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.019  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.019  1033  8168 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 16:56:14.019  1033  8168 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.019  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.019  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.019  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-06 16:56:14.019  1942  1942 D WfdsService: WifiP2pState is changed : true
09-06 16:56:14.019  1942  2350 D WfdsService: Receive the WFDS_ENABLE Method
09-06 16:56:14.019  1942  2350 D WfdsService: Set the WFDS Monitor: true
09-06 16:56:14.019  1942  2350 D WfdsService: Connected to the supplicant for wfds
09-06 16:56:14.019  1942  2350 D WfdsJNI : doCommand: WFDS_SET TRUE
09-06 16:56:14.019  8119  8119 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-06 16:56:14.020  1942  8171 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 16:56:14.020  1942  8171 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 16:56:14.020  6729  6793 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-06 16:56:14.020  1942  2350 D WfdsService: selectPreferredScanChannel [36]
09-06 16:56:14.020  1942  2350 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-06 16:56:14.021  6729  6793 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-06 16:56:14.022  1033  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-06 16:56:14.024  1033  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-06 16:56:14.024  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-06 16:56:14.024  1942  1942 D WfdsService: isConnected: false
09-06 16:56:14.024  1033  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-06 16:56:14.024  6729  6793 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@36ff16e9 Bundle[{}]
09-06 16:56:14.024  1033  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
09-06 16:56:14.025  1033  1536 D WifiNative-p2p0: SET device_name G3: returned true
09-06 16:56:14.025  1033  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-06 16:56:14.025  1033  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-06 16:56:14.025  1033  1536 D LGWifiP2pService: before postfix = G3
09-06 16:56:14.025  1033  1536 D WifiServerS,erviceExt: postfix byte check : 2
09-06 16:56:14.025  1033  1536 D LGWifiP2pService: after postfix = G3
09-06 16:56:14.025  1033  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-06 16:56:14.025  6729  6793 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 16:56:14.025  6729  6793 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-06 16:56:14.025  1033  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-06 16:56:14.026  1033  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-06 16:56:14.026  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-06 16:56:14.026  1033  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-06 16:56:14.026  1033  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-06 16:56:14.026  6729  6793 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-06 16:56:14.026  8119  8119 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-06 16:56:14.026  8119  8119 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 16:56:14.026  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-06 16:56:14.027  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 16:56:14.027  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 16:56:14.027  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 16:56:14.027  6729  6793 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 16:56:14.027  1033  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-06 16:56:14.027  1033  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-06 16:56:14.027  6729  6793 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-06 16:56:14.028  1033  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-06 16:56:14.028  1033  1537 D WifiNative-wlan0: doBoolean: SCAN
09-06 16:56:14.029  6729  6793 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-06 16:56:14.029  1033  1537 D WifiNative-wlan0: SCAN: returned false
09-06 16:56:14.029  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=139418  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 16:56:14.030  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=139418  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 16:56:14.030  1033  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-06 16:56:14.030  1033  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-06 16:56:14.030  1033  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 16:56:14.031  1033  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 16:56:14.031  1033  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 16:56:14.031  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:56:14.031  1033  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 16:56:14.031  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:56:14.032  1033  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 16:56:14.032  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:14.033  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:14.033  1033  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-06 16:56:14.033  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-06 16:56:14.034  1033  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-06 16:56:14.034  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress
09-06 16:56:14.034  1033  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-06 16:56:14.034  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.035  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.035  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 16:56:14.036  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 16:56:14.036  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
09-06 16:56:14.038  6729  6793 I System.out: Running OutgoingSocketThread
09-06 16:56:14.039  1033  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-06 16:56:14.039  1033  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-06 16:56:14.040  1033  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
09-06 16:56:14.040  1033  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-06 16:56:14.040  1033  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-06 16:56:14.040  1033  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-06 16:56:14.041  1033  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-06 16:56:14.041  1033  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-06 16:56:14.041  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
09-06 16:56:14.041  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-06 16:56:14.041  1942  1942 D WfdsService: Up,date P2p Interface State: 3
,09-06 16:56:14.042  6729  8175 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 891)
09-06 16:56:14.043  6729  8175 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 52971
09-06 16:56:14.043  6729  8175 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-06 16:56:14.044  8128  8173 W FormManager: Network not available. Please check & try again.
09-06 16:56:14.046  8128  8174 V FormManager: Network unavailable.
09-06 16:56:14.049  8128  8174 V FormManager: Network unavailable.
09-06 16:56:14.052  1033  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-06 16:56:14.052  1033  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-06 16:56:14.052  1033  1536 D LGWifiP2pService: InactiveState
09-06 16:56:14.052  1033  1536 D LGWifiP2pService: InactiveState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.052  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.052  1033  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,09-06 16:56:14.053  8119  8119 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 16:56:14.054  8119  8119 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 16:56:14.055  1033  8168 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 16:56:14.055  8119  8119 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
,09-06 16:56:14.055  1033  8168 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 16:56:14.055  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 16:56:14.055  8119  8119 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.055  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 16:56:14.055  1033  8168 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 16:56:14.055  1033  8168 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.055  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.055  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.055  8119  8119 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.055  1942  8171 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 16:56:14.056  1942  8171 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 16:56:14.056  1942  8171 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 16:56:14.056  1033  8168 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 16:56:14.056  1033  8168 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.056  1033  8168 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.056  1033  8168 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 16:56:14.056  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 16:56:14.056  1033  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-06 16:56:14.056  1033  1536 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.056  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.056  4759  4759 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 16:56:14.057  1033  1536 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.057  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.057  1033  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.058  1033  1536 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.058  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.058  1033  1536 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.058  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 16:56:14.058  1033  1536 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.058  1033  1536 D LGWifiP2pService: P2pEn,abledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.058  1033  1536 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.059  1033  1536 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.059  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.059  1033  1536 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.059  1033  1033 E WifiServerServiceExt: No p2p device connected
09-06 16:56:14.059  1942  2350 W WfdsService: DefaultState - msg [9441285] is not handled
09-06 16:56:14.061  4759  4759 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 16:56:14.067  4759  8176 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 16:56:14.070  4759  8177 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 16:56:14.070  4759  8177 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 16:56:14.120  1033  1049 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8178 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-06 16:56:14.144   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 471us total 24.017ms
,09-06 16:56:14.165   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 429us total 20.672ms
,09-06 16:56:14.184   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 372us total 18.044ms
09-06 16:56:14.233  7853  7864 E UEI.SmartControl: file observer is disposed!
,09-06 16:56:14.253  8178  8178 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 16:56:14.253  8178  8178 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-06 16:56:14.265  8178  8178 V [BNRBootReceiver]: Boot Receiver Return
09-06 16:56:14.266  8178  8178 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-06 16:56:14.321  1033  1905 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8197 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 16:56:14.325  1033  1905 I ActivityManager: Killing 7285:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-06 16:56:14.389  1033  1574 W libprocessgroup: failed to open /acct/uid_10085/pid_7285/cgroup.procs: No such file or directory
,09-06 16:56:14.417  8197  8197 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 16:56:14.448  8197  8197 D PluginManager: init()
,09-06 16:56:14.524  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-06 16:56:14.524  1033  8168 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-06 16:56:14.525  8119  8119 E wpa_supplicant: USIM:  scard_init function
09-06 16:56:14.525  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-06 16:56:14.525  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: WPS-AP-AVAILABLE 
09-06 16:56:14.525  1033  8168 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-06 16:56:14.525  8119  8119 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-06 16:56:14.526  1033  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-06 16:56:14.527  1033  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
,09-06 16:56:14.529  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-06 16:56:14.529  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-06 16:56:14.529  1033  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-06 16:56:14.530  1033  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
09-06 16:56:14.530  1033  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-06 16:56:14.537  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=139926  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-06 16:56:14.546  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=139935  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 16:56:14.548  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:56:14.548  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:56:14.549  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.549  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.549  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 16:56:14.550  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.550  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.550  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 16:56:14.550  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 16:56:14.550  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-06 16:56:14.551  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:14.554  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:56:14.554  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:56:14.555  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 16:56:14.642  8119  8119 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-06 16:56:14.642  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-06 16:56:14.642  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-06 16:56:14.642  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-06 16:56:14.642  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-06 16:56:14.642  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 16:56:14.643  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 16:56:14.643  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=140032  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 16:56:14.644  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=140032  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 16:56:14.644  1033  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 54 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140033
09-06 16:56:14.645  1033  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 54 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140033
,09-06 16:56:14.645  1033  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 54 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140034
09-06 16:56:14.646  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 54 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140034
09-06 16:56:14.646  1033  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 54 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=140035
09-06 16:56:14.647  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=140035  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 16:56:14.650  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:56:14.650  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:56:14.651  8119  8119 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 16:56:14.651  8119  8119 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 16:56:14.652  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 16:56:14.652  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 16:56:14.652  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-06 16:56:14.652  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 16:56:14.652  1033  8168 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 16:56:14.652  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-06 16:56:14.652  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 16:56:14.653  1033  8168 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 16:56:14.653  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 16:56:14.653  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 16:56:14.654  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.655  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.655  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 16:56:14.655  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:14.657  1033  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-06 16:56:14.664  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.664  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.664  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-06 16:56:14.664  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=140048  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 16:56:14.665  1033  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140054  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 16:56:14.666  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=140054  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 16:56:14.667  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 16:56:14.667  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-06 16:56:14.667  1033  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140055
09-06 16:56:14.667  1033  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=140056
09-06 16:56:14.668  1033  1537 D WifiNative-wlan0: doString: [STATUS]
09-06 16:56:14.668  1033  8168 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 16:56:14.668  1033  8168 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 16:56:14.669  1033  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 16:56:14.671  1033  1537 I WifiServiceExtension: setVHTCapabilityType  : false
09-06 16:56:14.676  1033  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-06 16:56:14.676  1033  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-06 16:56:14.676  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:56:14.676  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:56:14.677  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:14.683  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.683  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.683  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 16:56:14.686  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.686  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 16:56:14.686  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 16:56:14.695  1033  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,09-06 16:56:14.695  1033  1543 D ConnectivityService: Got NetworkAgent Messenger
09-06 16:56:14.695  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 16:56:14.695  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 16:56:14.696  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-06 16:56:14.696  1033  1543 D ConnectivityService: NetworkAgent connected
09-06 16:56:14.696  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 16:56:14.696  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 16:56:14.697  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:56:14.698  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:56:14.699  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:14.701  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:56:14.701  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:56:14.701  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 16:56:14.701  1033  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 16:56:14.701  1033  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 16:56:14.701  1033  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 16:56:14.701  1033  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-06 16:56:14.704  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:14.706  1033  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 16:56:14.707   318   893 D CommandListener: Setting iface cfg
09-06 16:56:14.710  1033  1537 E WifiStateMachine: Start Dhcp Watchdog 3
09-06 16:56:14.710  1033  8218 D DhcpStateMachine: StoppedState
09-06 16:56:14.710  1033  8218 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.710  1033  8218 D DhcpStateMachine: WaitBeforeStartState
09-06 16:56:14.710  1033  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=140099  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 16:56:14.711  1033  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=140099  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 16:56:14.711  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=140100  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 16:56:14.712  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:56:14.712  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:56:14.713  1033  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:56:14.713  1033  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:56:14.714  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:56:14.714  1033  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 16:56:14.715  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 16:56:14.715  1033  1033 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,09-06 16:56:14.719  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 16:56:14.719  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-06 16:56:14.720  1033  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=140108  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 16:56:14.720  1033  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=140109  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 16:56:14.721  1033  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=140109  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 16:56:14.722  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13698] from screen [on:0 period:-7806] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 16:56:14.723  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-7805] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 16:56:14.723  1033  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-06 16:56:14.726  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:14.728  1033  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-06 16:56:14.728  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:56:14.728  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:56:14.729  1033  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:56:14.729  1033  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:56:14.730  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:56:14.730  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:56:14.730  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 16:56:14.731  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=189,0,0
09-06 16:56:14.731  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=189,0,0
09-06 16:56:14.731  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-06 16:56:14.731  8119  8119 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-06 16:56:14.732  1033  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-06 16:56:14.732  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 0
09-06 16:56:14.732  1033  1537 D WifiNative-wlan0: SET ps 0: returned true
09-06 16:56:14.732  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-06 16:56:14.733  8119  8119 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-06 16:56:14.733  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-06 16:56:14.733  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23ea92f target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.733  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23ea92f target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.733  1033  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-06 16:56:14.733  1033  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 16:56:14.733  1033  8218 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.733  1033  8218 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-06 16:56:14.733  1033  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 16:56:14.734   318   893 D CommandListener: Setting iface cfg
09-06 16:56:14.735   318   893 D CommandListener: Trying to bring up wlan0
09-06 16:56:14.735  1033  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-06 16:56:14.736  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 16:56:14.736  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 16:56:14.737  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 16:56:14.737  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 16:56:14.738  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:56:14.739  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:56:14.739  1033  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,09-06 16:56:14.740  1033  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:56:14.740  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:56:14.740  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 16:56:14.741  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 16:56:14.742  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 16:56:14.742  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 16:56:14.743  1033  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.743  1033  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.743  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 16:56:14.743  8119  8119 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 16:56:14.744  1033  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 16:56:14.744  1033  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-06 16:56:14.744  8119  8119 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-06 16:56:14.744  1033  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-06 16:56:14.744  1033  1537 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 16:56:14.760  1033  1537 D WifiNative-wlan0: SET ps 1: returned true
,09-06 16:56:14.761  1033  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 16:56:14.761  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 16:56:14.761  1033  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 16:56:14.762  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 16:56:14.763  1033  1543 D ConnectivityService: ignoring duplicate network state non-change
09-06 16:56:14.766  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.766  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.767  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 16:56:14.767  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:56:14.767  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:56:14.768  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:14.771  1033  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 16:56:14.772  1033  1543 D ConnectivityService: Adding iface wlan0 to network 102
,09-06 16:56:14.778  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.778  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.778  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 16:56:14.783  1033  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 16:56:14.786  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 16:56:14.786  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.786  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 16:56:14.786  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 16:56:14.786  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-06 16:56:14.789  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-06 16:56:14.791  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:56:14.791  1600  1600 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 16:56:14.792  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:14.795  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:56:14.795  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 16:56:14.795  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:14.796  1033  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 16:56:14.796  1033  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-06 16:56:14.797  1033  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-06 16:56:14.798   318   893 E Netd    : netlink response contains error (File exists)
09-06 16:56:14.798  1033  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-06 16:56:14.800  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.800  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:56:14.800  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 16:56:14.800  1033  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-06 16:56:14.800  1033  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-06 16:56:14.800  1033  1543 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-06 16:56:14.801  1033  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 16:56:14.801  1033  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-06 16:56:14.801  1033  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-06 16:56:14.801  1033  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-06 16:56:14.801  1033  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 16:56:14.801  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:56:14.801  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 16:56:14.801  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:56:14.801  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-06 16:56:14.801  1033  1543 D ConnectivityService: currentScore = 0, newScore = 20
09-06 16:56:14.801  1033  1543 D ConnectivityService:    accepting network in place of null
09-06 16:56:14.801  1033  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:56:14.801  1600  1600 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:56:14.802  1033  8217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.802  1033  8217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-06 16:56:14.802  1600  1600 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 16:56:14.802  1033  8217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:14.802  1033  8217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-06 16:56:14.802  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:14.803  1033  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:56:14.803  1033  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 16:56:14.804   318  8228 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-06 16:56:14.807  1854  1854 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:56:14.807  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 16:56:14.809  1033  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBand,width>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 16:56:14.809  1033  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-06 16:56:14.810  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 16:56:14.811  1033  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:14.811  1033  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-06 16:56:14.811  1033  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-06 16:56:14.813  1033  1543 D ConnectivityService: validation of new default Network = false
09-06 16:56:14.813  1033  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-06 16:56:14.813  1033  1543 D DSQN    : enableDataServiceNotify 
09-06 16:56:14.813  1033  1543 D DSQN    : start dsqn bin
09-06 16:56:14.815  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-06 16:56:14.816  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 16:56:14.816  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 16:56:14.816  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-06 16:56:14.813  8229  8229 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:14.813  8229  8229 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:14.822  1033  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-06 16:56:14.822  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:56:14.822  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:56:14.822  1033  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-06 16:56:14.829  1600  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 16:56:14.833  8229  8229 E DSQN    : DSQN ssw
09-06 16:56:14.834  1033  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-06 16:56:14.848  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-06 16:56:14.848  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 16:56:14.849  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:14.860   318  8228 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-06 16:56:14.900   318  8228 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-06 16:56:14.935  1033  8218 D DhcpStateMachine: DHCPV4 request on wlan0
09-06 16:56:14.935  1033  8218 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-06 16:56:14.935  1033  8218 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-06 16:56:14.933  8233  8233 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:14.942   318   892 D LGDataListener: argv[0]=dsqncommand
09-06 16:56:14.942   318   892 D LGDataListener: argv[1]=wlan0
09-06 16:56:14.942   318   892 D LGDataListener: argv[2]=1
09-06 16:56:14.942   318   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-06 16:56:14.943  1033  1093 D DSQN    : DSQM DsqnNotification wlan0  1
09-06 16:56:14.943  1033  1093 D DSQN    : start to monitor internet connection
09-06 16:56:14.933  8233  8233 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 16:56:14.953  8233  8233 I dhcpcd  : version 5.5.6 starting
09-06 16:56:14.955  8233  8233 E dhcpcd  : get_duid: m
09-06 16:56:14.955  8233  8233 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-06 16:56:14.955  8233  8233 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-06 16:56:14.977  1033  8217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 14:56:14 GMT], X-Android-Received-Millis=[1473173774977], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473173774939]}
09-06 16:56:14.977  1033  8217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-06 16:56:14.977  1033  8217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,09-06 16:56:14.977  1033  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-06 16:56:14.978  1033  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-06 16:56:14.978  1033  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 16:56:14.978  1033  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:56:14.978  1033  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 16:56:14.978  1033  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-06 16:56:14.978  1033  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-06 16:56:14.978  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:56:14.978  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:56:14.978  1033  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:56:14.978  1033  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:56:14.978  1033  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 16:56:14.979  1033  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:56:14.979  1033  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 16:56:14.980  1600  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 16:56:14.980  1854  1854 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:56:14.981  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-06 16:56:15.001  1600  1600 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 16:56:15.001  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:15.002  1600  1600 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 16:56:15.005  8233  8233 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-06 16:56:15.005  8233  8233 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 16:56:15.005  8233  8233 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 16:56:15.005  8233  8233 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-06 16:56:15.005  8233  8233 D dhcpcd  : wlan0: sending REQUEST (xid 0x6a11b573), next in 3.15 seconds
09-06 16:56:15.011  8197  8197 W ExternalStrings: load override strings
09-06 16:56:15.011  8197  8197 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 16:56:15.011  8197  8197 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-06 16:56:15.013  8197  8197 D StatusProvider: onCreate
,09-06 16:56:15.027  8233  8233 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-06 16:56:15.041  6729  6793 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 892)
09-06 16:56:15.041  6729  6793 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 892)
,09-06 16:56:15.050  6729  6793 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 897)
09-06 16:56:15.052  6729  6793 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-06 16:56:15.052  6729  6793 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 898)
09-06 16:56:15.058  8233  8233 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-06 16:56:15.058  8233  8233 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-06 16:56:15.059  8233  8233 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,09-06 16:56:15.059  8233  8233 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-06 16:56:15.059  8233  8233 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 16:56:15.059  8233  8233 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 16:56:15.059  8233  8233 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 16:56:15.059  8233  8233 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-06 16:56:15.060  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.061  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24f092cc added. We now have 2 listener(s)
09-06 16:56:15.061  1033  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:15.062  8197  8197 V Signer  : override build config not found
09-06 16:56:15.062  8197  8197 D Signer  : value of property debug is false
09-06 16:56:15.063  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 16:56:15.063  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.063  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.063  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.063  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf0d915 added. We now have 9 listener(s)
09-06 16:56:15.063  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.063  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 16:56:15.065  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:56:15.067  6729  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:56:15.067  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:15.067  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:56:15.067  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:15.067  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:15.067  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.067  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:56:15.067  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:56:15.069  6729  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.069  6729  6793 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:56:15.069  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.069  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e85c21b added. We now have 3 listener(s)
09-06 16:56:15.069  1033  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: v,alid=true callingUser=0 foregroundUser=0
09-06 16:56:15.070  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:15.072  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 16:56:15.072  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.072  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.072  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.072  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bfa0fb8 added. We now have 10 listener(s)
09-06 16:56:15.072  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.073  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:56:15.073  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:15.073  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:56:15.073  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.073  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.073  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:15.073  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.073  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24f092cc removed from the list
09-06 16:56:15.073  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.073  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf0d915 removed from the list
09-06 16:56:15.076  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:15.076  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:56:15.076  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.076  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.076  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.077  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.077  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.077  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.077  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf0d915 not in the list
09-06 16:56:15.077  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.077  6729  6793 D org.thaliproject.p2p.btconne,ctorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.079  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.079  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.079  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.080  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bfa0fb8 removed from the list
09-06 16:56:15.080  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.080  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.080  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.080  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.080  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e85c21b removed from the list
09-06 16:56:15.080  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.081  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a92f191 added. We now have 2 listener(s)
09-06 16:56:15.081  1033  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:15.083  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 16:56:15.083  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.083  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.084  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.084  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5138f6 added. We now have 9 listener(s)
09-06 16:56:15.084  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:56:15.088  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 16:56:15.089  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:56:15.092  6729  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:56:15.092  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:15.092  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:56:15.092  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:15.092  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:15.092  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.092  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:56:15.092  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:56:15.093  6729  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.093  6729  6793 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:56:15.093  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.093  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1c6f64 added. We now have 3 listener(s)
09-06 16:56:15.093  1033  1740 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:15.095  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 16:56:15.095  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.095  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:15.095  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.095  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.095  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@376415cd added. We now have 10 listener(s)
09-06 16:56:15.095  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.095  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:56:15.095  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 16:56:15.095  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:56:15.095  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:56:15.095  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 16:56:15.097  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state change,s
,09-06 16:56:15.102  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 16:56:15.102  1033  1713 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:15.106  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 16:56:15.107  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 16:56:15.108  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 16:56:15.109  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:15.109  8197  8197 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,09-06 16:56:15.110  8197  8197 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-06 16:56:15.111  8197  8197 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-06 16:56:15.111  6729  6793 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 16:56:15.111  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:15.111  8197  8197 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-06 16:56:15.111  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:56:15.111  8197  8197 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-06 16:56:15.113  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:56:15.113  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:15.113  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:56:15.113  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.113  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.113  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:15.113  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.113  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a92f191 removed from the list
09-06 16:56:15.113  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.113  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5138f6 removed from the list
09-06 16:56:15.113  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:56:15.113  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.114  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.114  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.115  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.115  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.115  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.115  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5138f6 not in the list
09-06 16:56:15.115  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.115  8197  8197 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-06 16:56:15.115  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.115  8197  8197 D LGMD,MWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-06 16:56:15.115  8197  8197 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-06 16:56:15.115  8197  8197 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-06 16:56:15.115  8197  8197 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-06 16:56:15.116  8197  8197 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-06 16:56:15.116  8197  8197 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-06 16:56:15.116  8197  8197 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-06 16:56:15.118  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.119  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:56:15.119  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:56:15.119  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.119  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.119  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@376415cd removed from the list
09-06 16:56:15.119  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.119  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.119  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.119  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.119  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1c6f64 removed from the list
09-06 16:56:15.120  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.120  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e31dd0 added. We now have 2 listener(s)
09-06 16:56:15.121  1033  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 16:56:15.123  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 16:56:15.123  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.123  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.123  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.124  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a941c9 added. We now have 9 listener(s)
09-06 16:56:15.124  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.124  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 16:56:15.124  8197  8197 V LGMDMManager: Create singleton instance
09-06 16:56:15.127  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:56:15.131  6729  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:56:15.131  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:15.131  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:56:15.131  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:15.131  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:15.131  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.131  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:56:15.131  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:56:15.132  6729  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.132  6729  6793 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:56:15.134  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:15.136  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:15.136  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.136  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@190cfbef added. We now have 3 listener(s)
09-06 16:56:15.136  1033  1713 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:15.139  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 16:56:15.139  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.139  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.139  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.139  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@292446fc added. We now have 10 listener(s)
09-06 16:56:15.139  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.139  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:56:15.140  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:56:15.140  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 16:56:15.140  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:56:15.140  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:56:15.140  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 16:56:15.143  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 16:56:15.143  1033  1742 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:15.146  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 16:56:15.147  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 16:56:15.149  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 16:56:15.149  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:15.150  6729  6793 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 16:56:15.150  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:56:15.150  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:15.150  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:56:15.150  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.150  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.150  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:15.150  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.150  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e31dd0 removed from the list
09-06 16:56:15.150  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.150  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a941c9 removed from the list
09-06 16:56:15.150  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:56:15.150  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.151  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.151  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.151  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.151  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.151  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.151  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a941c9 not in the list
09-06 16:56:15.152  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.152  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.152  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.153  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:56:15.153  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:56:15.153  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.153  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.153  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@292446fc removed from the list
09-06, 16:56:15.153  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.153  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.153  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.153  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.153  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@190cfbef removed from the list
09-06 16:56:15.153  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.153  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad7680b added. We now have 2 listener(s)
09-06 16:56:15.153  1033  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:15.156  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 16:56:15.156  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.156  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.156  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.156  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ecd6e8 added. We now have 9 listener(s)
09-06 16:56:15.156  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.156  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 16:56:15.159  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:56:15.161  6729  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:56:15.161  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:15.161  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:56:15.161  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:15.161  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:15.161  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.161  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:56:15.161  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:56:15.162  6729  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.162  6729  6793 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:56:15.162  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.162  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f17cba6 added. We now have 3 listener(s)
09-06 16:56:15.163  1033  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:15.164  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:15.166  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:15.167  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 16:56:15.167  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.167  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.167  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.167  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@159279e7 added. We now have 10 listener(s)
09-06 16:56:15.167  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.168  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:56:15.168  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 16:56:15.168  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:56:15.168  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:56:15.168  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 16:56:15.170  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 16:56:15.170  1033  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:15.171  8197  8197 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
09-06 16:56:15.174  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 16:56:15.175  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 16:56:15.176  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 16:56:15.176  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:15.177  6729  6793 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 16:56:15.179  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:56:15.179  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:15.179  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:56:15.180  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.180  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.180  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:15.180  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.180  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad7680b removed from the list
09-06 16:56:15.180  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.180  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ecd6e8 removed from the list
09-06 16:56:15.180  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:56:15.180  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.181  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.181  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.181  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.181  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.182  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.182  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ecd6e8 not in the list
09-06 16:56:15.182  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.182  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.182  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.183  6729  6793 D BluetoothLeScanner: could not find callback wrapper
09-06 16:56:15.183  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:56:15.183  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.183  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.183  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@159279e7 removed from the list
09-06 ,16:56:15.183  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.183  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.183  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.183  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.183  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f17cba6 removed from the list
09-06 16:56:15.184  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.184  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ee4fc32 added. We now have 2 listener(s)
09-06 16:56:15.184  1033  1740 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:15.187  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 16:56:15.187  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.187  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.187  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.187  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d02cd83 added. We now have 9 listener(s)
09-06 16:56:15.187  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:56:15.195  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 16:56:15.196  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:56:15.199  6729  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:56:15.199  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:15.199  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 16:56:15.199  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:15.199  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:15.199  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.199  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:56:15.199  6729  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:56:15.201  6729  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 16:56:15.201  6729  6793 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:56:15.201  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:15.201  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c892f39 added. We now have 3 listener(s)
09-06 16:56:15.201  1033  1742 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 16:56:15.202  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:15.203  6729  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:15.205  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 16:56:15.205  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:15.205  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:15.206  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:15.206  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e2a97e added. We now have 10 listener(s)
09-06 16:56:15.206  6729  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:15.206  6729  6793 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:56:15.206  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:15.206  6729  6793 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:56:15.206  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.206  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.206  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:15.206  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.206  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ee4fc32 removed from the list
09-06 16:56:15.206  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.206  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d02cd83 removed from the list
09-06 16:56:15.206  6729  6793 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:56:15.206  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.207  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.207  6729  6793 D org.thal,iproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.209  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.209  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.209  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.209  6729  6793 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d02cd83 not in the list
09-06 16:56:15.209  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.209  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.210  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:15.210  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:15.210  6729  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:15.210  6729  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e2a97e removed from the list
09-06 16:56:15.210  6729  6793 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:15.210  6729  6793 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:15.210  6729  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:15.210  6729  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:15.210  6729  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c892f39 removed from the list
09-06 16:56:15.211  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 16:56:15.211  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 16:56:15.212  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 16:56:15.212  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:56:15.212  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 16:56:15.212  6729  6793 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 16:56:15.217  8197  8197 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:56:15.217  8197  8259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 16:56:15.223  6729  8262 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 905, name: My test thread name)
09-06 16:56:15.223  6729  8262 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 905, thread name: My test thread name)
09-06 16:56:15.223  6729  8262 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 905, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 16:56:15.226  6729  8263 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 907, name: My test thread name)
09-06 16:56:15.226  6729  8263 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 907, thread name: My test thread name)
,09-06 16:56:15.226  6729  8263 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 907, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 16:56:15.228  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 16:56:15.229  6729  6793 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-06 16:56:15.229  6729  6793 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 16:56:15.229  6729  6793 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 16:56:15.229  6729  6793 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 16:56:15.230  6729  6793 D com.test.thalitest.ThaliTestRunner: Total duration: 22816 ms
09-06 16:56:15.231  6729  6793 I jxcore-log: *Native tests were executed*
09-06 16:56:15.231  6729  6793 I jxcore-log: 
09-06 16:56:15.231  6729  6793 I jxcore-log: Total number of executed tests:  80
09-06 16:56:15.231  6729  6793 I jxcore-log: 
09-06 16:56:15.231  6729  6793 I jxcore-log: Number of passed tests:  80
09-06 16:56:15.231  6729  6793 I jxcore-log: 
09-06 16:56:15.231  6729  6793 I jxcore-log: Number of failed tests:  0
09-06 16:56:15.231  6729  6793 I jxcore-log: 
09-06 16:56:15.232  6729  6793 I jxcore-log: Number of ignored tests:  0
09-06 16:56:15.232  6729  6793 I jxcore-log: 
09-06 16:56:15.232  6729  6793 I jxcore-log: Total duration:  22816
09-06 16:56:15.232  6729  6793 I jxcore-log: 
09-06 16:56:15.232  6729  6793 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 16:56:15.232  6729  6793 I jxcore-log: 
09-06 16:56:15.238  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.238  6729  6793 I jxcore-log: 
,09-06 16:56:15.243  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.243  6729  6793 I jxcore-log: 
09-06 16:56:15.244  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.244  6729  6793 I jxcore-log: 
09-06 16:56:15.245  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.245  6729  6793 I jxcore-log: 
09-06 16:56:15.246  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.246  6729  6793 I jxcore-log: 
09-06 16:56:15.246  6729  6729 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 16:56:15.248  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.248  6729  6793 I jxcore-log: 
,09-06 16:56:15.249  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:15.251  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.251  6729  6793 I jxcore-log: 
09-06 16:56:15.253  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.253  6729  6793 I jxcore-log: 
09-06 16:56:15.254  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 16:56:15.254  6729  6793 I jxcore-log: 
09-06 16:56:15.259  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.259  6729  6793 I jxcore-log: 
09-06 16:56:15.260  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.260  6729  6793 I jxcore-log: 
09-06 16:56:15.262  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 16:56:15.262  6729  6793 I jxcore-log: 
09-06 16:56:15.263  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 16:56:15.263  6729  6793 I jxcore-log: 
09-06 16:56:15.263  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 16:56:15.263  6729  6793 I jxcore-log: 
09-06 16:56:15.264  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.264  6729  6793 I jxcore-log: 
09-06 16:56:15.265  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.265  6729  6793 I jxcore-log: 
,09-06 16:56:15.266  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.266  6729  6793 I jxcore-log: 
09-06 16:56:15.266  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.266  6729  6793 I jxcore-log: 
09-06 16:56:15.267  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.267  6729  6793 I jxcore-log: 
09-06 16:56:15.268  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.268  6729  6793 I jxcore-log: 
09-06 16:56:15.269  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.269  6729  6793 I jxcore-log: 
09-06 16:56:15.270  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 16:56:15.270  6729  6793 I jxcore-log: 
09-06 16:56:15.271  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 16:56:15.271  6729  6793 I jxcore-log: 
09-06 16:56:15.272  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 16:56:15.272  6729  6793 I jxcore-log: 
09-06 16:56:15.272  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.272  6729  6793 I jxcore-log: 
09-06 16:56:15.273  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.273  6729  6793 I jxcore-log: 
09-06 16:56:15.274  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.274  6729  6793 I jxcore-log: 
09-06 16:56:15.275  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.275  6729  6793 I jxcore-log: 
09-06 16:56:15.276  6729  6793 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:15.276  6729  6793 I jxcore-log: 
09-06 16:56:15.291  1033  1742 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8269 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-06 16:56:15.292  1033  1742 I ActivityManager: Killing 7312:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-06 16:56:15.338  1033  8218 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-06 16:56:15.339  1033  8218 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-06 16:56:15.339  1033  8218 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 16:56:15.339  1033  8218 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-06 16:56:15.339  1033  8218 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-06 16:56:15.339  1033  8218 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 16:56:15.339  1033  8218 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-06 16:56:15.339  1033  8218 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-06 16:56:15.340  1033  8218 D DhcpStateMachine: RunningState
,09-06 16:56:15.350  8197  8258 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-06 16:56:15.380  7853  7951 D UEI.SmartControl: Internal timer expired: 3
09-06 16:56:15.380  7853  7951 D UEI.SmartControl: unbind internal service
,09-06 16:56:15.470  8286  8286 D AndroidRuntime: 
09-06 16:56:15.470  8286  8286 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-06 16:56:15.473  8286  8286 D AndroidRuntime: CheckJNI is OFF
,09-06 16:56:15.540  1033  1713 W libprocessgroup: failed to open /acct/uid_10093/pid_7312/cgroup.procs: No such file or directory
,09-06 16:56:15.564  7853  7853 D UEI.SmartControl: Service.onUnbind: IControl
09-06 16:56:15.565  7853  7853 D UEI.SmartControl: Service.onDestroy
09-06 16:56:15.565  7853  7853 D UEI.SmartControl: Lock is in USE false
09-06 16:56:15.565  7853  7853 D UEI.SmartControl: unbind internal service
09-06 16:56:15.565  7853  7853 D serial_port: close(fd = 24)
,09-06 16:56:15.577  7853  7853 I UEI.SmartControl: Serial port is closed.
09-06 16:56:15.578  7853  7853 I UEI.SmartControl: Serial port is closed.
09-06 16:56:15.578  7853  7853 D UEI.SmartControl: Blaster closed
09-06 16:56:15.578  7853  7853 D UEI.SmartControl: Shut down QS...
09-06 16:56:15.578  7853  7853 D UEI.SmartControl: Stopping QS lib
09-06 16:56:15.578  7853  7853 D UEI.SmartControl: QS lib stop result = true
09-06 16:56:15.578  7853  7853 D UEI.SmartControl: Stopped QS lib
09-06 16:56:15.578  7853  7853 D UEI.SmartControl: QS shutdown complete
,09-06 16:56:15.599  8269  8269 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 16:56:15.629  8269  8269 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-06 16:56:15.665  8286  8286 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-06 16:56:15.675  1033  1091 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-06 16:56:15.675  1033  1091 I ActivityManager: Killing 6729:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-06 16:56:15.681  8269  8269 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-06 16:56:15.682  8269  8269 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-06 16:56:15.682  8269  8269 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-06 16:56:15.686  8269  8269 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-06 16:56:15.686  8269  8269 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-06 16:56:15.688  8269  8269 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-06 16:56:15.717  8197  8258 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 16:56:15.717  8197  8258 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 16:56:15.725  8269  8269 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-06 16:56:15.736  1033  1995 I WindowState: WIN DEATH: Window{e381111 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-06 16:56:15.737  1033  1542 D WifiService: Client connection lost with reason: 4
09-06 16:56:15.742  1033  1995 D InputDispatcher: Window went away: Window{e381111 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 16:56:15.819  8197  8258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,09-06 16:56:15.890  1033  1091 I ActivityManager:   Force finishing activity ActivityRecord{bd3f8a2 u0 com.test.thalitest/.MainActivity t6}
,09-06 16:56:15.935   346   371 E GBMv2   : DFP En is all cleared set to be enabled
,09-06 16:56:15.940  1033  1101 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-06 16:56:15.942  1033  1101 I ActivityManager:   Force finishing activity ActivityRecord{bd3f8a2 u0 com.test.thalitest/.MainActivity t6 f}
09-06 16:56:15.942  1033  1101 W ActivityManager: Duplicate finish request for ActivityRecord{bd3f8a2 u0 com.test.thalitest/.MainActivity t6 f}
09-06 16:56:15.972  1033  1977 W ActivityManager: Spurious death for ProcessRecord{14caa92b 6729:com.test.thalitest/u0a118}, curProc for 6729: null
,09-06 16:56:15.978  2033  2033 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-06 16:56:15.978  1942  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-06 16:56:15.979  2033  2033 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-06 16:56:15.980  1942  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1ea6ee9a co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-06 16:56:15.981  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-06 16:56:15.983  2033  2145 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-06 16:56:15.983  1942  4414 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-06 16:56:15.984  1942  4414 D SplitWindowPolicy: topRunningActivity=ActivityInfo{ee2b3cb co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-06 16:56:15.995  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-06 16:56:15.997  1600  1600 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,09-06 16:56:15.998  1906  1906 D ActionManagerService: notifyUserLog: 1000003
09-06 16:56:16.004  3787  4935 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-06 16:56:16.007  1996  1996 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-06 16:56:16.007  2469  2608 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-06 16:56:16.008  3787  3787 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-06 16:56:16.012  1033  1427 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-06 16:56:16.014  7753  7753 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-06 16:56:16.014  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-06 16:56:16.015  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:56:16.021  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:56:16.023  2033  2033 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-06 16:56:16.038  4945  4945 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-06 16:56:16.038  4945  4945 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-06 16:56:16.038  4945  4945 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-06 16:56:16.038  4945  4945 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-06 16:56:16.041  4945  4945 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 16:56:16.041  4945  4945 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 16:56:16.041  4945  4945 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:56:16.041  4945  4945 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 16:56:16.041  4945  4945 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:56:16.041  4945  4945 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:56:16.041  4945  4945 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,09-06 16:56:16.042  4945  4945 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 16:56:16.044  8197  8258 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,09-06 16:56:16.046  5048  5048 I art     : Explicit concurrent mark sweep GC freed 8249(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 617us total 67.592ms
09-06 16:56:16.061  1033  1959 V SIM_STK : Menu title from STK is T-Mobile
,09-06 16:56:16.070  1033  1090 W InputMethodInfo: Duplicated subtype definition found: , voice
09-06 16:56:16.089  2033  2033 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,09-06 16:56:16.100  1600  1600 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-06 16:56:16.109  8197  8258 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,09-06 16:56:16.113  8197  8258 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-06 16:56:16.113  8269  8269 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 16:56:16.117  2033  2033 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-06 16:56:16.118  8269  8269 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-06 16:56:16.119  8197  8258 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-06 16:56:16.120  8269  8269 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-06 16:56:16.129  8197  8258 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-06 16:56:16.129  8197  8258 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,09-06 16:56:16.135  1871  1871 D SplitUIManager: split_name #11 / not available #0
09-06 16:56:16.136  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-06 16:56:16.136  1871  1871 D SplitUIService: removed split : 
09-06 16:56:16.141  6960  6960 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,09-06 16:56:16.146  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-06 16:56:16.147  1600  1644 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-06 16:56:16.147  1600  1644 D KeyguardModel: createShortcutInfo...
09-06 16:56:16.148  1906  1906 D ActionManagerService: notifyUserLog: 1000004
09-06 16:56:16.149  3787  4935 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-06 16:56:16.149  3787  4927 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262123
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , expire_time: 0
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , display: false
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , animation: false }
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262287
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , expire_time: 0
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , display: false
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , animation: false }
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472828323135
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , create_time: 1472828323917
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , expire_time: 0
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , display: false
09-06 16:56:16.152  2033  2033 I GBoardWebViewUtils: , animation: false }
,09-06 16:56:16.159  8197  8258 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-06 16:56:16.160  1033  1537 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 16:56:16.161  1033  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 16:56:16.161  1033  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 16:56:16.162  1033  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 16:56:16.162  1033  1048 V SIM_STK : Menu title from STK is T-Mobile
09-06 16:56:16.162  1033  1048 V SIM_STK : Menu title from STK is T-Mobile
09-06 16:56:16.162  1033  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 16:56:16.163  1600  1644 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-06 16:56:16.163  1600  1644 D KeyguardModel: createShortcutInfo...
09-06 16:56:16.163  1033  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 16:56:16.163  1033  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-06 16:56:16.163  1033  1543 D ConnectivityService: identical MTU - not setting
09-06 16:56:16.163  1033  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 16:56:16.163  1033  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-06 16:56:16.163  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:56:16.163  1033  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:56:16.164  1033  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 16:56:16.165  1600  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-06 16:56:16.167  8197  8197 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:56:16.167  2033  8324 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-06 16:56:16.167  8197  8259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 16:56:16.171  1600  1644 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,09-06 16:56:16.172  1600  1644 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 16:56:16.172  1600  1644 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-06 16:56:16.173  1600  1600 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-06 16:56:16.173  1600  1600 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-06 16:56:16.174  8197  8258 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-06 16:56:16.174  1600  1644 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 16:56:16.175  1600  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 16:56:16.175  1600  1644 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-06 16:56:16.175  1871  1871 D SplitUIManager: split_name #11 / not available #0
09-06 16:56:16.175  1871  1871 I SplitUIService: split app #11
09-06 16:56:16.178  1600  1644 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-06 16:56:16.178  1600  1644 D KeyguardModel: createShortcutInfo...
09-06 16:56:16.181  1033  1033 D administrator: Handling package changes for user 0
09-06 16:56:16.183  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,09-06 16:56:16.204  1600  1644 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-06 16:56:16.204  1600  1644 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 16:56:16.205  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 16:56:16.205  1600  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 16:56:16.206  1600  1644 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-06 16:56:16.207  1600  1644 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-06 16:56:16.207  1600  1644 D KeyguardModel: createShortcutInfo...
,09-06 16:56:16.211  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:16.214  1600  1644 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 16:56:16.214  1600  1644 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-06 16:56:16.215  1600  1644 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-06 16:56:16.215  1600  1644 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 16:56:16.217  1600  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 16:56:16.217  1600  1644 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-06 16:56:16.218  1600  1644 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-06 16:56:16.218  1600  1644 D KeyguardModel: createShortcutInfo...
09-06 16:56:16.220  1600  1600 D KeyguardModel: handleShortcutListChanged...
09-06 16:56:16.220  1600  1600 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-06 16:56:16.223  1600  1644 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-06 16:56:16.223  1600  1644 D KeyguardModel: createShortcutInfo...
09-06 16:56:16.224  1600  1644 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-06 16:56:16.224  1600  1644 D KeyguardModel: createShortcutInfo...
09-06 16:56:16.225  1600  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 16:56:16.225  1600  1644 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-06 16:56:16.226  1600  1644 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-06 16:56:16.226  1600  1644 D KeyguardModel: createShortcutInfo...
,09-06 16:56:16.228  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:56:16.229  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:56:16.230  8269  8269 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 16:56:16.234  1033  1959 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-06 16:56:16.234  8197  8197 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:56:16.235  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-06 16:56:16.235  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-06 16:56:16.235  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-06 16:56:16.235  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 16:56:16.235  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 16:56:16.235  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 16:56:16.235  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 16:56:16.235  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 16:56:16.235  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 16:56:16.235  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 16:56:16.235  7753  7753 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 16:56:16.235  1600  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 16:56:16.235  1600  1644 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-06 16:56:16.235  8197  8259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 16:56:16.236  1600  1644 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-06 16:56:16.236  1600  1644 D KeyguardModel: createShortcutInfo...
09-06 16:56:16.237  1600  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 16:56:16.237  1600  1644 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-06 16:56:16.238  1600  1644 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-06 16:56:16.238  1600  1644 D KeyguardModel: createShortcutInfo...
09-06 16:56:16.243  1033  1741 V SIM_STK : Menu title from STK is T-Mobile
,09-06 16:56:16.255  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:56:16.269  1600  1600 D KeyguardModel: handleShortcutListChanged...
09-06 16:56:16.269  1600  1600 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-06 16:56:16.289  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:16.291  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-06 16:56:16.307  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-06 16:56:16.307  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-06 16:56:16.307  1033  1033 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-06 16:56:16.309  1033  1576 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-06 16:56:16.309  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:56:16.309  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:56:16.310  8269  8269 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 16:56:16.313  8197  8197 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:56:16.313  8197  8259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 16:56:16.318  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:56:16.322  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 16:56:16.338  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:56:16.338  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 16:56:16.339  8269  8269 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 16:56:16.341  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 16:56:16.343  6960  6960 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 16:56:16.343  6960  6960 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 16:56:16.343  6960  6960 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-06 16:56:16.344  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-06 16:56:16.345  6960  6960 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 16:56:16.345  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-06 16:56:16.345  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 16:56:16.345  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 16:56:16.345  6960  6960 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 16:56:16.345  6960  6960 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-06 16:56:16.346  6960  6960 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 16:56:16.349  8197  8197 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:56:16.349  8197  8259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 16:56:16.361  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:56:16.369  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:16.381  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:56:16.381  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:56:16.381  8269  8269 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 16:56:16.385  8197  8197 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:56:16.385  8197  8259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 16:56:16.389  1033  1101 I art     : Explicit concurrent mark sweep GC freed 83985(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 6.017ms total 262.071ms
09-06 16:56:16.397  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:56:16.406  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:16.407  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-06 16:56:16.412  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-06 16:56:16.414  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-06 16:56:16.417  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-06 16:56:16.419  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-06 16:56:16.419  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:56:16.419  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:56:16.420  8269  8269 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 16:56:16.421  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-06 16:56:16.423  8197  8197 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 16:56:16.435  1033  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c880c20 u0 com.lge.launcher2/.Launcher t5} time:141837
09-06 16:56:16.447  2033  2033 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-06 16:56:16.448  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-06 16:56:16.448  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-06 16:56:16.454  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 16:56:16.456  8286  8286 D AndroidRuntime: Shutting down VM
09-06 16:56:16.457  2033  2263 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-06 16:56:16.457  2033  2263 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-06 16:56:16.460  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:16.474  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,09-06 16:56:16.477  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-06 16:56:16.477  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 16:56:16.484  1033  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 16:56:16.489  1033  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-06 16:56:16.498  2033  2033 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-06 16:56:16.510  1033  1101 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8332 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-06 16:56:16.512  2681  2681 D [Concierge]Service: onStartCommand(). Type : 8
09-06 16:56:16.512  2681  2681 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-06 16:56:16.513  2681  2681 D [Concierge]Service: Update widget ID : 11
09-06 16:56:16.514  2033  2033 D [Concierge]WidgetView: change position of spinner
09-06 16:56:16.515  2681  2681 D [Concierge]Service: onStartCommand(). Type : 0
09-06 16:56:16.515  2033  2033 I [Concierge]WidgetView: initWebView(). Time : 1473173776515
09-06 16:56:16.520  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:56:16.520  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:56:16.521  8269  8269 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 16:56:16.530  8197  8197 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 16:56:16.549  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:56:16.560  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:16.567  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 16:56:16.567  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:56:16.570  2033  2033 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 869749874
09-06 16:56:16.571  2033  2033 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-06 16:56:16.571  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-06 16:56:16.576  8269  8269 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 16:56:16.576  2033  2033 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@26f4f1f2
09-06 16:56:16.577  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-06 16:56:16.579  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,09-06 16:56:16.579  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 16:56:16.580  8197  8197 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:56:16.588  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-06 16:56:16.589  2033  2033 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-06 16:56:16.590  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-06 16:56:16.591  2033  2033 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-06 16:56:16.592  2033  2033 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473173663237, New one : 1473173776515
09-06 16:56:16.592  2033  2033 D [Concierge]WidgetView: Unregister all receivers
09-06 16:56:16.592  2033  2033 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,09-06 16:56:16.596  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:56:16.597  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 16:56:16.600  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-06 16:56:16.603  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-06 16:56:16.603  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 16:56:16.604  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-06 16:56:16.606  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-06 16:56:16.608  1033  2014 I ActivityManager: Killing 7360:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-06 16:56:16.608  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-06 16:56:16.613  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 16:56:16.614  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 16:56:16.679  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:56:16.679  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:56:16.680  8269  8269 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 16:56:16.682  1033  1048 W libprocessgroup: failed to open /acct/uid_10005/pid_7360/cgroup.procs: No such file or directory
09-06 16:56:16.689  8197  8197 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:56:16.693  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-06 16:56:16.696  8150  8150 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-06 16:56:16.701  8150  8150 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:56:16.703  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:56:16.709  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:16.710  2033  2033 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-06 16:56:16.710  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-06 16:56:16.713  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 16:56:16.714  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:56:16.715  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:56:16.716  8269  8269 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 16:56:16.717  8269  8269 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 16:56:16.717  8269  8269 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-06 16:56:16.722  8197  8197 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 16:56:16.727  8150  8150 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-06 16:56:16.728  8150  8150 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-06 16:56:16.734  2033  2033 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@150879cf time:142136
,09-06 16:56:16.738  6960  6960 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 16:56:16.750  6960  6960 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 16:56:16.758  8269  8269 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 16:56:16.758  8269  8269 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 16:56:16.759  8269  8269 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 16:56:16.759  8269  8269 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 16:56:16.760  8269  8269 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-06 16:56:16.762  8197  8197 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 16:56:16.763  8197  8197 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-06 16:56:16.766  1818  1818 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-06 16:56:16.772  2188  2188 I ConfigService: onCreate
09-06 16:56:16.773  2188  2188 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-06 16:56:16.774  1818  1818 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-06 16:56:16.782  2188  2188 I ConfigService: onBind returning update interface
09-06 16:56:16.783  2188  2188 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-06 16:56:16.783  2188  2188 I ConfigService: onBind returning config service
09-06 16:56:16.789  2188  2188 I ConfigService: onDestroy
,09-06 16:56:16.790  1818  8352 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-06 16:56:16.802  7151  7151 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
,09-06 16:56:16.804  7151  7151 E SQLiteDatabase: Error inserting package=com.test.thalitest
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 16:56:16.804  7151  7151 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-06 16:56:16.827  5873  8357 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-06 16:56:16.828  2330  8360 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-06 16:56:16.841  1818  8361 I PeopleContactsSync: CP2 sync disabled
09-06 16:56:16.856  1033  1940 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8362 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-06 16:56:16.863  1818  5224 I Icing   : doRemovePackageData com.test.thalitest
09-06 16:56:16.873  2330  2444 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-06 16:56:16.876  1818  8359 W GmsApplication: Using Auth Proxy for data requests.
09-06 16:56:16.880  1818  5224 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
09-06 16:56:16.880  1818  5224 E Icing   : Could not init tag ds.tag.corpusid-1
09-06 16:56:16.880  1818  5224 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-13 for write failed: Read-only file system
09-06 16:56:16.880  1818  5224 E Icing   : Could not init tag ds.tag.corpusid-13
09-06 16:56:16.880  1818  5224 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-7 for write failed: Read-only file system
09-06 16:56:16.880  1818  5224 E Icing   : Could not init tag ds.tag.corpusid-7
09-06 16:56:16.880  1818  5224 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-8 for write failed: Read-only file system
09-06 16:56:16.880  1818  5224 E Icing   : Could not init tag ds.tag.corpusid-8
09-06 16:56:16.880  1818  5224 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-9 for write failed: Read-only file system
09-06 16:56:16.880  1818  5224 E Icing   : Could not init tag ds.tag.corpusid-9
09-06 16:56:16.880  1818  5224 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
09-06 16:56:16.880  1818  5224 E Icing   : Could not init tag ds.tag.deleted
09-06 16:56:16.882  1818  8359 W GmsApplication: Using Auth Proxy for data requests.
09-06 16:56:16.882  1818  5224 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
09-06 16:56:16.882  1818  5224 E Icing   : Writing status failed
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
09-06 16:56:16.885  18,18  8358 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:56:16.885  1818  8358 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:56:16.886  1818  8358 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForL,G: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:56:16.887  2330  2444 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at com.google.android.gms.common.d.a.delete(SourceFile:258)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:56:16.889  1818  8359 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 16:56:16.889  1818  8358 W SQLiteOpenHelper: Opened metrics.db in read-only mode
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: Runtime exception while performing operation
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at com.google.android.gms.common.d.a.delete(SourceFile:258)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:56:16.891  1818  8359 E ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at com.google.android.gms.common.d.a.delete(SourceFile:258)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:56:16.892  1818  8359 F ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 16:56:16.893  1818  8358 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
--------- beginning of crash
09-06 16:56:16.895  1818  8358 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
09-06 16:56:16.895  1818  8358 E AndroidRuntime: Process: com.google.android.gms, PID: 1818
09-06 16:56:16.895  1818  8358 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
09-06 16:56:16.895  1818  8358 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-06 16:56:16.895  1818  8358 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
09-06 16:56:16.895  1818  8358 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
09-06 16:56:16.895  1818  8358 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-06 16:56:16.895  1818  8358 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
09-06 16:56:16.895  1818  8358 E AndroidRuntime: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:215)
09-06 16:56:16.895  1818  8358 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
09-06 16:56:16.895  1818  8358 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-06 16:56:16.895  1818  8358 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:16.895  1818  8358 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:56:16.895  1818  8358 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 16:56:16.898  2330  8360 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
09-06 16:56:16.899  1033  8371 E DropBoxManagerService: Can't write: system_app_wtf
09-06 16:56:16.899  1033  8371 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-06 16:56:16.899  1033  8371 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-06 16:56:16.899  1033  8371 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 16:56:16.899  1033  8371 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 16:56:16.899  1033  8371 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 16:56:16.899  1033  8371 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-06 16:56:16.899  1033  8371 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-06 16:56:16.899  1033  8371 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 16:56:16.899  1033  8371 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 16:56:16.899  1033  8371 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 16:56:16.899  1033  8371 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 16:56:16.899  1033  8371 E DropBoxManagerService: 	... 5 more
09-06 16:56:16.900  2330  8360 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-06 16:56:16.900  2330  8360 E AndroidRuntime: Process: android.process.acore, PID: 2330
09-06 16:56:16.900  2330  8360 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-06 16:56:16.900  2330  8360 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 16:56:16.912  1818  8358 I Process : Sending signal. PID: 1818 SIG: 9
09-06 16:56:16.914  1033  8378 E DropBoxManagerService: Can't write: system_app_crash
09-06 16:56:16.914  1033  8378 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
09-06 16:56:16.914  1033  8378 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-06 16:56:16.914  1033  8378 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 16:56:16.914  1033  8378 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 16:56:16.914  1033  8378 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 16:56:16.914  1033  8378 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-06 16:56:16.914  1033  8378 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-06 16:56:16.914  1033  8378 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 16:56:16.914  1033  8378 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 16:56:16.914  1033  8378 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 16:56:16.914  1033  8378 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 16:56:16.914  1033  8378 E DropBoxManagerService: 	... 5 more
09-06 16:56:16.916  1033  8379 E DropBoxManagerService: Can't write: system_app_crash
09-06 16:56:16.916  1033  8379 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
09-06 16:56:16.916  1033  8379 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-06 16:56:16.916  1033  8379 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 16:56:16.916  1033  8379 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 16:56:16.916  1033  8379 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 16:56:16.916  1033  8379 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-06 16:56:16.916  1033  8379 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-06 16:56:16.916  1033  8379 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 16:56:16.916  1033  8379 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 16:56:16.916  1033  8379 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 16:56:16.916  1033  8379 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 16:56:16.916  1033  8379 E DropBoxManagerService: 	... 5 more
09-06 16:56:16.916  2330  8360 I Process : Sending signal. PID: 2330 SIG: 9
,09-06 16:56:16.935  1033  1542 D WifiService: Client connection lost with reason: 4
09-06 16:56:16.945  8362  8362 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 16:56:16.946  8362  8362 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.

```
