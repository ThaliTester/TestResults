#### Test 8289468293e136b_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-29 13:12:11.175  1043  1985 W libprocessgroup: failed to open /acct/uid_10044/pid_6097/cgroup.procs: No such file or directory
08-29 13:12:11.206  6597  6597 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:12:11.206  6597  6597 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 13:12:11.207  6597  6597 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-29 13:12:11.207  6597  6597 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
--------- beginning of main
08-29 13:12:11.310  6597  6597 I AppConfig: Total System Memory = 2995761152
08-29 13:12:11.320  6597  6597 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-29 13:12:11.357  1043  1948 I ActivityManager: Killing 6135:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-29 13:12:11.387  1987  1987 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-29 13:12:11.387  1987  1987 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-29 13:12:11.390  1043  1949 W libprocessgroup: failed to open /acct/uid_10080/pid_6135/cgroup.procs: No such file or directory
08-29 13:12:11.394  1987  1987 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-29 13:12:11.427  6457  6457 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-29 13:12:11.434  6457  6457 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-29 13:12:11.491  1043  1986 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6625 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:12:11.722  6625  6625 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-29 13:12:11.800  6625  6625 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:12:11.800  6625  6625 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 13:12:11.821   336   449 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-29 13:12:11.821  3273  6658 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-29 13:12:11.859  6625  6625 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-29 13:12:11.881  6625  6625 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-29 13:12:11.884  6625  6625 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-29 13:12:11.917  6625  6625 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 13:12:11.918  6625  6625 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-29 13:12:11.933  1043  1985 I ActivityManager: Killing 5491:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-29 13:12:11.967  1043  1949 W libprocessgroup: failed to open /acct/uid_10085/pid_5491/cgroup.procs: No such file or directory
08-29 13:12:11.977  5091  6663 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-29 13:12:12.024  1043  1986 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6664 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:12:12.029  3438  3453 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-29 13:12:12.040  1043  1913 V SIM_STK : Menu title from STK is T-Mobile
08-29 13:12:12.043  3438  3453 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@18b23ddd on behalf of 6625
08-29 13:12:12.055  6625  6625 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-29 13:12:12.083  6625  6625 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-29 13:12:12.195  1807  5236 I art     : Explicit concurrent mark sweep GC freed 31696(2000KB) AllocSpace objects, 12(192KB) LOS objects, 51% free, 29MB/61MB, paused 2.127ms total 69.106ms
08-29 13:12:12.232  5091  6663 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 254 ms] updated apps [took 254 ms] 
08-29 13:12:12.295  6664  6664 D DocsApplication: Installing DEX configuration.
08-29 13:12:12.312  6664  6664 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-29 13:12:12.316  6664  6664 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{30e887b7 com.google.android.apps.docs}
08-29 13:12:12.330  6664  6664 D TAG     : onCreate()
08-29 13:12:12.347  6664  6664 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-29 13:12:12.348  6687  6687 D AndroidRuntime: 
08-29 13:12:12.348  6687  6687 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 13:12:12.352  6687  6687 D AndroidRuntime: CheckJNI is OFF
08-29 13:12:12.500  6687  6687 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 13:12:12.513  1043  1060 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 13:12:12.528  1931  1947 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-29 13:12:12.535  1043  1060 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-29 13:12:12.536  1043  1060 D ActivityManager: setTaskToReturnTo : TaskRecord{2e07efd3 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 13:12:12.536  1043  1060 D ActivityManager: setTaskToReturnTo : TaskRecord{2e07efd3 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-29 13:12:12.537  1043  1060 D WindowStateEx: AppWindowTokenEx init.. 
08-29 13:12:12.538   353   380 E GBMv2   : DFP En is all cleared set to be enabled
08-29 13:12:12.565  1043  1060 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6705 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 13:12:12.566  6687  6687 D AndroidRuntime: Shutting down VM
08-29 13:12:12.607  1931  1947 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-29 13:12:12.607  1931  1947 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3bf46fe3 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 13:12:12.608  1931  1946 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-29 13:12:12.608  1931  1946 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2dbcfde0 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-29 13:12:12.658  6705  6705 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-29 13:12:12.736  6705  6705 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-29 13:12:12.743  6705  6705 I LibraryLoader: Loading: webviewchromium
08-29 13:12:12.746  6705  6705 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2999-3002)
08-29 13:12:12.746  6705  6705 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 13:12:12.758  6705  6705 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {10ae4e89}
08-29 13:12:12.759  6705  6705 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 13:12:12.759  6705  6705 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 13:12:12.767  6705  6705 I BrowserStartupController: Initializing chromium process, renderers=0
08-29 13:12:12.768  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 13:12:12.784  6705  6705 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-29 13:12:12.786  6705  6705 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-29 13:12:12.786  6705  6705 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-29 13:12:12.789   327  1717 V AudioPolicyService: registerClient() client 0xb0410020, uid 10118
08-29 13:12:12.794  1043  1120 D BluetoothManagerService: Message: 20
08-29 13:12:12.794  1043  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cac15c5:true
08-29 13:12:12.801  6705  6705 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 13:12:12.801  6705  6705 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 13:12:12.801  6705  6705 I Adreno-EGL: Build Date: 12/12/14 금
08-29 13:12:12.801  6705  6705 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 13:12:12.801  6705  6705 I Adreno-EGL: Remote Branch: 
08-29 13:12:12.801  6705  6705 I Adreno-EGL: Local Patches: 
08-29 13:12:12.801  6705  6705 I Adreno-EGL: Reconstruct Branch: 
,08-29 13:12:12.859  6705  6734 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-29 13:12:12.863  6705  6705 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-29 13:12:12.877  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 13:12:12.880  6705  6705 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-29 13:12:12.882  6705  6705 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-29 13:12:12.885  6705  6705 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-29 13:12:12.885  6705  6705 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-29 13:12:12.896  6705  6705 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-29 13:12:12.905  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 13:12:12.905  6705  6705 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 13:12:12.951  6705  6746 D OpenGLRenderer: Render dirty regions requested: true
08-29 13:12:12.951  6705  6746 I OpenGLRenderer: Initialized EGL, version 1.4
08-29 13:12:12.955  6705  6746 D OpenGLRenderer: Enabling debug mode 0
08-29 13:12:12.963  6705  6705 D Atlas   : Validating map...
,08-29 13:12:12.967  1043  1061 D SplitWindow: check instance of lgWin Window{40c7d17 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 13:12:13.002  6705  6744 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:12:13.003  6705  6744 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 13:12:13.108  1043  1121 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +502ms (total +569ms)
,08-29 13:12:13.110  1043  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{14a59710 u0 com.test.thalitest/.MainActivity t6} time:103367
08-29 13:12:13.112  6705  6705 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@13dcdaec time:103369
,08-29 13:12:13.197  6705  6705 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 13:12:13.225  6705  6705 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-29 13:12:13.225  6705  6705 I chromium: 
,08-29 13:12:13.233  1807  5236 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-29 13:12:13.246  6705  6744 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-29 13:12:13.246  6705  6744 I chromium: 
,08-29 13:12:13.263  1807  5236 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,08-29 13:12:13.307  1807  5236 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-29 13:12:13.347  6705  6757 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435157504
,08-29 13:12:13.356  6705  6757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 13:12:13.356  6705  6757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 13:12:13.356  6705  6757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 13:12:13.356  6705  6757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 13:12:13.356  6705  6757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 13:12:13.356  6705  6757 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d02ebf0 added. We now have 1 listener(s)
08-29 13:12:13.361  1043  1895 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:13.362  6705  6757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-29 13:12:13.365  6705  6757 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-29 13:12:13.367  6705  6757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:13.368  6705  6757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:13.376  6705  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 13:12:13.376  6705  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 13:12:13.376  6705  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 13:12:13.376  6705  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-29 13:12:13.376  6705  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 13:12:13.376  6705  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 13:12:13.376  6705  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 13:12:13.376  6705  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 13:12:13.376  6705  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 13:12:13.376  6705  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 13:12:13.376  6705  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 13:12:13.376  6705  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 13:12:13.376  6705  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 13:12:13.376  6705  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 13:12:13.376  6705  6757 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@389388f added. We now have 1 listener(s)
08-29 13:12:13.376  6705  6757 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:13.385  1043  1486 D WifiService: New client listening to asynchronous messages
08-29 13:12:13.387  6705  6757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:12:13.388  6705  6757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 13:12:13.388  6705  6757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 13:12:13.388  6705  6757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 13:12:13.388  6705  6757 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 13:12:13.390  6705  6757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:13.390  1043  2022 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:13.391  6705  6757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-29 13:12:13.398  6705  6757 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 13:12:13.398  6705  6757 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:13.398  6705  6757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:13.398  6705  6757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:13.398  6705  6757 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:13.398  6705  6757 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:13.398  6705  6757 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:13.398  6705  6757 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:13.398  6705  6757 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:13.398  6705  6757 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 13:12:13.398  6705  6757 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:13.399  6705  6757 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 13:12:13.401  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:13.403  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:13.430  6705  6705 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 13:12:13.681   353   382 E GBMv2   : DFP En is all cleared set to be enabled
,08-29 13:12:13.681   353   382 E GBMv2   : Set value is all cleared set the max
08-29 13:12:13.681   353   382 I GBMv2   : DFP Enabled. Ignore VFP set
,08-29 13:12:13.722  6664  6664 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:12:13.722  6664  6664 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 13:12:13.959  6664  6664 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-29 13:12:14.003  1043  1895 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6770 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-29 13:12:14.020   357   357 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 458us total 22.894ms
,08-29 13:12:14.040   357   357 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 423us total 19.605ms
,08-29 13:12:14.058  6705  6760 W jxcore-log: Initializing JXcore engine
08-29 13:12:14.058  6705  6760 W jxcore-log: JXcore engine is ready
08-29 13:12:14.062   357   357 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 415us total 20.654ms
,08-29 13:12:14.087  6770  6770 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-29 13:12:14.088  6760  6760 W Thread-787: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8861]" dev="sockfs" ino=8861 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-29 13:12:14.088  6760  6760 W Thread-787: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-29 13:12:14.088  6760  6760 W Thread-787: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9034]" dev="sockfs" ino=9034 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-29 13:12:14.088  6760  6760 W Thread-787: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-29 13:12:14.088  6760  6760 W Thread-787: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33111]" dev="sockfs" ino=33111 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-29 13:12:14.105  6705  6760 W jxcore-log: Starting JXcore engine
08-29 13:12:14.185  6705  6760 W jxcore-log: Platform android
08-29 13:12:14.185  6705  6760 W jxcore-log: 
08-29 13:12:14.185  6705  6760 W jxcore-log: Process ARCH arm
08-29 13:12:14.185  6705  6760 W jxcore-log: 
,08-29 13:12:14.219  1043  1949 I art     : Explicit concurrent mark sweep GC freed 27142(1310KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.156ms total 121.596ms
,08-29 13:12:14.220  6770  6770 I LockScreenSettings: New app installed broadcast received ..
08-29 13:12:14.227  6770  6770 I LockScreenSettings: Number of installed packages  1
08-29 13:12:14.275  1043  1913 V SIM_STK : Menu title from STK is T-Mobile
,08-29 13:12:14.344  1043  1986 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6795 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 13:12:14.346  1043  1986 I ActivityManager: Killing 5620:com.lge.bnr/1000 (adj 15): empty #17
,08-29 13:12:14.433  6705  6760 I jxcore-log: JXcore Cordova bridge is ready!
08-29 13:12:14.433  6705  6760 I jxcore-log: 
,08-29 13:12:14.433  6705  6760 W jxcore-log: JXcore engine is started
08-29 13:12:14.438  6705  6757 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-29 13:12:14.441  6705  6705 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-29 13:12:14.445  1043  1950 W libprocessgroup: failed to open /acct/uid_1000/pid_5620/cgroup.procs: No such file or directory
,08-29 13:12:14.496  6795  6795 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-29 13:12:14.496  6795  6795 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-29 13:12:14.562  1043  1986 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6815 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-29 13:12:14.562  1043  1986 I ActivityManager: Killing 6195:com.google.android.gm/u0a64 (adj 15): empty #17
,08-29 13:12:14.704  1043  1950 W libprocessgroup: failed to open /acct/uid_10064/pid_6195/cgroup.procs: No such file or directory
,08-29 13:12:14.773  6815  6815 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-29 13:12:14.794  6815  6815 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-29 13:12:14.800  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-29 13:12:14.830  1043  1948 I ActivityManager: Killing 5994:com.google.android.talk/u0a72 (adj 15): empty #17
,08-29 13:12:14.977  1043  1565 W libprocessgroup: failed to open /acct/uid_10072/pid_5994/cgroup.procs: No such file or directory
,08-29 13:12:17.866  6664  6664 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-29 13:12:17.873  1043  1061 I ActivityManager: Killing 5757:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-29 13:12:17.894  5724  5724 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-29 13:12:17.894  5724  5724 W System.err: android.os.DeadObjectException
08-29 13:12:17.894  5724  5724 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 13:12:17.894  5724  5724 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 13:12:17.894  5724  5724 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-29 13:12:17.894  5724  5724 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-29 13:12:17.894  5724  5724 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 13:12:17.894  5724  5724 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 13:12:17.894  5724  5724 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:12:17.894  5724  5724 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:12:17.894  5724  5724 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 13:12:17.894  5724  5724 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,08-29 13:12:17.894  5724  5724 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:17.895  5724  5724 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:17.895  5724  5724 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 13:12:17.895  5724  5724 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 13:12:17.895  5724  5724 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-29 13:12:17.895  5724  5724 W System.err: android.os.DeadObjectException
08-29 13:12:17.895  5724  5724 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 13:12:17.895  5724  5724 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 13:12:17.895  5724  5724 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-29 13:12:17.895  5724  5724 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-29 13:12:17.895  5724  5724 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 13:12:17.895  5724  5724 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 13:12:17.895  5724  5724 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:12:17.895  5724  5724 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:12:17.895  5724  5724 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 13:12:17.896  5724  5724 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 13:12:17.896  5724  5724 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:17.896  5724  5724 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:17.896  5724  5724 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 13:12:17.896  5724  5724 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 13:12:17.896  5724  5724 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-29 13:12:17.896  5724  5724 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-29 13:12:18.125  1043  1764 W libprocessgroup: failed to open /acct/uid_1000/pid_5757/cgroup.procs: No such file or directory
08-29 13:12:18.126  1043  1764 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-29 13:12:18.137  5724  5724 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-29 13:12:18.138  5724  5724 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 13:12:18.177  1043  1948 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6846 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 13:12:18.178  5724  5724 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-29 13:12:18.253  6846  6846 D UEI.SmartControl: Quickset Services start...
,08-29 13:12:18.256  6846  6846 I UEI.SmartControl: Manufacture = LGE
08-29 13:12:18.256  6846  6846 D UEI.SmartControl: Id = LGNevo
08-29 13:12:18.257  6846  6846 D UEI.SmartControl: File observer start...
08-29 13:12:18.258  6846  6846 E UEI.SmartControl: IR Port is disabled: false
08-29 13:12:18.258  6846  6846 D UEI.SmartControl: Starting file observer...
08-29 13:12:18.258  6846  6846 D UEI.SmartControl: Extracting JNI libs...
08-29 13:12:18.258  6846  6846 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-29 13:12:18.384  6846  6846 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-29 13:12:18.384  6846  6846 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-29 13:12:18.384  6846  6846 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-29 13:12:18.419  6846  6846 I UEI.SmartControl: --- Selecting new region: 6
,08-29 13:12:18.422  6846  6846 I UEI.SmartControl: Model = LG-D855
08-29 13:12:18.423  6846  6846 D UEI.SmartControl: QS Service created
08-29 13:12:18.439  6846  6846 I UEI.SmartControl: Service initServices...
,08-29 13:12:18.445  6846  6846 D UEI.SmartControl: QS start get config
08-29 13:12:18.493  6846  6846 D UEI.SmartControl: Loading JNI Libs...
,08-29 13:12:18.761  6846  6846 I UEI.SmartControl: Supports setup maps: true
,08-29 13:12:18.782  6846  6846 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 13:12:18.782  6846  6846 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 13:12:18.783  6846  6846 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 13:12:18.783  6846  6846 I UEI.SmartControl: ### init IR Blaster...
,08-29 13:12:18.795  6846  6846 D serial_port: Configuring serial port
,08-29 13:12:18.807  6846  6846 E UEI.SmartControl: UEIBLaster setting for 616
08-29 13:12:18.807  6846  6846 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 13:12:18.807  6846  6846 I UEI.SmartControl: configuring settings for MAXQ616
08-29 13:12:18.807  6846  6846 I UEI.SmartControl: Get version...
08-29 13:12:18.813  6664  6761 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-29 13:12:18.822  6846  6874 D UEI.SmartControl: serial port data available: 21
08-29 13:12:18.849  6846  6846 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 13:12:18.849  6846  6846 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 13:12:18.849  6846  6846 I UEI.SmartControl: QS saving settings...
08-29 13:12:18.849  6846  6846 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 13:12:18.867  6846  6874 D UEI.SmartControl: serial port data available: 4
,08-29 13:12:18.901  6846  6846 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 13:12:18.906  6846  6846 E UEI.SmartControl: Services init done
08-29 13:12:18.906  6846  6846 D UEI.SmartControl: QS Service init finished
08-29 13:12:18.908  6846  6846 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 13:12:18.908  6846  6846 D UEI.SmartControl: QS Service version code: 201091
08-29 13:12:18.910  6846  6846 D UEI.SmartControl: Service requested: Control
08-29 13:12:18.915  6846  6877 I UEI.SmartControl: Device manager: loading config....
08-29 13:12:18.916  6846  6877 D UEI.SmartControl: ----------- loading internal config...
,08-29 13:12:18.928  6846  6877 E UEI.SmartControl: Loading SETTINGS...
08-29 13:12:18.929  6846  6846 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 13:12:18.932  1043  1949 I ActivityManager: Killing 5724:com.lge.qremote/u0a112 (adj 15): empty #17
,08-29 13:12:18.939  6846  6877 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 13:12:18.944  6846  6876 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 13:12:18.944  6846  6876 D UEI.SmartControl: -----service ready thread exits
,08-29 13:12:19.035  1043  2023 W libprocessgroup: failed to open /acct/uid_10112/pid_5724/cgroup.procs: No such file or directory
,08-29 13:12:19.044  6846  6846 D UEI.SmartControl: Internal service binding...
,08-29 13:12:22.439  2779  2779 I MusicWidget: mDelayedStopHandler : unbind
,08-29 13:12:22.449  2152  2152 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-29 13:12:22.450  2152  2152 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-29 13:12:22.450  2152  2152 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-29 13:12:22.455  2152  2152 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-29 13:12:22.455  2152  2152 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-29 13:12:22.456  2152  2152 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,08-29 13:12:22.462  2152  2152 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-29 13:12:22.463  2152  2152 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-29 13:12:22.464  1043  1061 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1962873ecom.lge.music.MediaPlaybackService$5@2c1ca99f
08-29 13:12:22.465  2152  2152 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-29 13:12:22.465  2152  2152 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:12:22.466  2152  2152 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:12:22.467  2152  2152 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:12:22.467  2152  2152 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@20244a45
08-29 13:12:22.467  2152  2152 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:12:22.468  2152  2152 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-29 13:12:22.469  2152  2152 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-29 13:12:22.471  2152  2152 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-29 13:12:22.471  2152  2152 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-29 13:12:22.471  2152  2152 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:12:22.472  2152  2152 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:12:22.473  2152  2152 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:12:22.473  2152  2152 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:12:22.474  2152  2152 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-29 13:12:22.475  2152  2152 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-29 13:12:22.476  2152  2152 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-29 13:12:22.477  2152  2152 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-29 13:12:22.477  2152  2152 V MediaPlayer[Native]: reset
08-29 13:12:22.483  2152  2152 V MediaPlayer[Native]: setListener
08-29 13:12:22.483  2152  2152 V MediaPlayer[Native]: disconnect
,08-29 13:12:22.485  2152  2152 V MediaPlayer[Native]: destructor
08-29 13:12:22.485   327  1715 V AudioFlinger: releasing 18 from 2152 for -1
08-29 13:12:22.485   327  1715 V AudioFlinger:  decremented refcount to 0
08-29 13:12:22.485   327  1715 V AudioFlinger: purging stale effects
08-29 13:12:22.485  2152  2152 V MediaPlayer[Native]: disconnect
08-29 13:12:22.487  2152  2152 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-29 13:12:22.488  2152  2152 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-29 13:12:22.488  2152  2152 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-29 13:12:22.489  2152  2152 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-29 13:12:22.489  2152  2152 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-29 13:12:22.490  2152  2152 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-29 13:12:22.490  2152  2152 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 333241068
08-29 13:12:22.490  2152  2152 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 333241068
08-29 13:12:22.497  2152  2152 I SmartShareClient: [SmartShareManagerClient] terminate service: 2152/MediaPlaybackService/24373331
08-29 13:12:22.501  2152  2152 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-29 13:12:22.501  2152  2152 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3e454eb5
,08-29 13:12:22.505  2152  2152 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-29 13:12:22.506  2152  2152 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-29 13:12:22.507  2152  2152 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-29 13:12:22.507  2152  2152 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-29 13:12:22.509  1043  1949 I ActivityManager: Killing 5662:com.android.calendar/u0a13 (adj 15): empty #17
08-29 13:12:22.523  2152  2152 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29983
,08-29 13:12:22.656  1043  2023 W libprocessgroup: failed to open /acct/uid_10013/pid_5662/cgroup.procs: No such file or directory
,08-29 13:12:23.899  6846  6878 D UEI.SmartControl: Internal timer expired: 1
,08-29 13:12:23.900  6846  6878 D UEI.SmartControl: unbind internal service
,08-29 13:12:23.914  6846  6846 D UEI.SmartControl: Service.onUnbind: IControl
08-29 13:12:23.915  6846  6846 D UEI.SmartControl: Service.onDestroy
08-29 13:12:23.915  6846  6846 D UEI.SmartControl: Lock is in USE false
08-29 13:12:23.915  6846  6846 D UEI.SmartControl: unbind internal service
08-29 13:12:23.916  6846  6846 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@20244a45
08-29 13:12:23.916  6846  6846 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-29 13:12:23.917  6846  6846 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-29 13:12:23.917  6846  6846 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-29 13:12:23.917  6846  6846 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-29 13:12:23.917  6846  6846 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-29 13:12:23.917  6846  6846 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-29 13:12:23.917  6846  6846 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-29 13:12:23.917  6846  6846 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-29 13:12:23.917  6846  6846 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:23.917  6846  6846 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 13:12:23.917  6846  6846 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 13:12:23.917  6846  6846 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:23.917  6846  6846 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:23.917  6846  6846 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 13:12:23.918  6846  6846 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 13:12:23.918  6846  6846 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@20244a45
,08-29 13:12:23.927  6846  6846 D serial_port: close(fd = 25)
08-29 13:12:23.931  6846  6846 I UEI.SmartControl: Serial port is closed.
08-29 13:12:23.931  6846  6846 I UEI.SmartControl: Serial port is closed.
08-29 13:12:23.931  6846  6846 D UEI.SmartControl: Blaster closed
08-29 13:12:23.932  6846  6846 D UEI.SmartControl: Shut down QS...
08-29 13:12:23.932  6846  6846 D UEI.SmartControl: Stopping QS lib
08-29 13:12:23.932  6846  6846 D UEI.SmartControl: QS lib stop result = true
08-29 13:12:23.932  6846  6846 D UEI.SmartControl: Stopped QS lib
08-29 13:12:23.933  6846  6846 D UEI.SmartControl: Stopped file observer...
08-29 13:12:23.933  6846  6846 D UEI.SmartControl: QS shutdown complete
,08-29 13:12:24.152  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 13:12:24.152  6705  6760 I jxcore-log: 
,08-29 13:12:24.154  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 13:12:24.154  6705  6760 I jxcore-log: 
08-29 13:12:24.158  6705  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:24.158  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:24.158  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:24.158  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:24.158  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:24.158  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:24.158  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:24.158  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:24.161  6705  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:24.163  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 13:12:24.163  6705  6760 I jxcore-log: 
08-29 13:12:24.165  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 13:12:24.165  6705  6760 I jxcore-log: 
,08-29 13:12:24.681  6705  6760 D executeNativeTests: Running unit tests
,08-29 13:12:24.763  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:12:24.763  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 added. We now have 2 listener(s)
,08-29 13:12:24.764  1043  1949 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:24.766  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:12:24.766  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:24.766  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:24.766  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:24.766  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 added. We now have 2 listener(s)
08-29 13:12:24.766  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:24.767  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:12:24.769  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:24.772  6705  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:24.772  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:24.772  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:24.772  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:24.772  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:24.772  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:24.772  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:24.772  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:24.774  6705  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:24.774  6705  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:24.775  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:24.776  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:24.779  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-29 13:12:24.782  6705  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 13:12:24.782  6705  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-29 13:12:24.783  6705  6760 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
,08-29 13:12:24.784  6705  6760 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 13:12:24.785  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:12:24.785  6705  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:12:24.785  6705  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:12:24.785  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.786  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.786  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.786  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.786  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.787  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:24.787  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:24.787  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 removed from the list
08-29 13:12:24.787  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.787  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 removed from the list
08-29 13:12:24.787  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.787  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.788  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.788  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.790  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.790  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.790  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.790  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.792  6705  6760 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 13:12:24.792  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.792  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.792  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.793  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.793  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.793  6705  6760 D org.,thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.793  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.793  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.793  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.793  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.793  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.793  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.793  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.793  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.795  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.795  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.795  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.795  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.799  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 13:12:24.799  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 13:12:24.799  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 13:12:24.799  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 13:12:24.799  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 13:12:24.799  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 13:12:24.799  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 13:12:24.799  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 13:12:24.799  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 13:12:24.799  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 13:12:24.799  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 13:12:24.799  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 13:12:24.799  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 13:12:24.799  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 13:12:24.799  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 13:12:24.8,00  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 13:12:24.800  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.800  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.800  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.800  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.800  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.800  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.800  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.800  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.800  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.800  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.800  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.800  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.800  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.800  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.801  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.801  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.801  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.801  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.801  6705  6760 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 13:12:24.803  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:24.807  6705  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:24.807  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:24.807  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:24.807  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:24.807  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:24.807  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:24.807  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:24.807  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:24.808  6705  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Blue,tooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:24.808  6705  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:24.809  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:24.810  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:24.810  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:24.811  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:24.811  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:12:24.811  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:24.811  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:12:24.813  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:12:24.813  1043  1913 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:24.816  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 13:12:24.820  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 13:12:24.821  6705  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-29 13:12:24.822  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:12:24.823  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:24.824  6705  6760 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 13:12:24.824  6705  6760 I io.jxcore.node.ConnectionHelper: start: OK
08-29 13:12:24.826  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.826  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.826  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.827  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.827  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.827  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:24.827  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.827  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.827  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.827  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.827  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.827  6705  6760 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 13:12:24.828  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:24.830  6705  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:24.830  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:24.830  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:24.830  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:24.830  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:24.830  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:24.830  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:24.830  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:24.831  6705  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:24.831  6705  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:24.832  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:24.833  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:24.834  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:24.834  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:24.834  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:12:24.834  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:24.834  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:12:24.836  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:12:24.837  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:24.837  6705  6760 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 13:12:24.838  6705  6760 I io.jxcore.node.ConnectionHelper: start: OK
08-29 13:12:24.839  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.839  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.839  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.839  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.839  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.839  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:24.839  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.839  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.839  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.839  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.839  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.839  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.839  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.840  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.840  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.841  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:24.841  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:24.841  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.841  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.842  6705  6760 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 13:12:24.843  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:24.845  6705  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:24.845  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:24.845  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:24.845  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:24.845  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:24.845  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:24.845  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:24.845  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:24.846  6705  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:24.846  6705  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:24.847  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:24.848  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:24.848  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:24.848  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:24.848  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:12:24.848  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:24.848  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:12:24.850  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:12:24.851  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:24.851  6705  6760 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 13:12:24.851  6705  6760 I io.jxcore.node.ConnectionHelper: start: OK
08-29 13:12:24.851  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.851  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.852  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.852  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.852  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.852  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.852  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.852  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.852  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:24.852  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.852  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.853  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.853  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.853  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.853  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.853  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:24.853  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.854  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.854  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:24.854  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:24.854  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.854  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.854  6705  6760 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 13:12:24.855  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.855  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.855  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.855  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.855  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.855  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.855  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.855  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.855  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.855  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.855  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.855  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.855  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.855  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.856  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.856  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.856  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:24.856  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:24.856  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.856  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.857  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 13:12:24.857  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.857  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.857  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.857  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.857  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.857  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.857  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.857  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.858  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.858  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.858  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.858  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.858  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.858  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.858  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.858  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.859  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:24.859  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:24.859  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.859  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.859  6705  6760 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 13:12:24.859  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.859  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.859  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.860  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.860  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.860  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.860  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.860  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.860  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.860  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.860  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.860  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.860  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.860  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.861  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.861  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.861  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:24.861  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:24.861  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.861  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.861  6705  6760 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 13:12:24.861  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.862  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.862  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.862  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.862  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.862  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.862  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.862  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.862  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.862  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.862  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.862  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.862  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.862  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.863  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.863  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.864  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:24.864  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:24.864  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.864  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.864  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 13:12:24.865  6705  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:12:24.865  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:12:24.865  6705  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:12:24.865  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 13:12:24.865  6705  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:12:24.865  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.865  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.865  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.866  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.866  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.866  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.866  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.866  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.866  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.866  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.866  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.866  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.866  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.866  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.866  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.867  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.867  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:24.867  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:24.867  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.867  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.868  6705  6760 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:12:24.868  6705  6760 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 13:12:24.868  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 13:12:24.869  6705  6760 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:12:24.870  6705  6760 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 13:12:24.870  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 13:12:24.872  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 13:12:24.872  6705  6760 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 13:12:24.872  6705  6760 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:12:24.872  6705  6760 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 13:12:24.872  6705  6760 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:12:24.872  6705  6760 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:12:24.873  6705  6760 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 13:12:24.873  6705  6760 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:12:24.873  6705  6760 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:12:24.873  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 13:12:24.874  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 13:12:24.876  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 13:12:24.876  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 13:12:24.876  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 13:12:24.876  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 13:12:24.877  6705  6760 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 13:12:24.877  6705  6760 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:12:24.877  6705  6760 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 13:12:24.877  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.877  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.877  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.877  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.877  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.877  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.878  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 13:12:24.878  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.878  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.878  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.878  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.878  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.878  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.878  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.878  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.879  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.879  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.879  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:24.879  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:24.879  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.879  6705  6889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 851
08-29 13:12:24.879  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.880  6705  6760 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 13:12:24.880  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.881  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.881  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.881  6705  6888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 851)
08-29 13:12:24.882  6705  6888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 851)
08-29 13:12:24.882  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.882  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.882  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.882  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.882  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.882  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.882  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.882  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.882  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.882  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.882  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.883  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.883  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.883  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:24.883  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:24.884  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.884  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.884  6705  6760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 13:12:24.884  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.884  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.885  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.885  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.885  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.885  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.885  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.885  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.885  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.885  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.885  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.885  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.885  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.885  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.886  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.886  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.886  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:24.886  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:24.886  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.886  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.887  6705  6760 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 13:12:24.887  6705  6760 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 13:12:24.887  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:12:24.887  6705  6760 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 13:12:24.887  6705  6760 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 13:12:24.887  6705  6760 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 13:12:24.887  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:12:24.887  6705  6760 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 13:12:24.887  6705  6760 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 13:12:24.887  6705  6760 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 13:12:24.887  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:12:24.887  6705  6760 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 13:12:24.887  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.887  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.887  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.888  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.888  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.888  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.888  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.888  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.888  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.888  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.888  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.888  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.888  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.888  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.889  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.889  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.889  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:24.889  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:24.889  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.889  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.889  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.889  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.889  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.889  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.889  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.889  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.889  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.889  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.889  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.890  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.890  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.890  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.890  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.890  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.890  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.890  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.890  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.890  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.890  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.890  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.890  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.890  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.890  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.890  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.890  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.890  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.890  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.891  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.891  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.891  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.891  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.892  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:24.892  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:24.892  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.892  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.893  6705  6760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 13:12:24.893  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:24.893  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 13:12:24.894  6705  6760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 13:12:24.894  6705  6760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 13:12:24.894  6705  6705 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 13:12:24.894  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 13:12:24.894  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:12:24.895  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.895  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 13:12:24.895  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 13:12:24.895  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 13:12:24.895  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.895  6705  6760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 13:12:24.896  6705  6705 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 13:12:24.896  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.896  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.896  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:12:24.896  6705  6760 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:12:24.896  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:12:24.897  6705  6890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 13:12:24.897  6705  6890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 13:12:24.897  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:12:24.898  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:24.898  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:24.898  6705  6760 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:12:24.898  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.898  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.899  6705  6760 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:24.899  6705  6705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:24.899  6705  6705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:24.899  6705  6705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:24.899  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.899  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.899  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.899  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.900  6705  6705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 13:12:24.900  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.900  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.900  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.900  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.900  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.900  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.900  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.900  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.900  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.900  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.900  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.901  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.901  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.901  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.901  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.902  6705  6760 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 13:12:24.902  6705  6760 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 13:12:24.902  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:12:24.904  6705  6760 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:12:24.904  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.904  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.904  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.904  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.904  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.904  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.904  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.904  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.904  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.904  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.904  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.904  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.904  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.904  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.908  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.908  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.908  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.908  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.911  1043  1565 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:24.911  1043  1061 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:24.912  1043  1764 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:24.912  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.912  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.912  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.912  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.912  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.912  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.912  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.912  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.912  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.912  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.912  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.912  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.913  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.913  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.915  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.915  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.915  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.915  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.916  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:24.916  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:24.916  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:24.918  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:24.918  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.918  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.918  6705  6760 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eae6c0 not in the list
08-29 13:12:24.918  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.918  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.918  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:24.918  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.918  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.918  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:24.919  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:24.921  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:24.921  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:24.921  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:24.921  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2eff9 not in the list
08-29 13:12:24.924  6705  6760 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 13:12:24.924  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:12:24.925  6705  6760 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 13:12:24.925  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:12:24.925  6705  6760 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 13:12:24.925  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:12:24.927  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 13:12:24.927  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 13:12:24.928  6705  6760 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 13:12:24.928  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 13:12:24.928  6705  6760 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-29 13:12:24.928  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 13:12:24.928  6705  6760 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 13:12:24.928  6705  6760 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 13:12:24.929  6705  6760 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 13:12:24.929  6705  6760 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 13:12:24.930  6705  6760 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 13:12:24.930  6705  6760 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 13:12:24.930  6705  6760 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 13:12:24.930  6705  6760 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 13:12:24.931  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:24.931  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d4a7416 added. We now have 2 listener(s)
08-29 13:12:24.931  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:24.932  6705  6760 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 13:12:24.933  1043  1985 D WifiServiceImplEx: setWifiEnabled: true pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 13:12:24.933  1043  1985 D WifiService: setWifiEnabled: true pid=6705, uid=10118
08-29 13:12:24.933  1043  1985 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 13:12:24.935  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:24.935  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17165197 added. We now have 3 listener(s)
08-29 13:12:24.935  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:24.938  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:24.938  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1326ef84 added. We now have 4 listener(s)
08-29 13:12:24.938  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:24.939  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:24.939  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8a6636d added. We now have 5 listener(s)
08-29 13:12:24.939  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:24.941  1043  1895 D WifiServiceImplEx: setWifiEnabled: false pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 13:12:24.941  1043  1895 D WifiService: setWifiEnabled: false pid=6705, uid=10118
08-29 13:12:24.941  1043  1895 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 13:12:24.952  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 13:12:24.953  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 13:12:24.953  1043  1043 D Ulp_jni : JNI:system_update. Event-4
08-29 13:12:24.953  1043  1428 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 13:12:24.954  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 13:12:24.954  1043  2022 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:24.954  1043  1428 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 13:12:24.954  1043  2022 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@313e7e7 mBinding = false
08-29 13:12:24.954  1043  1428 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 13:12:24.954  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 13:12:24.954  1043  1428 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 13:12:24.954  1043  1428 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:12:24.954  1043  1428 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 13:12:24.955  1043  1428 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 13:12:24.955  1043  1428 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 13:12:24.961  1043  1428 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 13:12:24.961  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 13:12:24.961  1043  1378 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:24.961  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:24.961  2708  2708 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 13:12:24.961  1043  1428 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 13:12:24.961  1043  1428 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 13:12:24.962  1043  1428 D WifiNative-wlan0: SET ps 1: returned true
08-29 13:12:24.962  1043  2851 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:24.962   323   896 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:12:24.969  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 13:12:24.969  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 13:12:24.969  1043  1043 D Ulp_jni : JNI:system_update. Event-4
08-29 13:12:24.970  1043  1120 D BluetoothManagerService: Message: 2
08-29 13:12:24.972  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:24.975  1043  1120 D BluetoothManagerService: Sending off request.
,08-29 13:12:24.976  4312  4332 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 13:12:24.977  4312  4440 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 13:12:24.977  6705  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:24.977  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:24.977  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:24.977  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:24.977  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:24.977  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:24.977  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:24.977  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:24.977  4312  4440 D BluetoothAdapterProperties: Setting state to 13
08-29 13:12:24.977  4312  4440 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 13:12:24.977  4312  4440 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 13:12:24.977  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:24.977  4312  4440 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 13:12:24.978  6705  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:24.978  6705  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:24.982  4312  4447 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:12:24.983  4312  4440 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 13:12:24.984  1043  1120 D BluetoothManagerService: Message: 60
08-29 13:12:24.984  1043  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 13:12:24.984  1043  1120 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 13:12:24.984  4312  4772 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:12:24.984  4312  4440 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 13:12:24.984  4312  4767 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:12:24.984  4312  4786 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:12:24.985  4312  4727 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 13:12:24.985  4312  4727 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:12:24.985  4312  4727 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 13:12:24.985  4312  4727 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 13:12:24.985  4312  4727 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 13:12:24.985  4312  4727 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 13:12:24.985  4312  4727 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 13:12:24.985  4312  4727 V BluetoothMapMasInstance: 	at com.andro,id.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-29 13:12:24.985  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 13:12:24.986  4312  4728 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 13:12:24.989  4312  4550 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 13:12:24.991  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:12:24.991  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:12:24.991  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:12:24.991  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:12:24.991  4312  4550 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:24.991  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:12:24.991  4312  4550 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:24.991  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:12:24.991  4312  4550 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:12:24.991  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 13:12:24.991  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 13:12:24.991  4312  4550 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 13:12:24.992  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:24.992  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:24.992  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:24.992  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:24.992  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:24.992  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:24.992  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:24.992  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:24.992  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:24.992  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:24.993  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:24.995  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:24.996  1043  1509 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 13:12:24.996  1043  1509 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-29 13:12:24.997  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:24.997  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:24.997  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:24.997  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:24.997  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:24.997  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:24.997  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:24.997  6705  6705 V io.jxcore.node.Connect,ivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:24.997  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:24.998  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:24.998  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:25.006  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:25.006  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:25.006  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:25.006  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:25.006  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:25.006  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:25.006  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:25.006  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:25.006  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:25.006  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:25.006  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:25.008  1043  1565 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-29 13:12:25.008  1043  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:25.009  1043  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:25.009  1043  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-29 13:12:25.009  1043  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:25.009  1043  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-29 13:12:25.030  1043  1113 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6910 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-29 13:12:25.031   323  6918 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 13:12:25.031  1043  1509 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 13:12:25.031  1043  1509 D DSQN    : disableDataServiceNotify
08-29 13:12:25.031  1043  1509 D DSQN    : stop dsqn bin
08-29 13:12:25.032  4312  4312 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:25.032  4312  4312 D BluetoothMapService: STATE_TURNING_OFF
08-29 13:12:25.032  4312  4312 V BtOppService: Receiver DISABLED_ACTION 
08-29 13:12:25.032  4312  4312 V BluetoothMapService: Handler(): got msg=4
08-29 13:12:25.032  4312  4312 D BluetoothMapService: MAP Service closeService in
08-29 13:12:25.033  4312  4312 D BluetoothMapMasInstance: MAP Service shutdown
08-29 13:12:25.033  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 13:12:25.033  4312  4312 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 13:12:25.033  4312  4312 V BluetoothMapService: MAP Service closeService out
08-29 13:12:25.033  4312  4312 I BtOppRfcommListener: stopping Accept Thread
08-29 13:12:25.033  4312  4312 V BtOppRfcommListener: close mBtServerSocket
08-29 13:12:25.033  1043  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 13:12:25.034  4312  4312 V BtOppRfcommListener: waiting for thread to terminate
08-29 13:12:25.034  1043  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-29 13:12:25.034  4312  4767 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 13:12:25.034  1931  1931 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:25.034  4312  4312 V BtOppRfcommListener: done waiting for thread to terminate
08-29 13:12:25.036  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:25.036  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:25.036  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:25.036  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:25.036  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:25.036  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:25.036  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:25.036  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:25.036  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:25.038  1043  1509 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 13:12:25.038  1043  1509 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:25.038  1043  1509 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:12:25.038  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:25.038  1043  1509 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:12:25.038  1043  1509 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 13:12:25.039  1592  2041 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 13:12:25.039  1043  1509 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAge,ntInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 13:12:25.039  1043  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:25.039  1043  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:25.039  1043  1509 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 13:12:25.039  1043  2850 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 13:12:25.039  1043  1509 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 13:12:25.068  1043  1113 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6928 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 13:12:25.069  1043  1509 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:25.069  1043  1509 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 13:12:25.069  1043  1509 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:25.069  1043  1509 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:25.069  1043  1509 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:25.070  1043  1428 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:25.070  4312  4312 V BtOppService: onDestroy
08-29 13:12:25.070  1043  1509 D NetworkManagementService: Removing idletimer
08-29 13:12:25.070  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:25.070  1043  1428 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:25.070  1043  1509 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:25.071  1043  1428 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:25.071  1043  1509 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 13:12:25.071  4312  4312 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 13:12:25.071  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:25.071  1843  1843 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:25.071  1043  1428 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:25.071  1843  1843 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 13:12:25.072  1043  1428 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 13:12:25.072  1043  1428 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:25.072  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:25.072  1043  1428 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:25.073  1043  1428 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:25.073  1043  1378 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:25.073  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:25.073  1043  1428 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:12:25.073  1043  1378 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2286924f
08-29 13:12:25.075  1043  1043 D WifiHS20: hidePasspointNotification off =false
08-29 13:12:25.076  1931  1931 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-29 13:12:25.077  1043  1377 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 13:12:25.077  1043  1377 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 13:12:25.079  1043  1378 D LGWifiP2pService: P2pDisablingState
08-29 13:12:25.079  1043  1378 D LGWifiP2pService: P2pDisablingState{ when=-6ms what=14745,8 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:25.079  1043  1378 D LGWifiP2pService: p2p socket connection lost
08-29 13:12:25.079  1043  1378 D LGWifiP2pService: P2pDisabledState
08-29 13:12:25.079  1043  1428 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 13:12:25.079  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 13:12:25.080  1043  1378 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:25.080  1043  1378 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:25.080  2708  2708 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 13:12:25.080  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:25.080  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:25.080  1043  1428 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 13:12:25.080  1043  1428 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 13:12:25.080  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 13:12:25.080  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 13:12:25.080  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 13:12:25.080  1043  1428 D WifiNative-wlan0: SET ps 1: returned true
08-29 13:12:25.080  1043  1043 D WifiHS20: hidePasspointNotification off =false
,08-29 13:12:25.080   323   896 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:12:25.080  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:25.080  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:25.081  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 13:12:25.081  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 13:12:25.081  1043  1043 D RttService: SCAN_AVAILABLE : 1
08-29 13:12:25.081  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 13:12:25.081  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 13:12:25.081  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 13:12:25.081  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 13:12:25.081  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 13:12:25.081  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 13:12:25.081  1043  1546 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:25.081  1043  1547 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:25.083  1043  1428 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 13:12:25.083  1043  1428 D WifiNative-p2p0: TERMINATE: returned true
08-29 13:12:25.084  1043  1428 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:12:25.084  1043  1428 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:12:25.084  1043  1428 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 13:12:25.085  1043  1043 D WifiHS20: hidePasspointNotification off =false
08-29 13:12:25.085  1931  1931 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 13:12:25.085  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:25.085  1931  1931 D WfdsService: WifiP2pState is changed : false
08-29 13:12:25.085  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:25.085  1931  2284 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 13:12:25.085  1931  2284 D WfdsService: Set the WFDS Monitor: false
08-29 13:12:25.086  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:25.086  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:25.086  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 13:12:25.086  1931  2284 D WfdsMonitor: WFDS Monitor is stopped
08-29 13:12:25.086  1931  2284 D WfdsService: STATE : WfdsDisabledState - enter
08-29 13:12:25.086  1931  2764 D CtrlSupplicant: Received on exit socket, terminate
08-29 13:12:25.086  1931  2764 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 13:12:25.086  1931  2764 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 13,:12:25.086  1931  2764 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 13:12:25.087  1931  2287 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 13:12:25.087  1931  2284 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 13:12:25.088  1931  1931 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 13:12:25.089  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:25.091  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:25.091  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:25.091  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:25.091  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:25.091  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:25.091  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:25.091  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:25.091  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:25.091  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:25.091  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:25.091  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 13:12:25.091  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:25.092  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:12:25.092  1043  1043 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 13:12:25.093  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:12:25.093  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:25.093  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:25.093  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:25.093  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:25.093  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:25.093  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:25.093  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:25.093  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:25.093  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:25.093  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:25.119  6928  6928 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:12:25.119  6928  6928 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-29 13:12:25.120  6928  6928 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 13:12:25.120  6928  6928 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-29 13:12:25.121  6928  6928 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 13:12:25.121  6928  6928 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 13:12:25.123  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 13:12:25.124  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 13:12:25.124  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 13:12:25.143  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 13:12:25.143  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:25.144  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:25.144  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:25.144  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:25.145  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:25.153  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-29 13:12:25.153  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:25.154  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:25.155  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:25.163  6910  6910 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-29 13:12:25.164  6910  6910 W LG Account v2.2: No ProfileInfo entries
08-29 13:12:25.165  6910  6910 I LG Account v2.2: isEnabled: false
08-29 13:12:25.165  6910  6910 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 13:12:25.165  6910  6910 I Feature : [Lifetracker]Country: EU
08-29 13:12:25.165  2708  2708 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 13:12:25.165  6910  6910 I Feature : [Lifetracker]Operator: OPEN
08-29 13:12:25.165  2708  2708 I wpa_supplicant: monitor socket send errors count : 1
08-29 13:12:25.165  2708  2708 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1931-2\x00 that cannot receive messages
08-29 13:12:25.165  6910  6910 I Feature : [Lifetracker]Ranking support: false
08-29 13:12:25.165  6910  6910 I Feature : [Lifetracker]Comfort support: false
08-29 13:12:25.165  6910  6910 I Feature : [Lifetracker]Accessory: true
08-29 13:12:25.165  6910  6910 I Feature : [Lifetracker]Health device: true
08-29 13:12:25.165  6910  6910 I Feature : [Lifetracker]Extra Pedometer: false
08-29 13:12:25.166  6910  6910 I Feature : [Lifetracker]Blood glucose device: false
08-29 13:12:25.166  6910  6910 I Feature : [Lifetracker]Device Number: 3
08-29 13:12:25.166  1043  2763 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 13:12:25.166  1043  2763 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-29 13:12:25.167  1043  2851 D DhcpStateMachine: StoppedState
08-29 13:12:25.167  1043  2851 D DhcpStateMachine: StoppedState{ when=-87ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:25.169  1043  1428 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-29 13:12:25.170  1043  1428 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-29 13:12:25.175  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:25.208  1043  1950 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6947 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 13:12:25.210  2708  2708 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 13:12:25.211  1043  2763 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 13:12:25.211  1043  2763 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 13:12:25.211  1043  2763 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 13:12:25.211  2708  2708 W wpa_supplicant: USIM:  scard_deinit function
08-29 13:12:25.211  1043  1120 D Tethering: InitialState.processMessage what=4
08-29 13:12:25.212  1043  2763 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 13:12:25.212  1043  2763 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:12:25.212  1043  2763 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:12:25.213  1043  1428 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=115457
08-29 13:12:25.214  1043  1428 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=115458
08-29 13:12:25.214  1043  1950 I ActivityManager: Killing 6259:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-29 13:12:25.214  1043  1428 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=115459  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 13:12:25.215  1043  1428 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=115459  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 13:12:25.307  1043  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 13:12:25.313  1043  1428 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:25.318  1043  1428 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-29 13:12:25.328  1043  1764 W libprocessgroup: failed to open /acct/uid_10014/pid_6259/cgroup.procs: No such file or directory
08-29 13:12:25.370  1043  1113 I ActivityManager: Waited long enough for: ServiceRecord{22c4cbac u0 com.google.android.gms/.wearable.service.WearableService}
,08-29 13:12:25.395  2708  2708 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 13:12:25.395  1043  2763 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 13:12:25.395  1043  2763 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 13:12:25.395  1043  2763 D WifiMonitor: Disconnecting from the supplicant, no more events
08-29 13:12:25.395  6947  6947 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 13:12:25.396  1043  1428 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-29 13:12:25.399  6705  6705 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 13:12:25.400  6947  6947 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 13:12:25.400  6947  6947 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:12:25.402  1043  1060 I ActivityManager: Killing 6359:com.android.defcontainer/u0a4 (adj 15): empty #17
08-29 13:12:25.408  6928  6928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 13:12:25.448  1043  1646 W libprocessgroup: failed to open /acct/uid_10004/pid_6359/cgroup.procs: No such file or directory
,08-29 13:12:25.452  4312  4312 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 13:12:25.452  4312  4312 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:25.452  4312  4312 V BluetoothPbapReceiver: ***********state = 13
08-29 13:12:25.454  4312  4312 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 13:12:25.456  4312  4312 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:25.456  4312  4312 V BluetoothPbapService: state: 13
08-29 13:12:25.456  4312  4312 V BluetoothPbapService: Pbap Service closeService in
08-29 13:12:25.458  4312  4312 V BluetoothPbapService: successfully stopped pbap service
08-29 13:12:25.458  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:12:25.458  4312  4312 V BluetoothPbapService: Pbap Service closeService out
08-29 13:12:25.459  4312  4312 V BluetoothPbapService: Pbap Service onDestroy
08-29 13:12:25.459  4312  4312 V BluetoothPbapService: Pbap Service closeService in
08-29 13:12:25.459  4312  4312 V BluetoothPbapService: Pbap Service closeService out
08-29 13:12:25.459  4312  4312 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-29 13:12:25.478  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:25.498  1043  1428 D WifiOffDelayIfNotUsed: stopMonitoring
,08-29 13:12:25.498  1043  1428 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:12:25.498  1043  1428 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:12:25.498  1043  1428 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 13:12:25.498  1931  1931 D WfdsService: Supplicant Connection state is changed : false
08-29 13:12:25.498  1931  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 13:12:25.499  1931  2284 D WfdsService: Set the WFDS Monitor: false
08-29 13:12:25.499  1931  2284 D WfdsMonitor: WFDS Monitor is stopped
08-29 13:12:25.500  1931  1931 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-29 13:12:25.502  2454  2454 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:25.502  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:25.504  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 13:12:25.504  1043  1463 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 13:12:25.505  1043  1463 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 13:12:25.507  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:25.509  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:25.538  6928  6928 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:12:25.538  6928  6928 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 13:12:25.548  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:25.559  1043  1120 D BluetoothManagerService: Message: 20
08-29 13:12:25.559  1043  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2213cf7e:true
,08-29 13:12:25.576  1043  1120 D BluetoothManagerService: Message: 30
,08-29 13:12:25.579  1043  1120 D BluetoothManagerService: Message: 30
08-29 13:12:25.583  6928  6928 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 13:12:25.585  6928  6928 D BluetoothMap: Create BluetoothMap proxy object
08-29 13:12:25.586  1043  1120 D BluetoothManagerService: Message: 30
08-29 13:12:25.591  1043  1120 D BluetoothManagerService: Message: 30
,08-29 13:12:25.593  6928  6928 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 13:12:25.594  6928  6928 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-29 13:12:25.610  6928  6928 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-29 13:12:25.616  6928  6928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-29 13:12:25.628  6928  6928 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:12:25.642  6928  6928 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 13:12:25.646  6928  6928 D BluetoothInputDevice: Proxy object connected
08-29 13:12:25.647  6928  6928 D HidProfile: Bluetooth service connected
08-29 13:12:25.648  6928  6928 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 13:12:25.649  6928  6928 D PanProfile: Bluetooth service connected
08-29 13:12:25.650  6928  6928 D BluetoothMap: Proxy object connected
08-29 13:12:25.651  6928  6928 D MapProfile: Bluetooth service connected
08-29 13:12:25.651  6928  6928 D BluetoothMap: getConnectedDevices()
08-29 13:12:25.652  6928  6928 D BluetoothMap: Bluetooth is Not enabled
08-29 13:12:25.652  6928  6928 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 13:12:25.655  6928  6928 D BluetoothPermissionRequest: onReceive
,08-29 13:12:25.658  6928  6928 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 13:12:25.665  1043  1060 I ActivityManager: Killing 6497:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-29 13:12:25.671  6928  6928 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-29 13:12:25.707  1043  1895 W libprocessgroup: failed to open /acct/uid_10008/pid_6497/cgroup.procs: No such file or directory
,08-29 13:12:25.708  4312  4312 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 13:12:25.708  4312  4312 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-29 13:12:25.710  4312  4312 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-29 13:12:25.790  1043  1887 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6979 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-29 13:12:25.795  4312  4312 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:25.795  4312  4312 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 13:12:25.796  4312  4312 V BluetoothFtpService: Ftp Service onStartCommand
08-29 13:12:25.796  4312  4312 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:25.796  4312  4312 V BluetoothFtpService: Ftp Service closeService
08-29 13:12:25.797  4312  4312 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 13:12:25.798  4312  4312 V BluetoothFtpService: successfully stopped ftp service
08-29 13:12:25.799  4312  4312 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 13:12:25.799  4312  4312 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 13:12:25.799  4312  4312 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 13:12:25.799  4312  4312 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:25.799  4312  4312 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 13:12:25.799  4312  4312 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 13:12:25.800  4312  4312 V BluetoothFtpService: Ftp Service onDestroy
08-29 13:12:25.800  4312  4312 V BluetoothFtpService: Ftp Service closeService
08-29 13:12:25.855  1043  1895 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6996 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 13:12:25.856  4312  4312 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:25.856  4312  4312 V BluetoothSapService: state: 13
08-29 13:12:25.856  4312  4312 V BluetoothSapService: Stopping SAP server process
,08-29 13:12:25.858  4312  4312 V BluetoothSapService: Sap Service closeSapService in
08-29 13:12:25.858  4312  4312 V BluetoothSapService: Close listen Socket : 
08-29 13:12:25.858  4312  4312 V BluetoothSapService: Close rfcomm Socket : 
08-29 13:12:25.858  4312  4312 V BluetoothSapService: Close sapd  Socket : 
08-29 13:12:25.868  4312  4312 V BluetoothSapService: Sap Service closeSapService out
08-29 13:12:25.868  4312  4312 V BluetoothSapService: Sap Service onDestroy
08-29 13:12:25.868  4312  4312 V BluetoothSapService: Sap Service closeSapService in
08-29 13:12:25.868  4312  4312 V BluetoothSapService: Close listen Socket : 
08-29 13:12:25.868  4312  4312 V BluetoothSapService: Close rfcomm Socket : 
08-29 13:12:25.868  4312  4312 V BluetoothSapService: Close sapd  Socket : 
08-29 13:12:25.869  4312  4312 V BluetoothSapService: Sap Service closeSapService out
,08-29 13:12:25.889  6979  6979 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 13:12:25.913  6996  6996 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 13:12:25.916  6979  6979 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-29 13:12:25.929  1043  1060 I ActivityManager: Killing 6544:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-29 13:12:25.954  6979  6979 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-29 13:12:25.954  6979  6979 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-29 13:12:25.955  6979  6979 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-29 13:12:25.955  6979  6979 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-29 13:12:25.955  6979  6979 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-29 13:12:25.957  6979  6979 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-29 13:12:25.963  6979  6979 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-29 13:12:25.978  1043  1061 W libprocessgroup: failed to open /acct/uid_10011/pid_6544/cgroup.procs: No such file or directory
,08-29 13:12:25.994  4312  4550 W bt-btif : ag scb idx 1 not allocated
08-29 13:12:25.994  4312  4447 D bt_hci_bdroid: cleanup
08-29 13:12:25.994  4312  4550 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:12:25.994  4312  4550 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:12:25.994  4312  4550 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 13:12:25.997  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:25.998  4312  4552 I bt_lpm  : LPM is already off!!!
,08-29 13:12:25.999  4312  4702 I bt_userial_mct: exiting userial_read_thread
,08-29 13:12:26.000  4312  4702 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-29 13:12:26.001  4312  4447 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-29 13:12:26.001  4312  4552 I bt_vendor: hw_epilog_process
,08-29 13:12:26.001  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:26.002  4312  4447 D bt_hci_bdroid: cleanup Finalizing cleanup
,08-29 13:12:26.002  4312  4447 D bt_userial_mct: userial_close
,08-29 13:12:26.002  4312  4447 E bt_userial_mct: pthread_join() FAILED result:3,
,08-29 13:12:26.002  4312  4447 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0,
08-29 13:12:26.021  6979  6979 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-29 13:12:26.025  6979  6979 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-29 13:12:26.025  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:12:26.031  6947  6947 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 13:12:26.032  6947  6947 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-29 13:12:26.032  6947  6947 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:12:26.036  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:26.039  6979  6979 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-29 13:12:26.045  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 13:12:26.054  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE,
,08-29 13:12:26.054  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:26.057  6979  6979 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:12:26.058  4312  4447 D bt_hci_bdroid: set_power 0
08-29 13:12:26.058  4312  4447 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 13:12:26.058  4312  4447 I bt_vendor: bluetooth satus is on
08-29 13:12:26.058  4312  4447 I bt_vendor: bt-vendor : resetting BT status
08-29 13:12:26.058  4312  4447 I bt_vendor: Starting hciattach daemon
08-29 13:12:26.058  4312  4447 I bt_vendor: try to set false
08-29 13:12:26.060  4312  4447 I bt_vendor: Starting hciattach daemon
08-29 13:12:26.060  4312  4447 I bt_vendor: try to set false
08-29 13:12:26.060  4312  4447 I bt_vendor: cleanup
08-29 13:12:26.061  4312  4550 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 13:12:26.062  4312  4447 I GKI_LINUX: GKI_exit_task 0 done
08-29 13:12:26.062  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:26.062  4312  4447 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 13:12:26.064  4312  4440 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 13:12:26.071  6947  6947 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 13:12:26.071  6947  6947 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 13:12:26.071  6947  6947 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 13:12:26.076  4312  4312 D HeadsetService: Received stop request...Stopping profile...
08-29 13:12:26.079  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:12:26.079  4312  4312 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 13:12:26.079  4312  4312 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:12:26.080  4312  4312 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1b5e8e
08-29 13:12:26.080  4312  4504 D HeadsetStateMachine: Exit Disconnected: -1
08-29 13:12:26.081  1043  1043 D BluetoothHeadset: Proxy object disconnected
08-29 13:12:26.081  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 13:12:26.083  1843  1843 D BluetoothHeadset: Proxy object disconnected
08-29 13:12:26.083  1843  1843 D BluetoothHeadset: Proxy object disconnected
08-29 13:12:26.083  1843  1843 D BluetoothHeadset: Proxy object disconnected
,08-29 13:12:26.087  4312  4312 D A2dpService: Received stop request...Stopping profile...
08-29 13:12:26.087  4312  4531 D A2dpStateMachine: Exit Disconnected: -1
08-29 13:12:26.089  4312  4312 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 13:12:26.092  4312  4440 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 13:12:26.092  4312  4312 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 13:12:26.093  4312  4312 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:12:26.093  4312  4312 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1b5e8e
08-29 13:12:26.094  1043  1043 D BluetoothA2dp: Proxy object disconnected
08-29 13:12:26.094  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-29 13:12:26.098  4312  4312 D HeadsetStateMachine: Unbinding service...
08-29 13:12:26.099  4312  4312 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 13:12:26.099  4312  4312 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 13:12:26.099  4312  4312 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 13:12:26.099  4312  4312 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 13:12:26.099  4312  4312 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 13:12:26.099  4312  4312 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:12:26.099  4312  4312 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 13:12:26.100  4312  4312 D HidService: Received stop request...Stopping profile...
08-29 13:12:26.100  4312  4312 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1b5e8e
08-29 13:12:26.100  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:26.101  6928  6928 D BluetoothInputDevice: Proxy object disconnected
08-29 13:12:26.101  6928  6928 D HidProfile: Bluetooth service disconnected
08-29 13:12:26.102  4312  4312 D HealthService: Received stop request...Stopping profile...
08-29 13:12:26.102  4312  4312 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1b5e8e
08-29 13:12:26.104  4312  4312 D PanService: Received stop request...Stopping profile...
08-29 13:12:26.105  4312  4312 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1b5e8e
08-29 13:12:26.106  4312  4312 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 13:12:26.107  4312  4312 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 13:12:26.107  4312  4312 D BtGatt.GattService: stop()
08-29 13:12:26.108  4312  4312 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 13:12:26.109  4312  4312 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1b5e8e
08-29 13:12:26.110  6928  6928 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 13:12:26.110  6928  6928 D PanProfile: Bluetooth service disconnected
08-29 13:12:26.115  4312  4312 D BluetoothMapService: Received stop request...Stopping profile...
08-29 13:12:26.115  4312  4312 D BluetoothMapService: stop()
08-29 13:12:26.115  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:26.116  4312  4312 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 13:12:26.116  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:26.116  4312  4312 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 13:12:26.117  4312  4312 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d1b5e8e
08-29 13:12:26.118  6979  6979 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:12:26.118  6928  6928 D BluetoothMap: Proxy object disconnected
08-29 13:12:26.118  6928  6928 D MapProfile: Bluetooth service disconnected
08-29 13:12:26.118  4312  4312 I BluetoothA2dpServiceJni: cleanupNative
08-29 13:12:26.118  4312  4534 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 13:12:26.119  4312  4312 I GKI_LINUX: GKI_exit_task 2 done
08-29 13:12:26.119  4312  4312 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 13:12:26.119  4312  4312 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 13:12:26.119  4312  4312 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 13:12:26.119  4312  4312 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 13:12:26.120  4312  4312 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:12:26.120  4312  4312 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:12:26.120  4312  4312 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 13:12:26.120  4312  4312 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 13:12:26.122  4312  4312 V BluetoothMapService: Handler(): got msg=4
08-29 13:12:26.122  4312  4312 D BluetoothMapService: MAP Service closeService in
08-29 13:12:26.122  4312  4312 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 13:12:26.122  4312  4312 V BluetoothMapService: MAP Service closeService out
08-29 13:12:26.123  4312  4312 D BluetoothMapService: cleanup()
08-29 13:12:26.123  4312  4312 D BluetoothMapService: MAP Service closeService in
08-29 13:12:26.123  4312  4312 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 13:12:26.123  4312  4312 V BluetoothMapService: MAP Service closeService out
08-29 13:12:26.123  4312  4440 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 13:12:26.124  4312  4440 D BluetoothAdapterProperties: Setting state to 10
08-29 13:12:26.125  4312  4440 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 13:12:26.125  1043  1120 D BluetoothManagerService: Message: 60
08-29 13:12:26.125  1043  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 13:12:26.125  1043  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-29 13:12:26.126  4312  4440 I BluetoothAdapterState: Entering OffState
08-29 13:12:26.126  1843  1858 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:26.185  1043  1060 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7017 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-29 13:12:26.191  1843  2420 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:26.192  6928  6944 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 13:12:26.194  6928  6943 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 13:12:26.195  1043  1120 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:12:26.195  1843  1859 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:26.196  6928  6944 D BluetoothPan: onBluetoothStateChange on: false
08-29 13:12:26.197  6928  6943 D BluetoothMap: onBluetoothStateChange: up=false
08-29 13:12:26.198  1043  1120 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:26.199  1043  1120 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 13:12:26.199  1043  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-29 13:12:26.203  1043  1120 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 13:12:26.204  1043  1120 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 13:12:26.204  1043  1120 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@313e7e7 mBinding = false
08-29 13:12:26.205  1043  1120 D BluetoothManagerService: Sending unbind request.
08-29 13:12:26.206  1043  1120 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-29 13:12:26.214  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-29 13:12:26.218  4312  4447 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-29 13:12:26.220  4312  4312 I GKI_LINUX: GKI_exit_task 1 done
08-29 13:12:26.220  4312  4312 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 13:12:26.221  4312  4312 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 13:12:26.221  4312  4312 I art     : --- WEIRD: removing null entry 246
08-29 13:12:26.221  4312  4312 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-29 13:12:26.221  4312  4312 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 13:12:26.222  1931  1931 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:26.222  1931  2094 D LGBluetoothAPIService: Message: 2
08-29 13:12:26.222  1592  1592 D BluetoothAdapter: 1054278118: getState() :  mService = null. Returning STATE_OFF
08-29 13:12:26.222  1592  1592 D BluetoothAdapter: 1054278118: getState() :  mService = null. Returning STATE_OFF
08-29 13:12:26.223  1931  2094 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@a128899 mBinding = false
08-29 13:12:26.223  1931  2094 D LGBluetoothAPIService: Sending unbind request.
08-29 13:12:26.225  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:26.226  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:26.232  4312  4312 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 13:12:26.233  6928  6928 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 13:12:26.234  6928  6928 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 13:12:26.234  6928  6928 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 13:12:26.236  4312  4312 I art     : System.exit called, status: 0
08-29 13:12:26.236  4312  4312 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 13:12:26.241  6928  6928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 13:12:26.249  6928  6928 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:12:26.255   327  1717 V AudioFlinger: 4312 died, releasing its sessions
08-29 13:12:26.255   327  1717 V AudioFlinger:  pid 1843 @ 0
08-29 13:12:26.255   327  1717 V AudioFlinger:  pid 3228 @ 1
08-29 13:12:26.255   327  1717 V AudioFlinger:  pid 3228 @ 2
08-29 13:12:26.256  6928  6928 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-29 13:12:26.304  1043  1986 I ActivityManager: Process com.android.bluetooth (pid 4312) has died
08-29 13:12:26.304  1043  1986 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-29 13:12:26.312  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:12:26.330  6947  6947 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 13:12:26.336  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:12:26.354  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:26.355  6928  6928 D BluetoothPermissionRequest: onReceive
08-29 13:12:26.359  6928  6928 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 13:12:26.359  6928  6928 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 13:12:26.362  6928  6928 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 13:12:26.428  1043  1646 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7044 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 13:12:26.441  7017  7042 W FormManager: Network not available. Please check & try again.
08-29 13:12:26.460  7017  7043 V FormManager: Network unavailable.
,08-29 13:12:26.464  7017  7043 V FormManager: Network unavailable.
08-29 13:12:26.466  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 13:12:26.466  6928  6928 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 13:12:26.467  6928  6928 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 13:12:26.467  6928  6928 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 13:12:26.468  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-29 13:12:26.496  6928  6928 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 13:12:26.496  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,08-29 13:12:26.497  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 13:12:26.497  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 13:12:26.497  6928  6928 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 13:12:26.498  7044  7044 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 13:12:26.498  6928  6928 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 13:12:26.498  7044  7044 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 13:12:26.498  7044  7044 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-29 13:12:26.499  7044  7044 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 13:12:26.502  1043  1764 I ActivityManager: Killing 6056:com.android.contacts/u0a19 (adj 15): empty #17
08-29 13:12:26.519  7044  7044 D BluetoothAdapterApp: Loading JNI Library
,08-29 13:12:26.556  7044  7044 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@30e887b7 Instance Count = 1
08-29 13:12:26.558  1043  1895 W libprocessgroup: failed to open /acct/uid_10019/pid_6056/cgroup.procs: No such file or directory
08-29 13:12:26.559  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 13:12:26.560  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-29 13:12:26.562  7044  7044 D BluetoothAdapterApp: onCreate
08-29 13:12:26.566  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:12:26.571  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:12:26.591  7044  7044 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 13:12:26.591  7044  7044 D ProfileConfigQcom: Adding HeadsetService
08-29 13:12:26.592  7044  7044 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 13:12:26.592  6947  6947 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 13:12:26.592  7044  7044 D ProfileConfigQcom: Adding A2dpService
08-29 13:12:26.592  6947  6947 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 13:12:26.592  6947  6947 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:12:26.592  7044  7044 D ProfileConfigQcom: [BTUI] HidService is supported
,08-29 13:12:26.592  7044  7044 D ProfileConfigQcom: Adding HidService
08-29 13:12:26.593  7044  7044 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 13:12:26.593  7044  7044 D ProfileConfigQcom: Adding HealthService
,08-29 13:12:26.593  7044  7044 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 13:12:26.594  7044  7044 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 13:12:26.595  7044  7044 D ProfileConfigQcom: Adding PanService
08-29 13:12:26.595  7044  7044 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 13:12:26.595  7044  7044 D ProfileConfigQcom: Adding GattService
08-29 13:12:26.595  7044  7044 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 13:12:26.595  7044  7044 D ProfileConfigQcom: Adding BluetoothMapService
08-29 13:12:26.596  7044  7044 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 13:12:26.598  7044  7044 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-29 13:12:26.598  4806  7064 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 13:12:26.601  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:26.607  4806  7065 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-29 13:12:26.609  7044  7044 V LGMDMManagerInternal: Create singleton instance
08-29 13:12:26.619  7017  7070 V FormManager: Network unavailable.
,08-29 13:12:26.621  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:26.623  4806  7065 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 13:12:26.624  6928  6928 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 13:12:26.629  7017  7070 V FormManager: Network unavailable.
08-29 13:12:26.632  7017  7069 W FormManager: Network not available. Please check & try again.
,08-29 13:12:26.644  6979  6979 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 13:12:26.645  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-29 13:12:26.645  6979  6979 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-29 13:12:26.682  6979  6979 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:12:26.683  6979  6979 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 13:12:26.691  6979  6979 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-29 13:12:26.692  6979  6979 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-29 13:12:26.692  6979  6979 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-29 13:12:26.692  6979  6979 V SoundPool: doLoad: loading sample sampleID=1
08-29 13:12:26.693  6979  7074 V SoundPool: Start decode
08-29 13:12:26.693  6979  6979 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 13:12:26.693  6979  7074 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-29 13:12:26.695   327  1715 V MediaPlayerService: decode(23, 10857164, 17813)
08-29 13:12:26.695   327  1715 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-29 13:12:26.695   327  1715 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-29 13:12:26.695   327  1715 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-29 13:12:26.695   327  1715 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-29 13:12:26.695   327  1715 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-29 13:12:26.695   327  1715 V MediaPlayerService: player type = 3
08-29 13:12:26.695   327  1715 V AwesomePlayer: AwesomePlayer create()
,08-29 13:12:26.696  7044  7044 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:26.697  6979  6979 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-29 13:12:26.698   327  1715 V AwesomePlayer: reset_l() 
08-29 13:12:26.698   327  1715 V AwesomePlayer: cancelPlayerEvents
08-29 13:12:26.698   327  1715 V AwesomePlayer: setAudioSink() 
08-29 13:12:26.698   327  1715 V AwesomePlayer: reset_l() 
08-29 13:12:26.698   327  1715 V AudioCache: notify(0xb5474780, 8, 0, 0)
08-29 13:12:26.698   327  1715 V AudioCache: ignored
08-29 13:12:26.698   327  1715 V AwesomePlayer: cancelPlayerEvents
08-29 13:12:26.698   327  1715 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-29 13:12:26.698   327  1715 V AwesomePlayer: setDataSource_l dataSource
08-29 13:12:26.698   327  1715 V LGParserOSAL: SniffLGParser start
08-29 13:12:26.698   327  1715 V LGParserOSAL: MainType:5, SubType=0
08-29 13:12:26.698   327  1715 V LGParserOSAL: #### check Mime : application/ogg
08-29 13:12:26.698   327  1715 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-29 13:12:26.698   327  1715 E MediaExtractor: Use LGExtractor :application/ogg 
08-29 13:12:26.701  6846  6846 D UEI.SmartControl: QS Service created
08-29 13:12:26.701  7044  7044 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 13:12:26.702  7044  7044 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 13:12:26.702  7044  7044 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 13:12:26.703  7044  7044 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:26.703  7044  7044 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-29 13:12:26.709  6979  6979 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-29 13:12:26.710  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 13:12:26.717  6996  6996 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-29 13:12:26.721  6846  6846 I UEI.SmartControl: Service initServices...
,08-29 13:12:26.721  6846  6846 D UEI.SmartControl: QS start get config
08-29 13:12:26.726  6979  6979 V LGMDMManager: Create singleton instance
08-29 13:12:26.747   327  1715 V LGParserOSAL: supported mime: application/ogg
08-29 13:12:26.747   327  1715 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-29 13:12:26.747   327  1715 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-29 13:12:26.747   327  1715 V AwesomePlayer: mBitrate = -1 bits/sec
08-29 13:12:26.747   327  1715 V AwesomePlayer: AudioTrack Setting
08-29 13:12:26.747   327  1715 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-29 13:12:26.747   327  1715 V AwesomePlayer: setAudioSource() 
08-29 13:12:26.747   327  1715 V MediaPlayerService: prepare
08-29 13:12:26.747   327  1715 V AwesomePlayer: prepareAsync_l() 
08-29 13:12:26.747   327  1715 V MediaPlayerService: wait for prepare
08-29 13:12:26.747   327  7076 V AwesomePlayer: onPrepareAsyncEvent() 
08-29 13:12:26.747   327  7076 V AwesomePlayer: initAudioDecoder() 
08-29 13:12:26.747   327  7076 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 13:12:26.747   327  7076 V AudioSystem: isOffloadSupported()
08-29 13:12:26.747   327  7076 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 13:12:26.747   327  7076 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 13:12:26.747   327  7076 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 13:12:26.747   327  7076 V AwesomePlayer: getUseOffload() = 0 
08-29 13:12:26.747   327  7076 V OMXCodec: OMXCodec::Create
08-29 13:12:26.747   327  7076 V OMXCodec: findMatchingCodecs()
08-29 13:12:26.747   327  7076 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-29 13:12:26.747   327  7076 V OMXCodec: matchingCodecs.size()=1
08-29 13:12:26.748   327  7076 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-29 13:12:26.749   327  7076 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-29 13:12:26.749   327  7076 V LGCodecAdapter: LG Codec Adapter start
08-29 13:12:26.749   327  7076 V OMXCodec: OMXCodec Createtor
08-29 13:12:26.749   327  7076 V OMXCodec: setComponentRole
08-29 13:12:26.749   327  7076 V OMXCodec: configureCodec protected=0
08-29 13:12:26.749   327  7076 V LGCodecAdapter: called getLGCodecSpecificData
08-29 13:12:26.749   327  7076 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-29 13:12:26.750   327  7076 V LGCodecOSAL: Called LGconfigureCodecMETA
08-29 13:12:26.750   327  7076 V LGCodecOSAL: Called LGconfigureCodecMSG
08-29 13:12:26.750   327  7076 V LGCodecOSAL: Not support LGCodec
08-29 13:12:26.750   327  7076 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 13:12:26.750   327  7076 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-29 13:12:26.750   327  7076 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-29 13:12:26.750   327  7076 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-29 13:12:26.750   327  7076 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 13:12:26.750   327  7076 V AudioSystem: isOffloadSupported()
08-29 13:12:26.750   327  7076 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 13:12:26.750   327  7076 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 13:12:26.750   327  7076 V OMXCodec: [OMX.google.vorbis.deco,der] start mState=1
08-29 13:12:26.750   327  7076 V OMXCodec: init()
08-29 13:12:26.750   327  7076 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-29 13:12:26.750   327  7076 V OMXCodec: allocateBuffers
08-29 13:12:26.750   327  7076 V OMXCodec: allocateBuffersOnPort portIndex=0
08-29 13:12:26.750   327  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-29 13:12:26.750   327  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-29 13:12:26.750   327  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-29 13:12:26.750   327  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
08-29 13:12:26.750   327  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
08-29 13:12:26.750   327  7076 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 13:12:26.750   327  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 13:12:26.751   327  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-29 13:12:26.751   327  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-29 13:12:26.751   327  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fbf0 on output port
08-29 13:12:26.751   327  7076 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb17901f0 on output port
08-29 13:12:26.751   327  7076 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 13:12:26.751   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 13:12:26.751   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 13:12:26.751   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-29 13:12:26.751   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-29 13:12:26.751   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-29 13:12:26.751   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-29 13:12:26.751   327  7076 V OMXCodec: init() mAsyncCompletion wait free! 
08-29 13:12:26.751   327  7076 V AwesomePlayer: finishAsyncPrepare_l() 
08-29 13:12:26.751   327  7076 V AudioCache: notify(0xb5474780, 5, 0, 0)
08-29 13:12:26.751   327  7076 V AudioCache: ignored
08-29 13:12:26.751   327  7076 V AudioCache: notify(0xb5474780, 1, 0, 0)
08-29 13:12:26.751   327  7076 V AudioCache: prepared
08-29 13:12:26.751   327  1715 V AudioCache: wait - success
08-29 13:12:26.751   327  1715 V MediaPlayerService: start
08-29 13:12:26.751   327  1715 V AwesomePlayer: play_l() 
08-29 13:12:26.751   327  1715 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-29 13:12:26.751   327  1715 V AwesomePlayer: createAudioPlayer_l
08-29 13:12:26.751   327  1715 V AwesomePlayer: seekAudioIfNecessary_l() 
08-29 13:12:26.751   327  1715 V AwesomePlayer: startAudioPlayer_l() 
08-29 13:12:26.751   327  1715 D AudioPlayer: start of Playback, useOffload 0
08-29 13:12:26.751   327  1715 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 13:12:26.752   327  1715 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 13:12:26.754   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-29 13:12:26.754   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-29 13:12:26.754   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-29 13:12:26.754   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-29 13:12:26.754   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-29 13:12:26.754   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 13:12:26.754   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] Port is, disabled, freeing buffer 2957048416
08-29 13:12:26.754   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 13:12:26.754   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
08-29 13:12:26.754   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 13:12:26.754   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048816
08-29 13:12:26.755   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 13:12:26.755   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977497584
08-29 13:12:26.755   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 13:12:26.755   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-29 13:12:26.755   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 13:12:26.755   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-29 13:12:26.755   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-29 13:12:26.755   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-29 13:12:26.755   327  7078 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 13:12:26.755   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 13:12:26.755   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fbf0 on output port
08-29 13:12:26.755   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-29 13:12:26.755   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-29 13:12:26.755   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1790470 on output port
08-29 13:12:26.755   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-29 13:12:26.755   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-29 13:12:26.756   327  1715 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-29 13:12:26.756   327  1715 V AudioCache: notify(0xb5474780, 6, 0, 0)
08-29 13:12:26.756   327  1715 V AudioCache: ignored
08-29 13:12:26.756   327  1715 V MediaPlayerService: wait for playback complete
08-29 13:12:26.757   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.757   327  7079 V AudioCache: memcpy(0xaf006000, 0xb1509000, 4096)
08-29 13:12:26.759   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.759   327  7079 V AudioCache: memcpy(0xaf007000, 0xb1509000, 4096)
08-29 13:12:26.759   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.759   327  7079 V AudioCache: memcpy(0xaf008000, 0xb1509000, 4096)
08-29 13:12:26.760   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.760   327  7079 V AudioCache: memcpy(0xaf009000, 0xb1509000, 4096)
08-29 13:12:26.760   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.760   327  7079 V AudioCache: memcpy(0xaf00a000, 0xb1509000, 4096)
08-29 13:12:26.761   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.761   327  7079 V AudioCache: memcpy(0xaf00b000, 0xb1509000, 4096)
08-29 13:12:26.761   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.762   327  7079 V AudioCache: memcpy(0xaf00c000, 0xb1509000, 4096)
08-29 13:12:26.762   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.762   327  7079 V AudioCache: memcpy(0xaf00d000, 0xb1509000, 4096)
08-29 13:12:26.763   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.763   327  7079 V AudioCache: memcpy(0xaf00e000, 0xb1509000, 4096)
08-29 13:12:26.764   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.764   327  7079 V AudioCache: memcpy(0xaf00f000, 0xb1509000, 4096)
08-29 13:12:26.764   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.764   327  7079 V AudioCache: memcpy(0xaf010000, 0xb1509000, 4096)
08-29 13:12:26.764   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.765   327  7079 V AudioCache: memcpy(0xaf011000, 0xb1509000, 4096)
08-29 13:12:26.765   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.765   327  7079 V AudioCache: memcpy(0xaf012000, 0xb1509000, 4096)
08-29 13:12:26.766   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.766   327  7079 V AudioCache: memcpy(0xaf013000, 0xb1509000, 4096)
08-29 13:12:26.766   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.766   327  7079 V AudioCache: memcpy(0xaf014000, 0xb1509000, 4096)
08-29 13:12:26.767   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.767   327  7079 V AudioCache: memcpy(0xaf015000, 0xb1509000, 4096)
08-29 13:12:26.767   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.767   327  7079 V AudioCache: memcpy(0xaf016000, 0xb1509000, 4096)
08-29 13:12:26.768   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.768   327  7079 V AudioCache: memcpy(0xaf017000, 0xb1509000, 4096)
08-29 13:12:26.768   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.768   327  7079 V AudioCache: memcpy(0xaf018000, 0xb1509000, 4096)
08-29 13:12:26.769   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.769   327  7079 V AudioCache: memcpy(0xaf019000, 0xb1509000, 4096)
08-29 13:12:26.769   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.770   327  7079 V AudioCache: memcpy(0xaf01a000, 0xb1509000, 4096)
08-29 13:12:26.770   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.770   327  7079 V AudioCache: memcpy(0xaf01b000, 0xb1509000, 4096)
08-29 13:12:26.771   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.771   327  7079 V AudioCache: memcpy(0xaf01c000, 0xb1509000, 4096)
08-29 13:12:26.771   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.771   327  7079 V AudioCache: memcpy(0xaf01d000, 0xb1509000, 4096)
08-29 13:12:26.772   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.772   327  7079 V AudioCache: memcpy(0xaf01e000, 0xb1509000, 4096)
08-29 13:12:26.772   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.772   327  7079 V AudioCache: memcpy(0xaf01f000, 0xb1509000, 4096)
08-29 13:12:26.773   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.773   327  7079 V AudioCache: memcpy(0xaf020000, 0xb1509000, 4096)
08-29 13:12:26.773   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.774   327  7079 V AudioCache: memcpy(0xaf021000, 0xb1509000, 4096)
08-29 13:12:26.774   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.774   327  7079 V AudioCache: memcpy(0xaf022000, 0xb1509000, 4096)
08-29 13:12:26.775   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.775   327  7079 V AudioCache: memcpy(0xaf023000, 0xb1509000, 4096)
08-29 13:12:26.775   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.775   327  7079 V AudioCache: memcpy(0xaf024000, 0xb1509000, 4096)
08-29 13:12:26.776   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.776   327  7079 V AudioCache: memcpy(0xaf025000, 0xb1509000, 4096)
08-29 13:12:26.776   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.776   327  7079 V AudioCache: memcpy(0xaf026000, 0xb1509000, 4096)
08-29 13:12:26.777   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.777   327  7079 V AudioCache: memcpy(0xaf027000, 0xb1509000, 4096)
08-29 13:12:26.777   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.778   327  7079 V AudioCache: memcpy(0xaf028000, 0xb1509000, 4096)
08-29 13:12:26.778   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.778   327  7079 V AudioCache: memcpy(0xaf029000, 0xb1509000, 4096)
08-29 13:12:26.779   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.779   327  7079 V AudioCache: memcpy(0xaf02a000, 0xb1509000, 4096)
08-29 13:12:26.779   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.779   327  7079 V AudioCache: memcpy(0xaf02b000, 0xb1509000, 4096)
08-29 13:12:26.780   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.780   327  7079 V AudioCache: memcpy(0xaf02c000, 0xb1509000, 4096)
08-29 13:12:26.780   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.781   327  7079 V AudioCache: memcpy(0xaf02d000, 0xb1509000, 4096)
08-29 13:12:26.781   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.781   327  7079 V AudioCache: memcpy(0xaf02e000, 0xb1509000, 4096)
08-29 13:12:26.782   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.782   327  7079 V AudioCache: memcpy(0xaf02f000, 0xb1509000, 4096)
08-29 13:12:26.782   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.782   327  7079 V AudioCache: memcpy(0xaf030000, 0xb1509000, 4096)
08-29 13:12:26.783   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.783   327  7079 V AudioCache: memcpy(0xaf031000, 0xb1509000, 4096)
08-29 13:12:26.783   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.784   327  7079 V AudioCache: memcpy(0xaf032000, 0xb1509000, 4096)
08-29 13:12:26.784   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.784   327  7079 V AudioCache: memcpy(0xaf033000, 0xb1509000, 4096)
08-29 13:12:26.784   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.784   327  7079 V AudioCache: memcpy(0xaf034000, 0xb1509000, 4096)
08-29 13:12:26.785   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.785   327  7079 V AudioCache: memcpy(0xaf035000, 0xb1509000, 4096)
08-29 13:12:26.785   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.785   327  7079 V AudioCache: memcpy(0xaf036000, 0xb1509000, 4096)
08-29 13:12:26.786   327  7079 V AudioCache: write(0xb1509000, 4096)
08-29 13:12:26.786   327  7079 V AudioCache: memcpy(0xaf037000, 0xb1509000, 4096)
08-29 13:12:26.786   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-29 13:12:26.786   327  7079 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-29 13:12:26.786   327  7079 V AwesomePlayer: postAudioEOS() 
08-29 13:12:26.786   327  7079 V AudioCache: write(0xb1509000, 280)
08-29 13:12:26.786   327  7079 V AudioCache: memcpy(0xaf038000, 0xb1509000, 280)
08-29 13:12:26.788   327  7076 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-29 13:12:26.789   327  7076 V AwesomePlayer: onStreamDone
08-29 13:12:26.789   327  7076 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-29 13:12:26.789   327  7076 V AudioCache: notify(0xb5474780, 2, 0, 0)
08-29 13:12:26.789   327  7076 V AudioCache: playback complete
08-29 13:12:26.789   327  7076 V AwesomePlayer: pause_l() 
08-29 13:12:26.789   327  1715 V AudioCache: wait - success
08-29 13:12:26.789   327  7076 V AudioCache: notify(0xb5474780, 7, 0, 0)
08-29 13:12:26.789   327  1715 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-29 13:12:26.789   327  7076 V AudioCache: ignored
08-29 13:12:26.789   327  7076 V AwesomePlayer: cancelPlayerEvents
,08-29 13:12:26.790   327  7076 D AudioPlayer: Pause Playback at 1068125
08-29 13:12:26.791   327  1715 V AwesomePlayer: reset_l() 
08-29 13:12:26.791   327  1715 V AudioCache: notify(0xb5474780, 8, 0, 0)
08-29 13:12:26.791   327  1715 V AudioCache: ignored
08-29 13:12:26.791   327  1715 V AwesomePlayer: cancelPlayerEvents
08-29 13:12:26.791   327  1715 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-29 13:12:26.791   327  1715 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-29 13:12:26.791   327  1715 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-29 13:12:26.791   327  1715 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-29 13:12:26.791   327  1715 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 13:12:26.791   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 13:12:26.791   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 13:12:26.791   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-29 13:12:26.791   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
08-29 13:12:26.791   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-29 13:12:26.791   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
08-29 13:12:26.791   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-29 13:12:26.791   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-29 13:12:26.791   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-29 13:12:26.791   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-29 13:12:26.791   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-29 13:12:26.791   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 13:12:26.791   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1790470 on port 1
08-29 13:12:26.791   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-29 13:12:26.792   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-29 13:12:26.792   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-29 13:12:26.792   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
08-29 13:12:26.792   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-29 13:12:26.792   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fbf0 on port 1
08-29 13:12:26.792   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 13:12:26.792   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-29 13:12:26.792   327  1715 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 13:12:26.792   327  1715 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 13:12:26.792   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-29 13:12:26.792   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-29 13:12:26.792   327  7078 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-29 13:12:26.792   327  1715 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 13:12:26.792   327  1715 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-29 13:12:26.792   327  1715 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-29 13:12:26.793   327  1715 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-29 13:12:26.793   327  1715 D AudioPlayer: AudioPlayer releasing audio source
08-29 13:12:26.793   327  1715 D AudioPlayer: AudioPlayer done releasing audio source
08-29 13:12:26.793   327  1715 V AwesomePlayer: reset_l() 
08-29 13:12:26.793   327  1715 V AwesomePlayer: cancelPlayerEvents
08-29 13:12:26.793   327  1715 V AwesomePlayer: ~AwesomePlayer call
08-29 13:12:26.793   327  1715 V AwesomePlayer: reset_l() 
08-29 13:12:26.793   327  1715 V AwesomePlayer: cancelPlayerEvents
08-29 13:12:26.794  6979  7074 V SoundPool: close(31)
08-29 13:12:26.794  6979  7074 V SoundPool: pointer = 0x9fffb000, size = 205080, sampleRate = 48000, numChannels = 2
08-29 13:12:26.799  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 13:12:26.800  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-29 13:12:26.801  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:362
,08-29 13:12:26.939  1043  1367 V AlarmManager: RTC_WAKEUP set : Alarm{1fdbd551 type 0 when 1472469146925 com.android.vending} when 1472469146925
,08-29 13:12:26.977  4978  7080 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-29 13:12:26.995  1043  1764 V SIM_STK : Menu title from STK is T-Mobile
,08-29 13:12:27.014  6846  6846 I UEI.SmartControl: Supports setup maps: true
08-29 13:12:27.016  6846  6846 D UEI.SmartControl: QS start statue = true Error code = 0
,08-29 13:12:27.016  6846  6846 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 13:12:27.016  6846  6846 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 13:12:27.016  6846  6846 I UEI.SmartControl: ### init IR Blaster...
08-29 13:12:27.019  6846  6846 D serial_port: Configuring serial port
08-29 13:12:27.020  6846  6846 E UEI.SmartControl: UEIBLaster setting for 616
08-29 13:12:27.020  6846  6846 I UEI.SmartControl: Setting serial record hearder size = 2
08-29 13:12:27.020  6846  6846 I UEI.SmartControl: configuring settings for MAXQ616
08-29 13:12:27.020  6846  6846 I UEI.SmartControl: Get version...
08-29 13:12:27.036  6846  7086 D UEI.SmartControl: serial port data available: 21
,08-29 13:12:27.062  6846  6846 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-29 13:12:27.062  6846  6846 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-29 13:12:27.062  6846  6846 I UEI.SmartControl: QS saving settings...
08-29 13:12:27.063  6846  6846 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 13:12:27.078  6846  7086 D UEI.SmartControl: serial port data available: 4
,08-29 13:12:27.109  6846  7091 I UEI.SmartControl: Device manager: loading config....
,08-29 13:12:27.110  6846  6846 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-29 13:12:27.110  6846  7091 D UEI.SmartControl: ----------- loading internal config...
08-29 13:12:27.111  6846  6846 E UEI.SmartControl: Services init done
08-29 13:12:27.111  6846  6846 D UEI.SmartControl: QS Service init finished
08-29 13:12:27.112  6846  6846 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 13:12:27.112  6846  6846 D UEI.SmartControl: QS Service version code: 201091
08-29 13:12:27.112  6846  6846 D UEI.SmartControl: Service requested: Control
08-29 13:12:27.116  6846  7091 E UEI.SmartControl: Loading SETTINGS...
08-29 13:12:27.117  6846  6846 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 13:12:27.118  6846  6846 D UEI.SmartControl: Internal service binding...
08-29 13:12:27.119  6979  6979 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 13:12:27.121  6846  7091 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 13:12:27.121  6846  6861 I UEI.SmartControl: ------ IControl API: 11
08-29 13:12:27.121  6846  6861 D UEI.SmartControl: File observer start...
08-29 13:12:27.121  6846  6861 E UEI.SmartControl: IR Port is disabled: false
08-29 13:12:27.121  6846  6861 D UEI.SmartControl: Starting file observer...
08-29 13:12:27.122  6846  6861 I UEI.SmartControl: Registering callback...
,08-29 13:12:27.124  6846  6862 I UEI.SmartControl: ------ IControl API: 19
08-29 13:12:27.124  6846  6862 I UEI.SmartControl: Registering Services Ready callback...
08-29 13:12:27.142  6625  6625 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-29 13:12:27.148  6846  7090 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 13:12:27.148  6846  7090 D UEI.SmartControl: -----service ready thread exits
08-29 13:12:27.149  6979  6994 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-29 13:12:27.150  6979  7072 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-29 13:12:27.150  6979  7072 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-29 13:12:27.151  6979  6979 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-29 13:12:27.152  6979  6979 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,08-29 13:12:27.152  6846  6861 I UEI.SmartControl: ------ IControl API: 8
08-29 13:12:27.154  6979  6979 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-29 13:12:27.155  6979  6979 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-29 13:12:27.155  6979  6979 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-29 13:12:27.156  6979  6979 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-29 13:12:27.157  6979  6979 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-29 13:12:27.157  6979  6979 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-29 13:12:27.158  6979  6979 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-29 13:12:27.165  6979  6979 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 13:12:27.167  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 13:12:27.168  6979  6979 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-29 13:12:27.169  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 13:12:27.170  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 13:12:27.173  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-29 13:12:27.174  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-29 13:12:27.177  6979  6979 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472469147176]
08-29 13:12:27.180  6979  6979 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-29 13:12:27.185  1043  1948 I ActivityManager: Killing 6597:com.android.gallery3d/u0a27 (adj 15): empty #17
08-29 13:12:27.202  6979  7094 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-29 13:12:27.215  1043  1948 I ActivityManager: Killing 6568:com.lge.email/u0a23 (adj 15): empty #18
,08-29 13:12:27.247  1043  2022 W libprocessgroup: failed to open /acct/uid_10027/pid_6597/cgroup.procs: No such file or directory
,08-29 13:12:27.251  1043  1887 W libprocessgroup: failed to open /acct/uid_10023/pid_6568/cgroup.procs: No such file or directory
08-29 13:12:27.258  6979  6979 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-29 13:12:27.259  6979  6979 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-29 13:12:27.261  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-29 13:12:27.261  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-29 13:12:27.262  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-29 13:12:27.263  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-29 13:12:27.264  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-29 13:12:27.291  6979  6979 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-29 13:12:27.982  1043  1985 D WifiServiceImplEx: setWifiEnabled: true pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-29 13:12:27.990  1043  1985 D WifiService: setWifiEnabled: true pid=6705, uid=10118
08-29 13:12:27.991  1043  1985 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:12:28.014  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-29 13:12:28.014  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-29 13:12:28.014  1043  1043 D Ulp_jni : JNI:system_update. Event-4
08-29 13:12:28.016  1043  1428 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-29 13:12:28.016  1043  1428 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-29 13:12:28.018  1043  1428 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-29 13:12:28.018  1043  1428 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010],
08-29 13:12:28.019  1043  1428 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-29 13:12:28.019  1043  1428 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 13:12:28.019  1043  1428 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-29 13:12:28.019  1043  1428 E WifiHW  : unknown target_country: EU , set to default
08-29 13:12:28.019  1043  1428 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-29 13:12:28.019  1043  1428 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 13:12:28.019  1043  1428 I WifiUtil: gEnableBmps=1
08-29 13:12:28.072  1043  1509 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:28.096  1043  1120 D Tethering: MasterInitialState.processMessage what=3
08-29 13:12:28.107  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:28.111  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:28.114  1043  1509 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:28.117  1043  1120 D Tethering: MasterInitialState.processMessage what=3
08-29 13:12:28.126  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:28.130  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:28.130  1043  1110 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:28.132  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 13:12:28.139  5796  5796 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 13:12:28.159  5796  5796 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 13:12:28.160  6457  6485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-29 13:12:28.193  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:28.240  1043  1110 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:28.271  1043  1950 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7120 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-29 13:12:28.288  1043  1110 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:28.288  1043  1110 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 13:12:28.297   357   357 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 524us total 26.907ms
,08-29 13:12:28.325   357   357 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 26.707ms
,08-29 13:12:28.347   357   357 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 20.730ms
,08-29 13:12:28.360  7120  7120 I AppUp4:AppBoxCP: onCreate
08-29 13:12:28.361  7120  7120 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-29 13:12:28.371  7120  7120 I AppUp4:DB:  setFingerPrint start
,08-29 13:12:28.372  7120  7120 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-29 13:12:28.380  7120  7120 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-29 13:12:28.380  7120  7120 I AppUp4:DB:  SDK version = 21
08-29 13:12:28.380  7120  7120 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-29 13:12:28.383  7120  7120 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-29 13:12:28.384  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 13:12:28.384  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:28.387  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 13:12:28.387  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 13:12:28.394  7120  7120 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 13:12:28.437  7120  7120 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 13:12:28.437  7120  7120 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 13:12:28.446  7120  7120 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@10ae4e89
08-29 13:12:28.447  7120  7120 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 13:12:28.447  7120  7120 D AppUp4:CustFacade: isPhone : true
08-29 13:12:28.447  7120  7120 D AppUp4:CustModeStarterReceiver: begin check event
08-29 13:12:28.448  7120  7120 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-29 13:12:28.448  7120  7120 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-29 13:12:28.449  7120  7140 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,08-29 13:12:28.450  7120  7140 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-29 13:12:28.450  7120  7140 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-29 13:12:28.453  1043  1060 I ActivityManager: Killing 6664:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-29 13:12:28.518  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:28.518  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-29 13:12:28.518  1043  1913 W libprocessgroup: failed to open /acct/uid_10061/pid_6664/cgroup.procs: No such file or directory
08-29 13:12:28.521  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:12:28.530  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:12:28.540  4806  7148 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 13:12:28.543  4806  7149 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:28.544  4806  7149 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 13:12:28.614  1043  1950 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7153 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-29 13:12:28.681  7153  7153 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:12:28.681  7153  7153 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 13:12:28.683  7153  7153 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 13:12:28.685  7153  7153 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-29 13:12:28.704  1043  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 13:12:28.704  1043  1120 D Tethering: InitialState.processMessage what=4
08-29 13:12:28.704  1043  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 13:12:28.709   323   896 D SoftapController: Softap fwReload - Ok
08-29 13:12:28.711  1043  1428 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (686ms)
08-29 13:12:28.717   323   896 D CommandListener: Setting iface cfg
08-29 13:12:28.717   323   896 D CommandListener: Trying to bring down wlan0
08-29 13:12:28.720   323   896 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:12:28.724  1043  1428 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-29 13:12:28.726  1043  1428 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:12:28.726  1043  1428 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:12:28.726  1043  1428 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 13:12:28.735  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-29 13:12:28.739  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:28.740  1931  1931 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-29 13:12:28.742  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:28.743  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:28.744  1043  1428 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 13:12:28.744  1043  1428 D WifiMonitor: connecting to supplicant
08-29 13:12:28.752  7171  7171 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 13:12:28.718  7171  7171 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:28.718  7171  7171 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 13:12:28.787  7171  7171 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 13:12:28.787  7171  7171 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-29 13:12:28.804  7153  7153 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-29 13:12:28.818  7153  7153 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-29 13:12:28.842  7171  7171 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 13:12:28.869  7153  7153 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 13:12:28.902  7171  7171 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 13:12:28.906  7153  7153 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:12:28.907  7153  7153 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 13:12:28.920  7171  7171 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-29 13:12:28.921  1043  1428 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-29 13:12:28.921  1043  1428 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 13:12:28.922  1043  1428 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 13:12:28.922  7171  7171 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 13:12:28.922  1043  1428 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 13:12:28.923  1043  1428 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:28.923  1043  1428 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:28.924  1043  1428 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 13:12:28.924  1043  1428 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 13:12:28.924  1043  1428 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 13:12:28.925  1043  1428 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 13:12:28.925  1043  1428 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-29 13:12:28.925  1043  1428 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:12:28.925  1043  1428 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:12:28.925  1043  1428 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 13:12:28.926  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:28.926  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:28.926  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:28.926  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:28.926  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-29 13:12:28.927  1043  7174 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-29 13:12:28.927  1043  7174 D WifiMonitor: Dropping event because (p2p0) is stopped
08-29 13:12:28.928  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 13:12:28.928  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 13:12:28.928  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 13:12:28.928  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 13:12:28.928  1043  7174 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 13:12:28.928  1043  7174 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 13:12:28.930  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:28.931  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 13:12:28.931  1043  1463 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 13:12:28.932  1931  1931 D WfdService: Waiting for WifiP2p enabling
08-29 13:12:28.934  1043  1428 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 13:12:28.935  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:28.935  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:28.935  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:28.935  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:28.935  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:28.935  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:28.935  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:28.935  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:28.935  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:28.935  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:28.935  1043  1428 D WifiNative-wlan0: SET update_config 1: returned true
08-29 13:12:28.935  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:28.935  1043  1428 D WifiConfigStore: Loading config and enabling all networks 
08-29 13:12:28.935  1043  1428 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 13:12:28.935  1043  1428 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 13:12:28.936  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:28.936  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:28.936  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:28.936  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:28.936  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:28.936  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:28.936  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - ,BSSID name: null
08-29 13:12:28.936  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:28.936  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:28.936  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:28.936  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:28.943  1043  1428 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-29 13:12:28.953  1043  1428 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 13:12:28.953  1043  1428 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 13:12:28.954  1043  1428 D WifiStateMachine: enableVerboseLogging : level 2
08-29 13:12:28.954  1043  1428 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 13:12:28.955  1043  1428 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 13:12:28.955  1043  1428 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 13:12:28.955  1043  1428 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 13:12:28.955  1043  1428 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 13:12:28.956  1043  1428 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 13:12:28.956  1043  1428 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 13:12:28.956  1043  1428 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 13:12:28.956  1043  1428 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 13:12:28.957  1043  1428 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 13:12:28.957  1043  1428 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 13:12:28.957  1043  1428 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 13:12:28.957  1043  1428 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
,08-29 13:12:28.958  1043  1428 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 13:12:28.959  1043  1428 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 13:12:28.959  1043  1428 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 13:12:28.959  1043  1428 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
,08-29 13:12:28.959  1043  1428 D WifiNative-HAL: Setting external_sim to 1
08-29 13:12:28.959  1043  1428 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 13:12:28.960  1043  1428 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 13:12:28.960  1043  1428 I WifiNative-HAL: startHal
08-29 13:12:28.960  1043  1428 D wifi    : setting scan oui 0x956ea1e0
08-29 13:12:28.960  1931  1931 D WfdsService: Supplicant Connection state is changed : true
08-29 13:12:28.960  1043  1428 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 13:12:28.960  1043  1428 I WifiNative-HAL: startHal
08-29 13:12:28.960  1043  1428 D wifi    : setting scan oui 0x956ea1e0
08-29 13:12:28.961  1043  1428 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 13:12:28.961  1931  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 13:12:28.961  1931  2284 D WfdsService: Set the WFDS Monitor: true
08-29 13:12:28.961  1931  2284 D WfdsMonitor: WfdsMonitorThread create
08-29 13:12:28.962  1043  1428 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 13:12:28.962  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 13:12:28.962  7171  7171 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 13:12:28.962  1043  1428 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 13:12:28.962  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 13:12:28.962  7171  7171 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 13:12:28.963  1043  1428 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 13:12:28.963  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 13:12:28.963  7171  7171 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-29 13:12:28.963  1931  2284 D WfdsMonitor: WFDS Monitor is created and started
08-29 13:12:28.964  1931  2284 D WfdsService: WiFi: Supplicant connection re-established
08-29 13:12:28.964  1043  1428 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 13:12:28.964  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 13:12:28.964  7171  7171 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 13:12:28.964  1043  1428 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 13:12:28.964  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 13:12:28.964  7171  7171 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 13:12:28.965  1043  1428 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 13:12:28.965  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 13:12:28.965  7171  7171 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 13:12:28.965  1043  1428 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 13:12:28.965  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 13:12:28.966  7171  7171 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 13:12:28.966  1043  1428 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 13:12:28.967  1043  1428 E WifiNative: : [119,211,025 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 13:12:28.967  1043  1428 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 13:12:28.968  1043  1428 D WifiNative-wlan0: RECONNECT: returned true
08-29 13:12:28.968  1043  1428 D WifiNative-wlan0: doString: [STATUS]
08-29 13:12:28.968  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 13:12:28.968  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 13:12:28.968  1043  1428 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 13:12:28.968  1043  1428 D WifiNative-wlan0: doBoolean: SET, ps 1
08-29 13:12:28.969  1043  1428 D WifiNative-wlan0: SET ps 1: returned true
08-29 13:12:28.969  1043  1378 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:28.971  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 13:12:28.971  1043  1043 D RttService: SCAN_AVAILABLE : 3
08-29 13:12:28.972  1043  1547 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:28.972  1043  1546 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:28.972  1043  1546 I WifiNative-HAL: startHal
08-29 13:12:28.972  1043  1546 D wifi    : getting scan capabilities on interface[1] = 0x956ea1e0
08-29 13:12:28.972  1043  1546 D wifi    : failed to get capabilities : -3
08-29 13:12:28.972  1043  1546 E WifiScanningService: could not get scan capabilities
08-29 13:12:28.972  1043  1428 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 13:12:28.973  1043  1428 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 13:12:28.973  1931  7175 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 13:12:28.974   323   896 D CommandListener: Setting iface cfg
08-29 13:12:28.974  1043  1428 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 13:12:28.974   323   896 D CommandListener: Trying to bring up p2p0
08-29 13:12:28.974  1931  7175 E CtrlSupplicant: Succeed to open control connection
08-29 13:12:28.974  1931  7175 E CtrlSupplicant: Succeed to open monitor connection
08-29 13:12:28.974  1043  1428 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 13:12:28.974  1043  1378 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 13:12:28.974  1043  1378 D LGWifiP2pService: P2pEnablingState
08-29 13:12:28.975  1043  1378 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:28.975  1043  1378 D LGWifiP2pService: P2p socket connection successful
08-29 13:12:28.975  1043  1378 D LGWifiP2pService: P2pEnabledState
08-29 13:12:28.975  1043  1428 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=119219  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-29 13:12:28.976  1043  1378 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 13:12:28.977  1931  1931 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-29 13:12:28.978  1043  1378 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 13:12:28.978  1931  1931 D WfdsService: WifiP2pState is changed : true
08-29 13:12:28.978  1931  2284 D WfdsService: Receive the WFDS_ENABLE Method
08-29 13:12:28.978  1931  2284 D WfdsService: Set the WFDS Monitor: true
08-29 13:12:28.979  1931  2284 D WfdsService: Connected to the supplicant for wfds
08-29 13:12:28.979  1931  2284 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 13:12:28.979  7171  7171 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 13:12:28.979  1931  2284 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
08-29 13:12:28.979  7171  7171 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
08-29 13:12:28.980  1931  2284 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
08-29 13:12:28.982  1931  1931 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 13:12:28.982  1931  1931 D WfdsService: isConnected: false
08-29 13:12:28.983  1931  7175 D WfdsMonitor: Supplicant connection established
08-29 13:12:28.983  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=119227  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 13:12:28.983  1043  1428 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 13:12:28.984  1043  1428 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 13:12:28.984  1043  1378 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 13:12:28.984  1043  1378 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 13:12:28.984  1043  1428 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 13:12:28.984  1043  1428 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 13:12:28.985  7171  7171 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 13:12:28.985  1931  2284 D WfdsService: selectPreferredScanChannel [36]
08-29 13:12:28.985  1931  2284 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 13:12:28.985  1931  2284 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
08-29 13:12:28.985  1043  1428 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 13:12:28.985  1043  1378 D WifiNative-p2p0: SET device_name G3: returned true
08-29 13:12:28.985  1043  1378 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 13:12:28.985  1043  1378 D LGWifiP2pService: before postfix = G3
08-29 13:12:28.985  1043  1378 D WifiServerServiceExt: postfix byte check : 2
08-29 13:12:28.985  1043  1378 D LGWifiP2pService: after postfix = G3
08-29 13:12:28.985  1043  1428 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 13:12:28.985  1043  1378 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 13:12:28.986  1043  1428 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 13:12:28.986  1043  1378 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 13:12:28.986  1043  1428 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 13:12:28.986  1043  1378 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 13:12:28.986  7171  7171 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 13:12:28.986  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:28.986  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:28.986  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 13:12:28.987  1043  1428 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
,08-29 13:12:28.987  1043  1428 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 13:12:28.987  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:28.987  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:28.987  1043  1428 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-29 13:12:28.987  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 13:12:28.988  1043  1378 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
,08-29 13:12:28.988  1043  1378 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 13:12:28.988  1043  1378 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
,08-29 13:12:28.988  1043  1378 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 13:12:28.989  1043  1378 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
,08-29 13:12:28.989  1043  1378 D WifiNative-HAL: p2pGetDeviceAddress
08-29 13:12:28.989  1043  1378 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-29 13:12:28.991  7171  7171 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 13:12:28.993  7171  7171 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:28.994  7171  7171 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 13:12:28.994  7171  7171 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:28.995  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:28.995  7171  7171 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:28.996  1931  7175 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:28.996  1931  7175 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:28.996  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 13:12:28.996  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:28.997  1043  7174 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:28.997  1043  7174 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:28.997  1043  7174 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:28.997  1043  7174 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:28.997  1043  7174 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:28.997  1043  7174 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:28.997  1043  7174 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:28.997  1043  7174 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:28.997  1043  7174 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:28.997  1043  7174 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:28.998  1931  1931 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 13:12:28.998  1043  1428 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 13:12:28.998  1931  1931 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 13:12:28.999  1931  1931 D WfdsService: Update P2p Interface State: 3
08-29 13:12:28.999  1043  1378 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 13:12:28.999  1043  1378 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 13:12:28.999  1043  1428 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 13:12:28.999  1043  1378 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 13:12:28.999  1043  1378 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 13:12:28.999  1043  1428 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 13:12:29.000  1043  1378 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 13:12:29.000  1043  1428 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 13:12:29.000  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-29 13:12:29.000  1043  1378 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 13:12:29.000  7171  7171 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 13:12:29.000  7171  7171 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 13:12:29.001  1043  1428 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 13:12:29.001  1043  1428 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 13:12:29.001  1043  1428 D WifiNative-wlan0: BSS,_FLUSH 0: returned true
08-29 13:12:29.001  1043  1428 D WifiNative-wlan0: doBoolean: SCAN
08-29 13:12:29.002  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 13:12:29.002  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 13:12:29.002  1043  1428 D WifiNative-wlan0: SCAN: returned false
08-29 13:12:29.002  1043  7174 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 13:12:29.002  1043  7174 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 13:12:29.002  1043  1428 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=119247  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-29 13:12:29.004  1043  1378 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 13:12:29.004  1043  1378 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-29 13:12:29.007  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=119252  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 13:12:29.008  1043  1428 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:12:29.009  1043  1428 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:12:29.009  1043  1428 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:12:29.009  1043  1428 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:12:29.010  1043  1428 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:12:29.010  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.011  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.011  1043  1378 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 13:12:29.011  1043  1378 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 13:12:29.011  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 13:12:29.011  1043  1378 D LGWifiP2pService: InactiveState
08-29 13:12:29.011  1043  1378 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.011  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.011  1043  1378 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 13:12:29.012  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-29 13:12:29.012  1043  1043 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 13:12:29.012  7171  7171 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 13:12:29.012  7171  7171 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:29.013  1043  7174 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 13:12:29.013  1043  7174 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:29.013  1043  7174 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:29.013  1043  7174 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:29.013  7171  7171 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 13:12:29.013  7171  7171 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:29.013  1043  7174 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:29.014  1043  7174 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:29.014  1043  7174 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:29.014  1043  7174 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:29.014  1043  1378 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 13:12:29.014  7171  7171 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:29.014  1043  1378 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.014  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.014  1043  1378 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.014  1931  7175 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 13:12:29.014  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.014  1931  7175 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:29.014  1043  1378 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.014  1931  7175 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:29.015  1043  1378 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.015  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.015  1043  1378 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.015  1043  1378 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.015  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.015  1043  1378 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.015  1043  1378 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.015  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.015  1043  1378 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 ta,rget=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.015  1043  7174 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:29.015  1043  7174 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:29.015  1043  7174 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:29.015  1043  7174 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:29.016  1043  1043 E WifiServerServiceExt: No p2p device connected
,08-29 13:12:29.020  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:29.020  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:29.021  1931  2284 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 13:12:29.021  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 13:12:29.118  7153  7153 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 13:12:29.154  7153  7153 I HubEmail: JNI_OnLoad()
08-29 13:12:29.154  7153  7153 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 13:12:29.154  7153  7153 I HubEmail: registerNatives()
08-29 13:12:29.155  7153  7153 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 13:12:29.155  7153  7153 I HubEmail: registerNativeMethods()
,08-29 13:12:29.155  7153  7153 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-29 13:12:29.155  7153  7153 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-29 13:12:29.169  7153  7184 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:12:29.179  3228  3228 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 13:12:29.179  3228  3228 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:29.179  3228  3228 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 13:12:29.227  1043  1060 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7188 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-29 13:12:29.231  7017  7186 V FormManager: Network unavailable.
,08-29 13:12:29.233  7017  7185 W FormManager: Network not available. Please check & try again.
08-29 13:12:29.234  7017  7186 V FormManager: Network unavailable.
08-29 13:12:29.239  1043  1986 I ActivityManager: Killing 6770:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-29 13:12:29.294  1043  1646 W libprocessgroup: failed to open /acct/uid_10080/pid_6770/cgroup.procs: No such file or directory
,08-29 13:12:29.396  7188  7188 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:12:29.396  7188  7188 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 13:12:29.400  7188  7188 D PhoneMonitor: Register our PhoneStateListener
08-29 13:12:29.426  7188  7188 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-29 13:12:29.429  7188  7188 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-29 13:12:29.455  7188  7188 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-29 13:12:29.457  7188  7188 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-29 13:12:29.458  7188  7188 D TelephonyAutoProfiling: [parse] Load xml
08-29 13:12:29.465  7188  7188 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-29 13:12:29.465  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-29 13:12:29.465  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-29 13:12:29.465  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-29 13:12:29.465  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-29 13:12:29.466  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-29 13:12:29.466  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-29 13:12:29.466  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-29 13:12:29.466  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-29 13:12:29.466  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-29 13:12:29.466  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-29 13:12:29.466  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-29 13:12:29.466  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-29 13:12:29.466  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-29 13:12:29.466  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-29 13:12:29.466  7188  7188 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-29 13:12:29.466  7188  7188 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-29 13:12:29.478  7188  7188 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-29 13:12:29.490  1043  1985 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7211 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:12:29.493  1043  1985 I ActivityManager: Killing 6165:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-29 13:12:29.536  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 13:12:29.537  1043  7174 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 13:12:29.537  7171  7171 E wpa_supplicant: USIM:  scard_init function
08-29 13:12:29.537  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 13:12:29.537  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-29 13:12:29.537  1043  7174 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-29 13:12:29.537  7171  7171 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-29 13:12:29.537  1043  1428 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-29 13:12:29.538  1043  1428 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-29 13:12:29.538  1043  1428 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-29 13:12:29.538  1043  1428 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-29 13:12:29.539  1043  1428 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-29 13:12:29.539  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,08-29 13:12:29.539  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-29 13:12:29.555  1043  1913 W libprocessgroup: failed to open /acct/uid_10097/pid_6165/cgroup.procs: No such file or directory
,08-29 13:12:29.565  1043  1428 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=119810  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 13:12:29.568  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=119813  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 13:12:29.570  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:29.570  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:29.572  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.572  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.572  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 13:12:29.574  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 13:12:29.575  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:12:29.575  1043  1043 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 13:12:29.647  7171  7171 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-29 13:12:29.647  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-29 13:12:29.648  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 13:12:29.648  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 13:12:29.648  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 13:12:29.649  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:12:29.649  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:12:29.650  1043  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 13:12:29.651  1043  1428 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=119895  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-29 13:12:29.655  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=119900  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 13:12:29.656  1043  1428 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119900
08-29 13:12:29.656  1043  1428 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119901
08-29 13:12:29.657  1043  1428 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119901
08-29 13:12:29.657  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119902
08-29 13:12:29.658  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:12:29.658  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:12:29.658  1043  1428 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=119902
08-29 13:12:29.658  7171  7171 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 13:12:29.658  7171  7171 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 13:12:29.658  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-29 13:12:29.658  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 13:12:29.659  1043  7174 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 13:12:29.659  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-29 13:12:29.659  1043  1428 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=119903  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 13:12:29.660  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 13:12:29.660  1043  7174 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 13:12:29.660  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:12:29.660  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:12:29.661  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=119905  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 13:12:29.662  1043  1428 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:29.662  1043  1428 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:29.663  1043  1428 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:29.663  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-29 13:12:29.665  1043  1428 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:29.667  1043  1428 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=119911  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 13:12:29.667  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=119912  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 13:12:29.668  1043  1428 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=119912
08-29 13:12:29.668  1043  1428 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=119913
08-29 13:12:29.669  1043  1428 D WifiNative-wlan0: doString: [STATUS]
08-29 13:12:29.670  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:12:29.670  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:12:29.671  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:29.671  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:29.672  1043  1428 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 13:12:29.673  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:29.674  1043  1428 I WifiServiceExtension: setVHTCapabilityType  : false
,08-29 13:12:29.678  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.678  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.679  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 13:12:29.679  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.679  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.679  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 13:12:29.679  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:12:29.679  1043  1043 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 13:12:29.682  1043  1428 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 13:12:29.682  1043  1428 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-29 13:12:29.687  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.687  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:12:29.687  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 13:12:29.697  1043  1428 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 13:12:29.697  1043  1428 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:12:29.697  1043  1428 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 13:12:29.697  1043  1509 D ConnectivityService: Got NetworkAgent Messenger
08-29 13:12:29.698  1043  1509 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 13:12:29.698  1043  1509 D ConnectivityService: NetworkAgent connected
08-29 13:12:29.698  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.698  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.698  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 13:12:29.698  1043  1428 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 13:12:29.698  1043  1428 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 13:12:29.699  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:29.699  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:29.700  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:29.703  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:29.703  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:29.704  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:29.706  1043  1428 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 13:12:29.706  1043  1428 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:12:29.706  1043  1428 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-29 13:12:29.706  1043  1428 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 13:12:29.706  1043  1428 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 13:12:29.709  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:29.709  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:29.710  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:29.711  1043  1428 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 13:12:29.713   323   896 D CommandListener: Setting iface cfg
08-29 13:12:29.716  1043  1428 E WifiStateMachine: Start Dhcp Watchdog 2
08-29 13:12:29.716  1043  7230 D DhcpStateMachine: StoppedState
08-29 13:12:29.716  1043  7230 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.716  1043  7230 D DhcpStateMachine: WaitBeforeStartState
08-29 13:12:29.717  1043  1428 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=119961  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:12:29.717  1043  1428 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=119962  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-29 13:12:29.720  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=119964  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:12:29.721  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:12:29.721  1043  1043 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-29 13:12:29.722  1043  1428 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=119966  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:12:29.722  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:12:29.722  1043  1043 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 13:12:29.722  1043  1428 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=119967  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:12:29.723  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=119967  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:12:29.724  1043  1428 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:73004] from screen [on:0 period:-704632804] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 13:12:29.725  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-704632803] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 13:12:29.725  1043  1428 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 13:12:29.729  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:29.730  1043  1509 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-29 13:12:29.730  1043  1428 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 13:12:29.730  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:29.732  1043  1428 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:29.732  1043  1428 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:29.733  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:29.733  1043  1428 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:29.733  1043  1509 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-29 13:12:29.734  1043  1428 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=150,0,0
08-29 13:12:29.734  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=150,0,0
08-29 13:12:29.734  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 13:12:29.735  7171  7171 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 13:12:29.735  1043  1428 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 13:12:29.735  1043  1428 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 13:12:29.735  1043  1428 D WifiNative-wlan0: SET ps 0: returned true
08-29 13:12:29.735  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 13:12:29.736  7171  7171 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 13:12:29.736  1043  1428 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 13:12:29.736  1043  1378 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2723f74d target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.736  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2723f74d target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.736  1043  1428 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 13:12:29.736  1043  7230 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.736  1043  1428 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 13:12:29.736  1043  7230 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 13:12:29.737  1043  1428 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 13:12:29.737   323   896 D CommandListener: Setting iface cfg
08-29 13:12:29.738   323   896 D CommandListener: Trying to bring up wlan0
08-29 13:12:29.739  1043  1428 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 13:12:29.739  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:12:29.740  1043  1043 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 13:12:29.740  1043  1428 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:29.741  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:29.741  1043  1428 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:29.742  1043  1428 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:29.742  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:29.742  1043  1428 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:29.743  1043  1509 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-29 13:12:29.744  1043  1428 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 13:12:29.744  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 13:12:29.745  1043  1378 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.745  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.744  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 13:12:29.747  7171  7171 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 13:12:29.747  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:12:29.747  1043  1043 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 13:12:29.748  1043  1428 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 13:12:29.748  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-29 13:12:29.748  7171  7171 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 13:12:29.748  1043  1428 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 13:12:29.748  1043  1428 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 13:12:29.765  1043  1428 D WifiNative-wlan0: SET ps 1: returned true
08-29 13:12:29.766  1043  1509 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-29 13:12:29.766  1043  1428 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 13:12:29.767  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 13:12:29.767  1043  1428 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 13:12:29.769  1043  1509 D ConnectivityService: ignoring duplicate network state non-change
08-29 13:12:29.791  1043  1895 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7235 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-29 13:12:29.795  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:29.795  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:29.797  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:29.802  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:12:29.803  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.803  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 13:12:29.804  1043  1509 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 13:12:29.805  1043  1895 I ActivityManager: Killing 6795:com.lge.eula/1000 (adj 15): empty #17
08-29 13:12:29.806  1043  1509 D ConnectivityService: Adding iface wlan0 to network 101
08-29 13:12:29.832  1043  1509 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 13:12:29.832  1043  1509 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 13:12:29.833  1043  1509 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-29 13:12:29.834   323   896 E Netd    : netlink response contains error (File exists)
08-29 13:12:29.835  1043  1509 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-29 13:12:29.835  1043  1509 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 13:12:29.835  1043  1509 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-29 13:12:29.836  1043  1509 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-29 13:12:29.855  1043  1428 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 13:12:29.858  1043  1061 W libprocessgroup: failed to open /acct/uid_1000/pid_6795/cgroup.procs: No such file or directory
08-29 13:12:29.860  1043  1509 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 13:12:29.861  1043  1509 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 13:12:29.861  1043  1509 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 13:12:29.861  1043  1509 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-29 13:12:29.861  1043  1509 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:12:29.861  1043  7229 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.861  1043  7229 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 13:12:29.861  1043  1509 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:12:29.861  1043  1509 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 13:12:29.861  1043  7229 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:29.861  1043  1509 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:29.861  1043  7229 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 13:12:29.861  1043  1509 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 13:12:29.861  1043  1509 D ConnectivityService: currentScore = 0, newScore = 20
08-29 13:12:29.861  1043  1509 D ConnectivityService:    accepting network in place of null
08-29 13:12:29.861  1043  1509 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:29.863  1843  1843 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:29.863  1843  1843 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 13:12:29.863  1043  1509 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 13:12:29.863  1043  1509 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 13:12:29.863  1043  1509 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 13:12:29.864  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failo,ver: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:29.864  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:29.864  1043  1428 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:29.864  1043  1428 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:12:29.865   323  7257 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-29 13:12:29.865  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:29.866  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.866  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.866  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 13:12:29.868  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 13:12:29.872  1931  1931 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-29 13:12:29.875  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.875  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.875  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 13:12:29.876  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 13:12:29.880  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.880  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.881  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 13:12:29.881  1043  1509 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:29.881  1043  1509 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 13:12:29.881  1043  1509 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 13:12:29.882  1043  1509 D ConnectivityService: validation of new default Network = false
08-29 13:12:29.882  1043  1509 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 13:12:29.882  1043  1509 D DSQN    : enableDataServiceNotify 
08-29 13:12:29.882  1043  1509 D DSQN    : start dsqn bin
08-29 13:12:29.888  1043  1509 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-29 13:12:29.888  1043  1509 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:29.888  1043  1509 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:12:29.889  1043  1509 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-29 13:12:29.878  7259  7259 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:29.878  7259  7259 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:29.891  1043  1043 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 13:12:29.892  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 13:12:29.892  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 13:12:29.892  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 13:12:29.893  1592  2041 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 13:12:29.894  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:29.894  1592  1592 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 13:12:29.895  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 13:12:29.906  7259  7259 E DSQN    : DSQN ssw
08-29 13:12:29.906  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:29.906  1592  1592 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 13:12:29.906  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 13:12:29.922  1807  7263 I CheckinService: active receiver: enabled
,08-29 13:12:29.931  1807  7263 I CheckinService: Preparing to send checkin request
08-29 13:12:29.931  1807  7263 I EventLogService: Accumulating logs since 1472469074878
08-29 13:12:29.934  1043  1377 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-29 13:12:29.938  1043  7230 D DhcpStateMachine: DHCPV4 request on wlan0
08-29 13:12:29.939  1043  7230 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 13:12:29.939  1043  7230 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 13:12:29.928  7265  7265 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:29.928  7265  7265 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 13:12:29.944  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 13:12:29.945  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:29.946  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:29.953  7265  7265 I dhcpcd  : version 5.5.6 starting
,08-29 13:12:29.955  7265  7265 E dhcpcd  : get_duid: m
08-29 13:12:29.955  7265  7265 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 13:12:29.955  7265  7265 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-29 13:12:29.984  1043  1565 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7268 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:12:29.986  1043  1565 I ActivityManager: Killing 6815:com.lge.bnr/1000 (adj 15): empty #17
08-29 13:12:30.016  1043  1113 W ProcessCpuTracker: Skipping unknown process pid 7271
,08-29 13:12:30.026  7265  7265 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-29 13:12:30.030  7265  7265 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 13:12:30.030  7265  7265 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 13:12:30.030  7265  7265 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 13:12:30.030  7265  7265 D dhcpcd  : wlan0: sending REQUEST (xid 0x7567d465), next in 3.43 seconds
,08-29 13:12:30.034  1807  7263 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-29 13:12:30.038  1043  1764 W libprocessgroup: failed to open /acct/uid_1000/pid_6815/cgroup.procs: No such file or directory
,08-29 13:12:30.054  7265  7265 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-29 13:12:30.060  7268  7268 I art     : Almond Protected OAT
,08-29 13:12:30.065  7265  7265 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 13:12:30.065  7265  7265 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 13:12:30.066  7265  7265 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 13:12:30.066  7265  7265 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 13:12:30.067  7265  7265 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-29 13:12:30.067  7265  7265 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 13:12:30.067  7265  7265 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 13:12:30.068  7265  7265 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-29 13:12:30.079  1043  1378 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:30.079  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:30.079  1043  1378 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:12:30.085  1043  1428 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 13:12:30.085  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 13:12:30.086  1043  1428 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 13:12:30.086  1043  1428 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 13:12:30.086  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 13:12:30.086  1043  1428 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-29 13:12:30.136  1043  1895 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7293 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-29 13:12:30.137  7268  7268 D WeatherApplication: removeAccount
08-29 13:12:30.138  7268  7268 D WeatherApplication: Account.length = 0
08-29 13:12:30.139  7268  7268 E WeatherApplication: OPERATOR:OPEN
08-29 13:12:30.142  7268  7268 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:12:30
08-29 13:12:30.144  7268  7268 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 13:12:30.144  7268  7268 D Weather.Utils: 2 : All the weather widget is gone.
08-29 13:12:30.146  7268  7268 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 13:12:30.147  7268  7268 D WeatherAncestor: connectivity changed - connection : true
08-29 13:12:30.148  7268  7268 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-29 13:12:30.156  7268  7268 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 13:12:30.158  7268  7268 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 13:12:30.158  7268  7268 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-29 13:12:30.184  7268  7268 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 13:12:30.184  7268  7268 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:12:30
08-29 13:12:30.295  1043  1985 I art     : Explicit concurrent mark sweep GC freed 101333(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/64MB, paused 1.977ms total 121.069ms
,08-29 13:12:30.320  7293  7293 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 13:12:30.320  7293  7293 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-29 13:12:30.341  1043  7230 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-29 13:12:30.342  1043  7230 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-29 13:12:30.342  1043  7230 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 13:12:30.342  1043  7230 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 13:12:30.343  1043  7230 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-29 13:12:30.343  1043  7230 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 13:12:30.343  1043  7230 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-29 13:12:30.343  1043  7230 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 13:12:30.344  1043  7230 D DhcpStateMachine: RunningState
,08-29 13:12:30.345  1043  1895 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7327 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:12:30.346  1043  1895 I ActivityManager: Killing 2152:com.lge.music/u0a34 (adj 15): empty #17
08-29 13:12:30.359   327  1717 V AudioFlinger: 2152 died, releasing its sessions
08-29 13:12:30.359   327  1717 V AudioFlinger:  pid 1843 @ 0
08-29 13:12:30.359   327  1717 V AudioFlinger:  pid 3228 @ 1
08-29 13:12:30.359   327  1717 V AudioFlinger:  pid 3228 @ 2
,08-29 13:12:30.368  7293  7293 I MultiDex: VM with version 2.1.0 has multidex support
08-29 13:12:30.368  7293  7293 I MultiDex: install
,08-29 13:12:30.368  7293  7293 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-29 13:12:30.395  1043  1985 W libprocessgroup: failed to open /acct/uid_10034/pid_2152/cgroup.procs: No such file or directory
,08-29 13:12:30.417  7293  7293 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-29 13:12:30.508   279   345 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-29 13:12:30.508   279   345 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 13:12:30.508   279   345 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 13:12:30.508  7327  7348 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-29 13:12:30.510   279   345 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 13:12:30.510   279   345 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 13:12:30.510   279   345 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 13:12:30.511  7327  7348 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-29 13:12:30.525   279   345 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 13:12:30.525   279   345 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-29 13:12:30.525   279   345 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:12:30.526  7327  7350 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-29 13:12:30.529   279   345 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-29 13:12:30.529   279   345 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-29 13:12:30.529   279   345 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 13:12:30.530  7327  7350 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-29 13:12:30.658   323  7257 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-29 13:12:30.739  7293  7313 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:12:30.739  7293  7313 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 13:12:30.780  7370  7370 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-29 13:12:30.785  7327  7327 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-29 13:12:30.798  7327  7327 I LibraryLoader: Loading: webviewchromium
,08-29 13:12:30.820  7327  7327 I LibraryLoader: Time to load native libraries: 23 ms (timestamps 1053-1076)
,08-29 13:12:30.820  7327  7327 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 13:12:30.825  7327  7327 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {232b9d8}
08-29 13:12:30.825  7370  7370 I dex2oat : dex2oat took 45.082ms (threads: 4)
08-29 13:12:30.826  7327  7327 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 13:12:30.826  7327  7327 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 13:12:30.833  7327  7327 I BrowserStartupController: Initializing chromium process, renderers=0
,08-29 13:12:30.833  7327  7327 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 13:12:30.839  7293  7313 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 13:12:30.839  7293  7313 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 13:12:30.839  7293  7313 I Adreno-EGL: Build Date: 12/12/14 금
08-29 13:12:30.839  7293  7313 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 13:12:30.839  7293  7313 I Adreno-EGL: Remote Branch: 
08-29 13:12:30.839  7293  7313 I Adreno-EGL: Local Patches: 
08-29 13:12:30.839  7293  7313 I Adreno-EGL: Reconstruct Branch: 
08-29 13:12:30.842  7327  7327 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-29 13:12:30.843  7327  7327 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-29 13:12:30.843  7327  7327 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-29 13:12:30.847   327   327 V AudioPolicyService: registerClient() client 0xb0410580, uid 10093
,08-29 13:12:30.849  7327  7381 W AudioManagerAndroid: Requires BLUETOOTH permission
08-29 13:12:30.856  7327  7327 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 13:12:30.856  7327  7327 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 13:12:30.856  7327  7327 I Adreno-EGL: Build Date: 12/12/14 금
08-29 13:12:30.856  7327  7327 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 13:12:30.856  7327  7327 I Adreno-EGL: Remote Branch: 
08-29 13:12:30.856  7327  7327 I Adreno-EGL: Local Patches: 
08-29 13:12:30.856  7327  7327 I Adreno-EGL: Reconstruct Branch: 
,08-29 13:12:30.890  1043  1509 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 13:12:30.916  7327  7327 I NSApplication: Starting up...
,08-29 13:12:30.955  7293  7313 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 13:12:30.955  7293  7313 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 13:12:30.955  7293  7313 I Adreno-EGL: Build Date: 12/12/14 금
08-29 13:12:30.955  7293  7313 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 13:12:30.955  7293  7313 I Adreno-EGL: Remote Branch: 
08-29 13:12:30.955  7293  7313 I Adreno-EGL: Local Patches: 
08-29 13:12:30.955  7293  7313 I Adreno-EGL: Reconstruct Branch: 
,08-29 13:12:30.971  1043  1887 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7395 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-29 13:12:30.975  1043  1061 I ActivityManager: Killing 6910:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-29 13:12:31.085  1043  2023 W libprocessgroup: failed to open /acct/uid_10037/pid_6910/cgroup.procs: No such file or directory
08-29 13:12:31.087  1043  1060 D WifiServiceImplEx: setWifiEnabled: false pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 13:12:31.088  1043  1060 D WifiService: setWifiEnabled: false pid=6705, uid=10118
08-29 13:12:31.088  1043  1060 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 13:12:31.107  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 13:12:31.108  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 13:12:31.108  1043  1043 D Ulp_jni : JNI:system_update. Event-4
08-29 13:12:31.108  1043  1428 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 13:12:31.108  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-29 13:12:31.109  1043  1428 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-29 13:12:31.109  1043  1428 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-29 13:12:31.109  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-29 13:12:31.109  1043  1428 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 13:12:31.109  1043  1428 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:12:31.109  1043  1428 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 13:12:31.110  1043  1428 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 13:12:31.110  1043  1428 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-29 13:12:31.116  1043  1428 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 13:12:31.116  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 13:12:31.116  7171  7171 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 13:12:31.116  1043  1378 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:31.116  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:31.116  1043  1428 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 13:12:31.116  1043  1428 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 13:12:31.117  1043  1428 D WifiNative-wlan0: SET ps 1: returned true
08-29 13:12:31.117   323   896 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:12:31.117  1043  7230 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:31.124  7395  7395 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:12:31.144  1043  1509 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 13:12:31.144  1043  1509 D ConnectivityService: ignoring duplicate network state non-change
08-29 13:12:31.144  1043  1509 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-29 13:12:31.150  1043  1043 D WifiHS20: hidePasspointNotification off =false
08-29 13:12:31.151  1043  1378 D LGWifiP2pService: InactiveState{ when=-7ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:31.151  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:31.151  1043  1378 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2286924f
08-29 13:12:31.151  1043  1428 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:31.152  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:31.152  1043  1428 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:31.153  1043  1428 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:31.153  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:31.153  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:31.155  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:31.155  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:31.155  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 13:12:31.155  1043  1043 D WifiHS20: hidePasspointNotification off =false
08-29 13:12:31.156  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:31.156  1043  1428 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:31.157  1043  1428 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 13:12:31.160  1931  1931 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-29 13:12:31.161  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 13:12:31.162  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:31.162  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:31.163  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:31.163  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:31.163  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 13:12:31.163  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 13:12:31.163  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:31.164  1043  1043 D RttService: SCAN_AVAILABLE : 1
08-29 13:12:31.164  1043  1547 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:31.164  1043  1546 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:31.165  1043  1378 D LGWifiP2pService: P2pDisablingState
08-29 13:12:31.165  1043  1378 D LGWifiP2pService: P2pDisablingState{ when=-14ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:31.165  1043  1378 D LGWifiP2pService: p2p socket connection lost
08-29 13:12:31.165  1043  1378 D LGWifiP2pService: P2pDisabledState
08-29 13:12:31.166  1931  1931 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 13:12:31.166  1931  1931 D WfdsService: WifiP2pState is changed : false
08-29 13:12:31.166  1931  2284 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-29 13:12:31.166  1931  2284 D WfdsService: Set the WFDS Monitor: false
08-29 13:12:31.167  1043  1428 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-29 13:12:31.167  1931  2284 D WfdsMonitor: WFDS Monitor is stopped
08-29 13:12:31.167  1931  2284 D WfdsService: STATE : WfdsDisabledState - enter
08-29 13:12:31.167  1931  7175 D CtrlSupplicant: Received on exit socket, terminate
08-29 13:12:31.167  1931  7175 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-29 13:12:31.167  1931  7175 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-29 13:12:31.167  1931  7175 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-29 13:12:31.167  1931  2287 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-29 13:12:31.167  1931  2284 W WfdsService: DefaultState - msg [9445378] is not handled
08-29 13:12:31.170  1043  1378 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:31.170  1043  1378 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:31.170  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 13:12:31.170  7171  7171 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 13:12:31.170  1043  1428 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 13:12:31.170  1043  1428 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 13:12:31.171  1043  1428 D WifiNative-wlan0: SET ps 1: returned true
08-29 13:12:31.206   323   896 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:12:31.206  1043  1509 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-29 13:12:31.206  1043  1509 D DSQN    : disableDataServiceNotify
08-29 13:12:31.206  1043  1509 D DSQN    : stop dsqn bin
,08-29 13:12:31.207  1043  1428 D WifiNative-p2p0: doBoolean: TERMINATE
08-29 13:12:31.207  1043  1428 D WifiNative-p2p0: TERMINATE: returned true
08-29 13:12:31.207  1043  1428 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:12:31.207  1043  1428 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:12:31.207  1043  1428 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 13:12:31.208  1043  1043 D WifiHS20: hidePasspointNotification off =false
08-29 13:12:31.210  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 13:12:31.210  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:31.211  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:31.211  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:31.211  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 13:12:31.211  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:31.213  1931  1931 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-29 13:12:31.214  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-29 13:12:31.214  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:12:31.214  1043  1043 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-29 13:12:31.215  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:31.215  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:31.215  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:31.215  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:31.215  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:31.215  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:31.215  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:31.215  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:31.215  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:31.215  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:31.215  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:31.216  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:31.216  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:31.216  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:31.216  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:31.216  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:31.216  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is B,luetooth enabled: false
08-29 13:12:31.216  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:31.216  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:31.216  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:31.216  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:31.216  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:31.223  1043  1509 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-29 13:12:31.223  1043  1509 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:31.223  1043  1509 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:12:31.223  1043  1509 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:12:31.223  1043  1509 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-29 13:12:31.223  1043  1509 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-29 13:12:31.224  1043  1509 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 13:12:31.224  1043  1509 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 13:12:31.224  1043  1509 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:31.224  1043  1509 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 13:12:31.226  1592  2041 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 13:12:31.226  1043  1377 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-29 13:12:31.227  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 13:12:31.227  1043  1509 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:31.227  1043  1509 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:31.228  1043  1509 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:31.228  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 13:12:31.228  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 13:12:31.228  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 13:12:31.229  1043  1509 D NetworkManagementService: Removing idletimer
08-29 13:12:31.229  1043  1509 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:31.230  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:31.230  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-29 13:12:31.230  1043  1428 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:31.230  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 13:12:31.230  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 13:12:31.230  1043  1428 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:12:31.230  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 13:12:31.231  1843  1843 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:31.231  1843  1843 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 13:12:31.231  1043  1377 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,08-29 13:12:31.259  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 13:12:31.259  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:31.260  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 13:12:31.273  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 13:12:31.274  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:31.274  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:31.316  7171  7171 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 13:12:31.316  7171  7171 I wpa_supplicant: monitor socket send errors count : 1
08-29 13:12:31.316  7171  7171 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1931-4\x00 that cannot receive messages
,08-29 13:12:31.318  1043  7174 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-29 13:12:31.318  1043  7174 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-29 13:12:31.358  7171  7171 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 13:12:31.358  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-29 13:12:31.358  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 13:12:31.358  1043  7174 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 13:12:31.358  1043  7174 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-29 13:12:31.359  1043  1428 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=121603
08-29 13:12:31.359  1043  1428 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=121603
08-29 13:12:31.359  1043  1120 D Tethering: InitialState.processMessage what=4
08-29 13:12:31.360  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:12:31.360  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:12:31.360  7171  7171 W wpa_supplicant: USIM:  scard_deinit function
08-29 13:12:31.361  1043  1428 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=121605  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 13:12:31.361  1043  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 13:12:31.361  1043  1428 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=121605  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-29 13:12:31.361  1043  7230 D DhcpStateMachine: StoppedState
08-29 13:12:31.361  1043  7230 D DhcpStateMachine: StoppedState{ when=-191ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:12:31.362  1043  1428 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:31.362  1043  1428 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:31.362  1043  1428 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-29 13:12:31.362  1043  1428 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-29 13:12:31.367  7293  7313 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-29 13:12:31.367  7293  7313 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-29 13:12:31.367  7293  7313 I Adreno-EGL: Build Date: 12/12/14 금
08-29 13:12:31.367  7293  7313 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-29 13:12:31.367  7293  7313 I Adreno-EGL: Remote Branch: 
08-29 13:12:31.367  7293  7313 I Adreno-EGL: Local Patches: 
08-29 13:12:31.367  7293  7313 I Adreno-EGL: Reconstruct Branch: 
08-29 13:12:31.406  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 13:12:31.412  6457  6485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 13:12:31.422  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:31.428  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-29 13:12:31.428  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:31.429  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 13:12:31.429  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 13:12:31.430  7120  7120 I AppUp4:CustModeStarterReceiver: onReceive
08-29 13:12:31.432  7120  7120 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@10ae4e89
08-29 13:12:31.432  7120  7120 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 13:12:31.432  7120  7120 D AppUp4:CustFacade: isPhone : true
08-29 13:12:31.432  7120  7120 D AppUp4:CustModeStarterReceiver: begin check event
08-29 13:12:31.432  7120  7120 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 13:12:31.433   323  7434 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-29 13:12:31.433  1043  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 13:12:31.434  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:31.434  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 13:12:31.435  1807  7263 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-29 13:12:31.436  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:12:31.438  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:12:31.440  1807  7263 I CheckinService: active receiver: disabled
08-29 13:12:31.443  4806  7435 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 13:12:31.445  4806  7437 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:31.445  4806  7437 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-29 13:12:31.456  7153  7153 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 13:12:31.474  7171  7171 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 13:12:31.475  3228  3228 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 13:12:31.475  3228  3228 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:31.475  3228  3228 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-29 13:12:31.477  1043  7174 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-29 13:12:31.477  1043  7174 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-29 13:12:31.477  1043  7174 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-29 13:12:31.477  1043  1428 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-29 13:12:31.479  7188  7188 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 13:12:31.479  7188  7188 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 13:12:31.483  7153  7440 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:31.487  7017  7442 W FormManager: Network not available. Please check & try again.
08-29 13:12:31.487  7017  7443 V FormManager: Network unavailable.
,08-29 13:12:31.489  7268  7268 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:12:31
08-29 13:12:31.490  7268  7268 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 13:12:31.490  7268  7268 D Weather.Utils: 2 : All the weather widget is gone.
08-29 13:12:31.490  7268  7268 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 13:12:31.490  7268  7268 D WeatherAncestor: connectivity changed - connection : true
08-29 13:12:31.490  7268  7268 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@b4ab6af
08-29 13:12:31.491  7268  7268 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 13:12:31.491  7268  7268 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 13:12:31.491  7017  7443 V FormManager: Network unavailable.
08-29 13:12:31.491  7268  7268 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 13:12:31.491  7268  7268 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 13:12:31.492  7268  7268 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:12:31
08-29 13:12:31.510  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 13:12:31.510  6928  6928 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-29 13:12:31.510  6928  6928 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 13:12:31.511  6928  6928 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 13:12:31.511  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 13:12:31.512  6928  6928 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 13:12:31.512  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 13:12:31.512  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 13:12:31.512  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 13:12:31.512  6928  6928 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 13:12:31.512  6928  6928 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 13:12:31.518  6947  6947 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:12:31.520  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:31.521  7017  7446 W FormManager: Network not available. Please check & try again.
,08-29 13:12:31.525  7017  7447 V FormManager: Network unavailable.
08-29 13:12:31.525  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:31.532  7017  7447 V FormManager: Network unavailable.
08-29 13:12:31.536  6947  6947 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 13:12:31.540  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:31.543  7017  7448 W FormManager: Network not available. Please check & try again.
08-29 13:12:31.544  7017  7449 V FormManager: Network unavailable.
08-29 13:12:31.545  7017  7449 V FormManager: Network unavailable.
08-29 13:12:31.547  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:31.558  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 13:12:31.558  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 13:12:31.560  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 13:12:31.562  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:12:31.566  4806  7450 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 13:12:31.566  4806  7451 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 13:12:31.566  4806  7451 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 13:12:31.615  1043  1949 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7452 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-29 13:12:31.619  1043  1428 D WifiOffDelayIfNotUsed: stopMonitoring
08-29 13:12:31.619  1043  1428 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:12:31.619  1043  1428 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:12:31.619  1043  1428 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 13:12:31.622  1931  1931 D WfdsService: Supplicant Connection state is changed : false
08-29 13:12:31.622  1931  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-29 13:12:31.622  1931  2284 D WfdsService: Set the WFDS Monitor: false
08-29 13:12:31.622  1931  2284 D WfdsMonitor: WFDS Monitor is stopped
08-29 13:12:31.623  1931  1931 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-29 13:12:31.623  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:31.625  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-29 13:12:31.625  1043  1463 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-29 13:12:31.625  1043  1463 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-29 13:12:31.626  2454  2454 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:31.626  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:31.626  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:31.626  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:31.626  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:31.626  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:31.626  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:31.626  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:31.626  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:31.626  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:31.628  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:31.628  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:31.628  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:31.628  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:31.628  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:31.628  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:31.628  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:31.628  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:31.628  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:31.752  7452  7452 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 13:12:31.752  7452  7452 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-29 13:12:31.764  7452  7452 V [BNRBootReceiver]: Boot Receiver Return
,08-29 13:12:31.765  7452  7452 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 13:12:31.771  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:12:31.784  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:31.795  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:31.813  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 13:12:31.814  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 13:12:31.817  6979  6979 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:12:31.832  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:12:31.851  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:31.862  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:31.872  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 13:12:31.872  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:31.875  6979  6979 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:12:31.879  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-29 13:12:31.883  6928  6928 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-29 13:12:31.890  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:31.901  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:31.909  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:31.918  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:31.919  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 13:12:31.919  6979  6979 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:12:31.924  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:31.932  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:31.940  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:31.949  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 13:12:31.950  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 13:12:31.950  6979  6979 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:12:31.955  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:31.966  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:31.975  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:31.985  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 13:12:31.986  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:31.986  6979  6979 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:12:31.994  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:32.008  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:32.017  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:32.026  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:32.027  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:32.027  6979  6979 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 13:12:32.034  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:12:32.044  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:32.050  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:32.059  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:32.059  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:32.060  6979  6979 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 13:12:32.069  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:12:32.085  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:32.096  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 13:12:32.108  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:32.108  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:32.109  6846  7092 D UEI.SmartControl: Internal timer expired: 2
08-29 13:12:32.109  6846  7092 D UEI.SmartControl: unbind internal service
,08-29 13:12:32.116  6979  6979 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:12:32.124  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:12:32.138  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:32.149  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:32.160  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:32.161  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 13:12:32.163  6979  6979 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 13:12:32.174  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:32.183  6947  6947 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-29 13:12:32.196  6846  7089 D serial_port: close(fd = 24)
,08-29 13:12:32.200  1043  1486 D WifiService: New client listening to asynchronous messages
08-29 13:12:32.201  6846  7089 I UEI.SmartControl: Serial port is closed.
08-29 13:12:32.203  6947  6947 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:12:32.209  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:32.219  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:32.227  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 13:12:32.228  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 13:12:32.229  6979  6979 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 13:12:32.230  6979  6979 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 13:12:32.231  6979  6979 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 13:12:32.236  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:32.241  6947  6947 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 13:12:32.242  6947  6947 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 13:12:32.249  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:32.258  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:32.267  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:32.267  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:32.268  6979  6979 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 13:12:32.269  6979  6979 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 13:12:32.270  6979  6979 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 13:12:32.273  1043  1060 I ActivityManager: Killing 6996:com.lge.settings.easy/1000 (adj 15): empty #17
,08-29 13:12:32.306  1043  1887 W libprocessgroup: failed to open /acct/uid_1000/pid_6996/cgroup.procs: No such file or directory
,08-29 13:12:32.310  2186  2186 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-29 13:12:32.322  2186  2186 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-29 13:12:32.322  2186  2186 D c       : Getting all permits...
08-29 13:12:32.322  2186  2186 D a       : Opening database...
08-29 13:12:32.327  2186  2186 D a       : Opening database auth.proximity.permit_store...
08-29 13:12:32.328  2186  2186 D a       : Closing database...
08-29 13:12:32.342  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:12:32.347  6947  6947 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-29 13:12:32.347  6947  6947 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 13:12:32.347  6947  6947 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:12:32.350  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:32.357  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:32.365  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:32.365  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 13:12:32.367  6979  6979 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:12:32.373  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:32.379  6947  6947 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-29 13:12:32.379  6947  6947 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 13:12:32.379  6947  6947 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:12:32.383  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:12:32.389  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:32.397  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 13:12:32.398  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:32.400  6979  6979 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:12:32.406  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:32.413  6947  6947 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-29 13:12:32.413  6947  6947 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 13:12:32.413  6947  6947 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 13:12:32.421  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:32.430  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:32.437  6979  6979 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:32.437  6979  6979 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 13:12:32.439  6979  6979 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:12:32.448  6947  6947 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:12:32.451  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:12:32.461  7017  7480 W FormManager: Network not available. Please check & try again.
08-29 13:12:32.465  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 13:12:32.468  7017  7481 V FormManager: Network unavailable.
08-29 13:12:32.473  7017  7481 V FormManager: Network unavailable.
08-29 13:12:32.485  2186  2186 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-29 13:12:32.501  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-29 13:12:32.502  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 13:12:32.504  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:12:32.507  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:12:32.513  4806  7482 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 13:12:32.516  6947  6947 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-29 13:12:32.516  6947  6947 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-29 13:12:32.516  6947  6947 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:12:32.518  4806  7483 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 13:12:32.518  4806  7483 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 13:12:32.520  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:12:32.526  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:32.544  7017  7485 W FormManager: Network not available. Please check & try again.
,08-29 13:12:32.548  7017  7486 V FormManager: Network unavailable.
,08-29 13:12:32.551  7017  7486 V FormManager: Network unavailable.
08-29 13:12:32.732  1043  1428 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-704629796] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 13:12:32.735  1043  1428 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-704629793] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-29 13:12:32.883  1043  1509 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:32.897  1043  1120 D Tethering: MasterInitialState.processMessage what=3
08-29 13:12:32.902  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:32.906  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:32.911  1043  1110 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:32.914  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 13:12:32.915  6457  6485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-29 13:12:32.928  5796  5796 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 13:12:32.949  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:32.968  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 13:12:32.968  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:32.968  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 13:12:32.968  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-29 13:12:32.973  7120  7120 I AppUp4:CustModeStarterReceiver: onReceive
08-29 13:12:32.976  7120  7120 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@10ae4e89
08-29 13:12:32.976  7120  7120 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 13:12:32.976  7120  7120 D AppUp4:CustFacade: isPhone : true
08-29 13:12:32.979  7120  7120 D AppUp4:CustModeStarterReceiver: begin check event
08-29 13:12:32.979  7120  7120 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 13:12:32.984  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:32.984  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 13:12:32.986  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 13:12:32.991  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:12:32.999  7153  7153 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 13:12:33.029  3228  3228 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 13:12:33.029  3228  3228 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:33.029  3228  3228 I LgeMiscReceiver: networkInfo.isConnected() = true
08-29 13:12:33.029  3228  3228 D PhoneState: setPdpRejectCasuse : false
,08-29 13:12:33.035  7188  7188 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 13:12:33.036  7188  7188 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 13:12:33.054  4806  7500 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 13:12:33.057  7268  7268 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:12:33
08-29 13:12:33.057  1043  1110 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:33.061  7153  7499 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:33.062  7268  7268 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 13:12:33.062  7268  7268 D Weather.Utils: 2 : All the weather widget is gone.
08-29 13:12:33.064  7268  7268 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 13:12:33.064  7268  7268 D WeatherAncestor: connectivity changed - connection : true
08-29 13:12:33.064  7268  7268 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@b4ab6af
08-29 13:12:33.065  7268  7268 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 13:12:33.065  7268  7268 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 13:12:33.065  7268  7268 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,08-29 13:12:33.065  7268  7268 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 13:12:33.065  7268  7268 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:12:33
08-29 13:12:33.071  4806  7514 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:33.076  4806  7514 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 13:12:33.077  7017  7515 W FormManager: Network not available. Please check & try again.
08-29 13:12:33.079  7017  7516 V FormManager: Network unavailable.
08-29 13:12:33.084  7017  7516 V FormManager: Network unavailable.
,08-29 13:12:34.110  1043  1565 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 13:12:34.111  1043  1565 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-29 13:12:34.146  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 13:12:34.146  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 13:12:34.146  1043  1043 D Ulp_jni : JNI:system_update. Event-4
,08-29 13:12:34.149  1043  1120 D BluetoothManagerService: Message: 1
08-29 13:12:34.149  1043  1120 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-29 13:12:34.186  1043  1120 D BluetoothManagerService: Message: 20
08-29 13:12:34.186  1043  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ec8390d:true
,08-29 13:12:34.189  7044  7044 D BluetoothAdapterState: make
08-29 13:12:34.193  7044  7044 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 13:12:34.194  7044  7044 I bluedroid-qcom: init
08-29 13:12:34.195  7044  7530 I BluetoothAdapterState: Entering OffState
08-29 13:12:34.195  7044  7044 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 13:12:34.196  7044  7044 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 13:12:34.196  7044  7044 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 13:12:34.196  7044  7044 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 13:12:34.196  7044  7044 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 13:12:34.198  7044  7044 I bluedroid-qcom: get_profile_interface socket
08-29 13:12:34.198  7044  7044 I bluedroid-qcom: get_profile_interface map_client
,08-29 13:12:34.202  7044  7534 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 13:12:34.198  7533  7533 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:34.198  7533  7533 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:34.208  7044  7534 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-29 13:12:34.216  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-29 13:12:34.216  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 13:12:34.216  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
,08-29 13:12:34.219  1043  1120 D BluetoothManagerService: Message: 40
08-29 13:12:34.219  1043  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 13:12:34.221  7533  7533 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 13:12:34.221  7533  7533 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 13:12:34.221  7533  7533 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-29 13:12:34.223  7044  7061 I bluedroid-qcom: config_hci_snoop_log
08-29 13:12:34.224  1043  1120 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 13:12:34.224  1043  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 13:12:34.225  1043  1509 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:34.226  7533  7533 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-29 13:12:34.235  7533  7533 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 13:12:34.235  7533  7533 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-29 13:12:34.246  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:34.248  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:34.250  1043  1509 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:34.261  7044  7530 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-29 13:12:34.264  1043  1120 D Tethering: MasterInitialState.processMessage what=3
08-29 13:12:34.269  7044  7534 D BluetoothAdapterProperties: Name is: G3
,08-29 13:12:34.270  1043  1120 D Tethering: MasterInitialState.processMessage what=3
08-29 13:12:34.270  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-29 13:12:34.270  7044  7530 D BluetoothAdapterProperties: Setting state to 11
08-29 13:12:34.273  7044  7530 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 13:12:34.274  6457  6485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-29 13:12:34.277  1043  1120 D BluetoothManagerService: Message: 60
,08-29 13:12:34.277  1043  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 13:12:34.277  1043  1120 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 13:12:34.278  7044  7530 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 13:12:34.282  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:34.285  1931  1931 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:34.286  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:34.287  6928  6928 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-29 13:12:34.287  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 13:12:34.288  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:34.289  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:34.293  5796  5796 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-29 13:12:34.298  7044  7530 D BluetoothBondStateMachine: make
08-29 13:12:34.300  7044  7530 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:34.300  7044  7530 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 13:12:34.300  7044  7530 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
,08-29 13:12:34.301  7044  7530 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 13:12:34.301  7044  7044 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 13:12:34.302  7044  7044 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:34.302  7044  7044 V BluetoothPbapReceiver: ***********state = 11
08-29 13:12:34.305  7044  7550 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 13:12:34.306  7044  7530 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 13:12:34.310  7044  7530 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:12:34.313  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:12:34.320  7044  7530 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:12:34.324  7044  7044 D HeadsetService: Received start request. Starting profile...
08-29 13:12:34.325  7044  7044 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 13:12:34.325  7044  7044 D LGBluetoothHfpAdapter: Version 1.6
08-29 13:12:34.328  7044  7044 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 13:12:34.329  7044  7044 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 13:12:34.330  7044  7044 D HeadsetStateMachine: make
08-29 13:12:34.331  5796  5796 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-29 13:12:34.355  1043  2023 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7554 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-29 13:12:34.361  7044  7530 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 13:12:34.366  7044  7044 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:12:34.366  7044  7044 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 13:12:34.368  7044  7530 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:12:34.370  7044  7044 D HeadsetStateMachine: max_hf_connections = 1
08-29 13:12:34.370  7044  7044 I bluedroid-qcom: get_profile_interface handsfree
08-29 13:12:34.370  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:34.372  7044  7044 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-29 13:12:34.374  1043  1110 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:34.375   327  1715 V AudioPolicyService: registerClient() client 0xb0410940, uid 1002
08-29 13:12:34.375   327  1717 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 13:12:34.375   327  1717 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 13:12:34.375   327  1717 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 13:12:34.375  7044  7044 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 13:12:34.376   327   327 V AudioFlinger: registerClient() client 0xb55815c8, pid 7044
08-29 13:12:34.376   327  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:12:34.376   327  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:12:34.376  7044  7044 V ToneGenerator: Create Track: 0xb4928080
08-29 13:12:34.376  7044  7044 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 13:12:34.376  7044  7044 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 13:12:34.376  1592  3184 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:12:34.376  1592  3184 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:12:34.376   327  1717 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 13:12:34.376   327  1717 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 13:12:34.376   327  1717 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 13:12:34.376   327  1717 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 13:12:34.376  1043  1913 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:12:34.376  1043  1913 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:12:34.377  7044  7044 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 13:12:34.377   327  1717 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 13:12:34.377   327   327 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 13:12:34.377  7044  7060 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:12:34.377   327   327 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 13:12:34.377   327   327 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 13:12:34.377  7044  7060 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-29 13:12:34.377   327   327 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 13:12:34.377   327  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:12:34.377   327  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:12:34.377  7044  7044 V AudioSystem: getLatency() output 2, latency 50
08-29 13:12:34.377  7044  7044 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 13:12:34.377  7044  7044 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 13:12:34.378  7044  7530 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:12:34.378  1843  1858 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:12:34.378  1843  1858 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:12:34.378  3228  3261 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:12:34.378  3228  3261 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:12:34.378  1843  2420 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:12:34.378  3228  3267 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:12:34.378  3228  3267 V AudioSystem: ioConfigCh,anged() opening already existing output! 4
08-29 13:12:34.378  1843  2420 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:12:34.378  1043  1764 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:12:34.378  1043  1764 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:12:34.378   327  1715 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 13:12:34.379   327  1715 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 13:12:34.379   327  1715 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 13:12:34.379   327  1715 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 13:12:34.379   327  1715 V AudioFlinger: createTrack() lSessionId: 22
08-29 13:12:34.379  1592  1613 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:12:34.379  7044  7535 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:12:34.379  1592  1613 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:12:34.379  7044  7535 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 13:12:34.379  7044  7044 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 13:12:34.380   327  1715 V AudioFlinger: acquiring 22 from 7044, for 7044
08-29 13:12:34.380   327  1715 V AudioFlinger:  added new entry for 22
08-29 13:12:34.380  7044  7044 V ToneGenerator: ToneGenerator INIT OK, time: 124636
08-29 13:12:34.380  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:34.382  7044  7552 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-29 13:12:34.382  7044  7552 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 13:12:34.382  7044  7552 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 13:12:34.382  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:34.382  7044  7552 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 13:12:34.383   327  1384 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7044
08-29 13:12:34.383   327  1384 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 13:12:34.383   327  1384 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 13:12:34.383   327  1384 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 13:12:34.383   327  1384 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 13:12:34.383   327  1384 V voice   : voice_set_parameters: exit with code(0)
08-29 13:12:34.383   327  1384 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 13:12:34.383   327  1384 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 13:12:34.384   327  1384 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 13:12:34.384   327  1384 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 13:12:34.384   327  1384 V audio_hw_primary: adev_set_parameters: exit with code(0)
,08-29 13:12:34.384   327  1384 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 13:12:34.384  7044  7552 V ToneGenerator: ToneGenerator destructor
08-29 13:12:34.384  7044  7044 D A2dpService: Received start request. Starting profile...
08-29 13:12:34.384  7044  7552 V ToneGenerator: stopTone
08-29 13:12:34.384  7044  7552 V ToneGenerator: Delete Track: 0xb4928080
08-29 13:12:34.384  7044  7044 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 13:12:34.385  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 13:12:34.385  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:34.385  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 13:12:34.385  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 13:12:34.385  7044  7044 V Avrcp   : make
,08-29 13:12:34.386  7044  7044 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 13:12:34.386  7044  7044 I bluedroid-qcom: get_profile_interface avrcp
08-29 13:12:34.387  7044  7552 V AudioTrack: ~AudioTrack, releasing session id from 7044 on behalf of 7044
08-29 13:12:34.387   327  1717 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 13:12:34.387   327  1717 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 13:12:34.387   327  1715 V AudioFlinger: releasing 22 from 7044 for 7044
08-29 13:12:34.387   327  1717 V AudioFlinger: PlaybackThread::Track destructor
08-29 13:12:34.387   327  1260 V AudioPolicyService: AudioCommandThread() waking up
08-29 13:12:34.387   327  1715 V AudioFlinger:  decremented refcount to 0
,08-29 13:12:34.387   327  1717 V AudioFlinger: removeClient_l() pid 7044, calling pid 327
08-29 13:12:34.387   327  1715 V AudioFlinger: purging stale effects
08-29 13:12:34.387   327  1260 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 13:12:34.387   327  1260 V AudioPolicyManager: releaseOutput() 2
08-29 13:12:34.387   327  1260 V AudioPolicyService: AudioCommandThread() going to sleep
,08-29 13:12:34.390  7044  7530 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:12:34.397  7044  7044 V AudioManager: registerRemoteController: size of Media player list: 0
08-29 13:12:34.397  7044  7530 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:12:34.398  7044  7044 E AudioManager: No RCC entry present to update
,08-29 13:12:34.398  7044  7044 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 13:12:34.398  7120  7120 I AppUp4:CustModeStarterReceiver: onReceive
08-29 13:12:34.399  1043  1110 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:34.400  7044  7044 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 13:12:34.401  7044  7044 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 13:12:34.401  7044  7044 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 13:12:34.406  7044  7044 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 13:12:34.407  7120  7120 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@10ae4e89
08-29 13:12:34.407  7120  7120 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 13:12:34.407  7120  7120 D AppUp4:CustFacade: isPhone : true
08-29 13:12:34.410  7120  7120 D AppUp4:CustModeStarterReceiver: begin check event
08-29 13:12:34.411  7120  7120 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 13:12:34.412  7044  7530 V LGMDMManager: Create singleton instance
,08-29 13:12:34.414  7044  7530 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 13:12:34.447  1043  1110 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:34.447  1043  1110 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 13:12:34.449  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:34.450  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 13:12:34.454  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:12:34.460  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 13:12:34.470  4806  7576 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 13:12:34.472  7153  7153 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-29 13:12:34.491  7153  7578 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:12:34.492  4806  7577 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:34.492  4806  7577 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 13:12:34.497  1043  1948 V SIM_STK : Menu title from STK is T-Mobile
08-29 13:12:34.497  1043  1948 V SIM_STK : Menu title from STK is T-Mobile
08-29 13:12:34.500  3228  3228 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 13:12:34.500  3228  3228 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:34.500  3228  3228 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 13:12:34.514  7017  7581 W FormManager: Network not available. Please check & try again.
,08-29 13:12:34.515  7017  7582 V FormManager: Network unavailable.
,08-29 13:12:34.517  7017  7582 V FormManager: Network unavailable.
08-29 13:12:34.523  7554  7554 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-29 13:12:34.523  7554  7554 W LG Account v2.2: No ProfileInfo entries
08-29 13:12:34.523  7188  7188 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 13:12:34.523  7554  7554 I LG Account v2.2: isEnabled: false
08-29 13:12:34.524  7188  7188 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 13:12:34.524  7554  7554 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-29 13:12:34.524  7554  7554 I Feature : [Lifetracker]Country: EU
08-29 13:12:34.524  7554  7554 I Feature : [Lifetracker]Operator: OPEN
08-29 13:12:34.524  7554  7554 I Feature : [Lifetracker]Ranking support: false
08-29 13:12:34.524  7554  7554 I Feature : [Lifetracker]Comfort support: false
08-29 13:12:34.524  7554  7554 I Feature : [Lifetracker]Accessory: true
08-29 13:12:34.524  7554  7554 I Feature : [Lifetracker]Health device: true
08-29 13:12:34.524  7554  7554 I Feature : [Lifetracker]Extra Pedometer: false
08-29 13:12:34.525  7554  7554 I Feature : [Lifetracker]Blood glucose device: false
08-29 13:12:34.525  7554  7554 I Feature : [Lifetracker]Device Number: 3
08-29 13:12:34.531  7268  7268 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:12:34
,08-29 13:12:34.533  7268  7268 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 13:12:34.533  7268  7268 D Weather.Utils: 2 : All the weather widget is gone.
08-29 13:12:34.534  7268  7268 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 13:12:34.534  7268  7268 D WeatherAncestor: connectivity changed - connection : true
08-29 13:12:34.534  7268  7268 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@b4ab6af
08-29 13:12:34.534  7268  7268 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 13:12:34.534  7268  7268 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 13:12:34.534  7268  7268 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 13:12:34.535  7268  7268 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 13:12:34.535  7268  7268 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:12:34
08-29 13:12:34.535  6928  6928 D BluetoothPermissionRequest: onReceive
08-29 13:12:34.542  6928  6928 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 13:12:34.552  6457  6457 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-29 13:12:34.554  6457  6485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-29 13:12:34.567  2186  2186 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:34.573  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-29 13:12:34.573  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:34.573  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-29 13:12:34.573  7120  7120 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-29 13:12:34.574  7120  7120 I AppUp4:CustModeStarterReceiver: onReceive
08-29 13:12:34.577  7120  7120 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@10ae4e89
08-29 13:12:34.577  7120  7120 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 13:12:34.577  7120  7120 D AppUp4:CustFacade: isPhone : true
08-29 13:12:34.577  7120  7120 D AppUp4:CustModeStarterReceiver: begin check event
08-29 13:12:34.577  7120  7120 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-29 13:12:34.580  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:34.580  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 13:12:34.581  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 13:12:34.584  1043  1887 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-29 13:12:34.591  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:12:34.591  7044  7044 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 13:12:34.595  7044  7044 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 13:12:34.596  7044  7044 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 13:12:34.596  7044  7044 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 13:12:34.596  7044  7044 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
,08-29 13:12:34.596  7044  7044 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 13:12:34.596  7044  7044 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 13:12:34.596  7044  7044 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 13:12:34.596  7044  7044 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 13:12:34.596  7044  7044 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 13:12:34.596  7044  7044 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 13:12:34.597  7044  7044 I BluetoothA2dpServiceJni: classInitNative
08-29 13:12:34.597  7044  7044 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 13:12:34.597  7044  7044 D A2dpStateMachine: make
08-29 13:12:34.599  7044  7044 I bluedroid-qcom: get_profile_interface a2dp
08-29 13:12:34.599  7044  7588 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 13:12:34.599  4806  7585 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-29 13:12:34.601  4806  7587 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:34.601  4806  7587 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 13:12:34.601  7153  7153 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-29 13:12:34.603  7044  7044 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 13:12:34.603  7044  7044 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 13:12:34.604  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:34.605  7044  7044 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 13:12:34.606  7044  7586 D A2dpStateMachine: Enter Disconnected: -2
08-29 13:12:34.607  7044  7044 D HidService: Received start request. Starting profile...
,08-29 13:12:34.607  7044  7044 I bluedroid-qcom: get_profile_interface hidhost
08-29 13:12:34.607  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:34.607  7044  7044 D HeadsetStateMachine: Proxy object connected
08-29 13:12:34.608  7044  7044 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-29 13:12:34.608  7044  7044 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-29 13:12:34.609  7044  7044 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 13:12:34.613  7044  7044 D HealthService: Received start request. Starting profile...
08-29 13:12:34.614  7044  7044 I bluedroid-qcom: get_profile_interface health
08-29 13:12:34.615  7044  7044 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 13:12:34.615  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:34.617  7044  7552 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-29 13:12:34.619  3228  3228 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-29 13:12:34.619  3228  3228 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:34.619  7044  7552 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 13:12:34.619  3228  3228 I LgeMiscReceiver: networkInfo.isConnected() = false
08-29 13:12:34.619  7044  7552 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-29 13:12:34.621  7153  7590 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:34.622  7044  7044 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 13:12:34.623  7188  7188 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-29 13:12:34.623  7188  7188 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-29 13:12:34.624  7044  7044 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 13:12:34.624  7017  7595 W FormManager: Network not available. Please check & try again.
,08-29 13:12:34.626  7044  7044 D PanService: Received start request. Starting profile...
08-29 13:12:34.626  7044  7044 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 13:12:34.626  7044  7044 I bluedroid-qcom: get_profile_interface pan
08-29 13:12:34.629  7017  7596 V FormManager: Network unavailable.
08-29 13:12:34.632  7044  7044 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-29 13:12:34.632  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:34.633  7044  7044 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-29 13:12:34.634  7268  7268 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:12:34
08-29 13:12:34.636  7017  7596 V FormManager: Network unavailable.
08-29 13:12:34.636  7268  7268 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-29 13:12:34.636  7268  7268 D Weather.Utils: 2 : All the weather widget is gone.
08-29 13:12:34.637  7268  7268 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-29 13:12:34.637  7268  7268 D WeatherAncestor: connectivity changed - connection : true
08-29 13:12:34.637  7268  7268 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@b4ab6af
08-29 13:12:34.637  7268  7268 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-29 13:12:34.637  7268  7268 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-29 13:12:34.637  7268  7268 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-29 13:12:34.637  7268  7268 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-29 13:12:34.638  7268  7268 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:12:34
08-29 13:12:34.638  7044  7044 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 13:12:34.638  7044  7044 D BtGatt.GattService: Received start request. Starting profile...
08-29 13:12:34.638  7044  7044 D BtGatt.GattService: start()
08-29 13:12:34.638  7044  7044 I bluedroid-qcom: get_profile_interface gatt
08-29 13:12:34.638  7044  7044 D BtGatt.AdvertiseManager: advertise manager created
08-29 13:12:34.644  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:34.645  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
,08-29 13:12:34.646  7044  7044 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-29 13:12:34.646  7044  7044 V BluetoothMapService: BluetoothMapBinder()
08-29 13:12:34.647  7044  7044 D BluetoothMapService: Received start request. Starting profile...
08-29 13:12:34.647  7044  7044 D BluetoothMapService: start()
08-29 13:12:34.651  7044  7044 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-29 13:12:34.651  7044  7044 D BluetoothMapEmailAppObserver: createReceiver()
08-29 13:12:34.652  7044  7044 D BluetoothMapEmailAppObserver: initObservers()
08-29 13:12:34.652  7044  7044 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 13:12:34.659  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
,08-29 13:12:34.662  7044  7044 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 13:12:34.664  7044  7044 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 13:12:34.666  7044  7044 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 13:12:34.668  7044  7044 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 13:12:34.668  7044  7044 V PanService: [BTUI] SIM Extra State :ABSENT
08-29 13:12:34.671  7044  7044 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 13:12:34.671  7044  7044 V BluetoothMapService: Handler(): got msg=1
,08-29 13:12:34.672  7044  7530 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 13:12:34.673  7044  7530 I bluedroid-qcom: enable
08-29 13:12:34.673  7044  7600 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 13:12:34.673  7044  7530 I bt_hci_bdroid: init
08-29 13:12:34.674  7044  7044 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:34.674  7044  7530 I bt_vendor: bt-vendor : init
08-29 13:12:34.674  7044  7530 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 13:12:34.674  7044  7530 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 13:12:34.674  7044  7530 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 13:12:34.674  7044  7530 D bt_userial_mct: userial_init
08-29 13:12:34.674  7044  7600 I bt-btu  : btu_task pending for preload complete event
08-29 13:12:34.674  7044  7530 D bt_hci_bdroid: set_power 1
08-29 13:12:34.674  7044  7530 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 13:12:34.674  7044  7530 I bt_vendor: Starting hciattach daemon
08-29 13:12:34.674  7044  7530 I bt_vendor: try to set true
08-29 13:12:34.676  7044  7044 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 13:12:34.676  7044  7044 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 13:12:34.676  7044  7044 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 13:12:34.676  7044  7044 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:34.676  7044  7044 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 13:12:34.668  7603  7603 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:34.668  7603  7603 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:34.707  7604  7604 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 13:12:34.731  1043  1764 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7606 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-29 13:12:34.752   357   357 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 453us total 21.357ms
,08-29 13:12:34.773   357   357 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 420us total 20.837ms
08-29 13:12:34.785  7627  7627 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 13:12:34.792   357   357 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 372us total 18.632ms
08-29 13:12:34.796  7606  7606 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 13:12:34.803  7628  7628 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 13:12:34.812  1043  1764 I ActivityManager: Killing 6625:com.android.vending/u0a44 (adj 15): empty #17
08-29 13:12:34.825  7630  7630 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 13:12:34.835  7631  7631 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 13:12:34.846  7632  7632 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-29 13:12:34.858  7633  7633 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 13:12:34.880  1043  2022 W libprocessgroup: failed to open /acct/uid_10044/pid_6625/cgroup.procs: No such file or directory
,08-29 13:12:34.895  7635  7635 I libmdmdetect: ESOC framework not supported
08-29 13:12:34.896  7635  7635 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 13:12:34.906  7635  7635 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-29 13:12:34.906  7635  7635 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 13:12:34.906  7635  7635 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 13:12:34.906  7635  7635 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 13:12:34.906  7635  7635 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 13:12:34.906  7635  7635 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 13:12:34.906  7635  7635 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 13:12:34.945  7635  7636 E QC-QMI  : qmi_client [7635] 14: failed to locate client data
,08-29 13:12:34.950   474   474 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-29 13:12:34.950   474   474 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-29 13:12:34.989  7637  7637 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 13:12:35.015  7638  7638 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 13:12:35.077  7044  7530 I bt_vendor: bluetooth satus is on
08-29 13:12:35.077  7044  7530 D bt_hci_bdroid: preload
08-29 13:12:35.077  7044  7602 D bt_userial_mct: userial_open(port:0)
08-29 13:12:35.078  7044  7602 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-29 13:12:35.081  7044  7602 I bt_vendor: Done intiailizing UART
,08-29 13:12:35.082  7044  7602 I bt_vendor: Done intiailizing UART
08-29 13:12:35.082  7044  7602 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 13:12:35.082  7044  7602 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 13:12:35.083  7044  7600 I bt-btu  : btu_task received preload complete event
08-29 13:12:35.083  7044  7643 D bt_userial_mct: Entering userial_read_thread()
08-29 13:12:35.084  7044  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 13:12:35.084  7044  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 13:12:35.087  7044  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-29 13:12:35.090  7044  7600 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 13:12:35.090  7044  7600 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 13:12:35.090  7044  7600 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 13:12:35.090  7044  7600 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 13:12:35.090  7044  7600 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 13:12:35.090  7044  7600 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 13:12:35.090  7044  7600 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 13:12:35.090  7044  7600 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 13:12:35.091  7044  7600 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 13:12:35.091  7044  7600 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 13:12:35.091  7044  7600 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 13:12:35.091  7044  7600 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 13:12:35.091  7044  7600 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 13:12:35.091  7044  7600 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 13:12:35.091  7044  7600 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 13:12:35.091  7044  7600 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 13:12:35.194  7044  7600 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-29 13:12:35.194  7044  7600 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0209061 
,08-29 13:12:35.194  7044  7600 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0209061 
,08-29 13:12:35.247  7044  7534 E bt-btif : Calling BTA_HhEnable
,08-29 13:12:35.247  7044  7534 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-29 13:12:35.248  7044  7534 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 13:12:35.258  7044  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 13:12:35.258  7044  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 13:12:35.258  7044  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-29 13:12:35.259  7044  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 13:12:35.259  7044  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 13:12:35.262  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 13:12:35.265  7044  7534 D BluetoothAdapterProperties: Name is: G3
08-29 13:12:35.268  7044  7534 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:12:35.268  7044  7534 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:12:35.268  7044  7534 D bt_hci_bdroid: postload
,08-29 13:12:35.270  7044  7602 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 13:12:35.271  7044  7534 D bte_conf: Device ID record 1 : primary
08-29 13:12:35.271  7044  7534 D bte_conf:   vendorId            = 00c4
08-29 13:12:35.271  7044  7534 D bte_conf:   vendorIdSource      = 0001
08-29 13:12:35.271  7044  7534 D bte_conf:   product             = 13a1
08-29 13:12:35.271  7044  7534 D bte_conf:   version             = 1000
08-29 13:12:35.271  7044  7534 D bte_conf:   clientExecutableURL = 
08-29 13:12:35.271  7044  7534 D bte_conf:   serviceDescription  = 
08-29 13:12:35.271  7044  7534 D bte_conf:   documentationURL    = 
08-29 13:12:35.271  7044  7534 D bte_conf: bte_load_did_conf no section named DID2.
08-29 13:12:35.272  7044  7600 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 13:12:35.274  7044  7602 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 13:12:35.277  7044  7530 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 13:12:35.277  7044  7530 D BluetoothAdapterProperties: ScanMode =  20
08-29 13:12:35.277  7044  7530 D BluetoothAdapterProperties: State =  11
08-29 13:12:35.277  7044  7530 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 13:12:35.277  7044  7530 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 13:12:35.277  7044  7530 D BluetoothAdapterProperties: Setting state to 12
08-29 13:12:35.277  7044  7530 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 13:12:35.278  7044  7534 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 13:12:35.279  7044  7534 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 13:12:35.268  7651  7651 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 13:12:35.278  7651  7651 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:35.290  1043  1120 D BluetoothManagerService: Message: 60
08-29 13:12:35.290  1043  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 13:12:35.290  1043  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-29 13:12:35.292  7044  7530 I BluetoothAdapterState: Entering On State
08-29 13:12:35.300  7044  7602 D bt_hci_bdroid: Used up Tx Cmd credits
,08-29 13:12:35.304  7044  7602 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 13:12:35.307  7044  7643 E bt_mct  : hci lib postload completed
08-29 13:12:35.309  7044  7530 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 13:12:35.310  7044  7530 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 13:12:35.310  7044  7530 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-29 13:12:35.313  7044  7530 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-29 13:12:35.315  7044  7600 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:12:35.315  7044  7600 W bt-smp  : Plain text(LSB ~ MSB) = 9d 8c 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 13:12:35.315  7044  7600 W bt-smp  : Encrypted text(LSB ~ MSB) = eb 71 0d 27 86 a5 76 19 db 5b 14 7f c2 b5 96 2c 
08-29 13:12:35.316  7044  7600 W bt-btm  : Stopping oneshot timer
08-29 13:12:35.326  1843  1859 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:12:35.343  7044  7530 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-29 13:12:35.349  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 13:12:35.360  7044  7600 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:12:35.361  7044  7600 W bt-smp  : Plain text(LSB ~ MSB) = 87 92 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 13:12:35.361  7044  7600 W bt-smp  : Encrypted text(LSB ~ MSB) = 39 15 1f a2 b4 ef 5c 70 a2 fb e8 4c 29 0c df 90 
,08-29 13:12:35.363  7044  7600 W bt-btm  : Stopping oneshot timer
08-29 13:12:35.364  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:35.364  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:35.364  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:35.364  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:35.364  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:35.364  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:35.364  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:35.364  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:35.365  7044  7534 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:12:35.366  7044  7534 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-29 13:12:35.366  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:35.378  7044  7600 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:12:35.378  7044  7600 W bt-smp  : Plain text(LSB ~ MSB) = 2a 1f 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 13:12:35.378  7044  7600 W bt-smp  : Encrypted text(LSB ~ MSB) = 27 42 f8 ad 69 e2 00 dc c3 b0 4e 54 d6 14 43 ea 
,08-29 13:12:35.381  7044  7600 W bt-btm  : Stopping oneshot timer
08-29 13:12:35.382  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:35.382  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:35.382  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:35.382  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:35.382  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:35.382  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:35.382  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:35.382  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:35.385  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:35.398  7044  7600 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:12:35.398  7044  7600 W bt-smp  : Plain text(LSB ~ MSB) = b1 2e 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 13:12:35.398  7044  7600 W bt-smp  : Encrypted text(LSB ~ MSB) = fd a8 21 6d bb a4 ce 93 13 da 1f c2 0e 6a 11 1a 
,08-29 13:12:35.401  7044  7600 W bt-btm  : Stopping oneshot timer
08-29 13:12:35.409  1843  2420 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:35.413  1843  1843 D BluetoothHeadset: Proxy object connected
,08-29 13:12:35.427  1843  1843 D BluetoothHeadset: Proxy object connected
,08-29 13:12:35.435  7669  7669 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-29 13:12:35.436  7044  7600 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:12:35.436  7044  7600 W bt-smp  : Plain text(LSB ~ MSB) = 32 cd 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 13:12:35.436  7044  7600 W bt-smp  : Encrypted text(LSB ~ MSB) = 2f b3 72 62 dc f8 67 54 a2 6e 55 67 8b aa 8c 8c 
08-29 13:12:35.436  7044  7600 W bt-btm  : Stopping oneshot timer
08-29 13:12:35.438  6928  6944 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:12:35.442  6928  6928 D BluetoothInputDevice: Proxy object connected
08-29 13:12:35.442  6928  6928 D HidProfile: Bluetooth service connected
08-29 13:12:35.443  6928  6943 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 13:12:35.446  1043  1120 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:12:35.448  1043  1043 D BluetoothA2dp: Proxy object connected
08-29 13:12:35.449  1843  1858 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:35.451  1043  1113 W ProcessCpuTracker: Skipping unknown process pid 7651
08-29 13:12:35.451  1043  1113 W ProcessCpuTracker: Skipping unknown process pid 7655
08-29 13:12:35.452  1843  1843 D BluetoothHeadset: Proxy object connected
08-29 13:12:35.453  6928  6944 D BluetoothPan: onBluetoothStateChange on: true
08-29 13:12:35.453  6928  6944 D BluetoothPan: onBluetoothStateChange call bindService
,08-29 13:12:35.456  6928  6943 D BluetoothMap: onBluetoothStateChange: up=true
08-29 13:12:35.457  6928  6928 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 13:12:35.457  6928  6928 D PanProfile: Bluetooth service connected
08-29 13:12:35.459  1043  1120 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:35.459  1043  1043 D BluetoothHeadset: Proxy object connected
08-29 13:12:35.462  1043  1120 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 13:12:35.462  1043  1120 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-29 13:12:35.462  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 13:12:35.464  1931  1931 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:35.464  6928  6928 D BluetoothMap: Proxy object connected
08-29 13:12:35.464  6928  6928 D MapProfile: Bluetooth service connected
08-29 13:12:35.464  6928  6928 D BluetoothMap: getConnectedDevices()
08-29 13:12:35.464  1931  2094 D LGBluetoothAPIService: Message: 1
08-29 13:12:35.464  1931  2094 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 13:12:35.465  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 13:12:35.466  7044  7535 V BluetoothMapService: getConnectedDevices()
08-29 13:12:35.467  1043  1120 D BluetoothManagerService: Message: 40
08-29 13:12:35.467  1043  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-29 13:12:35.470  7044  7044 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:35.470  7044  7044 D BluetoothMapService: STATE_ON
08-29 13:12:35.472  6705  6705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-29 13:12:35.475  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:35.476  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:35.476  1931  2094 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-29 13:12:35.477  6928  6928 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 13:12:35.479  1043  1120 D BluetoothManagerService: Message: 30
08-29 13:12:35.481  6928  6928 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-29 13:12:35.483  1043  1120 D BluetoothManagerService: Message: 30
,08-29 13:12:35.484  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:35.484  7044  7044 V BluetoothPbapService: Pbap Service onCreate
08-29 13:12:35.484  7044  7044 V BluetoothPbapService: Starting PBAP service
08-29 13:12:35.486  7044  7044 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 13:12:35.486  7044  7044 V BluetoothMapService: Handler(): got msg=1
08-29 13:12:35.487  7044  7044 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 13:12:35.488  7044  7044 V BluetoothPbapService: Pbap Service onBind
08-29 13:12:35.488  7044  7675 D BluetoothMapMasInstance: MAS initSocket()
08-29 13:12:35.488  7044  7675 D BluetoothMapMasInstance:   masId = 00
08-29 13:12:35.488  7044  7675 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 13:12:35.488  7044  7675 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 13:12:35.488  7044  7675 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 13:12:35.489  7044  7044 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:35.489  7044  7044 V BluetoothPbapService: state: 12
08-29 13:12:35.491  7044  7044 D LGBluetoothAPIServer: [BTUI] onCreate()
08-29 13:12:35.492  1043  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:35.493  7044  7044 D LGBluetoothAPIServer: [BTUI] onBind()
08-29 13:12:35.494  7044  7675 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:12:35.495  7044  7675 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 13:12:35.495  7044  7675 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 13:12:35.495  7044  7675 D BluetoothMapMasInstance: Accepting socket connection...
08-29 13:12:35.594  1043  1986 I art     : Explicit concurrent mark sweep GC freed 94034(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.574ms total 100.936ms
08-29 13:12:35.594  1931  1931 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-29 13:12:35.594  1931  2094 D LGBluetoothAPIService: Message: 100
08-29 13:12:35.594  1931  2094 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 13:12:35.595  7044  7044 V BluetoothPbapService: Handler(): got msg=1
08-29 13:12:35.595  7044  7044 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-29 13:12:35.597  7044  7534 D BluetoothAdapterProperties: Scan Mode:21
08-29 13:12:35.597  7044  7534 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 13:12:35.598  7044  7677 V BluetoothPbapService: Pbap Service initSocket
08-29 13:12:35.600  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:35.604  1043  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:35.606  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:35.607  7044  7677 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:12:35.608  7044  7677 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 13:12:35.608  7044  7677 V BluetoothPbapService: Succeed to create listening socket 
08-29 13:12:35.608  7044  7677 V BluetoothPbapService: Accepting socket connection...
08-29 13:12:35.609  6928  6928 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 13:12:35.610  6928  6928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 13:12:35.612  6928  6928 D BluetoothA2dp: Proxy object connected
08-29 13:12:35.612  6928  6928 D A2dpProfile: Bluetooth service connected
,08-29 13:12:35.614  7044  7044 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 13:12:35.614  7044  7044 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:35.614  7044  7044 V BluetoothPbapReceiver: ***********state = 12
08-29 13:12:35.615  6928  6928 D BluetoothPbap: Proxy object connected
08-29 13:12:35.615  6928  6928 D PbapServerProfile: Bluetooth service connected
08-29 13:12:35.615  6928  6928 D BluetoothHeadset: Proxy object connected
08-29 13:12:35.616  6928  6928 D HeadsetProfile: Bluetooth service connected
08-29 13:12:35.617  7327  7351 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-29 13:12:35.620  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:12:35.621  2186  2186 D c       : Getting all permits...
08-29 13:12:35.621  6928  6928 D DockEventReceiver: finishStartingService: stopping service
08-29 13:12:35.621  2186  2186 D a       : Opening database...
,08-29 13:12:35.626  2186  2186 D a       : Opening database auth.proximity.permit_store...
08-29 13:12:35.627  2186  2186 D a       : Closing database...
08-29 13:12:35.637  6928  6928 D BluetoothPermissionRequest: onReceive
,08-29 13:12:35.638  6928  6928 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 13:12:35.639  6928  6928 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 13:12:35.642  7044  7044 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 13:12:35.643  7044  7044 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 13:12:35.649  7044  7044 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 13:12:35.663   323  7257 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-29 13:12:35.665  1043  7229 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.SocketException: Binding socket to network 101 failed: errno 64 (Machine is not on the network)
08-29 13:12:35.665  1043  7229 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4s442ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:35.665  1043  7229 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4s442ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:35.665  1043  7229 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 13:12:35.668  7044  7044 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-29 13:12:35.669  7044  7044 V BtOppService: onCreate
08-29 13:12:35.673  7044  7044 V BluetoothOppNotification: send message
08-29 13:12:35.677  7044  7044 V BtOppService: Starting RfcommListener
,08-29 13:12:35.681  7044  7044 D BluetoothOppPreference: Dumping Names:  
08-29 13:12:35.681  7044  7044 D BluetoothOppPreference: {}
08-29 13:12:35.681  7044  7044 D BluetoothOppPreference: Dumping Channels:  
08-29 13:12:35.681  7044  7044 D BluetoothOppPreference: {}
08-29 13:12:35.683  7044  7044 V BtOppService: onStartCommand
08-29 13:12:35.685  7044  7687 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 13:12:35.694  7044  7044 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:35.695  7044  7044 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 13:12:35.695  7044  7684 V BtOppService: Deleted complete outbound shares, number =  0
08-29 13:12:35.698  7044  7684 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 13:12:35.698  7044  7684 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 13:12:35.698  7044  7687 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 13:12:35.700  7044  7684 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23100438 on behalf of 
08-29 13:12:35.701  7044  7044 V BluetoothOppNotification: new notify threadi!
08-29 13:12:35.702  7044  7044 V BluetoothOppNotification: send delay message
08-29 13:12:35.703  7044  7687 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a6b0c11 on behalf of 
08-29 13:12:35.704  7044  7044 V BtOppService: start RfcommListener
08-29 13:12:35.705  7044  7688 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 13:12:35.706  7044  7687 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 13:12:35.706  7044  7687 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-29 13:12:35.707  7044  7688 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33678176 on behalf of 
08-29 13:12:35.708  7044  7687 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c84377 on behalf of 
08-29 13:12:35.708  7044  7688 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-29 13:12:35.710  7044  7687 V BluetoothOppNotification: update too frequent, put in queue
08-29 13:12:35.711  7044  7044 V BtOppService: RfcommListener started
08-29 13:12:35.711  7044  7044 V BtOppService: ContentObserver received notification
08-29 13:12:35.711  7044  7044 V BtOppService: ContentObserver received notification
08-29 13:12:35.712  7044  7687 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 13:12:35.712  7044  7689 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 13:12:35.713  7044  7687 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 13:12:35.713  1043  1895 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:35.714  7044  7688 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 13:12:35.714  7044  7689 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:12:35.716  7044  7689 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-29 13:12:35.716  7044  7689 V BtOppRfcommListener: Started RFCOMM listener....
08-29 13:12:35.716  7044  7689 I BtOppRfcommListener: Accept thread started.
08-29 13:12:35.716  7044  7689 V BtOppRfcommListener: Accepting connection...
08-29 13:12:35.718  7044  7687 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5dd2be4 on behalf of 
08-29 13:12:35.719  7044  7687 V BluetoothOppNotification: update too frequent, put in queue
08-29 13:12:35.720  7044  7688 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38e3584d on behalf of 
,08-29 13:12:35.721  7044  7687 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-29 13:12:35.723  7044  7688 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 13:12:35.726  7044  7688 V BluetoothOppNotification: outbound notification was removed.
08-29 13:12:35.726  7044  7688 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-29 13:12:35.728  7044  7688 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16423f02 on behalf of 
08-29 13:12:35.729  7044  7688 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-29 13:12:35.730  7044  7688 V BluetoothOppNotification: inbound notification was removed.
08-29 13:12:35.730  7044  7688 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 13:12:35.731  7044  7688 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26f3a013 on behalf of 
08-29 13:12:35.734  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:35.734  7044  7044 V BluetoothFtpService: Ftp Service onCreate
08-29 13:12:35.734  7044  7044 I BluetoothFtpService: Ftp Service onCreate
08-29 13:12:35.734  7044  7044 V BluetoothFtpService: Ftp Service onStartCommand
08-29 13:12:35.735  7044  7044 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:35.735  7044  7044 V BluetoothFtpService: Starting Listening on sockets
08-29 13:12:35.735  7044  7044 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-29 13:12:35.735  7044  7044 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 13:12:35.735  7044  7044 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 13:12:35.735  7044  7044 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:35.735  7044  7044 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-29 13:12:35.735  7044  7044 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 13:12:35.738  7044  7044 V BluetoothFtpService: Handler(): got msg=1
08-29 13:12:35.738  7044  7044 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 13:12:35.739  7044  7044 V BluetoothFtpService: Ftp Service initSocket
08-29 13:12:35.741  1043  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:35.741  7044  7044 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:12:35.747  7044  7044 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-29 13:12:35.747  7044  7044 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-29 13:12:35.750  7044  7690 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-29 13:12:35.762  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:35.762  7044  7044 V BluetoothSapService: Sap Service onCreate
,08-29 13:12:35.764  7044  7044 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:35.764  7044  7044 V BluetoothSapService: state: 12
08-29 13:12:35.764  7044  7044 V BluetoothSapService: Starting SAP server process
08-29 13:12:35.766  7044  7044 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 13:12:35.758  7691  7691 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:35.758  7691  7691 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:35.769  7044  7692 V BluetoothSapService: Sap Service initRfcommSocket
08-29 13:12:35.769  1043  1764 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:35.772  7044  7692 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:12:35.774  7044  7692 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-29 13:12:35.774  7044  7692 V BluetoothSapService: Succeed to create listening socket 
08-29 13:12:35.774  7044  7692 V BluetoothSapService: Accepting socket connection...
,08-29 13:12:35.780  7691  7691 V BT_SAP  : Event pipe created
08-29 13:12:35.781  7691  7691 V BT_SAP  : create_server_socket qcom.sap.server
08-29 13:12:35.781  7691  7691 V BT_SAP  : created socket fd 6
,08-29 13:12:36.166  1043  1378 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:36.166  1043  1378 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:12:36.212  1043  1428 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 13:12:36.213  1043  1428 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-29 13:12:36.428  1043  1764 I ActivityManager: Killing 7452:com.lge.bnr/1000 (adj 15): empty #17
,08-29 13:12:36.460  1043  1764 I ActivityManager: Killing 6846:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-29 13:12:36.480  6979  6979 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-29 13:12:36.481  6979  6979 W System.err: android.os.DeadObjectException
08-29 13:12:36.481  6979  6979 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 13:12:36.481  6979  6979 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 13:12:36.481  6979  6979 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-29 13:12:36.481  6979  6979 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-29 13:12:36.481  6979  6979 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 13:12:36.481  6979  6979 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 13:12:36.481  6979  6979 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:12:36.481  6979  6979 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:12:36.481  6979  6979 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 13:12:36.481  6979  6979 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 13:12:36.481  6979  6979 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:36.481  6979  6979 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:36.481  6979  6979 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 13:12:36.481  6979  6979 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 13:12:36.482  6979  6979 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-29 13:12:36.482  6979  6979 W System.err: android.os.DeadObjectException
08-29 13:12:36.482  6979  6979 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 13:12:36.482  6979  6979 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 13:12:36.482  6979  6979 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-29 13:12:36.482  6979  6979 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-29 13:12:36.482  6979  6979 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-29 13:12:36.482  6979  6979 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-29 13:12:36.482  6979  6979 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:12:36.482  6979  6979 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:12:36.483  6979  6979 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 13:12:36.483  6979  6979 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 13:12:36.483  6979  6979 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:36.483  6979  6979 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:36.483  6979  6979 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 13:12:36.483  6979  6979 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-29 13:12:36.483  6979  6979 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,08-29 13:12:36.490  6979  6979 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-29 13:12:36.494  1043  2023 W libprocessgroup: failed to open /acct/uid_1000/pid_7452/cgroup.procs: No such file or directory
08-29 13:12:36.497  1043  1060 W libprocessgroup: failed to open /acct/uid_1000/pid_6846/cgroup.procs: No such file or directory
08-29 13:12:36.498  1043  1060 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-29 13:12:36.505  6979  6979 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-29 13:12:36.505  6979  6979 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 13:12:36.556  1043  1986 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7702 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 13:12:36.578  6979  6979 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-29 13:12:36.641  7702  7702 D UEI.SmartControl: Quickset Services start...
,08-29 13:12:36.646  7702  7702 I UEI.SmartControl: Manufacture = LGE
,08-29 13:12:36.646  7702  7702 D UEI.SmartControl: Id = LGNevo
08-29 13:12:36.649  7702  7702 D UEI.SmartControl: File observer start...
08-29 13:12:36.651  7702  7702 E UEI.SmartControl: IR Port is disabled: false
08-29 13:12:36.651  7702  7702 D UEI.SmartControl: Starting file observer...
08-29 13:12:36.652  7702  7702 D UEI.SmartControl: Extracting JNI libs...
08-29 13:12:36.652  7702  7702 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-29 13:12:36.704  7044  7044 V BluetoothOppNotification: new notify threadi!
08-29 13:12:36.704  7044  7044 V BluetoothOppNotification: send delay message
,08-29 13:12:36.708  7044  7734 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 13:12:36.714  7044  7734 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37b0137c on behalf of 
08-29 13:12:36.714  7044  7734 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 13:12:36.727  7044  7734 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-29 13:12:36.732  7044  7734 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29d04405 on behalf of 
08-29 13:12:36.734  7044  7734 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 13:12:36.737  7044  7734 V BluetoothOppNotification: outbound notification was removed.
08-29 13:12:36.738  7044  7734 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 13:12:36.740  7044  7734 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2344ac5a on behalf of 
08-29 13:12:36.742  7044  7734 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-29 13:12:36.745  7044  7734 V BluetoothOppNotification: inbound notification was removed.
08-29 13:12:36.745  7044  7734 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-29 13:12:36.747  7044  7734 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@185cfe8b on behalf of 
08-29 13:12:36.768  7702  7702 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-29 13:12:36.768  7702  7702 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-29 13:12:36.768  7702  7702 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-29 13:12:36.810  7702  7702 I UEI.SmartControl: --- Selecting new region: 6
,08-29 13:12:36.812  7702  7702 I UEI.SmartControl: Model = LG-D855
,08-29 13:12:36.814  7702  7702 D UEI.SmartControl: QS Service created
08-29 13:12:36.833  7702  7702 I UEI.SmartControl: Service initServices...
,08-29 13:12:36.839  7702  7702 D UEI.SmartControl: QS start get config
,08-29 13:12:36.913  7702  7702 D UEI.SmartControl: Loading JNI Libs...
,08-29 13:12:37.168  1043  1565 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 13:12:37.168  1043  1565 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2d972c5c mBinding = false
,08-29 13:12:37.194  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 13:12:37.194  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 13:12:37.194  1043  1043 D Ulp_jni : JNI:system_update. Event-4
08-29 13:12:37.196  1043  1120 D BluetoothManagerService: Message: 2
08-29 13:12:37.197  1043  1120 D BluetoothManagerService: Sending off request.
08-29 13:12:37.198  7044  7535 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-29 13:12:37.198  7044  7530 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-29 13:12:37.198  7044  7530 D BluetoothAdapterProperties: Setting state to 13
08-29 13:12:37.198  7044  7530 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 13:12:37.199  1043  1120 D BluetoothManagerService: Message: 60
08-29 13:12:37.199  7044  7530 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 13:12:37.199  1043  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-29 13:12:37.199  1043  1120 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-29 13:12:37.199  7044  7530 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 13:12:37.200  7044  7534 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:12:37.201  7044  7530 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-29 13:12:37.201  1931  1931 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:37.205  7044  7677 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:12:37.205  7044  7530 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 13:12:37.205  7044  7692 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:12:37.206  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-29 13:12:37.207  7044  7689 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:12:37.208  7044  7690 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:12:37.208  7044  7600 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-29 13:12:37.209  7044  7675 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-29 13:12:37.209  7044  7675 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:12:37.209  7044  7675 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-29 13:12:37.209  7044  7675 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-29 13:12:37.209  7044  7675 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-29 13:12:37.209  7044  7675 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-29 13:12:37.209  7044  7675 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-29 13:12:37.209  7044  7675 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-29 13:12:37.216  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:12:37.216  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:12:37.216  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:12:37.216  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:12:37.216  7044  7600 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:37.216  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:12:37.216  7044  7600 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:37.216  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:12:37.216  7044  7600 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:12:37.217  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-29 13:12:37.217  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-29 13:12:37.217  7044  7600 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 13:12:37.219  6928  6928 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-29 13:12:37.221  7044  7044 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:37.221  7044  7044 D BluetoothMapService: STATE_TURNING_OFF
08-29 13:12:37.221  7044  7044 V BtOppService: Receiver DISABLED_ACTION 
08-29 13:12:37.221  7044  7044 V BluetoothMapService: Handler(): got msg=4
08-29 13:12:37.221  7044  7044 D BluetoothMapService: MAP Service closeService in
08-29 13:12:37.222  7044  7044 D BluetoothMapMasInstance: MAP Service shutdown
08-29 13:12:37.222  7044  7044 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 13:12:37.222  7044  7044 V BluetoothMapService: MAP Service closeService out
08-29 13:12:37.223  7044  7044 I BtOppRfcommListener: stopping Accept Thread
08-29 13:12:37.223  7044  7044 V BtOppRfcommListener: close mBtServerSocket
08-29 13:12:37.223  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 13:12:37.223  7044  7044 V BtOppRfcommListener: waiting for thread to terminate
08-29 13:12:37.223  7044  7689 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 13:12:37.224  7044  7044 V BtOppRfcommListener: done waiting for thread to terminate
08-29 13:12:37.228  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:37.229  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:37.229  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:37.229  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:37.229  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:37.229  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:37.229  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:37.229  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:37.229  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:37.231  6928  6928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 13:12:37.232  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:37.232  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:37.237  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:37.237  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:37.237  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:37.237  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:37.237  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:37.237  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:37.237  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:37.237  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:37.237  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:37.237  6705  6705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:37.237  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:37.238  7044  7044 V BtOppService: onDestroy
08-29 13:12:37.243  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:37.250  6928  6928 D DockEventReceiver: finishStartingService: stopping service
08-29 13:12:37.250  7044  7044 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-29 13:12:37.250  7044  7044 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 13:12:37.250  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:37.250  7044  7044 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:37.250  7044  7044 V BluetoothPbapReceiver: ***********state = 13
08-29 13:12:37.254  7044  7044 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-29 13:12:37.258  7044  7044 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:37.259  7044  7044 V BluetoothPbapService: state: 13
08-29 13:12:37.259  7044  7044 V BluetoothPbapService: Pbap Service closeService in
,08-29 13:12:37.263  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:12:37.266  7044  7044 V BluetoothPbapService: successfully stopped pbap service
08-29 13:12:37.266  7044  7044 V BluetoothPbapService: Pbap Service closeService out
08-29 13:12:37.266  6928  6928 D BluetoothPbap: Proxy object disconnected
08-29 13:12:37.266  6928  6928 D PbapServerProfile: Bluetooth service disconnected
08-29 13:12:37.267  7044  7044 V BluetoothPbapService: Pbap Service onDestroy
08-29 13:12:37.267  7044  7044 V BluetoothPbapService: Pbap Service closeService in
08-29 13:12:37.267  7044  7044 V BluetoothPbapService: Pbap Service closeService out
08-29 13:12:37.267  7044  7044 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-29 13:12:37.277  6928  6928 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-29 13:12:37.282  6928  6928 D BluetoothPermissionRequest: onReceive
08-29 13:12:37.283  6928  6928 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-29 13:12:37.288  6928  6928 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 13:12:37.292  7044  7044 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-29 13:12:37.292  7044  7044 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-29 13:12:37.293  7044  7044 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-29 13:12:37.299  7044  7044 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:37.299  7044  7044 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 13:12:37.300  7044  7044 V BluetoothFtpService: Ftp Service onStartCommand
08-29 13:12:37.300  7044  7044 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:37.300  7044  7044 V BluetoothFtpService: Ftp Service closeService
08-29 13:12:37.300  7044  7044 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-29 13:12:37.301  7044  7044 V BluetoothFtpService: successfully stopped ftp service
08-29 13:12:37.301  7044  7044 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 13:12:37.301  7044  7044 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 13:12:37.302  7044  7044 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 13:12:37.302  7044  7044 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:37.302  7044  7044 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-29 13:12:37.302  7044  7044 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-29 13:12:37.303  7044  7044 V BluetoothFtpService: Ftp Service onDestroy
08-29 13:12:37.303  7044  7044 V BluetoothFtpService: Ftp Service closeService
08-29 13:12:37.305  7044  7044 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:37.305  7044  7044 V BluetoothSapService: state: 13
08-29 13:12:37.305  7044  7044 V BluetoothSapService: Stopping SAP server process
08-29 13:12:37.306  7044  7044 V BluetoothSapService: Sap Service closeSapService in
08-29 13:12:37.306  7044  7044 V BluetoothSapService: Close listen Socket : 
08-29 13:12:37.306  7044  7044 V BluetoothSapService: Close rfcomm Socket : 
08-29 13:12:37.306  7044  7044 V BluetoothSapService: Close sapd  Socket : 
08-29 13:12:37.307  7044  7044 V BluetoothSapService: Sap Service closeSapService out
08-29 13:12:37.308  7044  7044 V BluetoothSapService: Sap Service onDestroy
08-29 13:12:37.308  7044  7044 V BluetoothSapService: Sap Service closeSapService in
08-29 13:12:37.308  7044  7044 V BluetoothSapService: Close listen Socket : 
08-29 13:12:37.308  7044  7044 V BluetoothSapService: Close rfcomm Socket : 
08-29 13:12:37.308  7044  7044 V BluetoothSapService: Close sapd  Socket : 
08-29 13:12:37.308  7044  7044 V BluetoothSapService: Sap Service closeSapService out
,08-29 13:12:37.414  7702  7702 I UEI.SmartControl: Supports setup maps: true
,08-29 13:12:37.418  7702  7702 D UEI.SmartControl: QS start statue = true Error code = 0
08-29 13:12:37.418  7702  7702 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-29 13:12:37.418  7702  7702 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-29 13:12:37.418  7702  7702 I UEI.SmartControl: ### init IR Blaster...
08-29 13:12:37.426  7702  7702 D serial_port: Configuring serial port
08-29 13:12:37.438  7702  7702 E UEI.SmartControl: UEIBLaster setting for 616
08-29 13:12:37.438  7702  7702 I UEI.SmartControl: Setting serial record hearder size = 2
,08-29 13:12:37.440  7702  7702 I UEI.SmartControl: configuring settings for MAXQ616
,08-29 13:12:37.440  7702  7702 I UEI.SmartControl: Get version...
08-29 13:12:37.458  7702  7759 D UEI.SmartControl: serial port data available: 21
,08-29 13:12:37.488  7702  7702 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-29 13:12:37.488  7702  7702 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-29 13:12:37.488  7702  7702 I UEI.SmartControl: QS saving settings...
,08-29 13:12:37.491  7702  7702 D UEI.SmartControl: IR Blaster version: 25672567
,08-29 13:12:37.509  7702  7759 D UEI.SmartControl: serial port data available: 4
,08-29 13:12:37.551  7702  7762 I UEI.SmartControl: Device manager: loading config....
,08-29 13:12:37.551  7702  7702 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-29 13:12:37.552  7702  7762 D UEI.SmartControl: ----------- loading internal config...
08-29 13:12:37.556  7702  7702 E UEI.SmartControl: Services init done
08-29 13:12:37.556  7702  7702 D UEI.SmartControl: QS Service init finished
08-29 13:12:37.559  7702  7702 D UEI.SmartControl: QS Service version name: 2.1.91
08-29 13:12:37.559  7702  7702 D UEI.SmartControl: QS Service version code: 201091
08-29 13:12:37.561  7702  7702 D UEI.SmartControl: Service requested: Control
08-29 13:12:37.570  7702  7762 E UEI.SmartControl: Loading SETTINGS...
,08-29 13:12:37.574  7702  7702 D UEI.SmartControl: Request IControl service: devices are loaded...
08-29 13:12:37.581  6979  6979 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-29 13:12:37.582  7702  7717 I UEI.SmartControl: ------ IControl API: 11
08-29 13:12:37.582  1043  1061 I ActivityManager: Killing 6979:com.lge.qremote/u0a112 (adj 15): empty #17
08-29 13:12:37.584  7702  7717 I UEI.SmartControl: Registering callback...
08-29 13:12:37.589  7702  7762 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-29 13:12:37.605  7702  7761 I UEI.SmartControl: Notify AllClients services are ready: 0
08-29 13:12:37.605  7702  7761 D UEI.SmartControl: -----service ready thread exits
,08-29 13:12:37.676  1043  1949 W libprocessgroup: failed to open /acct/uid_10112/pid_6979/cgroup.procs: No such file or directory
08-29 13:12:37.677  7702  7702 D UEI.SmartControl: Internal service binding...
,08-29 13:12:38.121  7044  7534 D bt_hci_bdroid: cleanup
,08-29 13:12:38.131  7044  7643 I bt_userial_mct: exiting userial_read_thread
08-29 13:12:38.132  7044  7602 I bt_lpm  : LPM is already off!!!
08-29 13:12:38.134  7044  7643 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 13:12:38.135  7044  7600 W bt-btif : ag scb idx 1 not allocated
08-29 13:12:38.135  7044  7600 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 13:12:38.135  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:12:38.135  7044  7600 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:38.135  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:12:38.135  7044  7600 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:38.135  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:12:38.135  7044  7600 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:12:38.135  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:12:38.135  7044  7600 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:38.135  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:12:38.136  7044  7600 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:38.136  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:12:38.136  7044  7600 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:12:38.136  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-29 13:12:38.136  7044  7600 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:38.136  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-29 13:12:38.137  7044  7600 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:38.137  7044  7600 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-29 13:12:38.137  7044  7600 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:12:38.137  7044  7600 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-29 13:12:38.137  7044  7534 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 13:12:38.137  7044  7602 I bt_vendor: hw_epilog_process
08-29 13:12:38.138  7044  7534 D bt_hci_bdroid: cleanup Finalizing cleanup
08-29 13:12:38.138  7044  7534 D bt_userial_mct: userial_close
08-29 13:12:38.138  7044  7534 E bt_userial_mct: pthread_join() FAILED result:3
08-29 13:12:38.138  7044  7534 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-29 13:12:38.143  7044  7534 D bt_hci_bdroid: set_power 0
08-29 13:12:38.143  7044  7534 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 13:12:38.144  7044  7534 I bt_vendor: bluetooth satus is on
08-29 13:12:38.144  7044  7534 I bt_vendor: bt-vendor : resetting BT status
08-29 13:12:38.144  7044  7534 I bt_vendor: Starting hciattach daemon
08-29 13:12:38.144  7044  7534 I bt_vendor: try to set false
,08-29 13:12:38.149  7044  7534 I bt_vendor: Starting hciattach daemon
08-29 13:12:38.149  7044  7534 I bt_vendor: try to set false
08-29 13:12:38.150  7044  7534 I bt_vendor: cleanup
08-29 13:12:38.150  7044  7600 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 13:12:38.152  7044  7534 I GKI_LINUX: GKI_exit_task 0 done
08-29 13:12:38.152  7044  7534 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 13:12:38.153  7044  7530 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 13:12:38.158  7044  7044 D HeadsetService: Received stop request...Stopping profile...
,08-29 13:12:38.162  7044  7044 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 13:12:38.162  7044  7044 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:12:38.162  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:38.162  7044  7552 D HeadsetStateMachine: Exit Disconnected: -1
08-29 13:12:38.169  1843  1843 D BluetoothHeadset: Proxy object disconnected
08-29 13:12:38.169  1843  1843 D BluetoothHeadset: Proxy object disconnected
08-29 13:12:38.169  1843  1843 D BluetoothHeadset: Proxy object disconnected
08-29 13:12:38.170  1043  1043 D BluetoothHeadset: Proxy object disconnected
08-29 13:12:38.170  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-29 13:12:38.174  7044  7044 D A2dpService: Received stop request...Stopping profile...
08-29 13:12:38.176  7044  7586 D A2dpStateMachine: Exit Disconnected: -1
08-29 13:12:38.177  7044  7530 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 13:12:38.178  7044  7044 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-29 13:12:38.180  7044  7044 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-29 13:12:38.180  7044  7044 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:12:38.180  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:38.182  1043  1043 D BluetoothA2dp: Proxy object disconnected
08-29 13:12:38.182  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-29 13:12:38.184  7044  7044 D HidService: Received stop request...Stopping profile...
08-29 13:12:38.184  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:38.187  7044  7044 D HealthService: Received stop request...Stopping profile...
08-29 13:12:38.187  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:38.189  7044  7044 D HeadsetStateMachine: Unbinding service...
08-29 13:12:38.190  7044  7044 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 13:12:38.190  7044  7044 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 13:12:38.190  7044  7044 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 13:12:38.190  7044  7044 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 13:12:38.191  7044  7044 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 13:12:38.191  7044  7044 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:12:38.191  7044  7044 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-29 13:12:38.192  7044  7044 D PanService: Received stop request...Stopping profile...
08-29 13:12:38.193  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:38.194  7044  7044 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 13:12:38.197  7044  7044 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 13:12:38.197  7044  7044 D BtGatt.GattService: stop()
08-29 13:12:38.197  7044  7044 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 13:12:38.199  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:38.201  7044  7044 D BluetoothMapService: Received stop request...Stopping profile...
08-29 13:12:38.201  7044  7044 D BluetoothMapService: stop()
08-29 13:12:38.202  7044  7044 D BluetoothMapEmailAppObserver: deinitObservers()
08-29 13:12:38.202  7044  7044 D BluetoothMapEmailAppObserver: removeReceiver()
08-29 13:12:38.203  7044  7044 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b4ab6af
08-29 13:12:38.204  7044  7044 I BluetoothA2dpServiceJni: cleanupNative
08-29 13:12:38.204  7044  7588 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 13:12:38.206  7044  7044 I GKI_LINUX: GKI_exit_task 2 done
08-29 13:12:38.206  7044  7044 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 13:12:38.206  7044  7044 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 13:12:38.206  7044  7044 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 13:12:38.206  7044  7044 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-29 13:12:38.209  7044  7044 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:12:38.209  7044  7044 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:12:38.210  7044  7044 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 13:12:38.210  7044  7044 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 13:12:38.212  7044  7044 V BluetoothMapService: Handler(): got msg=4
08-29 13:12:38.212  7044  7044 D BluetoothMapService: MAP Service closeService in
08-29 13:12:38.212  7044  7044 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 13:12:38.212  7044  7044 V BluetoothMapService: MAP Service closeService out
08-29 13:12:38.214  7044  7530 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-29 13:12:38.214  7044  7530 D BluetoothAdapterProperties: Setting state to 10
08-29 13:12:38.214  7044  7530 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 13:12:38.214  7044  7044 D BluetoothMapService: cleanup()
08-29 13:12:38.215  7044  7044 D BluetoothMapService: MAP Service closeService in
08-29 13:12:38.215  7044  7044 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-29 13:12:38.215  7044  7044 V BluetoothMapService: MAP Service closeService out
08-29 13:12:38.216  1043  1120 D BluetoothManagerService: Message: 60
08-29 13:12:38.216  1043  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-29 13:12:38.216  1043  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-29 13:12:38.216  7044  7530 I BluetoothAdapterState: Entering OffState
08-29 13:12:38.216  1843  2420 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:38.217  1843  1858 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:38.218  6928  6944 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 13:12:38.224  6928  6944 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 13:12:38.225  6928  6944 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 13:12:38.226  6928  6944 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:12:38.226  1043  1120 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:12:38.227  1843  2434 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:38.227  6928  6944 D BluetoothPan: onBluetoothStateChange on: false
08-29 13:12:38.228  6928  6944 D BluetoothMap: onBluetoothStateChange: up=false
08-29 13:12:38.228  1043  1120 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:38.229  1043  1120 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-29 13:12:38.229  1043  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-29 13:12:38.231  1043  1120 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-29 13:12:38.231  1043  1120 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-29 13:12:38.231  1043  1120 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2d972c5c mBinding = false
,08-29 13:12:38.234  1043  1120 D BluetoothManagerService: Sending unbind request.
08-29 13:12:38.238  7044  7534 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-29 13:12:38.240  7044  7044 I GKI_LINUX: GKI_exit_task 1 done
08-29 13:12:38.240  7044  7044 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 13:12:38.240  7044  7044 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 13:12:38.240  7044  7044 I art     : --- WEIRD: removing null entry 248
08-29 13:12:38.240  7044  7044 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-29 13:12:38.240  7044  7044 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-29 13:12:38.241  7044  7044 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-29 13:12:38.243  1043  1120 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-29 13:12:38.246  7044  7044 I art     : System.exit called, status: 0
08-29 13:12:38.246  7044  7044 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 13:12:38.267   327  1384 V AudioFlinger: 7044 died, releasing its sessions
08-29 13:12:38.267   327  1384 V AudioFlinger:  pid 1843 @ 0
08-29 13:12:38.267   327  1384 V AudioFlinger:  pid 3228 @ 1
08-29 13:12:38.267   327  1384 V AudioFlinger:  pid 3228 @ 2
,08-29 13:12:38.270  1931  1931 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-29 13:12:38.271  1931  2094 D LGBluetoothAPIService: Message: 101
08-29 13:12:38.271  1931  2094 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-29 13:12:38.271  1931  2094 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-29 13:12:38.271  1931  2094 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-29 13:12:38.273  6928  6928 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-29 13:12:38.303  1043  1950 I ActivityManager: Process com.android.bluetooth (pid 7044) has died
,08-29 13:12:38.306  1043  1950 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-29 13:12:38.306  1043  1950 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 13999ms
08-29 13:12:38.313  1931  1931 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:38.313  1931  2094 D LGBluetoothAPIService: Message: 2
08-29 13:12:38.313  1931  2094 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-29 13:12:38.314  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 13:12:38.315  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:38.317  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:38.319  6928  6928 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-29 13:12:38.319  6928  6928 D LGBluetoothEventManager: [BTUI] clear device connection state
08-29 13:12:38.323  6928  6928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-29 13:12:38.325  1592  1592 D BluetoothAdapter: 1054278118: getState() :  mService = null. Returning STATE_OFF
08-29 13:12:38.326  1592  1592 D BluetoothAdapter: 1054278118: getState() :  mService = null. Returning STATE_OFF
08-29 13:12:38.385  1043  1895 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7791 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-29 13:12:38.387  6928  6928 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:12:38.450  7791  7791 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 13:12:38.451  7791  7791 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 13:12:38.451  7791  7791 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-29 13:12:38.452  7791  7791 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 13:12:38.472  7791  7791 D BluetoothAdapterApp: Loading JNI Library
,08-29 13:12:38.504  7791  7791 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@30e887b7 Instance Count = 1
,08-29 13:12:38.511  7791  7791 D BluetoothAdapterApp: onCreate
,08-29 13:12:38.537  7791  7791 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-29 13:12:38.537  7791  7791 D ProfileConfigQcom: Adding HeadsetService
08-29 13:12:38.538  7791  7791 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-29 13:12:38.538  7791  7791 D ProfileConfigQcom: Adding A2dpService
08-29 13:12:38.538  7791  7791 D ProfileConfigQcom: [BTUI] HidService is supported
08-29 13:12:38.538  7791  7791 D ProfileConfigQcom: Adding HidService
08-29 13:12:38.538  7791  7791 D ProfileConfigQcom: [BTUI] HealthService is supported
08-29 13:12:38.539  7791  7791 D ProfileConfigQcom: Adding HealthService
,08-29 13:12:38.539  7791  7791 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-29 13:12:38.540  7791  7791 D ProfileConfigQcom: [BTUI] PanService is supported
08-29 13:12:38.541  7791  7791 D ProfileConfigQcom: Adding PanService
08-29 13:12:38.541  7791  7791 D ProfileConfigQcom: [BTUI] GattService is supported
08-29 13:12:38.541  7791  7791 D ProfileConfigQcom: Adding GattService
08-29 13:12:38.541  7791  7791 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-29 13:12:38.541  7791  7791 D ProfileConfigQcom: Adding BluetoothMapService
08-29 13:12:38.542  7791  7791 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-29 13:12:38.543  7791  7791 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 13:12:38.544  7791  7791 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:38.544  7791  7791 V BluetoothPbapReceiver: ***********state = 10
08-29 13:12:38.546  7791  7791 V LGMDMManagerInternal: Create singleton instance
08-29 13:12:38.627  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:12:38.631  7791  7791 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-29 13:12:38.631  7791  7791 D LGBluetoothAPIServer: [BTUI] onBind()
08-29 13:12:38.631  6928  6928 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-29 13:12:38.640  1931  1931 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-29 13:12:38.640  1931  2094 D LGBluetoothAPIService: Message: 100
08-29 13:12:38.640  1931  2094 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-29 13:12:38.651  6928  6928 D BluetoothPermissionRequest: onReceive
,08-29 13:12:38.656  6928  6928 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-29 13:12:38.656  6928  6928 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-29 13:12:38.660  6928  6928 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 13:12:38.668  7791  7791 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-29 13:12:38.676  7791  7791 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:38.679  7791  7791 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 13:12:38.680  7791  7791 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 13:12:38.680  7791  7791 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 13:12:38.681  7791  7791 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:38.681  7791  7791 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-29 13:12:38.694  7606  7606 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-29 13:12:39.971  1592  1592 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-29 13:12:39.995  1043  1369 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 13:12:40.045  2024  2024 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-29 13:12:40.082  1043  1113 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7822 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-29 13:12:40.087  1592  1592 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-29 13:12:40.088  1592  1592 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-29 13:12:40.114  1043  1043 D administrator: Handling package changes for user 0
,08-29 13:12:40.140  2024  2024 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 13:12:40.166  7822  7822 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 13:12:40.196  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:40.196  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:40.225  1043  1043 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-29 13:12:40.225  1043  1043 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-29 13:12:40.251  7822  7822 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 13:12:40.251  7822  7822 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 13:12:40.272  1043  1110 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:12:40.283  1043  1110 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-29 13:12:40.289  2024  2024 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-29 13:12:40.292  2454  2454 V GmsNetworkLocationProvi: DISABLE
08-29 13:12:40.317  1043  1110 D LocationProviderProxy: applying state to connected service
,08-29 13:12:40.319  2454  2454 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-29 13:12:40.339  7822  7868 I Babel   : MmsConfig: mnc/mcc: 0/0
08-29 13:12:40.339  7822  7868 I Babel   : MmsConfig.loadMmsSettings
08-29 13:12:40.341  7822  7868 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-29 13:12:40.341  7822  7868 I Babel   : MmsConfig.loadFromDatabase
,08-29 13:12:40.356  7822  7868 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-29 13:12:40.356  7822  7868 I Babel   : MmsConfig.loadFromResources
08-29 13:12:40.361  7822  7868 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-29 13:12:40.361  7822  7868 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-29 13:12:40.374  7822  7866 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 13:12:40.375  7822  7866 W AudioCapabilities: Unsupported mime audio/qcelp
08-29 13:12:40.377  7822  7866 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-29 13:12:40.385  7822  7866 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-29 13:12:40.386  7822  7866 W AudioCapabilities: Unsupported mime audio/qcelp
08-29 13:12:40.387  7822  7866 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 13:12:40.391  7822  7822 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:40.396  7822  7866 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-29 13:12:40.404  7822  7866 W VideoCapabilities: Unsupported mime video/divx
08-29 13:12:40.405  7822  7866 W VideoCapabilities: Unsupported mime video/divx311
08-29 13:12:40.407  7822  7866 W VideoCapabilities: Unsupported mime video/divx4
,08-29 13:12:40.418  7822  7866 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-29 13:12:40.436  1807  7870 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-29 13:12:40.436  1807  7870 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-29 13:12:40.441  7120  7120 I AppUp4:CustModeStarterReceiver: onReceive
,08-29 13:12:40.445  7120  7120 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@10ae4e89
08-29 13:12:40.445  7120  7120 D AppUp4:CustFacade: isCustomizationCompleted : false
08-29 13:12:40.445  7120  7120 D AppUp4:CustFacade: isPhone : true
08-29 13:12:40.445  7120  7120 D AppUp4:CustModeStarterReceiver: begin check event
08-29 13:12:40.445  7120  7120 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-29 13:12:40.457  1807  5236 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-29 13:12:40.462  7822  7866 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-29 13:12:40.467  7822  7866 W AudioCapabilities: Unsupported mime audio/eac3
08-29 13:12:40.468  7822  7866 W AudioCapabilities: Unsupported mime audio/ac3
08-29 13:12:40.469  7822  7866 W AudioCapabilities: Unsupported mime audio/g726
08-29 13:12:40.470  7822  7866 W AudioCapabilities: Unsupported mime audio/wma-voice
,08-29 13:12:40.471  7822  7866 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-29 13:12:40.474  7822  7866 W AudioCapabilities: Unsupported mime audio/adpcm
08-29 13:12:40.476  1043  1565 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7873 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-29 13:12:40.480  7822  7866 W VideoCapabilities: Unsupported mime video/theora
08-29 13:12:40.483  1043  2023 I ActivityManager: Killing 6947:com.lge.sync/1000 (adj 15): empty #17
,08-29 13:12:40.485  7822  7866 W VideoCapabilities: Unsupported mime video/mjpg
08-29 13:12:40.497  1043  1486 D WifiService: Client connection lost with reason: 4
,08-29 13:12:40.676  1043  1895 W libprocessgroup: failed to open /acct/uid_1000/pid_6947/cgroup.procs: No such file or directory
,08-29 13:12:40.717  7873  7873 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:12:40.717  7873  7873 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 13:12:40.717  7873  7873 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-29 13:12:40.719  7873  7873 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-29 13:12:40.719  7873  7873 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 13:12:40.787  7873  7873 I SystemConfig: BUILD Country: EU
,08-29 13:12:40.787  7873  7873 I SystemConfig: BUILD Operator: OPEN
08-29 13:12:40.830  1043  2022 I ActivityManager: Killing 7153:com.lge.email/u0a23 (adj 15): empty #17
,08-29 13:12:40.932  1043  2023 W libprocessgroup: failed to open /acct/uid_10023/pid_7153/cgroup.procs: No such file or directory
,08-29 13:12:41.008  1043  2022 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7893 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-29 13:12:41.015  7873  7891 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-29 13:12:41.016  7873  7891 I SystemConfig: existFile = false
08-29 13:12:41.016  7873  7891 I SystemConfig: canReadFile = false
08-29 13:12:41.016  7873  7891 I SystemConfig: systemFeature RCS result false
08-29 13:12:41.016  7873  7891 D SystemConfig: refreshRcsSupport() :false
,08-29 13:12:41.103  7893  7893 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:12:41.104  7893  7893 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 13:12:41.104  7893  7893 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-29 13:12:41.104  7893  7893 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-29 13:12:41.234  1043  1509 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-29 13:12:41.236  7893  7893 I AppConfig: Total System Memory = 2995761152
,08-29 13:12:41.246  7893  7893 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-29 13:12:41.358  1043  1895 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7918 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:12:41.360  1043  1895 I ActivityManager: Killing 7017:com.lge.formmanager/u0a26 (adj 15): empty #17
08-29 13:12:41.476  1043  1646 W libprocessgroup: failed to open /acct/uid_10026/pid_7017/cgroup.procs: No such file or directory
,08-29 13:12:41.676  7918  7918 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-29 13:12:41.779  7918  7918 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 13:12:41.780  7918  7918 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-29 13:12:41.836  7918  7918 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-29 13:12:41.858  7918  7918 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-29 13:12:41.859  7918  7918 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-29 13:12:41.876  7918  7918 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 13:12:41.876  7918  7918 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-29 13:12:41.894  1043  1367 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3c71ca03 type 2 when 132135 com.google.android.gms} when 132135
,08-29 13:12:41.895  1043  2022 I ActivityManager: Killing 6457:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-29 13:12:41.959  1043  1565 W libprocessgroup: failed to open /acct/uid_1000/pid_6457/cgroup.procs: No such file or directory
,08-29 13:12:41.969  3438  3453 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-29 13:12:41.972  3438  3453 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@8abdd52 on behalf of 7918
08-29 13:12:41.974  5091  7964 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-29 13:12:42.031  1043  1950 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7968 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-29 13:12:42.125  7918  7918 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-29 13:12:42.156  7918  7918 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-29 13:12:42.161  7968  7968 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-29 13:12:42.198  7968  7968 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-29 13:12:42.198  7968  7968 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-29 13:12:42.198  7968  7968 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-29 13:12:42.198  7968  7968 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-29 13:12:42.198  7968  7968 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-29 13:12:42.198  7968  7968 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-29 13:12:42.211   323  8002 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-29 13:12:42.213  1043  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-29 13:12:42.254  1043  1060 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=8003 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-29 13:12:42.259  1043  1060 I ActivityManager: Killing 7188:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-29 13:12:42.307  1043  2023 W libprocessgroup: failed to open /acct/uid_10046/pid_7188/cgroup.procs: No such file or directory
,08-29 13:12:42.336  8003  8003 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 13:12:42.371  8003  8003 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-29 13:12:42.425  8003  8003 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-29 13:12:42.426  8003  8003 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-29 13:12:42.426  8003  8003 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-29 13:12:42.427  8003  8003 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-29 13:12:42.427  8003  8003 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-29 13:12:42.429  8003  8003 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-29 13:12:42.435  8003  8003 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-29 13:12:42.443  8003  8003 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-29 13:12:42.444  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:362
,08-29 13:12:42.448  8003  8003 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-29 13:12:42.451  8003  8003 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-29 13:12:42.452  8003  8003 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 13:12:42.453  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 13:12:42.453  8003  8003 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-29 13:12:42.481  1043  1895 V SIM_STK : Menu title from STK is T-Mobile
,08-29 13:12:42.489  8003  8003 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:12:42.490  8003  8003 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 13:12:42.496  8003  8003 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-29 13:12:42.499  8003  8003 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-29 13:12:42.499  8003  8003 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-29 13:12:42.499  8003  8003 V SoundPool: doLoad: loading sample sampleID=1
08-29 13:12:42.499  8003  8024 V SoundPool: Start decode
08-29 13:12:42.499  8003  8024 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-29 13:12:42.500   327  1385 V MediaPlayerService: decode(23, 10857164, 17813)
08-29 13:12:42.500   327  1385 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-29 13:12:42.500   327  1385 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-29 13:12:42.500   327  1385 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-29 13:12:42.500   327  1385 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-29 13:12:42.500   327  1385 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-29 13:12:42.500   327  1385 V MediaPlayerService: player type = 3
08-29 13:12:42.500   327  1385 V AwesomePlayer: AwesomePlayer create()
08-29 13:12:42.501  8003  8003 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-29 13:12:42.501   327  1385 V AwesomePlayer: reset_l() 
08-29 13:12:42.501   327  1385 V AwesomePlayer: cancelPlayerEvents
08-29 13:12:42.501   327  1385 V AwesomePlayer: setAudioSink() 
08-29 13:12:42.501   327  1385 V AwesomePlayer: reset_l() 
08-29 13:12:42.501   327  1385 V AudioCache: notify(0xb14322c0, 8, 0, 0)
08-29 13:12:42.501   327  1385 V AudioCache: ignored
08-29 13:12:42.501   327  1385 V AwesomePlayer: cancelPlayerEvents
08-29 13:12:42.502   327  1385 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-29 13:12:42.502   327  1385 V AwesomePlayer: setDataSource_l dataSource
08-29 13:12:42.502   327  1385 V LGParserOSAL: SniffLGParser start
08-29 13:12:42.502   327  1385 V LGParserOSAL: MainType:5, SubType=0
08-29 13:12:42.502   327  1385 V LGParserOSAL: #### check Mime : application/ogg
08-29 13:12:42.502   327  1385 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-29 13:12:42.502   327  1385 E MediaExtractor: Use LGExtractor :application/ogg 
08-29 13:12:42.504  8003  8003 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-29 13:12:42.511  8003  8003 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 13:12:42.511  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-29 13:12:42.516  5091  7964 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 542 ms] updated apps [took 542 ms] 
08-29 13:12:42.532  8003  8003 V LGMDMManager: Create singleton instance
08-29 13:12:42.548  7702  7763 D UEI.SmartControl: Internal timer expired: 1
08-29 13:12:42.549  7702  7763 D UEI.SmartControl: unbind internal service
08-29 13:12:42.549   327  1385 V LGParserOSAL: supported mime: application/ogg
08-29 13:12:42.549   327  1385 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-29 13:12:42.549   327  1385 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-29 13:12:42.549   327  1385 V AwesomePlayer: mBitrate = -1 bits/sec
,08-29 13:12:42.549   327  1385 V AwesomePlayer: AudioTrack Setting
08-29 13:12:42.549   327  1385 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-29 13:12:42.549   327  1385 V AwesomePlayer: setAudioSource() 
08-29 13:12:42.549   327  1385 V MediaPlayerService: prepare
08-29 13:12:42.549   327  1385 V AwesomePlayer: prepareAsync_l() 
08-29 13:12:42.549   327  1385 V MediaPlayerService: wait for prepare
08-29 13:12:42.550   327  8025 V AwesomePlayer: onPrepareAsyncEvent() 
08-29 13:12:42.550   327  8025 V AwesomePlayer: initAudioDecoder() 
08-29 13:12:42.550   327  8025 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 13:12:42.550   327  8025 V AudioSystem: isOffloadSupported()
08-29 13:12:42.550   327  8025 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 13:12:42.550   327  8025 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 13:12:42.550   327  8025 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 13:12:42.550   327  8025 V AwesomePlayer: getUseOffload() = 0 
08-29 13:12:42.550   327  8025 V OMXCodec: OMXCodec::Create
08-29 13:12:42.550   327  8025 V OMXCodec: findMatchingCodecs()
08-29 13:12:42.550   327  8025 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-29 13:12:42.550   327  8025 V OMXCodec: matchingCodecs.size()=1
08-29 13:12:42.550   327  8025 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-29 13:12:42.552   327  8025 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-29 13:12:42.552   327  8025 V LGCodecAdapter: LG Codec Adapter start
08-29 13:12:42.552   327  8025 V OMXCodec: OMXCodec Createtor
08-29 13:12:42.552   327  8025 V OMXCodec: setComponentRole
08-29 13:12:42.552   327  8025 V OMXCodec: configureCodec protected=0
08-29 13:12:42.552   327  8025 V LGCodecAdapter: called getLGCodecSpecificData
08-29 13:12:42.552   327  8025 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-29 13:12:42.552   327  8025 V LGCodecOSAL: Called LGconfigureCodecMETA
08-29 13:12:42.552   327  8025 V LGCodecOSAL: Called LGconfigureCodecMSG
08-29 13:12:42.552   327  8025 V LGCodecOSAL: Not support LGCodec
08-29 13:12:42.552   327  8025 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-29 13:12:42.552   327  8025 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-29 13:12:42.552   327  8025 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-29 13:12:42.552   327  8025 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-29 13:12:42.553   327  8025 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-29 13:12:42.553   327  8025 V AudioSystem: isOffloadSupported()
08-29 13:12:42.553   327  8025 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-29 13:12:42.553   327  8025 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-29 13:12:42.553   327  8025 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-29 13:12:42.553   327  8025 V OMXCodec: init()
08-29 13:12:42.553   327  8025 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-29 13:12:42.553   327  8025 V OMXCodec: allocateBuffers
08-29 13:12:42.553   327  8025 V OMXCodec: allocateBuffersOnPort portIndex=0
08-29 13:12:42.553   327  8025 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-29 13:12:42.553   327  8025 V OMXCodec: [OMX.google.vorb,is.decoder] allocated buffer 0xb040f1f0 on input port
08-29 13:12:42.553   327  8025 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
08-29 13:12:42.553   327  8025 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-29 13:12:42.553   327  8025 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-29 13:12:42.553   327  8025 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 13:12:42.553   327  8025 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-29 13:12:42.553   327  8025 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-29 13:12:42.553   327  8025 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-29 13:12:42.553   327  8025 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-29 13:12:42.554   327  8025 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-29 13:12:42.554   327  8025 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 13:12:42.554   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 13:12:42.554   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 13:12:42.554   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-29 13:12:42.554   327  8025 V OMXCodec: init() mAsyncCompletion wait!!! 
08-29 13:12:42.554   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-29 13:12:42.554   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-29 13:12:42.554   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-29 13:12:42.554   327  8025 V OMXCodec: init() mAsyncCompletion wait free! 
08-29 13:12:42.554   327  8025 V AwesomePlayer: finishAsyncPrepare_l() 
08-29 13:12:42.554   327  8025 V AudioCache: notify(0xb14322c0, 5, 0, 0)
,08-29 13:12:42.554   327  8025 V AudioCache: ignored,
08-29 13:12:42.554   327  8025 V AudioCache: notify(0xb14322c0, 1, 0, 0)
08-29 13:12:42.554   327  8025 V AudioCache: prepared
,08-29 13:12:42.554   327  1385 V AudioCache: wait - success
08-29 13:12:42.554   327  1385 V MediaPlayerService: start
08-29 13:12:42.554   327  1385 V AwesomePlayer: play_l() 
,08-29 13:12:42.554   327  1385 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-29 13:12:42.554   327  1385 V AwesomePlayer: createAudioPlayer_l
08-29 13:12:42.554   327  1385 V AwesomePlayer: seekAudioIfNecessary_l() ,
08-29 13:12:42.554   327  1385 V AwesomePlayer: startAudioPlayer_l() 
08-29 13:12:42.554   327  1385 D AudioPlayer: start of Playback, useOffload 0
,08-29 13:12:42.554   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-29 13:12:42.554   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,08-29 13:12:42.557   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-29 13:12:42.557   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7,
08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
,08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048256
08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0,
08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
,08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-29 13:12:42.558   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1),
08-29 13:12:42.559   327  8027 V OMXCodec: allocateBuffersOnPort portIndex=1
08-29 13:12:42.559   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,08-29 13:12:42.559   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-29 13:12:42.559   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
,08-29 13:12:42.559   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-29 13:12:42.559   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1790150 on output port
08-29 13:12:42.559   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,08-29 13:12:42.559   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-29 13:12:42.560   327  1385 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-29 13:12:42.561   327  1385 V AudioCache: notify(0xb14322c0, 6, 0, 0)
,08-29 13:12:42.561   327  1385 V AudioCache: ignored
08-29 13:12:42.561   327  1385 V MediaPlayerService: wait for playback complete
,08-29 13:12:42.562   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.562   327  8028 V AudioCache: memcpy(0xaf006000, 0xb16f6000, 4096)
08-29 13:12:42.565   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.565   327  8028 V AudioCache: memcpy(0xaf007000, 0xb16f6000, 4096),
08-29 13:12:42.568   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.568   327  8028 V AudioCache: memcpy(0xaf008000, 0xb16f6000, 4096)
08-29 13:12:42.569   327  8028 V AudioCache: write(0xb16f6000, 4096)
,08-29 13:12:42.569   327  8028 V AudioCache: memcpy(0xaf009000, 0xb16f6000, 4096)
08-29 13:12:42.569   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.569   327  8028 V AudioCache: memcpy(0xaf00a000, 0xb16f6000, 4096)
08-29 13:12:42.570   327  8028 V AudioCache: write(0xb16f6000, 4096)
,08-29 13:12:42.570   327  8028 V AudioCache: memcpy(0xaf00b000, 0xb16f6000, 4096)
08-29 13:12:42.571   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.571   327  8028 V AudioCache: memcpy(0xaf00c000, 0xb16f6000, 4096)
08-29 13:12:42.572   327  8028 V AudioCache: write(0xb16f6000, 4096)
,08-29 13:12:42.572   327  8028 V AudioCache: memcpy(0xaf00d000, 0xb16f6000, 4096)
08-29 13:12:42.573   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.573   327  8028 V AudioCache: memcpy(0xaf00e000, 0xb16f6000, 4096)
08-29 13:12:42.574   327  8028 V AudioCache: write(0xb16f6000, 4096)
,08-29 13:12:42.574   327  8028 V AudioCache: memcpy(0xaf00f000, 0xb16f6000, 4096)
08-29 13:12:42.575   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.575   327  8028 V AudioCache: memcpy(0xaf010000, 0xb16f6000, 4096)
08-29 13:12:42.575   327  8028 V AudioCache: write(0xb16f6000, 4096)
,08-29 13:12:42.575   327  8028 V AudioCache: memcpy(0xaf011000, 0xb16f6000, 4096)
08-29 13:12:42.576   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.576   327  8028 V AudioCache: memcpy(0xaf012000, 0xb16f6000, 4096)
08-29 13:12:42.577   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.577   327  8028 V AudioCache: memcpy(0xaf013000, 0xb16f6000, 4096),
08-29 13:12:42.578   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.578   327  8028 V AudioCache: memcpy(0xaf014000, 0xb16f6000, 4096)
08-29 13:12:42.578   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.578   327  8028 V AudioCache: memcpy(0xaf015000, 0xb16f6000, 4096)
,08-29 13:12:42.578   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.578   327  8028 V AudioCache: memcpy(0xaf016000, 0xb16f6000, 4096)
08-29 13:12:42.578   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.578   327  8028 V AudioCache: memcpy(0xaf017000, 0xb16f6000, 4096)
08-29 13:12:42.582   327  8028 V AudioCache: write(0xb16f6000, 4096),
08-29 13:12:42.582   327  8028 V AudioCache: memcpy(0xaf018000, 0xb16f6000, 4096)
08-29 13:12:42.582   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.583   327  8028 V AudioCache: memcpy(0xaf019000, 0xb16f6000, 4096)
08-29 13:12:42.583   327  8028 V AudioCache: write(0xb16f6000, 4096)
,08-29 13:12:42.583   327  8028 V AudioCache: memcpy(0xaf01a000, 0xb16f6000, 4096)
08-29 13:12:42.583   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.583   327  8028 V AudioCache: memcpy(0xaf01b000, 0xb16f6000, 4096)
,08-29 13:12:42.586   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.586   327  8028 V AudioCache: memcpy(0xaf01c000, 0xb16f6000, 4096)
08-29 13:12:42.586   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.586   327  8028 V AudioCache: memcpy(0xaf01d000, 0xb16f6000, 4096)
08-29 13:12:42.586   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.586   327  8028 V AudioCache: memcpy(0xaf01e000, 0xb16f6000, 4096)
08-29 13:12:42.587   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.587   327  8028 V AudioCache: memcpy(0xaf01f000, 0xb16f6000, 4096)
08-29 13:12:42.587   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.587   327  8028 V AudioCache: memcpy(0xaf020000, 0xb16f6000, 4096)
08-29 13:12:42.588   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.588   327  8028 V AudioCache: memcpy(0xaf021000, 0xb16f6000, 4096)
08-29 13:12:42.588   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.588   327  8028 V AudioCache: memcpy(0xaf022000, 0xb16f6000, 4096)
08-29 13:12:42.589   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.589   327  8028 V AudioCache: memcpy(0xaf023000, 0xb16f6000, 4096)
08-29 13:12:42.589   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.589   327  8028 V AudioCache: memcpy(0xaf024000, 0xb16f6000, 4096)
08-29 13:12:42.590   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.590   327  8028 V AudioCache: memcpy(0xaf025000, 0xb16f6000, 4096)
08-29 13:12:42.590   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.590   327  8028 V AudioCache: memcpy(0xaf026000, 0xb16f6000, 4096)
08-29 13:12:42.590   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.590   327  8028 V AudioCache: memcpy(0xaf027000, 0xb16f6000, 4096)
08-29 13:12:42.591   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.591   327  8028 V AudioCache: memcpy(0xaf028000, 0xb16f6000, 4096)
08-29 13:12:42.591   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.591   327  8028 V AudioCache: memcpy(0xaf029000, 0xb16f6000, 4096)
08-29 13:12:42.592   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.592   327  8028 V AudioCache: memcpy(0xaf02a000, 0xb16f6000, 4096)
08-29 13:12:42.593   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.593   327  8028 V AudioCache: memcpy(0xaf02b000, 0xb16f6000, 4096)
08-29 13:12:42.593   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.593   327  8028 V AudioCache: memcpy(0xaf02c000, 0xb16f6000, 4096)
08-29 13:12:42.594   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.594   327  8028 V AudioCache: memcpy(0xaf02d000, 0xb16f6000, 4096)
08-29 13:12:42.595   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.595   327  8028 V AudioCache: memcpy(0xaf02e000, 0xb16f6000, 4096)
08-29 13:12:42.595   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.595   327  8028 V AudioCache: memcpy(0xaf02f000, 0xb16f6000, 4096)
08-29 13:12:42.596   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.596   327  8028 V AudioCache: memcpy(0xaf030000, 0xb16f6000, 4096)
,08-29 13:12:42.598   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.598   327  8028 V AudioCache: memcpy(0xaf031000, 0xb16f6000, 4096)
08-29 13:12:42.599   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.599   327  8028 V AudioCache: memcpy(0xaf032000, 0xb16f6000, 4096)
08-29 13:12:42.600   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.600   327  8028 V AudioCache: memcpy(0xaf033000, 0xb16f6000, 4096)
08-29 13:12:42.601   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.601   327  8028 V AudioCache: memcpy(0xaf034000, 0xb16f6000, 4096)
08-29 13:12:42.601   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.601   327  8028 V AudioCache: memcpy(0xaf035000, 0xb16f6000, 4096)
08-29 13:12:42.602   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.602   327  8028 V AudioCache: memcpy(0xaf036000, 0xb16f6000, 4096)
08-29 13:12:42.602   327  8028 V AudioCache: write(0xb16f6000, 4096)
08-29 13:12:42.602   327  8028 V AudioCache: memcpy(0xaf037000, 0xb16f6000, 4096)
08-29 13:12:42.602   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-29 13:12:42.602   327  8028 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-29 13:12:42.602   327  8028 V AwesomePlayer: postAudioEOS() 
08-29 13:12:42.602   327  8028 V AudioCache: write(0xb16f6000, 280)
08-29 13:12:42.602   327  8028 V AudioCache: memcpy(0xaf038000, 0xb16f6000, 280)
08-29 13:12:42.604   327  8025 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-29 13:12:42.604   327  8025 V AwesomePlayer: onStreamDone
08-29 13:12:42.604   327  8025 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-29 13:12:42.604   327  8025 V AudioCache: notify(0xb14322c0, 2, 0, 0)
,08-29 13:12:42.604   327  8025 V AudioCache: playback complete
08-29 13:12:42.604   327  8025 V AwesomePlayer: pause_l() 
08-29 13:12:42.604   327  1385 V AudioCache: wait - success
08-29 13:12:42.604   327  8025 V AudioCache: notify(0xb14322c0, 7, 0, 0)
08-29 13:12:42.604   327  8025 V AudioCache: ignored
08-29 13:12:42.604   327  1385 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-29 13:12:42.604   327  8025 V AwesomePlayer: cancelPlayerEvents
08-29 13:12:42.605   327  8025 D AudioPlayer: Pause Playback at 1068125
08-29 13:12:42.605   327  1385 V AwesomePlayer: reset_l() 
08-29 13:12:42.605   327  1385 V AudioCache: notify(0xb14322c0, 8, 0, 0)
08-29 13:12:42.605   327  1385 V AudioCache: ignored
08-29 13:12:42.605   327  1385 V AwesomePlayer: cancelPlayerEvents
08-29 13:12:42.605   327  1385 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-29 13:12:42.605   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-29 13:12:42.605   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-29 13:12:42.605   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-29 13:12:42.605   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 13:12:42.605   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-29 13:12:42.605   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 0
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1790150 on port 1
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 1
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-29 13:12:42.606   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 13:12:42.606   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-29 13:12:42.606   327  8027 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-29 13:12:42.606   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-29 13:12:42.6,06   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-29 13:12:42.607   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-29 13:12:42.608   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-29 13:12:42.608   327  1385 D AudioPlayer: AudioPlayer releasing audio source
08-29 13:12:42.608   327  1385 D AudioPlayer: AudioPlayer done releasing audio source
08-29 13:12:42.608   327  1385 V AwesomePlayer: reset_l() 
08-29 13:12:42.608   327  1385 V AwesomePlayer: cancelPlayerEvents
08-29 13:12:42.608   327  1385 V AwesomePlayer: ~AwesomePlayer call
08-29 13:12:42.608   327  1385 V AwesomePlayer: reset_l() 
08-29 13:12:42.608   327  1385 V AwesomePlayer: cancelPlayerEvents
08-29 13:12:42.609  8003  8024 V SoundPool: close(31)
08-29 13:12:42.609  8003  8024 V SoundPool: pointer = 0x9fffb000, size = 205080, sampleRate = 48000, numChannels = 2
,08-29 13:12:42.625  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-29 13:12:42.626  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting,
,08-29 13:12:42.628  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:806
08-29 13:12:42.632  8003  8003 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-29 13:12:42.633  7702  7717 I UEI.SmartControl: ------ IControl API: 11
08-29 13:12:42.633  7702  7717 I UEI.SmartControl: Registering callback...
08-29 13:12:42.634  7702  7718 I UEI.SmartControl: ------ IControl API: 19
08-29 13:12:42.635  7702  7718 I UEI.SmartControl: Registering Services Ready callback...
08-29 13:12:42.635  7702  7718 I UEI.SmartControl: Notify client services are ready...
08-29 13:12:42.636  8003  8019 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-29 13:12:42.636  8003  8022 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-29 13:12:42.636  8003  8022 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-29 13:12:42.637  8003  8003 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-29 13:12:42.637  8003  8003 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-29 13:12:42.637  7702  7764 I UEI.SmartControl: ------ IControl API: 8
08-29 13:12:42.639  8003  8003 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-29 13:12:42.639  8003  8003 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-29 13:12:42.639  8003  8003 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-29 13:12:42.640  8003  8003 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-29 13:12:42.641  8003  8003 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-29 13:12:42.641  8003  8003 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-29 13:12:42.643  8003  8003 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-29 13:12:42.646  8003  8003 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-29 13:12:42.647  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-29 13:12:42.647  8003  8003 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 13:12:42.648  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-29 13:12:42.648  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-29 13:12:42.649  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-29 13:12:42.650  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-29 13:12:42.650  8003  8003 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472469162650]
08-29 13:12:42.653  8003  8003 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-29 13:12:42.654  1043  1565 I ActivityManager: Killing 7211:com.android.chrome/u0a57 (adj 15): empty #17
,08-29 13:12:42.676  8003  8029 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-29 13:12:42.772  7702  7760 D serial_port: close(fd = 25)
,08-29 13:12:42.776  1043  1060 W libprocessgroup: failed to open /acct/uid_10057/pid_7211/cgroup.procs: No such file or directory
08-29 13:12:42.777  7702  7760 I UEI.SmartControl: Serial port is closed.
08-29 13:12:42.785  8003  8003 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-29 13:12:42.787  8003  8003 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-29 13:12:42.788  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,08-29 13:12:42.789  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,08-29 13:12:42.790  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-29 13:12:42.791  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,08-29 13:12:42.791  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-29 13:12:42.812  8003  8003 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-29 13:12:43.202  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:12:43.202  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ce47033 added. We now have 6 listener(s)
,08-29 13:12:43.202  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:43.215  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:43.216  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e57ff0 added. We now have 7 listener(s)
08-29 13:12:43.216  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:43.217  6705  6760 I System.out: IsBluetoothEnabled
08-29 13:12:43.219  1043  1913 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:43.219  1043  1913 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-29 13:12:43.220  1043  1120 D BluetoothManagerService: Message: 2
08-29 13:12:43.223  6705  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:43.225  1043  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:43.226  1043  1950 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-29 13:12:43.244  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-29 13:12:43.245  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 13:12:43.245  1043  1043 D Ulp_jni : JNI:system_update. Event-4
08-29 13:12:43.245  1043  1120 D BluetoothManagerService: Message: 1
08-29 13:12:43.245  1043  1120 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-29 13:12:43.270  1043  1120 D BluetoothManagerService: Message: 20
08-29 13:12:43.271  1043  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20976c47:true
,08-29 13:12:43.275  7791  7791 D BluetoothAdapterState: make
08-29 13:12:43.280  7791  7791 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-29 13:12:43.280  7791  7791 I bluedroid-qcom: init
08-29 13:12:43.281  7791  8039 I BluetoothAdapterState: Entering OffState
08-29 13:12:43.281  7791  7791 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 13:12:43.282  7791  7791 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 13:12:43.282  7791  7791 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 13:12:43.282  7791  7791 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 13:12:43.282  7791  7791 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-29 13:12:43.284  7791  7791 I bluedroid-qcom: get_profile_interface socket
08-29 13:12:43.284  7791  7791 I bluedroid-qcom: get_profile_interface map_client
,08-29 13:12:43.288  7791  8043 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 13:12:43.278  8042  8042 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:43.278  8042  8042 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:43.297  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-29 13:12:43.299  1043  1120 D BluetoothManagerService: Message: 40
08-29 13:12:43.299  1043  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-29 13:12:43.300  7791  7806 I bluedroid-qcom: config_hci_snoop_log
08-29 13:12:43.307  8042  8042 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-29 13:12:43.307  8042  8042 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-29 13:12:43.307  8042  8042 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-29 13:12:43.308  1043  1120 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-29 13:12:43.308  1043  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-29 13:12:43.312  7791  8043 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 13:12:43.316  8042  8042 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-29 13:12:43.318  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 13:12:43.318  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 13:12:43.319  7791  8043 D BluetoothAdapterProperties: Name is: G3
08-29 13:12:43.322  8042  8042 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-29 13:12:43.322  8042  8042 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-29 13:12:43.325  7791  8039 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-29 13:12:43.326  7791  8039 D BluetoothAdapterProperties: Setting state to 11
08-29 13:12:43.326  7791  8039 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-29 13:12:43.329  1043  1120 D BluetoothManagerService: Message: 60
08-29 13:12:43.329  1043  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-29 13:12:43.330  1043  1120 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-29 13:12:43.331  7791  8039 I LGBluetoothServiceJni: classInitNative: succeeds
08-29 13:12:43.336  1931  1931 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:43.337  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 13:12:43.340  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:43.345  6928  6928 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-29 13:12:43.351  7791  7791 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 13:12:43.351  7791  7791 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:43.351  7791  7791 V BluetoothPbapReceiver: ***********state = 11
08-29 13:12:43.363  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:12:43.373  7791  8039 D BluetoothBondStateMachine: make
08-29 13:12:43.376  7791  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd34abc
08-29 13:12:43.376  7791  8039 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-29 13:12:43.376  7791  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd34abc
,08-29 13:12:43.376  7791  8039 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-29 13:12:43.377  7791  8039 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-29 13:12:43.378  7791  8058 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 13:12:43.381  7791  8039 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:12:43.386  6928  6928 D BluetoothPermissionRequest: onReceive
08-29 13:12:43.389  7791  7791 D HeadsetService: Received start request. Starting profile...
08-29 13:12:43.390  6928  6928 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 13:12:43.390  7791  7791 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 13:12:43.390  7791  7791 D LGBluetoothHfpAdapter: Version 1.6
08-29 13:12:43.390  7791  8039 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:12:43.393  7791  7791 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-29 13:12:43.394  7791  7791 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 13:12:43.395  7791  7791 D HeadsetStateMachine: make
08-29 13:12:43.399  7791  8039 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:12:43.404  7791  8039 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:12:43.410  7791  8039 E BluetoothAdapterService: File transfer profiles supported!!
,08-29 13:12:43.416  7791  8039 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:12:43.430  7791  7791 D LgDataFeature: LgDataFeature() Constructor: none
,08-29 13:12:43.430  7791  7791 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 13:12:43.521  1043  1948 I art     : Explicit concurrent mark sweep GC freed 26725(1273KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.417ms total 102.494ms
08-29 13:12:43.522  7791  7791 D HeadsetStateMachine: max_hf_connections = 1
08-29 13:12:43.522  7791  7791 I bluedroid-qcom: get_profile_interface handsfree
08-29 13:12:43.524  7791  7791 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-29 13:12:43.527   327  1715 V AudioPolicyService: registerClient() client 0xb0410140, uid 1002
08-29 13:12:43.528   327  1717 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-29 13:12:43.528   327  1717 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 13:12:43.528   327  1717 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 13:12:43.529  7791  7791 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 13:12:43.530  7791  8039 E BluetoothAdapterService: File transfer profiles supported!!
08-29 13:12:43.530   327   327 V AudioFlinger: registerClient() client 0xb55816e8, pid 7791
08-29 13:12:43.531   327  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:12:43.531   327  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:12:43.532  1043  1646 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:12:43.532  1043  1646 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:12:43.532  3228  3261 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:12:43.532   327  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:12:43.532  3228  3261 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:12:43.532   327  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:12:43.534  7791  7806 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:12:43.534  7791  7806 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-29 13:12:43.534  7791  7791 V ToneGenerator: Create Track: 0xb4928a80
08-29 13:12:43.534  7791  7791 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-29 13:12:43.534  1043  1913 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:12:43.534  1043  1913 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:12:43.534  7791  7791 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-29 13:12:43.534  3228  3267 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:12:43.534  3228  3267 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:12:43.535  1843  1859 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:12:43.535  1843  1859 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:12:43.535  1843  1859 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:12:43.535   327  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 13:12:43.535  1843  1859 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:12:43.535   327  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-29 13:12:43.536  1592  1613 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-29 13:12:43.536  1592  1613 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-29 13:12:43.536   327  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-29 13:12:43.536  1592  1613 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:12:43.536  1592  1613 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-29 13:12:43.536   327  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 13:12:43.536  7791  7808 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-29 13:12:43.536  7791  7791 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-29 13:12:43.537  7791  7808 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
,08-29 13:12:43.539   327  1717 I AudioFlinger: isAudioPlaybackHookOn() false
08-29 13:12:43.543   327  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-29 13:12:43.543   327  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-29 13:12:43.543   327  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-29 13:12:43.543   327  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-29 13:12:43.544  7791  7791 V AudioSystem: getLatency() output 2, latency 50
08-29 13:12:43.544  7791  7791 V AudioSystem: getFrameCount() output 2, frameCount 960
08-29 13:12:43.544  7791  7791 V AudioTrack: createTrack_l() output 2 afLatency 50
08-29 13:12:43.544   327   327 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 13:12:43.544   327   327 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 13:12:43.544   327   327 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-29 13:12:43.544   327   327 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-29 13:12:43.544   327   327 V AudioFlinger: createTrack() lSessionId: 23
08-29 13:12:43.545  7791  7791 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-29 13:12:43.545   327  1717 V AudioFlinger: acquiring 23 from 7791, for 7791
08-29 13:12:43.545   327  1717 V AudioFlinger:  added new entry for 23
08-29 13:12:43.546  7791  7791 V ToneGenerator: ToneGenerator INIT OK, time: 133802
08-29 13:12:43.546  7791  7791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd34abc
08-29 13:12:43.547  7791  8061 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
,08-29 13:12:43.547  7791  8061 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-29 13:12:43.547  7791  8061 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-29 13:12:43.548  7791  7791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd34abc
08-29 13:12:43.548  7791  8061 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-29 13:12:43.552   327  1715 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7791
08-29 13:12:43.552  7791  7791 D A2dpService: Received start request. Starting profile...
08-29 13:12:43.552   327  1715 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-29 13:12:43.553   327  1715 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-29 13:12:43.553   327  1715 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-29 13:12:43.553   327  1715 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-29 13:12:43.553   327  1715 V voice   : voice_set_parameters: exit with code(0)
08-29 13:12:43.553   327  1715 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-29 13:12:43.553   327  1715 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-29 13:12:43.553  7791  7791 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 13:12:43.554   327  1715 V msm8974_platform: platform_set_parameters: exit with code(0)
08-29 13:12:43.554   327  1715 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-29 13:12:43.554   327  1715 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-29 13:12:43.554   327  1715 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-29 13:12:43.555  7791  8061 V ToneGenerator: ToneGenerator destructor
08-29 13:12:43.555  7791  8061 V ToneGenerator: stopTone
08-29 13:12:43.555  7791  8061 V ToneGenerator: Delete Track: 0xb4928a80
08-29 13:12:43.555   327  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
08-29 13:12:43.555   327  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-29 13:12:43.555  7791  7791 V Avrcp   : make
08-29 13:12:43.556   327  1260 V AudioPolicyService: AudioCommandThread() waking up
08-29 13:12:43.556   327  1260 V AudioPolicyService: AudioCommandThread() processing release output 2
08-29 13:12:43.556   327  1260 V AudioPolicyManager: releaseOutput() 2
08-29 13:12:43.556   327  1260 V AudioPolicyService: AudioCommandThread() going to sleep
08-29 13:12:43.556   327  1384 V AudioFlinger: PlaybackThread::Track destructor
08-29 13:12:43.556   327  1384 V AudioFlinger: removeClient_l() pid 7791, calling pid 327
08-29 13:12:43.556  7791  8061 V AudioTrack: ~AudioTrack, releasing session id from 7791 on behalf of 7791
08-29 13:12:43.556   327  1717 V AudioFlinger: releasing 23 from 7791 for 7791
08-29 13:12:43.556   327  1717 V AudioFlinger:  decremented refcount to 0
08-29 13:12:43.556   327  1717 V AudioFlinger: purging stale effects
,08-29 13:12:43.557  7791  7791 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-29 13:12:43.557  7791  7791 I bluedroid-qcom: get_profile_interface avrcp
08-29 13:12:43.566  7791  7791 V AudioManager: registerRemoteController: size of Media player list: 0
08-29 13:12:43.568  7791  7791 E AudioManager: No RCC entry present to update
08-29 13:12:43.568  7791  7791 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 13:12:43.568  7791  8039 V LGMDMManager: Create singleton instance
08-29 13:12:43.570  7791  7791 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-29 13:12:43.571  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-29 13:12:43.571  7791  7791 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-29 13:12:43.573  7791  8039 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 13:12:43.574  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-29 13:12:43.654  1043  1565 V SIM_STK : Menu title from STK is T-Mobile
08-29 13:12:43.654  1043  1565 V SIM_STK : Menu title from STK is T-Mobile
,08-29 13:12:43.728  1043  1985 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-29 13:12:43.736  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 13:12:43.739  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 13:12:43.740  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 13:12:43.740  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 13:12:43.740  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 13:12:43.740  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 13:12:43.740  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 13:12:43.740  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 13:12:43.740  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 13:12:43.740  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 13:12:43.740  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 13:12:43.741  7791  7791 I BluetoothA2dpServiceJni: classInitNative
08-29 13:12:43.741  7791  7791 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 13:12:43.741  7791  7791 D A2dpStateMachine: make
08-29 13:12:43.744  7791  7791 I bluedroid-qcom: get_profile_interface a2dp
08-29 13:12:43.744  7791  8068 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-29 13:12:43.749  7791  7791 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-29 13:12:43.749  7791  7791 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-29 13:12:43.750  7791  7791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd34abc
08-29 13:12:43.750  7791  8067 D A2dpStateMachine: Enter Disconnected: -2
08-29 13:12:43.751  7791  7791 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 13:12:43.753  7791  7791 D HidService: Received start request. Starting profile...
08-29 13:12:43.753  7791  7791 I bluedroid-qcom: get_profile_interface hidhost
08-29 13:12:43.753  7791  7791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd34abc
08-29 13:12:43.753  7791  7791 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 13:12:43.754  7791  7791 D HealthService: Received start request. Starting profile...
08-29 13:12:43.758  7791  7791 I bluedroid-qcom: get_profile_interface health
08-29 13:12:43.758  7791  7791 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-29 13:12:43.758  7791  7791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd34abc
08-29 13:12:43.759  7791  7791 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 13:12:43.764  7791  7791 D PanService: Received start request. Starting profile...
08-29 13:12:43.764  7791  7791 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 13:12:43.764  7791  7791 I bluedroid-qcom: get_profile_interface pan
08-29 13:12:43.770  7791  7791 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-29 13:12:43.770  7791  7791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd34abc
08-29 13:12:43.771  7791  7791 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-29 13:12:43.774  7791  7791 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 13:12:43.775  7791  7791 D BtGatt.GattService: Received start request. Starting profile...
08-29 13:12:43.775  7791  7791 D BtGatt.GattService: start()
08-29 13:12:43.775  7791  7791 I bluedroid-qcom: get_profile_interface gatt
08-29 13:12:43.775  7791  7791 D BtGatt.AdvertiseManager: advertise manager created
08-29 13:12:43.786  7791  7791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd34abc
08-29 13:12:43.787  7791  7791 D HeadsetStateMachine: Proxy object connected
,08-29 13:12:43.788  7791  7791 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,08-29 13:12:43.789  7791  7791 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-29 13:12:43.793  7791  7791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd34abc
08-29 13:12:43.794  7791  7791 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-29 13:12:43.797  7791  7791 V BluetoothMapService: BluetoothMapBinder()
08-29 13:12:43.798  7791  7791 D BluetoothMapService: Received start request. Starting profile...
08-29 13:12:43.798  7791  7791 D BluetoothMapService: start()
,08-29 13:12:43.805  7791  7791 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-29 13:12:43.805  7791  7791 D BluetoothMapEmailAppObserver: createReceiver()
08-29 13:12:43.810  7791  7791 D BluetoothMapEmailAppObserver: initObservers()
08-29 13:12:43.810  7791  7791 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-29 13:12:43.828  7791  7791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd34abc
,08-29 13:12:43.829  7791  8061 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-29 13:12:43.829  7791  8061 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 13:12:43.830  7791  8061 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-29 13:12:43.834  7791  7791 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 13:12:43.836  7791  7791 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:43.842  7791  7791 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-29 13:12:43.845  7791  7791 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 13:12:43.850  7791  7791 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 13:12:43.854  7791  7791 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-29 13:12:43.854  7791  7791 V PanService: [BTUI] SIM Extra State :ABSENT
08-29 13:12:43.858  7791  7791 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-29 13:12:43.858  7791  7791 V BluetoothMapService: Handler(): got msg=1
08-29 13:12:43.859  7791  8039 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-29 13:12:43.859  7791  8039 I bluedroid-qcom: enable
,08-29 13:12:43.860  7791  8039 I bt_hci_bdroid: init
,08-29 13:12:43.861  7791  8039 I bt_vendor: bt-vendor : init
08-29 13:12:43.861  7791  8039 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 13:12:43.861  7791  8039 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 13:12:43.861  7791  8039 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-29 13:12:43.861  7791  8039 D bt_userial_mct: userial_init
08-29 13:12:43.862  7791  7791 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-29 13:12:43.862  7791  7791 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 13:12:43.862  7791  7791 V BluetoothSapReceiver: SapReceiver onReceive 
08-29 13:12:43.862  7791  7791 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:43.862  7791  7791 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-29 13:12:43.863  7791  8078 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 13:12:43.864  7791  8078 I bt-btu  : btu_task pending for preload complete event
08-29 13:12:43.864  7791  8039 D bt_hci_bdroid: set_power 1
08-29 13:12:43.865  7791  8039 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 13:12:43.865  7791  8039 I bt_vendor: Starting hciattach daemon
08-29 13:12:43.865  7791  8039 I bt_vendor: try to set true
08-29 13:12:43.858  8081  8081 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:43.858  8081  8081 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-29 13:12:43.899  8082  8082 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 13:12:44.007  8088  8088 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 13:12:44.022  8089  8089 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 13:12:44.060  8091  8091 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 13:12:44.072  8092  8092 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 13:12:44.084  8093  8093 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 13:12:44.096  8094  8094 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-29 13:12:44.124  8096  8096 I libmdmdetect: ESOC framework not supported
,08-29 13:12:44.126  8096  8096 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 13:12:44.134  8096  8096 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-29 13:12:44.134  8096  8096 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-29 13:12:44.135  8096  8096 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-29 13:12:44.135  8096  8096 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-29 13:12:44.135  8096  8096 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-29 13:12:44.135  8096  8096 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-29 13:12:44.135  8096  8096 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-29 13:12:44.179  8096  8097 E QC-QMI  : qmi_client [8096] 15: failed to locate client data
08-29 13:12:44.180   474   474 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-29 13:12:44.180   474   474 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-29 13:12:44.238  8098  8098 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-29 13:12:44.268  8099  8099 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 13:12:44.323  7791  8039 I bt_vendor: bluetooth satus is on
08-29 13:12:44.323  7791  8039 D bt_hci_bdroid: preload
08-29 13:12:44.324  7791  8080 D bt_userial_mct: userial_open(port:0)
08-29 13:12:44.324  7791  8080 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-29 13:12:44.328  7791  8080 I bt_vendor: Done intiailizing UART
,08-29 13:12:44.332  7791  8080 I bt_vendor: Done intiailizing UART
08-29 13:12:44.332  7791  8080 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 13:12:44.333  7791  8080 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 13:12:44.333  7791  8104 D bt_userial_mct: Entering userial_read_thread()
08-29 13:12:44.334  7791  8078 I bt-btu  : btu_task received preload complete event
08-29 13:12:44.335  7791  8078 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-29 13:12:44.335  7791  8078 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-29 13:12:44.341  7791  8078 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_GAP
,08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 13:12:44.351  7791  8078 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 13:12:44.448  7791  8078 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-29 13:12:44.449  7791  8078 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0209061 
08-29 13:12:44.449  7791  8078 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0209061 
,08-29 13:12:44.485  7791  8043 E bt-btif : Calling BTA_HhEnable
08-29 13:12:44.485  7791  8043 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-29 13:12:44.485  7791  8043 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-29 13:12:44.492  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-29 13:12:44.493  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
08-29 13:12:44.494  7791  8043 D BluetoothAdapterProperties: Name is: G3
08-29 13:12:44.496  7791  8043 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:12:44.496  7791  8043 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:12:44.497  7791  8043 D bt_hci_bdroid: postload
08-29 13:12:44.499  7791  8043 D bte_conf: Device ID record 1 : primary
08-29 13:12:44.499  7791  8043 D bte_conf:   vendorId            = 00c4
08-29 13:12:44.499  7791  8043 D bte_conf:   vendorIdSource      = 0001
08-29 13:12:44.499  7791  8043 D bte_conf:   product             = 13a1
08-29 13:12:44.499  7791  8043 D bte_conf:   version             = 1000
08-29 13:12:44.499  7791  8043 D bte_conf:   clientExecutableURL = 
08-29 13:12:44.499  7791  8043 D bte_conf:   serviceDescription  = 
08-29 13:12:44.499  7791  8043 D bte_conf:   documentationURL    = 
08-29 13:12:44.503  7791  8080 D bt_hci_bdroid: Used up Tx Cmd credits
,08-29 13:12:44.506  7791  8043 D bte_conf: bte_load_did_conf no section named DID2.
08-29 13:12:44.510  7791  8039 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 13:12:44.511  7791  8039 D BluetoothAdapterProperties: ScanMode =  20
08-29 13:12:44.511  7791  8039 D BluetoothAdapterProperties: State =  11
08-29 13:12:44.511  7791  8039 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-29 13:12:44.511  7791  8039 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-29 13:12:44.511  7791  8039 D BluetoothAdapterProperties: Setting state to 12
08-29 13:12:44.511  7791  8039 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 13:12:44.512  7791  8043 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 13:12:44.508  8109  8109 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:44.515  1043  1120 D BluetoothManagerService: Message: 60
08-29 13:12:44.515  1043  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-29 13:12:44.515  1043  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-29 13:12:44.508  8109  8109 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:44.524  7791  8080 D bt_hci_bdroid: Used up Tx Cmd credits
08-29 13:12:44.538  7791  8104 E bt_mct  : hci lib postload completed
,08-29 13:12:44.550  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:44.550  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:44.550  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:44.550  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:44.550  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:44.550  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:44.550  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:44.550  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:44.553  7791  8043 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:12:44.554  7791  8043 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-29 13:12:44.555  7791  8039 I BluetoothAdapterState: Entering On State
08-29 13:12:44.555  1843  2420 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:44.564  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:44.576  7791  8039 D LGBluetoothServiceAdapter: [BTUI] OnState
08-29 13:12:44.576  7791  8039 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-29 13:12:44.576  7791  8039 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-29 13:12:44.584  7791  8039 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-29 13:12:44.589  1843  1843 D BluetoothHeadset: Proxy object connected
08-29 13:12:44.589  1843  2434 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:44.591  1843  1843 D BluetoothHeadset: Proxy object connected
08-29 13:12:44.592  6928  6943 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:44.596  7791  8078 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-29 13:12:44.596  7791  8078 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-29 13:12:44.596  7791  8078 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-29 13:12:44.599  7791  8078 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-29 13:12:44.599  7791  8078 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-29 13:12:44.599  7791  8078 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-29 13:12:44.600  7791  8043 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 13:12:44.612  7791  8039 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-29 13:12:44.617  6928  7672 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:12:44.624  7791  8078 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:12:44.624  7791  8078 W bt-smp  : Plain text(LSB ~ MSB) = 6c e2 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 13:12:44.624  7791  8078 W bt-smp  : Encrypted text(LSB ~ MSB) = c8 4d fb 37 f1 99 2d ba 8e 60 6c 47 a7 2c 60 d0 
,08-29 13:12:44.626  7791  8078 W bt-btm  : Stopping oneshot timer
08-29 13:12:44.640  8115  8115 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-29 13:12:44.651  6928  6928 D BluetoothHeadset: Proxy object connected
,08-29 13:12:44.651  6928  6928 D HeadsetProfile: Bluetooth service connected
08-29 13:12:44.652  6928  6943 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 13:12:44.659  6928  6928 D BluetoothInputDevice: Proxy object connected
08-29 13:12:44.659  6928  6928 D HidProfile: Bluetooth service connected
08-29 13:12:44.660  6928  7672 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 13:12:44.665  1043  1120 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 13:12:44.666  6928  6928 D BluetoothA2dp: Proxy object connected
08-29 13:12:44.666  1043  1043 D BluetoothA2dp: Proxy object connected
08-29 13:12:44.666  6928  6928 D A2dpProfile: Bluetooth service connected
08-29 13:12:44.666  1843  1858 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:44.668  1843  1843 D BluetoothHeadset: Proxy object connected
,08-29 13:12:44.668  6928  6944 D BluetoothPan: onBluetoothStateChange on: true
08-29 13:12:44.668  6928  6944 D BluetoothPan: onBluetoothStateChange call bindService
08-29 13:12:44.669  7791  8078 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:12:44.669  7791  8078 W bt-smp  : Plain text(LSB ~ MSB) = 02 11 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 13:12:44.669  7791  8078 W bt-smp  : Encrypted text(LSB ~ MSB) = 66 64 9f b1 b8 01 56 09 3d e2 7a 03 15 83 70 63 
08-29 13:12:44.669  7791  8078 W bt-btm  : Stopping oneshot timer
08-29 13:12:44.670  6928  7672 D BluetoothMap: onBluetoothStateChange: up=true
08-29 13:12:44.671  6928  6928 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 13:12:44.671  6928  6928 D PanProfile: Bluetooth service connected
08-29 13:12:44.673  1043  1120 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:44.673  6928  6928 D BluetoothMap: Proxy object connected
08-29 13:12:44.673  6928  6928 D MapProfile: Bluetooth service connected
08-29 13:12:44.673  6928  6928 D BluetoothMap: getConnectedDevices()
08-29 13:12:44.674  1043  1043 D BluetoothHeadset: Proxy object connected
08-29 13:12:44.674  7791  7808 V BluetoothMapService: getConnectedDevices()
,08-29 13:12:44.677  1043  1120 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-29 13:12:44.677  1043  1120 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-29 13:12:44.679  1931  1931 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:44.679  1931  2094 D LGBluetoothAPIService: Message: 1
08-29 13:12:44.679  1931  2094 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-29 13:12:44.679  1931  2094 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-29 13:12:44.679  1931  2094 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-29 13:12:44.680  7791  8078 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:12:44.680  7791  8078 W bt-smp  : Plain text(LSB ~ MSB) = fe f2 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 13:12:44.680  7791  8078 W bt-smp  : Encrypted text(LSB ~ MSB) = fd 8d ef 23 50 2e 5a fc 28 8c 33 65 51 d3 38 74 
08-29 13:12:44.680  7791  8078 W bt-btm  : Stopping oneshot timer
08-29 13:12:44.681  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:44.682  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-29 13:12:44.682  1043  1120 D BluetoothManagerService: Message: 40
08-29 13:12:44.682  1043  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-29 13:12:44.683  1592  1592 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-29 13:12:44.687  7791  7791 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:44.687  7791  7791 D BluetoothMapService: STATE_ON
,08-29 13:12:44.689  6928  6928 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-29 13:12:44.691  6928  6928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-29 13:12:44.693  7791  8078 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:12:44.693  7791  8078 W bt-smp  : Plain text(LSB ~ MSB) = c8 85 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 13:12:44.693  7791  8078 W bt-smp  : Encrypted text(LSB ~ MSB) = a4 a1 24 01 b2 b4 6d e2 6f e4 ee b5 55 ae dd 60 
08-29 13:12:44.693  7791  8078 W bt-btm  : Stopping oneshot timer
08-29 13:12:44.698  6928  6928 D DockEventReceiver: finishStartingService: stopping service
08-29 13:12:44.706  7791  8078 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-29 13:12:44.706  7791  8078 W bt-smp  : Plain text(LSB ~ MSB) = 44 47 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-29 13:12:44.706  7791  8078 W bt-smp  : Encrypted text(LSB ~ MSB) = c4 5c c5 71 38 03 04 cd 32 a9 e4 fc 50 31 3e 59 
08-29 13:12:44.706  7791  8078 W bt-btm  : Stopping oneshot timer
,08-29 13:12:44.712  7791  7791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd34abc
08-29 13:12:44.712  7791  7791 V BluetoothPbapService: Pbap Service onCreate
08-29 13:12:44.712  7791  7791 V BluetoothPbapService: Starting PBAP service
08-29 13:12:44.714  7791  7791 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-29 13:12:44.714  7791  7791 V BluetoothMapService: Handler(): got msg=1
08-29 13:12:44.715  7791  7791 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-29 13:12:44.715  7791  7791 V BluetoothPbapService: Pbap Service onBind
08-29 13:12:44.716  7791  7791 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:44.716  6928  6928 D BluetoothPbap: Proxy object connected
08-29 13:12:44.716  6928  6928 D PbapServerProfile: Bluetooth service connected
08-29 13:12:44.716  7791  7791 V BluetoothPbapService: state: 12
08-29 13:12:44.716  7791  7791 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-29 13:12:44.717  7791  7791 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:44.717  7791  7791 V BluetoothPbapReceiver: ***********state = 12
08-29 13:12:44.717  7791  8133 D BluetoothMapMasInstance: MAS initSocket()
08-29 13:12:44.717  7791  8133 D BluetoothMapMasInstance:   masId = 00
08-29 13:12:44.717  7791  8133 D BluetoothMapMasInstance:   msgTypes = 0e
08-29 13:12:44.717  7791  8133 D BluetoothMapMasInstance:   masName = SMS/MMS
08-29 13:12:44.717  7791  8133 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-29 13:12:44.718  7791  7791 V BluetoothPbapService: Handler(): got msg=1
08-29 13:12:44.720  1043  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:44.720  7791  7791 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,08-29 13:12:44.724  2186  2186 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:12:44.724  2186  2186 D c       : Getting all permits...
08-29 13:12:44.724  2186  2186 D a       : Opening database...
08-29 13:12:44.728  2186  2186 D a       : Opening database auth.proximity.permit_store...
08-29 13:12:44.729  2186  2186 D a       : Closing database...
08-29 13:12:44.730  7791  8134 V BluetoothPbapService: Pbap Service initSocket
,08-29 13:12:44.730  7791  8133 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:12:44.735  7791  8133 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-29 13:12:44.735  7791  8133 V BluetoothMapMasInstance: Succeed to create listening socket 
08-29 13:12:44.735  7791  8133 D BluetoothMapMasInstance: Accepting socket connection...
08-29 13:12:44.737  1043  1949 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 13:12:44.737  7791  8043 D BluetoothAdapterProperties: Scan Mode:21
08-29 13:12:44.737  7791  8043 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-29 13:12:44.739  7791  8134 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:12:44.740  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:44.742  7791  8134 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-29 13:12:44.742  7791  8134 V BluetoothPbapService: Succeed to create listening socket 
08-29 13:12:44.742  7791  8134 V BluetoothPbapService: Accepting socket connection...
08-29 13:12:44.746  6928  6928 D BluetoothPermissionRequest: onReceive
08-29 13:12:44.748  6928  6928 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-29 13:12:44.749  6928  6928 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-29 13:12:44.752  7791  7791 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-29 13:12:44.753  7791  7791 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-29 13:12:44.759  7791  7791 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-29 13:12:44.782  7791  7791 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-29 13:12:44.782  7791  7791 V BtOppService: onCreate
,08-29 13:12:44.787  7791  7791 V BluetoothOppNotification: send message
08-29 13:12:44.791  7791  7791 V BtOppService: Starting RfcommListener
08-29 13:12:44.800  7791  7791 D BluetoothOppPreference: Dumping Names:  
08-29 13:12:44.800  7791  7791 D BluetoothOppPreference: {}
08-29 13:12:44.800  7791  7791 D BluetoothOppPreference: Dumping Channels:  
08-29 13:12:44.800  7791  7791 D BluetoothOppPreference: {}
08-29 13:12:44.801  7791  7791 V BtOppService: onStartCommand
08-29 13:12:44.802  7791  8141 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-29 13:12:44.804  7791  7791 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:44.804  7791  7791 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-29 13:12:44.807  7791  7791 V BluetoothOppNotification: new notify threadi!
08-29 13:12:44.809  7791  8141 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 13:12:44.809  7791  7791 V BluetoothOppNotification: send delay message
08-29 13:12:44.809  7791  8138 V BtOppService: Deleted complete outbound shares, number =  0
08-29 13:12:44.810  7791  7791 V BtOppService: start RfcommListener
08-29 13:12:44.810  7791  8142 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-29 13:12:44.811  7791  8138 V BtOppService: Deleted complete inbound failed shares, number = 0
08-29 13:12:44.812  7791  8138 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-29 13:12:44.812  7791  8141 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23100438 on behalf of 
08-29 13:12:44.813  7791  8138 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a6b0c11 on behalf of 
08-29 13:12:44.814  7791  8142 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33678176 on behalf of 
08-29 13:12:44.814  7791  7791 V BtOppService: RfcommListener started
,08-29 13:12:44.816  7791  7791 V BtOppService: ContentObserver received notification
08-29 13:12:44.817  7791  8143 V BtOppRfcommListener: Starting RFCOMM listener....
08-29 13:12:44.818  1043  1948 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:44.821  7791  8143 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:12:44.822  7791  8143 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-29 13:12:44.822  7791  8143 V BtOppRfcommListener: Started RFCOMM listener....
08-29 13:12:44.822  7791  8141 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 13:12:44.822  7791  8143 I BtOppRfcommListener: Accept thread started.
08-29 13:12:44.822  7791  8141 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 13:12:44.822  7791  8143 V BtOppRfcommListener: Accepting connection...
08-29 13:12:44.826  7791  8142 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-29 13:12:44.828  7791  8142 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 13:12:44.830  7791  8141 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c84377 on behalf of 
08-29 13:12:44.831  7791  8142 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5dd2be4 on behalf of 
08-29 13:12:44.831  7791  8141 V BluetoothOppNotification: update too frequent, put in queue
08-29 13:12:44.832  7791  8141 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 13:12:44.832  7791  8142 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 13:12:44.834  7791  8142 V BluetoothOppNotification: outbound notification was removed.
08-29 13:12:44.835  7791  8142 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 13:12:44.837  7791  8142 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38e3584d on behalf of 
08-29 13:12:44.838  7791  8142 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 13:12:44.841  7791  8142 V BluetoothOppNotification: inbound notification was removed.
08-29 13:12:44.841  7791  8142 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-29 13:12:44.841  7791  7791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd34abc
,08-29 13:12:44.841  7791  7791 V BluetoothFtpService: Ftp Service onCreate
08-29 13:12:44.841  7791  7791 I BluetoothFtpService: Ftp Service onCreate
08-29 13:12:44.842  7791  7791 V BluetoothFtpService: Ftp Service onStartCommand
08-29 13:12:44.842  7791  7791 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:44.842  7791  7791 V BluetoothFtpService: Starting Listening on sockets
08-29 13:12:44.843  7791  7791 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-29 13:12:44.843  7791  7791 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-29 13:12:44.843  7791  7791 V BluetoothSapReceiver: SapReceiver onReceive 
,08-29 13:12:44.843  7791  7791 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:44.843  7791  7791 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
,08-29 13:12:44.844  7791  7791 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-29 13:12:44.844  7791  8142 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26f3a013 on behalf of 
08-29 13:12:44.846  7791  7791 V BtOppService: ContentObserver received notification
08-29 13:12:44.846  7791  7791 V BluetoothFtpService: Handler(): got msg=1
08-29 13:12:44.847  7791  8145 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-29 13:12:44.848  7791  8145 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-29 13:12:44.849  7791  7791 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-29 13:12:44.849  7791  7791 V BluetoothFtpService: Ftp Service initSocket
08-29 13:12:44.850  7791  8145 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32332250 on behalf of 
08-29 13:12:44.851  7791  8145 V BluetoothOppNotification: update too frequent, put in queue
08-29 13:12:44.852  1043  1764 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:44.852  7791  7791 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:12:44.853  7791  8145 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-29 13:12:44.854  7791  7791 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-29 13:12:44.856  7791  8146 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-29 13:12:44.870  7791  7791 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd34abc
,08-29 13:12:44.870  7791  7791 V BluetoothSapService: Sap Service onCreate
,08-29 13:12:44.872  7791  7791 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:44.872  7791  7791 V BluetoothSapService: state: 12
08-29 13:12:44.872  7791  7791 V BluetoothSapService: Starting SAP server process
08-29 13:12:44.874  7791  7791 V BluetoothSapService: SAP Service startRfcommListenerThread
08-29 13:12:44.875  7791  8148 V BluetoothSapService: Sap Service initRfcommSocket
,08-29 13:12:44.868  8147  8147 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:44.876  1043  1949 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:44.868  8147  8147 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:44.877  7791  8148 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:12:44.878  7791  8148 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-29 13:12:44.878  7791  8148 V BluetoothSapService: Succeed to create listening socket 
08-29 13:12:44.878  7791  8148 V BluetoothSapService: Accepting socket connection...
08-29 13:12:44.900  8147  8147 V BT_SAP  : Event pipe created
08-29 13:12:44.900  8147  8147 V BT_SAP  : create_server_socket qcom.sap.server
08-29 13:12:44.900  8147  8147 V BT_SAP  : created socket fd 6
,08-29 13:12:45.277  6705  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:45.277  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:45.277  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:45.277  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:45.277  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:45.277  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:45.277  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:45.277  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:45.286  6705  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:45.287  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:45.287  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f52c969 added. We now have 8 listener(s)
08-29 13:12:45.287  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:45.293  1043  1986 D WifiServiceImplEx: setWifiEnabled: false pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 13:12:45.295  1043  1986 D WifiService: setWifiEnabled: false pid=6705, uid=10118
08-29 13:12:45.295  1043  1986 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:12:45.303  6705  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:45.304  1043  1764 D WifiServiceImplEx: setWifiEnabled: true pid=6705, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-29 13:12:45.304  1043  1764 D WifiService: setWifiEnabled: true pid=6705, uid=10118
08-29 13:12:45.304  1043  1764 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:12:45.323  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-29 13:12:45.323  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-29 13:12:45.323  1043  1043 D Ulp_jni : JNI:system_update. Event-4
,08-29 13:12:45.325  1043  1428 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-29 13:12:45.325  1043  1428 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-29 13:12:45.328  1043  1428 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-29 13:12:45.328  1043  1428 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 13:12:45.328  1043  1428 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,08-29 13:12:45.328  1043  1428 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-29 13:12:45.328  1043  1428 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,08-29 13:12:45.328  1043  1428 E WifiHW  : unknown target_country: EU , set to default
08-29 13:12:45.328  1043  1428 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-29 13:12:45.328  1043  1428 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-29 13:12:45.328  1043  1428 I WifiUtil: gEnableBmps=1
,08-29 13:12:45.811  7791  7791 V BluetoothOppNotification: new notify threadi!,
08-29 13:12:45.811  7791  7791 V BluetoothOppNotification: send delay message
,08-29 13:12:45.837  7791  8167 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-29 13:12:45.845  7791  8167 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37b0137c on behalf of 
08-29 13:12:45.846  7791  8167 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-29 13:12:45.847  7791  8167 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-29 13:12:45.848  7791  8167 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29d04405 on behalf of 
08-29 13:12:45.849  7791  8167 V BluetoothOppNotification: outbound: succ-0  fail-0
08-29 13:12:45.850  7791  8167 V BluetoothOppNotification: outbound notification was removed.
08-29 13:12:45.850  7791  8167 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-29 13:12:45.851  7791  8167 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2344ac5a on behalf of 
08-29 13:12:45.852  7791  8167 V BluetoothOppNotification: inbound: succ-0  fail-0
08-29 13:12:45.855  7791  8167 V BluetoothOppNotification: inbound notification was removed.
08-29 13:12:45.855  7791  8167 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-29 13:12:45.858  7791  8167 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@185cfe8b on behalf of 
,08-29 13:12:45.918   323   896 D SoftapController: Softap fwReload - Ok
,08-29 13:12:45.934  1043  1428 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (601ms)
,08-29 13:12:45.939  1043  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 13:12:45.939  1043  1120 D Tethering: InitialState.processMessage what=4
,08-29 13:12:45.950   323   896 D CommandListener: Setting iface cfg
08-29 13:12:45.950   323   896 D CommandListener: Trying to bring down wlan0
08-29 13:12:45.954   323   896 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:12:45.956  1043  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 13:12:45.968  1043  1428 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-29 13:12:45.968  8169  8169 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:45.982  1043  1428 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:12:45.982  1043  1428 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:12:45.982  1043  1428 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 13:12:45.978  8169  8169 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:45.995  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 13:12:46.004  1931  1931 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-29 13:12:46.023  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-29 13:12:46.036  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:46.051  1043  1428 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 13:12:46.051  1043  1428 D WifiMonitor: connecting to supplicant
08-29 13:12:46.056  8169  8169 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 13:12:46.060  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 13:12:46.060  6928  6928 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 13:12:46.060  6928  6928 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 13:12:46.060  6928  6928 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 13:12:46.061  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 13:12:46.062  6928  6928 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 13:12:46.062  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 13:12:46.062  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 13:12:46.062  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 13:12:46.062  6928  6928 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 13:12:46.062  6928  6928 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 13:12:46.065  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 13:12:46.065  6928  6928 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-29 13:12:46.065  6928  6928 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 13:12:46.065  6928  6928 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 13:12:46.066  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 13:12:46.067  6928  6928 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 13:12:46.067  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-29 13:12:46.067  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 13:12:46.067  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 13:12:46.067  6928  6928 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 13:12:46.067  6928  6928 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 13:12:46.094  8169  8169 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 13:12:46.094  8169  8169 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-29 13:12:46.114  1043  1950 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8187 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-29 13:12:46.152  8169  8169 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 13:12:46.186  8169  8169 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-29 13:12:46.194  1043  1428 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-29 13:12:46.195  1043  1428 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-29 13:12:46.195  1043  1428 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-29 13:12:46.196  1043  1428 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-29 13:12:46.196  1043  1428 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:46.196  1043  1428 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-29 13:12:46.197  1043  1428 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:46.197  1043  1428 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:46.198  1043  1428 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-29 13:12:46.198  1043  1428 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-29 13:12:46.199  1043  1428 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-29 13:12:46.199  1043  1428 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-29 13:12:46.199  1043  1428 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-29 13:12:46.215  1043  1895 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8209 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 13:12:46.217  1043  1428 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-29 13:12:46.217  1043  1428 E WifiStateMachine: useWiFiOffloading() : false
08-29 13:12:46.217  1043  1428 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-29 13:12:46.217  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:46.217  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:12:46.218  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:46.218  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:46.218  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-29 13:12:46.219  1043  1428 D WifiNative-wlan0: doBoolean: SET update_config 1
08-29 13:12:46.220  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:46.220  1043  1428 D WifiNative-wlan0: SET update_config 1: returned true
08-29 13:12:46.220  1043  1428 D WifiConfigStore: Loading config and enabling all networks 
08-29 13:12:46.220  1043  1428 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-29 13:12:46.221  1931  1931 D WfdService: Waiting for WifiP2p enabling
08-29 13:12:46.222  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-29 13:12:46.223  1043  1428 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-29 13:12:46.223  1043  1463 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-29 13:12:46.224  8187  8206 W FormManager: Network not available. Please check & try again.
08-29 13:12:46.225  1043  8208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 13:12:46.225  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 13:12:46.225  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:46.225  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:46.225  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:46.225  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:46.225  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:46.225  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:46.225  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:46.225  6705  6705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:46.226  8169  8169 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-29 13:12:46.226  1043  8208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-29 13:12:46.226  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-29 13:12:46.226  1043  8208 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-29 13:12:46.226  1043  8208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-29 13:12:46.227  6705  6705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:46.235  8187  8207 V FormManager: Network unavailable.
08-29 13:12:46.237  8187  8207 V FormManager: Network unavailable.
,08-29 13:12:46.244  1043  1428 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-29 13:12:46.248  1043  1565 I ActivityManager: Killing 7235:com.lge.drmservice/u0a62 (adj 15): empty #17
08-29 13:12:46.254  1043  1428 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-29 13:12:46.254  1043  1428 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 13:12:46.287  1043  2023 W libprocessgroup: failed to open /acct/uid_10062/pid_7235/cgroup.procs: No such file or directory
08-29 13:12:46.287  1043  1428 D WifiStateMachine: enableVerboseLogging : level 2
08-29 13:12:46.287  1043  1428 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-29 13:12:46.287  1043  1428 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-29 13:12:46.287  1043  1428 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-29 13:12:46.288  1043  1428 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-29 13:12:46.288  1043  1428 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-29 13:12:46.288  1043  1428 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-29 13:12:46.288  1043  1428 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-29 13:12:46.289  1043  1428 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-29 13:12:46.289  1043  1428 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-29 13:12:46.289  1043  1428 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-29 13:12:46.289  1043  1428 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-29 13:12:46.290  1043  1428 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-29 13:12:46.290  1043  1428 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-29 13:12:46.290  1043  1428 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-29 13:12:46.290  1043  1428 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 13:12:46.290  1043  1428 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-29 13:12:46.291  1931  1931 D WfdsService: Supplicant Connection state is changed : true
08-29 13:12:46.291  1931  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-29 13:12:46.291  1931  2284 D WfdsService: Set the WFDS Monitor: true
08-29 13:12:46.291  1931  2284 D WfdsMonitor: WfdsMonitorThread create
08-29 13:12:46.291  1931  2284 D WfdsMonitor: WFDS Monitor is created and started
08-29 13:12:46.291  1931  2284 D WfdsService: WiFi: Supplicant connection re-established
08-29 13:12:46.291  1043  1428 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-29 13:12:46.291  1043  1428 D WifiNative-HAL: Setting external_sim to 1
08-29 13:12:46.291  1043  1428 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-29 13:12:46.292  1043  1428 D WifiNative-wlan0: SET external_sim 1: returned true
08-29 13:12:46.292  1043  1428 I WifiNative-HAL: startHal
08-29 13:12:46.292  1931  8227 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-29 13:12:46.292  1043  1428 D wifi    : setting scan oui 0x956ea1e0
08-29 13:12:46.292  1043  1428 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 13:12:46.292  1043  1428 I WifiNative-HAL: startHal
08-29 13:12:46.292  1931  8227 E CtrlSupplicant: Succeed to open control connection
08-29 13:12:46.292  1043  1428 D wifi    : setting scan oui 0x956ea1e0
08-29 13:12:46.293  1043  1428 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-29 13:12:46.293  1931  8227 E CtrlSupplicant: Succeed to open monitor connection
08-29 13:12:46.293  1931  8227 D WfdsMonitor: Supplicant connection established
08-29 13:12:46.293  1931  2284 D WfdsService: Connected to the supplicant for wfds
08-29 13:12:46.293  1043  1428 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-29 13:12:46.293  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-29 13:12:46.293  7822  7822 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:46.294  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-29 13:12:46.294  1043  1428 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-29 13:12:46.294  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 13:12:46.295  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILT,ER-STOP
08-29 13:12:46.295  1043  1428 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 13:12:46.295  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-29 13:12:46.295  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,08-29 13:12:46.296  1043  1428 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-29 13:12:46.296  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 13:12:46.296  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 13:12:46.301  1043  1428 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 13:12:46.301  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-29 13:12:46.301  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-29 13:12:46.301  1043  1428 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-29 13:12:46.301  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-29 13:12:46.302  8169  8169 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-29 13:12:46.302  1043  1428 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-29 13:12:46.302  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-29 13:12:46.302  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-29 13:12:46.303  1043  1428 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-29 13:12:46.304  1043  1428 E WifiNative: : [136,547,559 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-29 13:12:46.304  1043  1428 D WifiNative-wlan0: doBoolean: RECONNECT
08-29 13:12:46.305  1043  1428 D WifiNative-wlan0: RECONNECT: returned true
08-29 13:12:46.305  1043  1428 D WifiNative-wlan0: doString: [STATUS]
08-29 13:12:46.305  1043  8208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-29 13:12:46.305  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-29 13:12:46.305  1043  1428 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 13:12:46.305  1043  1428 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 13:12:46.306  1043  1428 D WifiNative-wlan0: SET ps 1: returned true
,08-29 13:12:46.307  1043  1378 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.308  1043  1428 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-29 13:12:46.308  1043  1428 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-29 13:12:46.309  1043  1428 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-29 13:12:46.309  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 13:12:46.309  1043  1043 D RttService: SCAN_AVAILABLE : 3
08-29 13:12:46.309  1043  1428 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-29 13:12:46.310  1043  1428 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-29 13:12:46.310  1043  1547 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.311  1043  1546 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.311  1043  1546 I WifiNative-HAL: startHal
08-29 13:12:46.311  1043  1428 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-29 13:12:46.311  1043  1546 D wifi    : getting scan capabilities on interface[1] = 0x956ea1e0
08-29 13:12:46.311  1043  1546 D wifi    : failed to get capabilities : -3
08-29 13:12:46.311  1043  1546 E WifiScanningService: could not get scan capabilities
08-29 13:12:46.311  1043  1428 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-29 13:12:46.311  1043  1428 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-29 13:12:46.311  8169  8169 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-29 13:12:46.312   323   896 D CommandListener: Setting iface cfg
08-29 13:12:46.312  1043  1428 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-29 13:12:46.312   323   896 D CommandListener: Trying to bring up p2p0
08-29 13:12:46.313  1043  1378 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 13:12:46.314  1043  1378 D LGWifiP2pService: P2pEnablingState
08-29 13:12:46.314  1043  1378 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.314  1043  1378 D LGWifiP2pService: P2p socket connection successful
08-29 13:12:46.314  1043  1378 D LGWifiP2pService: P2pEnabledState
08-29 13:12:46.314  1043  1428 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-29 13:12:46.315  1043  1378 D LGWifiP2pService: sending p2p connection changed broadcast
08-29 13:12:46.315  1043  1428 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-29 13:12:46.315  1043  1428 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-29 13:12:46.315  8169  8169 E wpa_supplicant: disconnect_rssi_lvl: -100
08-29 13:12:46.316  1043  1428 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=136560  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 13:12:46.316  1931  1931 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
,08-29 13:12:46.316  1931  1931 D WfdsService: WifiP2pState is changed : true
08-29 13:12:46.316  1931  2284 D WfdsService: Receive the WFDS_ENABLE Method,
08-29 13:12:46.316  1931  2284 D WfdsService: Set the WFDS Monitor: true
08-29 13:12:46.316  1931  2284 D WfdsService: Connected to the supplicant for wfds
08-29 13:12:46.316  1931  2284 D WfdsJNI : doCommand: WFDS_SET TRUE
08-29 13:12:46.316  8169  8169 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-29 13:12:46.317  1931  2284 D WfdsService: selectPreferredScanChannel [36]
08-29 13:12:46.317  1931  2284 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-29 13:12:46.317  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=136561  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 13:12:46.317  1043  1428 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
,08-29 13:12:46.318  1043  1428 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 13:12:46.318  1043  1428 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-29 13:12:46.318  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-29 13:12:46.319  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 13:12:46.319  8169  8169 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:46.320  8169  8169 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 13:12:46.320  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:46.320  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:46.320  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.320  1043  8208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-29 13:12:46.321  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:46.321  1043  8208 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:46.321  1043  8208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:46.321  1043  8208 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:46.321  1043  8208 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.321  1043  8208 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.321  1043  8208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.321  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.322  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:46.322  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:46.322  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-29 13:12:46.322  1931  8227 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:46.322  1931  8227 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:46.322  1043  8208 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:46.322  1043  8208 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.322  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:46.322  1043  8208 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.322  1043  8208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.322  1043  1428 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-29 13:12:46.323  1043  1428 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-29 13:12:46.324  1043  1428 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-29 13:12:46.324  1931  1931 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-29 13:12:46.324  1043  1428 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-29 13:12:46.324  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-29 13:12:46.324  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-29 13:12:46.324  8169  8169 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 13:12:46.325  1931  1931 D WfdsService: isConnected: false
08-29 13:12:46.325  1043  1378 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-29 13:12:46.326  1043  8208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-29 13:12:46.326  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 13:12:46.326  1043  8208 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 13:12:46.326  1043  8208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-29 13:12:46.326  1043  1428 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-29 13:12:46.326  1043  1428 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-29 13:12:46.326  1043  1378 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-29 13:12:46.327  1043  1428 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-29 13:12:46.327  1043  1378 D WifiNative-p2p0: doBoolean: SET device_name G3
08-29 13:12:46.327  1043  1428 D WifiNative-wlan0: doBoolean: SCAN
,08-29 13:12:46.327  1043  1378 D WifiNative-p2p0: SET device_name G3: returned true
08-29 13:12:46.327  1043  1378 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-29 13:12:46.327  1043  1378 D LGWifiP2pService: before postfix = G3
08-29 13:12:46.327  1043  1378 D WifiServerServiceExt: postfix byte check : 2
08-29 13:12:46.327  1043  1378 D LGWifiP2pService: after postfix = G3
08-29 13:12:46.327  1043  1378 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-29 13:12:46.327  1043  1428 D WifiNative-wlan0: SCAN: returned false
08-29 13:12:46.328  1043  1428 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=136572  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-29 13:12:46.329  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=136573  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-29 13:12:46.330  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:46.330  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:46.330  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-29 13:12:46.331  1043  1378 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-29 13:12:46.331  1043  1378 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-29 13:12:46.332  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:12:46.332  1043  1043 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 13:12:46.332  6705  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:46.332  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:46.332  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:46.332  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:46.332  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:46.332  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:46.332  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:46.332  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:46.333  6705  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:46.334  1043  1378 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-29 13:12:46.334  1043  1378 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-29 13:12:46.334  1043  1428 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:12:46.335  1043  1428 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:12:46.335  1043  1428 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:12:46.335  1043  1428 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:12:46.336  1043  1378 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-29 13:12:46.336  1043  1428 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-29 13:12:46.336  1043  1378 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-29 13:12:46.336  1043  1378 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-29 13:12:46.336  1043  1378 D WifiNative-HAL: p2pGetDeviceAddress
08-29 13:12:46.337  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:12:46.337  1043  1043 D WifiServerServiceExt: setSupplicantStateSCANNING
08-29 13:12:46.337  1043  1378 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-29 13:12:46.337  1043  1378 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-29 13:12:46.337  1043  1378 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-29 13:12:46.338  8209  8209 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:12:46.338  1931  1931 I WfdStateTracker: handleP2pThisDeviceChanged
08-29 13:12:46.339  6705  6760 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-29 13:12:46.339  1931  1931 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-29 13:12:46.339,  1931  1931 D WfdsService: Update P2p Interface State: 3
08-29 13:12:46.339  6705  6760 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 13:12:46.339  1043  1378 D WifiNative-p2p0: P2P_FLUSH: returned true
08-29 13:12:46.339  1043  1378 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-29 13:12:46.340  1043  1378 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-29 13:12:46.340  1043  1378 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-29 13:12:46.340  1043  1378 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-29 13:12:46.340  1043  1378 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-29 13:12:46.342  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:46.342  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:46.344  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:46.346  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:46.346  6705  6760 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@32178c43 Bundle[{}]
08-29 13:12:46.347  6705  6760 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 13:12:46.347  6705  6760 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 13:12:46.348  6705  6760 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 13:12:46.348  6705  6760 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 13:12:46.349  6705  6760 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 13:12:46.350  1043  1378 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-29 13:12:46.350  1043  1378 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-29 13:12:46.350  1043  1378 D LGWifiP2pService: InactiveState
08-29 13:12:46.350  1043  1378 D LGWifiP2pService: InactiveState{ when=-27ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.350  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-27ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.350  1043  1378 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-29 13:12:46.350  6705  6760 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 13:12:46.350  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-29 13:12:46.351  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:46.351  1931  8227 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 13:12:46.351  1043  8208 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-29 13:12:46.351  1043  8208 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:46.351  1043  8208 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:46.351  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:46.351  1043  8208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-29 13:12:46.351  8169  8169 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-29 13:12:46.351  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.352  1931  8227 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:46.352  1043  8208 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:46.352  1043  1950 I ActivityManager: Killing 7268:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-29 13:12:46.352  1043  8208 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.352  1043  8208 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.352  1043  8208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.352  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.353  1043  1378 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-29 13:12:46.353  1931  8227 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:46.353  1043  1378 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.i,nternal.util.StateMachine$SmHandler }
08-29 13:12:46.353  1043  8208 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-29 13:12:46.353  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.353  1043  8208 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.353  1043  1378 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.353  1043  8208 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.353  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.353  1043  8208 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-29 13:12:46.353  1043  1378 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.353  1043  1378 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:12:46.356  6705  6760 I System.out: Running OutgoingSocketThread
08-29 13:12:46.353  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.357  1043  1378 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.357  1043  1378 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.357  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.357  1043  1378 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.357  1043  1378 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.357  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.357  1043  1378 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:46.358  1043  1043 E WifiServerServiceExt: No p2p device connected
08-29 13:12:46.358  1931  2284 W WfdsService: DefaultState - msg [9441285] is not handled
08-29 13:12:46.359  6705  8231 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 881)
08-29 13:12:46.360  6705  8231 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 58923
08-29 13:12:46.360  6705  8231 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-29 13:12:46.386  1043  1061 W libprocessgroup: failed to open /acct/uid_10085/pid_7268/cgroup.procs: No such file or directory
,08-29 13:12:46.409  8209  8209 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-29 13:12:46.415  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:12:46.417  8187  8233 W FormManager: Network not available. Please check & try again.
08-29 13:12:46.420  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:46.433  8187  8234 V FormManager: Network unavailable.
,08-29 13:12:46.441  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 13:12:46.441  4806  4806 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-29 13:12:46.442  8187  8234 V FormManager: Network unavailable.
08-29 13:12:46.445  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-29 13:12:46.454  4806  4806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-29 13:12:46.458  4806  8235 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-29 13:12:46.460  4806  8236 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-29 13:12:46.461  4806  8236 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-29 13:12:46.523  1043  1060 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8237 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-29 13:12:46.543   357   357 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 431us total 23.214ms
,08-29 13:12:46.566   357   357 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 559us total 21.750ms
,08-29 13:12:46.586   357   357 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 371us total 19.121ms
,08-29 13:12:46.594  8237  8237 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-29 13:12:46.616  8237  8237 D PluginManager: init()
,08-29 13:12:46.908  8237  8237 W ExternalStrings: load override strings
08-29 13:12:46.908  8237  8237 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 13:12:46.908  8237  8237 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-29 13:12:46.914  8237  8237 D StatusProvider: onCreate
,08-29 13:12:46.922  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-29 13:12:46.922  1043  8208 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-29 13:12:46.922  1043  8208 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-29 13:12:46.922  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
08-29 13:12:46.922  1043  8208 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-29 13:12:46.925  8169  8169 E wpa_supplicant: USIM:  scard_init function
08-29 13:12:46.926  1043  1428 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 13:12:46.926  1043  1428 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 13:12:46.926  1043  1428 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 13:12:46.927  8169  8169 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-29 13:12:46.927  1043  1428 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-29 13:12:46.927  1043  1428 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-29 13:12:46.927  1043  8208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-29 13:12:46.927  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-29 13:12:46.940  1043  1428 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=137184  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-29 13:12:46.942  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=137186  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-29 13:12:46.945  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:46.945  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:46.946  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:46.946  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:46.946  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 13:12:46.948  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:46.949  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:12:46.949  1043  1043 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-29 13:12:46.955  8237  8237 V Signer  : override build config not found
08-29 13:12:46.955  8237  8237 D Signer  : value of property debug is false
,08-29 13:12:46.998  8237  8237 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-29 13:12:46.999  8237  8237 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-29 13:12:46.999  8237  8237 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-29 13:12:46.999  8237  8237 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-29 13:12:46.999  8237  8237 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-29 13:12:46.999  8237  8237 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-29 13:12:47.000  8237  8237 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-29 13:12:47.000  8237  8237 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-29 13:12:47.000  8237  8237 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-29 13:12:47.000  8237  8237 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-29 13:12:47.000  8237  8237 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-29 13:12:47.001  8237  8237 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-29 13:12:47.001  8237  8237 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-29 13:12:47.014  8237  8237 V LGMDMManager: Create singleton instance
,08-29 13:12:47.041  8169  8169 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 13:12:47.051  1043  8208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,08-29 13:12:47.052  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-29 13:12:47.052  1043  8208 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-29 13:12:47.052  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-29 13:12:47.052  1043  8208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:12:47.052  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:12:47.060  1043  1428 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=137304  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-29 13:12:47.061  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=137305  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-29 13:12:47.062  1043  1428 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137306
08-29 13:12:47.063  1043  1428 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137307
08-29 13:12:47.064  1043  1428 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137309
08-29 13:12:47.065  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137310
08-29 13:12:47.066  1043  1428 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=137310
08-29 13:12:47.067  1043  1428 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=137311  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 13:12:47.072  8169  8169 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 13:12:47.072  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:47.072  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:47.072  8169  8169 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-29 13:12:47.076  1043  8208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:12:47.076  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:12:47.077  1043  8208 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-29 13:12:47.077  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 13:12:47.077  1043  8208 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 13:12:47.077  1043  8208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
,08-29 13:12:47.077  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 13:12:47.077  1043  8208 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-29 13:12:47.077  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:47.077  1043  8208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:12:47.077  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-29 13:12:47.079  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=137324  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-29 13:12:47.080  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.080  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.080  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-29 13:12:47.080  1043  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 13:12:47.081  1043  1428 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:47.081  1043  1428 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:47.081  1043  1428 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:47.082  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:47.082  1043  1428 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-29 13:12:47.088  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.088  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.088  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-29 13:12:47.089  1043  1428 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=137333  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 13:12:47.089  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=137333  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-29 13:12:47.089  1043  1428 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=137334
08-29 13:12:47.090  1043  1428 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=137334
08-29 13:12:47.090  1043  1428 D WifiNative-wlan0: doString: [STATUS]
08-29 13:12:47.090  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:12:47.090  1043  1043 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-29 13:12:47.091  1043  8208 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-29 13:12:47.091  1043  8208 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-29 13:12:47.093  1043  1428 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-29 13:12:47.099  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:47.099  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:47.100  1043  1428 I WifiServiceExtension: setVHTCapabilityType  : false
08-29 13:12:47.103  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 13:12:47.109  1043  1428 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-29 13:12:47.109  1043  1428 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-29 13:12:47.126  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:47.126  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-29 13:12:47.127  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.127  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.127  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 13:12:47.129  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.129  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.129  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-29 13:12:47.130  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:47.131  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:47.131  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:47.132  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:47.134  1043  1428 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-29 13:12:47.134  1043  1509 D ConnectivityService: Got NetworkAgent Messenger
08-29 13:12:47.134  1043  1428 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:12:47.134  1043  1428 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 13:12:47.134  1043  1509 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 13:12:47.134  1043  1509 D ConnectivityService: NetworkAgent connected
08-29 13:12:47.134  1043  1428 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 13:12:47.135  1043  1428 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-29 13:12:47.140  1043  1428 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 13:12:47.140  1043  1428 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:12:47.140  1043  1428 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-29 13:12:47.140  1043  1428 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-29 13:12:47.140  1043  1428 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-29 13:12:47.145  1043  1428 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-29 13:12:47.146   323   896 D CommandListener: Setting iface cfg
08-29 13:12:47.151  1043  1428 E WifiStateMachine: Start Dhcp Watchdog 3
08-29 13:12:47.151  1043  8272 D DhcpStateMachine: StoppedState
08-29 13:12:47.151  1043  8272 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:47.151  1043  8272 D DhcpStateMachine: WaitBeforeStartState
,08-29 13:12:47.152  1043  1428 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=137396  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:12:47.152  1043  1428 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=137396  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:12:47.153  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=137397  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:12:47.154  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:12:47.154  1043  1043 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-29 13:12:47.154  1043  1428 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=137398  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:12:47.154  1043  1428 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=137399  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:12:47.155  1043  1428 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=137399  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-29 13:12:47.156  1043  1428 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14420] from screen [on:0 period:-704615372] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 13:12:47.156  8237  8237 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-29 13:12:47.157  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-704615371] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-29 13:12:47.157  1043  1428 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-29 13:12:47.160  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:47.161  1043  1509 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-29 13:12:47.161  1043  1428 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:47.162  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:47.162  1043  1428 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:47.162  1043  1428 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:47.163  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:47.164  1043  1428 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:47.164  1043  1509 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-29 13:12:47.164  1043  1428 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=154,0,0
08-29 13:12:47.165  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=154,0,0
08-29 13:12:47.165  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-29 13:12:47.165  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-29 13:12:47.165  1043  1428 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-29 13:12:47.165  1043  1428 D WifiNative-wlan0: doBoolean: SET ps 0
08-29 13:12:47.166  1043  1428 D WifiNative-wlan0: SET ps 0: returned true
08-29 13:12:47.166  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-29 13:12:47.166  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-29 13:12:47.166  1043  1428 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-29 13:12:47.167  1043  1378 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@24a9c4a9 target=com.android.internal.ut,il.StateMachine$SmHandler }
08-29 13:12:47.167  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@24a9c4a9 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:47.167  1043  8272 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:47.167  1043  8272 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-29 13:12:47.167  1043  1428 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-29 13:12:47.167  1043  1428 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 13:12:47.168  1043  1428 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 13:12:47.168   323   896 D CommandListener: Setting iface cfg
08-29 13:12:47.169   323   896 D CommandListener: Trying to bring up wlan0
08-29 13:12:47.169  1043  1428 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-29 13:12:47.170  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:12:47.170  1043  1043 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 13:12:47.171  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-29 13:12:47.171  1043  1043 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-29 13:12:47.172  1043  1428 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:47.172  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:47.173  1043  1428 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-29 13:12:47.173  1043  1428 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:47.173  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:47.174  1043  1428 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-29 13:12:47.174  1043  1509 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-29 13:12:47.174  1043  1428 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 13:12:47.175  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-29 13:12:47.175  1043  1378 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:47.175  1043  1378 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:12:47.176  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-29 13:12:47.176  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-29 13:12:47.176  1043  1428 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-29 13:12:47.176  1043  1428 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1,
08-29 13:12:47.177  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-29 13:12:47.177  1043  1428 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-29 13:12:47.177  1043  1428 D WifiNative-wlan0: doBoolean: SET ps 1
08-29 13:12:47.193  1043  1428 D WifiNative-wlan0: SET ps 1: returned true
08-29 13:12:47.194  1043  1509 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-29 13:12:47.194  1043  1428 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-29 13:12:47.194  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-29 13:12:47.194  1043  1428 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 13:12:47.195  1043  1509 D ConnectivityService: ignoring duplicate network state non-change
08-29 13:12:47.197  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:47.197  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:47.198  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:47.198  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.198  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.198  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 13:12:47.200  1043  1509 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 13:12:47.201  1043  1509 D ConnectivityService: Adding iface wlan0 to network 102
08-29 13:12:47.204  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.204  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.204  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-29 13:12:47.207  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-29 13:12:47.210  1931  1931 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-29 13:12:47.212  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.212  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.212  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-29 13:12:47.215  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-29 13:12:47.219  1043  1428 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 13:12:47.220  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:47.220  1592  1592 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-29 13:12:47.221  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.221  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:47.221  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-29 13:12:47.222  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-29 13:12:47.223  1043  1509 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 13:12:47.223  1043  1509 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-29 13:12:47.224  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:47.224  1592  1592 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 13:12:47.224  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:47.224  1043  1509 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-29 13:12:47.225   323   896 E Netd    : netlink response contains error (File exists)
08-29 13:12:47.226  1043  1509 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-29 13:12:47.226  1043  1509 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-29 13:12:47.226  1043  1509 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-29 13:12:47.226  1043  1509 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-29 13:12:47.227  1043  1509 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 13:12:47.227  1043  1509 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 13:12:47.227  1592  1592 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:47.227  1592  1592 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-29 13:12:47.227  1043  1509 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-29 13:12:47.227  1043  1509 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-29 13:12:47.227  1043  8269 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:47.227  1043  1509 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:12:47.227  1043  8269 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-29 13:12:47.227  1043  1509 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:12:47.227  1043  1509 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-29 13:12:47.227  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:47.227  1043  8269 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:47.228  1043  1509 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:47.228  1043  8269 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-29 13:12:47.228  1043  1509 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-29 13:12:47.228  1043  1509 D ConnectivityService: currentScore = 0, newScore = 20
08-29 13:12:47.228  1043  1509 D ConnectivityService:    accepting network in place of null
08-29 13:12:47.228  1043  1509 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&T,RUSTED&NOT_VPN] ]
08-29 13:12:47.228  1043  1428 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:47.228  1043  1428 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:12:47.229  1843  1843 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:47.229  1843  1843 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-29 13:12:47.230  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:47.230  1043  1509 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 13:12:47.230  1043  1509 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-29 13:12:47.230  1043  1509 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 13:12:47.231   323  8280 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-29 13:12:47.234  8237  8278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 13:12:47.236  1043  1509 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:47.236  1043  1509 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-29 13:12:47.237  1043  1509 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-29 13:12:47.238  1043  1509 D ConnectivityService: validation of new default Network = false
08-29 13:12:47.238  1043  1509 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-29 13:12:47.238  1043  1509 D DSQN    : enableDataServiceNotify 
08-29 13:12:47.238  1043  1509 D DSQN    : start dsqn bin
,08-29 13:12:47.240  1043  1043 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-29 13:12:47.241  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-29 13:12:47.241  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-29 13:12:47.241  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-29 13:12:47.228  8281  8281 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:47.243  1043  1509 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-29 13:12:47.243  1043  1509 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:47.228  8281  8281 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:47.243  1043  1509 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:12:47.244  1043  1509 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:12:47.244  1592  2041 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 13:12:47.249  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:47.256  8281  8281 E DSQN    : DSQN ssw
08-29 13:12:47.257  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:47.265  8003  8003 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:47.265  1043  1377 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-29 13:12:47.267  8003  8003 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 13:12:47.274  1592  1592 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-29 13:12:47.275  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:47.275  1592  1592 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-29 13:12:47.276  8003  8003 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:12:47.312  1043  1986 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8289 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-29 13:12:47.314  1043  1986 I ActivityManager: Killing 7327:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-29 13:12:47.361  6705  6760 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 882)
08-29 13:12:47.361  6705  6760 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 882)
,08-29 13:12:47.367  6705  6760 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 887)
08-29 13:12:47.368  1043  8272 D DhcpStateMachine: DHCPV4 request on wlan0
08-29 13:12:47.369  1043  8272 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-29 13:12:47.369  1043  8272 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-29 13:12:47.369  6705  6760 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 13:12:47.369  6705  6760 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 888)
,08-29 13:12:47.372  8237  8277 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-29 13:12:47.358  8306  8306 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:47.358  8306  8306 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-29 13:12:47.379  8306  8306 I dhcpcd  : version 5.5.6 starting
08-29 13:12:47.379  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:47.379  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fd3efee added. We now have 2 listener(s)
08-29 13:12:47.381  8306  8306 E dhcpcd  : get_duid: m
08-29 13:12:47.381  8306  8306 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-29 13:12:47.381  8306  8306 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-29 13:12:47.445  8306  8306 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-29 13:12:47.445  8306  8306 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-29 13:12:47.445  8306  8306 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 13:12:47.446  8306  8306 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-29 13:12:47.446  8306  8306 D dhcpcd  : wlan0: sending REQUEST (xid 0x5484d358), next in 3.07 seconds
,08-29 13:12:47.483  8306  8306 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-29 13:12:47.484  8306  8306 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-29 13:12:47.484  8306  8306 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-29 13:12:47.485  8306  8306 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-29 13:12:47.485  8306  8306 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-29 13:12:47.485  8306  8306 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-29 13:12:47.485  8306  8306 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-29 13:12:47.485  8306  8306 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-29 13:12:47.485  8306  8306 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-29 13:12:47.547  1043  1948 W libprocessgroup: failed to open /acct/uid_10093/pid_7327/cgroup.procs: No such file or directory
,08-29 13:12:47.566  1043  1646 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-29 13:12:47.570  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:12:47.570  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:47.570  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:47.571  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:47.571  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bdc8f added. We now have 9 listener(s)
08-29 13:12:47.571  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:47.571  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:12:47.575  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:47.581  6705  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:47.581  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:47.581  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:47.581  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:47.581  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:47.581  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:47.581  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:47.581  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:47.585  6705  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:47.585  6705  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:47.586  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:47.586  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13459325 added. We now have 3 listener(s)
08-29 13:12:47.586  1043  1565 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:47.588  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:47.589  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:12:47.589  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:47.589  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:47.589  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:47.590  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b131cfa added. We now have 10 listener(s)
08-29 13:12:47.590  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:47.590  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:47.590  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:47.591  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:47.591  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:47.591  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:47.591  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.591  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:47.591  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:47.591  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fd3efee removed from the list
08-29 13:12:47.591  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:47.591  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bdc8f removed from the list
08-29 13:12:47.591  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:47.591  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.592  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.592  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.592  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:47.593  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:47.593  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:47.593  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bdc8f not in the list
08-29 13:12:47.593  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.593  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.594  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:47.594  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:47.594  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:47.594  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b131cfa removed from the list
08-29 13:12:47.594  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:47.594  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.594  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.594  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:47.594  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13459325 removed from th,e list
08-29 13:12:47.595  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:47.595  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d53b2ab added. We now have 2 listener(s)
08-29 13:12:47.595  1043  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:47.598  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:12:47.598  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:47.598  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:47.599  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:47.599  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38555d08 added. We now have 9 listener(s)
08-29 13:12:47.599  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:47.601  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:12:47.603  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:47.608  6705  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:47.608  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:47.608  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:47.608  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:47.608  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:47.608  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:47.608  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:47.608  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:47.614  6705  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:47.614  6705  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:47.615  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:47.615  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37e60ec6 added. We now have 3 listener(s)
08-29 13:12:47.615  1043  1061 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:47.617  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:47.619  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:12:47.619  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:47.619  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:47.619  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:47.619  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1898ce87 added. We now have 10 listener(s)
08-29 13:12:47.619  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:47.619  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:47.619  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:47.619  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:12:47.619  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:47.619  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:12:47.621  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:47.624  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:12:47.624  1043  1061 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:47.629  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 13:12:47.630  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 13:12:47.631  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:12:47.632  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:47.634  6705  6760 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 13:12:47.634  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:47.634  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:12:47.639  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:47.639  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:47.639  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:47.639  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:47.639  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.639  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:47.639  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:47.639  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d53b2ab removed from the list
08-29 13:12:47.639  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:47.639  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38555d08 removed from the list
08-29 13:12:47.639  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:47.639  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.640  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.640  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.641  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:47.641  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:47.641  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:47.641  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38555d08 not in the list
08-29 13:12:47.641  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.641  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.642  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:47.642  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:47.642  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:47.643  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:47.643  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:47.643  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1898ce87 removed from the list
08-29 13:12:47.643  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:12:47.643  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.643  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.643  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:47.643  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37e60ec6 removed from the list
08-29 13:12:47.644  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:47.644  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1aa45152 added. We now have 2 listener(s)
08-29 13:12:47.644  1043  1948 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:47.646  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:12:47.646  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:47.646  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:47.646  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:47.647  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2029cc23 added. We now have 9 listener(s)
08-29 13:12:47.647  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:47.647  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:12:47.649  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:47.655  6705  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:47.655  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:47.655  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:47.655  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:47.655  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:47.655  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:47.655  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:47.655  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:47.657  6705  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:47.657  6705  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:47.657  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:47.657  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1df3ded9 added. We now have 3 listener(s)
08-29 13:12:47.657  1043  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: v,alid=true callingUser=0 foregroundUser=0
08-29 13:12:47.659  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:12:47.659  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:47.659  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:47.659  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:47.659  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@392309e added. We now have 10 listener(s)
08-29 13:12:47.659  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:47.660  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:47.660  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:47.660  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:47.660  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:12:47.660  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:47.660  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:12:47.661  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:47.662  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:47.663  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:12:47.663  1043  1646 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:47.666  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 13:12:47.667  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 13:12:47.668  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:12:47.669  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:47.670  6705  6760 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 13:12:47.670  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:47.670  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:47.670  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:47.670  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:47.670  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.670  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:47.670  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:47.670  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1aa45152 removed from the list
08-29 13:12:47.670  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:47.670  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2029cc23 removed from the list
08-29 13:12:47.670  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:47.670  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.671  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.671  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.671  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:47.671  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:47.671  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:47.671  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2029cc23 not in the list
08-29 13:12:47.671  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.671  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.672  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:47.672  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:47.672,  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:47.672  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:47.672  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:47.672  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@392309e removed from the list
08-29 13:12:47.672  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:47.672  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.672  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.672  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:47.672  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1df3ded9 removed from the list
08-29 13:12:47.673  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:47.673  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63a8f95 added. We now have 2 listener(s)
08-29 13:12:47.674  1043  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:47.675  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:12:47.675  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:47.675  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:47.676  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:47.676  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20ecb8aa added. We now have 9 listener(s)
08-29 13:12:47.676  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:47.676  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:12:47.678  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:47.680  6705  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:47.680  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:47.680  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:47.680  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:47.680  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:47.680  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:47.680  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:47.680  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:47.681  6705  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:47.681  6705  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:47.681  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:47.681  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b9e1838 added. We now have 3 listener(s)
08-29 13:12:47.682  1043  2022 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:47.684  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:12:47.684  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:47.684  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:47.684  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:47.684  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31019011 added. We now have 10 listener(s)
08-29 13:12:47.684  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:47.684  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:47.684  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:47.684  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:12:47.684  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:47.684  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:12:47.687  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:47.688  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:12:47.688  1043  2022 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true c,allingUser=0 foregroundUser=0
08-29 13:12:47.688  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:47.690  8289  8289 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 13:12:47.690  8289  8289 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-29 13:12:47.691  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 13:12:47.692  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 13:12:47.693  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:12:47.693  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:47.694  6705  6760 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-29 13:12:47.695  8289  8289 V [BNRBootReceiver]: Boot Receiver Return
08-29 13:12:47.696  8289  8289 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-29 13:12:47.697  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:47.698  8237  8278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 13:12:47.700  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:47.700  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:47.700  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:47.700  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:47.700  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.700  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:47.700  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:47.700  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63a8f95 removed from the list
08-29 13:12:47.700  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:47.700  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20ecb8aa removed from the list
,08-29 13:12:47.700  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:47.700  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.700  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.700  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.701  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:47.701  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:47.701  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:47.701  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20ecb8aa not in the list
08-29 13:12:47.701  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.701  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.701  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:47.702  6705  6760 D BluetoothLeScanner: could not find callback wrapper
08-29 13:12:47.702  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:47.702  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:47.702  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:47.702  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31019011 removed from the list
08-29 13:12:47.702  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:47.702  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.702  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.702  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:47.702  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b9e1838 removed from the list
08-29 13:12:47.703  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:47.703  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b387fe4 added. We now have 2 listener(s)
08-29 13:12:47.703  1043  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:47.705  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:12:47.705  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:47.705  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:47.705  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:47.705  6705  6760 V org.thaliproject.p2p.btconnectorlib.Disco,veryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5e1c4d added. We now have 9 listener(s)
08-29 13:12:47.705  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:47.706  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:12:47.706  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:12:47.708  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:47.711  6705  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:47.711  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:47.711  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-29 13:12:47.711  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:47.711  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:47.711  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:47.711  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:47.711  6705  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:47.712  6705  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:47.713  6705  6760 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:47.713  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:47.713  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6360413 added. We now have 3 listener(s)
08-29 13:12:47.713  1043  1950 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-29 13:12:47.714  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:47.716  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:47.716  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-29 13:12:47.716  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:47.716  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:47.716  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:47.716  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13efb650 added. We now have 10 listener(s)
08-29 13:12:47.716  6705  6760 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:47.717  6705  6705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:47.717  6705  6760 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:47.718  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:47.718  6705  6760 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:47.718  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:47.718  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably al,ready removed
08-29 13:12:47.718  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:47.718  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:47.718  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b387fe4 removed from the list
08-29 13:12:47.718  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:47.718  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5e1c4d removed from the list
08-29 13:12:47.718  6705  6760 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:47.718  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.718  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.718  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:47.718  8003  8003 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:47.719  8003  8003 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:47.719  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:47.719  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:47.719  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:47.719  6705  6760 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5e1c4d not in the list
08-29 13:12:47.719  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.719  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:47.719  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:47.719  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:47.719  6705  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:47.720  8003  8003 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-29 13:12:47.720  6705  6760 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13efb650 removed from the list
08-29 13:12:47.720  6705  6760 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:47.720  6705  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:47.720  6705  6760 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:47.720  6705  6760 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:47.720  6705  6760 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6360413 removed from the list
08-29 13:12:47.720  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 13:12:47.720  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 13:12:47.721  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 13:12:47.721  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:47.721  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 13:12:47.721  6705  6760 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:47.723  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-29 13:12:47.725  6928  6928 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-29 13:12:47.727  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:47.729  8237  8278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 13:12:47.730  6705  8341 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 895, name: My test thread name)
08-29 13:12:47.730  6705  8341 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 895, thread name: My test thread name)
08-29 13:12:47.730  6705  8341 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 895, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 13:12:47.730  8237  8277 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:12:47.731  8237  8277 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 13:12:47.732  6705  8342 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 897, name: My test thread name)
08-29 13:12:47.732  6705  8342 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 897, thread name: My test thread name)
08-29 13:12:47.732  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:47.732  6705  8342 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 897, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 13:12:47.733  6705  6760 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 13:12:47.733  6705  6760 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 13:12:47.733  6705  6760 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 13:12:47.734  6705  6760 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 13:12:47.734  6705  6760 D com.test.thalitest.ThaliTestRunner: Total duration: 22973 ms
08-29 13:12:47.735  6705  6760 I jxcore-log: *Native tests were executed*
08-29 13:12:47.735  6705  6760 I jxcore-log: 
08-29 13:12:47.735  6705  6760 I jxcore-log: Total number of executed tests:  80
08-29 13:12:47.735  6705  6760 I jxcore-log: 
08-29 13:12:47.735  6705  6760 I jxcore-log: Number of passed tests:  80
08-29 13:12:47.735  6705  6760 I jxcore-log: 
08-29 13:12:47.735  6705  6760 I jxcore-log: Number of failed tests:  0
08-29 13:12:47.735  6705  6760 I jxcore-log: 
08-29 13:12:47.735  6705  6760 I jxcore-log: Number of ignored tests:  0
08-29 13:12:47.735  6705  6760 I jxcore-log: 
08-29 13:12:47.736  6705  6760 I jxcore-log: Total duration:  22973
08-29 13:12:47.736  6705  6760 I jxcore-log: 
08-29 13:12:47.736  6705  6760 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 13:12:47.736  6705  6760 I jxcore-log: 
08-29 13:12:47.737  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:47.741  8003  8003 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:47.741  8003  8003 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:47.741  8003  8003 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:12:47.742  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:47.742  6705  6760 I jxcore-log: 
08-29 13:12:47.743  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-29 13:12:47.743  6928  6928 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-29 13:12:47.743  6928  6928 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-29 13:12:47.743  6928  6928 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-29 13:12:47.743  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-29 13:12:47.744  6928  6928 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-29 13:12:47.745  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-29 13:12:47.745  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-29 13:12:47.745  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-29 13:12:47.745  6928  6928 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-29 13:12:47.745  6928  6928 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-29 13:12:47.745  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:47.745  6705  6760 I jxcore-log: 
08-29 13:12:47.745  6928  6928 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-29 13:12:47.745  6705  6705 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 13:12:47.746  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:47.746  6705  6760 I jxcore-log: 
08-29 13:12:47.747  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:47.747  6705  6760 I jxcore-log: 
08-29 13:12:47.747  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:47.748  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:47.748  6705  6760 I jxcore-log: 
08-29 13:12:47.748  8237  8278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 13:12:47.749  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:47.749  6705  6760 I jxcore-log: 
08-29 13:12:47.751  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:47.751  6705  6760 I jxcore-log: 
08-29 13:12:47.751  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:12:47.753  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:12:47.753  6705  6760 I jxcore-log: 
08-29 13:12:47.753  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:12:47.753  6705  6760 I jxcore-log: 
08-29 13:12:47.754  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:47.754  6705  6760 I jxcore-log: 
,08-29 13:12:47.755  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:47.755  6705  6760 I jxcore-log: 
08-29 13:12:47.756  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:12:47.756  6705  6760 I jxcore-log: 
08-29 13:12:47.757  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:12:47.757  6705  6760 I jxcore-log: 
08-29 13:12:47.758  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:12:47.758  6705  6760 I jxcore-log: 
08-29 13:12:47.758  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:47.758  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:47.758  6705  6760 I jxcore-log: 
08-29 13:12:47.759  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:47.759  6705  6760 I jxcore-log: 
08-29 13:12:47.759  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:12:47.759  6705  6760 I jxcore-log: 
08-29 13:12:47.760  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:12:47.760  6705  6760 I jxcore-log: 
08-29 13:12:47.761  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:47.761  6705  6760 I jxcore-log: 
08-29 13:12:47.761  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:47.761  6705  6760 I jxcore-log: 
08-29 13:12:47.762  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:12:47.762  6705  6760 I jxcore-log: 
08-29 13:12:47.763  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:12:47.763  6705  6760 I jxcore-log: 
08-29 13:12:47.763  8003  8003 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:47.763  8003  8003 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:47.763  8003  8003 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:12:47.763  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:12:47.763  6705  6760 I jxcore-log: 
08-29 13:12:47.764  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:12:47.764  6705  6760 I jxcore-log: 
08-29 13:12:47.764  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:47.764  6705  6760 I jxcore-log: 
08-29 13:12:47.765  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bss,idName":"f4:f2:6d:22:99:3e"}
08-29 13:12:47.765  6705  6760 I jxcore-log: 
08-29 13:12:47.766  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:47.766  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:47.766  6705  6760 I jxcore-log: 
08-29 13:12:47.766  8237  8278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 13:12:47.766  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:47.766  6705  6760 I jxcore-log: 
08-29 13:12:47.767  6705  6760 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:47.767  6705  6760 I jxcore-log: 
,08-29 13:12:47.770  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:12:47.771  1043  8272 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-29 13:12:47.772  1043  8272 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-29 13:12:47.772  1043  8272 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-29 13:12:47.772  1043  8272 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-29 13:12:47.772  1043  8272 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-29 13:12:47.772  1043  8272 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-29 13:12:47.772  1043  8272 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-29 13:12:47.772  1043  8272 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-29 13:12:47.772  1043  8272 D DhcpStateMachine: RunningState
08-29 13:12:47.774  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:47.778  8003  8003 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:47.778  8003  8003 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:47.778  8003  8003 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:12:47.780  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:12:47.782  8237  8278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 13:12:47.786  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:12:47.789  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:47.792  8003  8003 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 13:12:47.792  8003  8003 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:47.793  8003  8003 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-29 13:12:47.794  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:47.795  8237  8278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 13:12:47.797  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:12:47.800  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:47.804  8003  8003 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:47.804  8003  8003 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:47.804  8003  8003 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:12:47.811  8237  8278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 13:12:47.812  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:12:47.820  8237  8277 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-29 13:12:47.822  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:47.830  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:47.832  8237  8277 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-29 13:12:47.836  8003  8003 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:47.836  8003  8003 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:47.837  8237  8277 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-29 13:12:47.837  8237  8277 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-29 13:12:47.838  8237  8277 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-29 13:12:47.838  8237  8277 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-29 13:12:47.838  8237  8277 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,08-29 13:12:47.840  8237  8277 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-29 13:12:47.841  8237  8277 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-29 13:12:47.842  8003  8003 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:12:47.845  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:12:47.845  8237  8278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 13:12:47.851  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-29 13:12:47.855  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-29 13:12:47.859  8003  8003 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:47.860  8003  8003 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:47.860  8003  8003 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-29 13:12:47.863  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-29 13:12:47.863  8237  8278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-29 13:12:47.865  8209  8209 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 13:12:47.867  8209  8209 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:12:47.869  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:12:47.872  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:47.878  8003  8003 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-29 13:12:47.878  8003  8003 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-29 13:12:47.879  8003  8003 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 13:12:47.880  8003  8003 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 13:12:47.880  8003  8003 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 13:12:47.889  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-29 13:12:47.892  8209  8209 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-29 13:12:47.892  8237  8278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-29 13:12:47.892  8209  8209 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-29 13:12:47.894  6928  6928 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-29 13:12:47.898  6928  6928 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-29 13:12:47.903  8003  8003 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-29 13:12:47.903  8003  8003 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-29 13:12:47.904  8003  8003 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-29 13:12:47.904  8003  8003 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-29 13:12:47.905  8003  8003 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-29 13:12:47.908  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 13:12:47.909  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 13:12:47.910  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 13:12:47.911  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 13:12:47.913  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 13:12:47.914  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-29 13:12:47.915  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-29 13:12:47.917  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-29 13:12:47.920  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 13:12:47.921  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 13:12:47.923  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-29 13:12:47.924  1043  1646 I ActivityManager: Killing 7293:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-29 13:12:47.985  8344  8344 D AndroidRuntime: 
08-29 13:12:47.985  8344  8344 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 13:12:47.987  8344  8344 D AndroidRuntime: CheckJNI is OFF
,08-29 13:12:48.017  1043  2023 W libprocessgroup: failed to open /acct/uid_10005/pid_7293/cgroup.procs: No such file or directory
,08-29 13:12:48.167  8344  8344 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 13:12:48.185  1043  1113 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-29 13:12:48.186  1043  1113 I ActivityManager: Killing 6705:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-29 13:12:48.214  1043  1428 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:12:48.214  1043  1428 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:12:48.215  1043  1428 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:12:48.215  1043  1428 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:12:48.215  1043  1428 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:12:48.215  1043  1428 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-29 13:12:48.216  1043  1509 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-29 13:12:48.216  1043  1509 D ConnectivityService: identical MTU - not setting
08-29 13:12:48.216  1043  1509 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-29 13:12:48.216  1043  1509 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 13:12:48.216  1043  1509 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:48.216  1043  1509 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-29 13:12:48.216  1043  1509 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-29 13:12:48.217  1592  2041 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-29 13:12:48.267  1043  1950 I WindowState: WIN DEATH: Window{40c7d17 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 13:12:48.269  1043  1486 D WifiService: Client connection lost with reason: 4
,08-29 13:12:48.278  1043  1950 D InputDispatcher: Window went away: Window{40c7d17 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 13:12:48.417  1043  1113 I ActivityManager:   Force finishing activity ActivityRecord{14a59710 u0 com.test.thalitest/.MainActivity t6}
,08-29 13:12:48.435   353   380 E GBMv2   : DFP En is all cleared set to be enabled
,08-29 13:12:48.438  1043  1986 W ActivityManager: Spurious death for ProcessRecord{2be60a66 6705:com.test.thalitest/u0a118}, curProc for 6705: null
08-29 13:12:48.438  1043  1126 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-29 13:12:48.441  1043  1126 I ActivityManager:   Force finishing activity ActivityRecord{14a59710 u0 com.test.thalitest/.MainActivity t6 f}
08-29 13:12:48.441  1043  1126 W ActivityManager: Duplicate finish request for ActivityRecord{14a59710 u0 com.test.thalitest/.MainActivity t6 f}
,08-29 13:12:48.464   323  8280 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-29 13:12:48.465  2024  2024 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-29 13:12:48.467  2024  2024 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-29 13:12:48.470  1931  1946 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-29 13:12:48.470  1931  1946 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1524180c co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-29 13:12:48.471  2024  2024 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-29 13:12:48.472  2024  2115 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-29 13:12:48.474  1931  2939 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-29 13:12:48.474  1931  2939 D SplitWindowPolicy: topRunningActivity=ActivityInfo{24fa1555 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-29 13:12:48.478  1896  1896 D ActionManagerService: notifyUserLog: 1000003
08-29 13:12:48.479  2024  2024 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-29 13:12:48.479  3806  4971 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-29 13:12:48.485  1592  1592 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-29 13:12:48.490  1043  1369 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 13:12:48.497  2454  2662 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 13:12:48.499  1987  1987 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-29 13:12:48.499  3806  3806 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-29 13:12:48.503  7791  7791 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-29 13:12:48.504  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-29 13:12:48.506  8237  8237 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-29 13:12:48.517  5091  5091 I art     : Explicit concurrent mark sweep GC freed 8249(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 585us total 61.424ms
08-29 13:12:48.534  1043  1948 V SIM_STK : Menu title from STK is T-Mobile
,08-29 13:12:48.561  4978  4978 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-29 13:12:48.561  4978  4978 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-29 13:12:48.562  4978  4978 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-29 13:12:48.562  4978  4978 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-29 13:12:48.562  4978  4978 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:12:48.562  4978  4978 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:12:48.562  4978  4978 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-29 13:12:48.562  4978  4978 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-29 13:12:48.562  4978  4978 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:48.562  4978  4978 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:48.562  4978  4978 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-29 13:12:48.562  4978  4978 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-29 13:12:48.571  1043  1110 W InputMethodInfo: Duplicated subtype definition found: , voice
08-29 13:12:48.575  1043  1043 D administrator: Handling package changes for user 0
,08-29 13:12:48.579  2024  2024 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-29 13:12:48.586  1807  1807 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-29 13:12:48.590  2024  2024 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-29 13:12:48.590  1592  1592 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-29 13:12:48.611  2024  2024 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-29 13:12:48.615  2186  2186 I ConfigService: onCreate
08-29 13:12:48.616  2186  2186 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-29 13:12:48.625  1896  1896 D ActionManagerService: notifyUserLog: 1000004
08-29 13:12:48.625  2024  2024 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-29 13:12:48.625  3806  4971 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,08-29 13:12:48.627  1807  1807 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-29 13:12:48.627  1592  1643 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 13:12:48.627  1592  1643 D KeyguardModel: createShortcutInfo...
08-29 13:12:48.631  3806  3822 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 13:12:48.633  2024  2024 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-29 13:12:48.633  2024  2024 I GBoardWebViewUtils: , create_time: 1430832262123
08-29 13:12:48.633  2024  2024 I GBoardWebViewUtils: , expire_time: 0
08-29 13:12:48.633  2024  2024 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-29 13:12:48.633  2024  2024 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-29 13:12:48.633  2024  2024 I GBoardWebViewUtils: , display: false
08-29 13:12:48.633  2024  2024 I GBoardWebViewUtils: , animation: false }
08-29 13:12:48.633  2024  2024 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-29 13:12:48.633  2024  2024 I GBoardWebViewUtils: , create_time: 1430832262287
08-29 13:12:48.633  2024  2024 I GBoardWebViewUtils: , expire_time: 0
08-29 13:12:48.633  2024  2024 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 13:12:48.633  2024  2024 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 13:12:48.633  2024  2024 I GBoardWebViewUtils: , display: false
08-29 13:12:48.633  2024  2024 I GBoardWebViewUtils: , animation: false }
08-29 13:12:48.633  2186  2186 I ConfigService: onBind returning update interface
08-29 13:12:48.634  2024  2024 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-29 13:12:48.634  2024  2024 I GBoardWebViewUtils: , create_time: 1472216588858
08-29 13:12:48.634  2024  2024 I GBoardWebViewUtils: , expire_time: 0
08-29 13:12:48.634  2024  2024 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-29 13:12:48.634  2024  2024 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-29 13:12:48.634  2024  2024 I GBoardWebViewUtils: , display: false
08-29 13:12:48.634  2024  2024 I GBoardWebViewUtils: , animation: false }
08-29 13:12:48.634  2186  2186 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-29 13:12:48.634  2186  2186 I ConfigService: onBind returning config service
08-29 13:12:48.637  1860  1860 D SplitUIManager: split_name #11 / not available #0
08-29 13:12:48.637  1860  1860 D SplitUIService: removed split : 
,08-29 13:12:48.642  1592  1592 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-29 13:12:48.642  1592  1592 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-29 13:12:48.642  1592  1643 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 13:12:48.642  1592  1643 D KeyguardModel: createShortcutInfo...
08-29 13:12:48.645  1043  1646 V SIM_STK : Menu title from STK is T-Mobile
08-29 13:12:48.645  1043  1646 V SIM_STK : Menu title from STK is T-Mobile
08-29 13:12:48.646  2024  8374 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-29 13:12:48.647  1592  1643 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 13:12:48.647  1592  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:12:48.648  1592  1643 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-29 13:12:48.649  1592  1643 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 13:12:48.654  1592  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 13:12:48.654  1592  1643 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-29 13:12:48.656  2024  2024 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-29 13:12:48.657  2186  2186 I ConfigService: onDestroy
08-29 13:12:48.666  1807  8376 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-29 13:12:48.672  1592  1643 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 13:12:48.672  1592  1643 D KeyguardModel: createShortcutInfo...
08-29 13:12:48.676  1592  1643 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-29 13:12:48.676  1592  1643 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 13:12:48.682  1860  1860 D SplitUIManager: split_name #11 / not available #0
08-29 13:12:48.682  1860  1860 I SplitUIService: split app #11
,08-29 13:12:48.682  1592  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 13:12:48.682  1592  1643 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 13:12:48.686  1592  1643 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 13:12:48.686  1592  1643 D KeyguardModel: createShortcutInfo...
08-29 13:12:48.693  1043  1950 V SIM_STK : Menu title from STK is T-Mobile
08-29 13:12:48.697  1592  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:12:48.697  1592  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 13:12:48.697  1592  1643 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-29 13:12:48.697  1592  1643 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-29 13:12:48.697  1592  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 13:12:48.697  1592  1643 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-29 13:12:48.699  1043  1764 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-29 13:12:48.699  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-29 13:12:48.699  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-29 13:12:48.699  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-29 13:12:48.700  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-29 13:12:48.700  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-29 13:12:48.700  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 13:12:48.700  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-29 13:12:48.700  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-29 13:12:48.700  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-29 13:12:48.700  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-29 13:12:48.700  7791  7791 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-29 13:12:48.700  1592  1643 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 13:12:48.700  1592  1643 D KeyguardModel: createShortcutInfo...
08-29 13:12:48.703  5838  8381 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-29 13:12:48.706  1592  1592 D KeyguardModel: handleShortcutListChanged...
08-29 13:12:48.706  1592  1592 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 13:12:48.712  1592  1643 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-29 13:12:48.712  1592  1643 D KeyguardModel: createShortcutInfo...
,08-29 13:12:48.715  1592  1643 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-29 13:12:48.716  1592  1643 D KeyguardModel: createShortcutInfo...
08-29 13:12:48.717  1592  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 13:12:48.717  1592  1643 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-29 13:12:48.720  1592  1643 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-29 13:12:48.720  1592  1643 D KeyguardModel: createShortcutInfo...
08-29 13:12:48.722  1592  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 13:12:48.722  1592  1643 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-29 13:12:48.723  1807  8383 I PeopleContactsSync: CP2 sync disabled
08-29 13:12:48.723  1592  1643 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-29 13:12:48.723  1592  1643 D KeyguardModel: createShortcutInfo...
08-29 13:12:48.726  1592  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 13:12:48.726  1592  1643 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-29 13:12:48.728  1592  1643 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-29 13:12:48.728  1592  1643 D KeyguardModel: createShortcutInfo...
,08-29 13:12:48.737  2024  2024 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 13:12:48.743  2024  2024 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-29 13:12:48.747  1807  8382 W GmsApplication: Using Auth Proxy for data requests.
08-29 13:12:48.751  1807  8382 W GmsApplication: Using Auth Proxy for data requests.
,08-29 13:12:48.754  1807  5236 I Icing   : doRemovePackageData com.test.thalitest
08-29 13:12:48.767  1592  1592 D KeyguardModel: handleShortcutListChanged...
,08-29 13:12:48.769  1592  1592 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-29 13:12:48.790   336   449 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-29 13:12:48.790  3273  8386 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-29 13:12:48.790  7120  7120 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-29 13:12:48.802  2360  8387 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 13:12:48.805  2186  2225 I art     : Explicit concurrent mark sweep GC freed 6314(375KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 1.688ms total 21.207ms
08-29 13:12:48.829  1043  1913 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8388 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-29 13:12:48.841  2024  2024 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-29 13:12:48.844  2024  2024 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 13:12:48.846  2024  2024 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-29 13:12:48.847  2024  2024 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-29 13:12:48.848  2024  2024 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-29 13:12:48.849  2024  2024 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-29 13:12:48.858  1043  1043 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-29 13:12:48.858  1043  1043 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-29 13:12:48.858  1043  1043 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 13:12:48.861  1043  1567 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,08-29 13:12:48.874  2024  2024 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-29 13:12:48.875  2024  2024 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 13:12:48.875  2024  2151 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-29 13:12:48.875  2024  2151 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-29 13:12:48.876  1043  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{17ae0572 u0 com.lge.launcher2/.Launcher t5} time:139132
,08-29 13:12:48.889  2024  2024 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-29 13:12:48.890  2024  2024 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 13:12:48.890  2024  2024 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 13:12:48.892  8388  8388 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:12:48.892  8388  8388 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-29 13:12:48.893  8388  8388 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-29 13:12:48.894  8388  8388 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-29 13:12:48.898  2024  2024 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-29 13:12:48.899  2565  2565 D [Concierge]Service: onStartCommand(). Type : 8
08-29 13:12:48.899  2565  2565 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-29 13:12:48.900  2565  2565 D [Concierge]Service: Update widget ID : 11
08-29 13:12:48.901  2024  2024 D [Concierge]WidgetView: change position of spinner
08-29 13:12:48.902  2565  2565 D [Concierge]Service: onStartCommand(). Type : 0
08-29 13:12:48.903  2024  2024 I [Concierge]WidgetView: initWebView(). Time : 1472469168903
08-29 13:12:48.928  2024  2024 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 691797540
08-29 13:12:48.928  2024  2024 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-29 13:12:48.928  2024  2024 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-29 13:12:48.931  2024  2024 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@325f9fa4
08-29 13:12:48.931  2024  2024 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-29 13:12:48.932  2024  2024 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-29 13:12:48.932  2024  2024 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 13:12:48.938  2024  2024 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-29 13:12:48.938  2024  2024 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-29 13:12:48.939  2024  2024 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-29 13:12:48.939  2024  2024 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472469057740, New one : 1472469168903
08-29 13:12:48.939  2024  2024 D [Concierge]WidgetView: Unregister all receivers
08-29 13:12:48.939  2024  2024 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-29 13:12:48.940  2024  2024 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 13:12:48.941  2024  2024 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-29 13:12:48.941  1043  1126 I art     : Explicit concurrent mark sweep GC freed 85602(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.450ms total 339.020ms
08-29 13:12:48.942  2024  2024 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-29 13:12:48.943  2024  2024 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-29 13:12:48.945  2024  2024 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-29 13:12:48.946  2024  2024 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-29 13:12:48.950  2024  2024 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 13:12:48.950  2024  2024 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-29 13:12:48.984  2024  2024 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-29 13:12:48.996  8344  8344 D AndroidRuntime: Shutting down VM
,08-29 13:12:49.004  2024  2024 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-29 13:12:49.004  2024  2024 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-29 13:12:49.004  8388  8388 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-29 13:12:49.006  2024  2024 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-29 13:12:49.016  8388  8388 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-29 13:12:49.025  2024  2024 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2c49b9b9 time:139282
08-29 13:12:49.028  1043  1126 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8409 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-29 13:12:49.047  8388  8388 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 13:12:49.068  1043  1565 I ActivityManager: Killing 7822:com.google.android.talk/u0a72 (adj 15): empty #17
08-29 13:12:49.070  8388  8388 D LgDataFeature: LgDataFeature() Constructor: none
08-29 13:12:49.070  8388  8388 D LgDataFeature: LgDataFeature() Constructor Done, null
08-29 13:12:49.072  1043  1110 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:12:49.079  1043  1110 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-29 13:12:49.142  2024  2024 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-29 13:12:49.174  1043  1986 W libprocessgroup: failed to open /acct/uid_10072/pid_7822/cgroup.procs: No such file or directory
,08-29 13:12:49.176  2024  2024 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-29 13:12:49.178  2024  2867 I GBoardtInterface: onReloaded()
08-29 13:12:49.180  2024  2024 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-29 13:12:49.181  3806  3822 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 13:12:49.183  3806  4967 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 13:12:49.189  1896  1896 D ActionManagerService: notifyUserLog: 1000001
,08-29 13:12:49.190  3806  4971 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 13:12:49.190  3806  4971 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-29 13:12:49.193  1896  1896 D ActionManagerService: notifyUserLog: 1000001
08-29 13:12:49.194  3806  4971 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-29 13:12:49.194  3806  4971 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-29 13:12:49.194  3806  4971 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-29 13:12:49.194  3806  4971 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-29 13:12:49.195  3806  3822 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-29 13:12:49.197  2024  2024 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-29 13:12:49.197  2024  2024 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-29 13:12:49.199  2024  2024 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-29 13:12:49.199  2024  2024 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-29 13:12:49.200  2024  2024 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-29 13:12:49.200  2024  2024 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-29 13:12:49.210  8388  8388 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-29 13:12:49.219  1043  2022 I ActivityManager: Killing 7918:com.android.vending/u0a44 (adj 15): empty #17
,08-29 13:12:49.265  1043  1895 W libprocessgroup: failed to open /acct/uid_10044/pid_7918/cgroup.procs: No such file or directory
,08-29 13:12:49.265  1987  1987 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-29 13:12:49.265  1987  1987 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-29 13:12:49.267  1987  1987 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-29 13:12:49.280  8237  8237 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-29 13:12:49.286  7554  7554 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-29 13:12:49.287  6928  6928 D PackageIntentReceiver: Not supported Hotkey customization function 
08-29 13:12:49.291  6928  6928 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
,08-29 13:12:49.291  6928  6928 D HideNavigationAppsReceiver: replacing : false
08-29 13:12:49.294  6928  6928 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-29 13:12:49.295  6928  6928 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-29 13:12:49.295  6928  6928 D ButtonCombinationReceiver: replacing : false
08-29 13:12:49.326  1043  1060 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8433 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a

```
