#### Test 81444731251ddd8_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-26 19:02:41.704  6650  6650 I AppConfig: Total System Memory = 2995761152
08-26 19:02:41.718  6650  6650 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
--------- beginning of system
08-26 19:02:41.753  1034  2013 I ActivityManager: Killing 6190:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-26 19:02:41.787  1996  1996 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-26 19:02:41.787  1996  1996 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-26 19:02:41.788  1034  1969 W libprocessgroup: failed to open /acct/uid_10080/pid_6190/cgroup.procs: No such file or directory
08-26 19:02:41.792  1996  1996 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-26 19:02:41.829  6509  6509 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-26 19:02:41.834  6509  6509 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-26 19:02:41.880  1034  1908 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6675 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:02:41.914   354   354 I art     : Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 426us total 33.855ms
08-26 19:02:41.938   354   354 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 423us total 22.675ms
08-26 19:02:41.958   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 422us total 19.112ms
08-26 19:02:42.085  6675  6675 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-26 19:02:42.160  6675  6675 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:02:42.160  6675  6675 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 19:02:42.211  6675  6675 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-26 19:02:42.231  6675  6675 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 19:02:42.232  6675  6675 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 19:02:42.250  6675  6675 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 19:02:42.250  6675  6675 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-26 19:02:42.266  1034  2032 I ActivityManager: Killing 5550:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-26 19:02:42.310  1034  1969 W libprocessgroup: failed to open /acct/uid_10085/pid_5550/cgroup.procs: No such file or directory
08-26 19:02:42.318  5086  6711 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-26 19:02:42.325  3359  3375 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-26 19:02:42.329  3359  3375 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3f050c51 on behalf of 6675
08-26 19:02:42.370  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-26 19:02:42.372  1034  2013 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6713 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:02:42.393  6675  6675 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-26 19:02:42.436  6675  6675 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-26 19:02:42.483  5086  6711 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 165 ms] updated apps [took 164 ms] 
,08-26 19:02:42.637  6713  6713 D DocsApplication: Installing DEX configuration.
08-26 19:02:42.657  6713  6713 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-26 19:02:42.661  6713  6713 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1df550b com.google.android.apps.docs}
08-26 19:02:42.678  6713  6713 D TAG     : onCreate()
08-26 19:02:42.703  6713  6713 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-26 19:02:42.850  6733  6733 D AndroidRuntime: 
08-26 19:02:42.850  6733  6733 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 19:02:42.854  6733  6733 D AndroidRuntime: CheckJNI is OFF
08-26 19:02:43.034  6733  6733 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 19:02:43.040  1034  2032 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 19:02:43.055  1943  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-26 19:02:43.059  1034  2032 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-26 19:02:43.063  1034  2032 D ActivityManager: setTaskToReturnTo : TaskRecord{3578c203 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 19:02:43.063  1034  2032 D ActivityManager: setTaskToReturnTo : TaskRecord{3578c203 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 19:02:43.065  1034  2032 D WindowStateEx: AppWindowTokenEx init.. 
08-26 19:02:43.065   333   344 E GBMv2   : DFP En is all cleared set to be enabled
08-26 19:02:43.092  1034  2032 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6749 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 19:02:43.094  6733  6733 D AndroidRuntime: Shutting down VM
08-26 19:02:43.126  1943  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-26 19:02:43.130  1943  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{9be9977 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 19:02:43.132  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-26 19:02:43.133  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{21f3c9e4 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 19:02:43.195  6749  6749 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-26 19:02:43.269  6749  6749 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-26 19:02:43.276  6749  6749 I LibraryLoader: Loading: webviewchromium
08-26 19:02:43.279  6749  6749 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6620-6623)
08-26 19:02:43.279  6749  6749 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 19:02:43.294  6749  6749 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {20b3913d}
08-26 19:02:43.295  6749  6749 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 19:02:43.296  6749  6749 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 19:02:43.303  6749  6749 I BrowserStartupController: Initializing chromium process, renderers=0
08-26 19:02:43.304  6749  6749 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 19:02:43.312  6749  6749 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-26 19:02:43.312  6749  6749 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-26 19:02:43.313  6749  6749 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-26 19:02:43.313   318  1393 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
08-26 19:02:43.316  1034  1096 D BluetoothManagerService: Message: 20
08-26 19:02:43.316  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@216d675:true
08-26 19:02:43.322  6749  6749 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 19:02:43.322  6749  6749 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 19:02:43.322  6749  6749 I Adreno-EGL: Build Date: 12/12/14 금
08-26 19:02:43.322  6749  6749 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 19:02:43.322  6749  6749 I Adreno-EGL: Remote Branch: 
08-26 19:02:43.322  6749  6749 I Adreno-EGL: Local Patches: 
08-26 19:02:43.322  6749  6749 I Adreno-EGL: Reconstruct Branch: 
08-26 19:02:43.402  6749  6788 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-26 19:02:43.404  6749  6749 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-26 19:02:43.418  6749  6749 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 19:02:43.422  6749  6749 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 19:02:43.425  6749  6749 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-26 19:02:43.427  6749  6749 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-26 19:02:43.427  6749  6749 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-26 19:02:43.440  6749  6749 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-26 19:02:43.446  6749  6749 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 19:02:43.446  6749  6749 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 19:02:43.470  6749  6801 D OpenGLRenderer: Render dirty regions requested: true
08-26 19:02:43.470  6749  6801 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 19:02:43.483  1818  5257 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-26 19:02:43.488  6749  6801 D OpenGLRenderer: Enabling debug mode 0
08-26 19:02:43.499  6749  6749 D Atlas   : Validating map...
,08-26 19:02:43.504  1034  1734 D SplitWindow: check instance of lgWin Window{3dbae447 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 19:02:43.529  1818  5257 I art     : Explicit concurrent mark sweep GC freed 31127(1934KB) AllocSpace objects, 12(192KB) LOS objects, 51% free, 29MB/61MB, paused 1.018ms total 33.204ms
,08-26 19:02:43.562  1818  5257 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-26 19:02:43.564  6749  6799 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:02:43.564  6749  6799 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:02:43.598  1818  5257 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-26 19:02:43.603  1034  1097 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +478ms (total +536ms)
08-26 19:02:43.603  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{20d9b580 u0 com.test.thalitest/.MainActivity t6} time:106948
08-26 19:02:43.603  6749  6749 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8b00d30 time:106948
08-26 19:02:43.725  6749  6749 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 19:02:43.806  6749  6799 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-26 19:02:43.806  6749  6799 I chromium: 
,08-26 19:02:43.895  6749  6813 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435169792
,08-26 19:02:43.906  6749  6813 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 19:02:43.906  6749  6813 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 19:02:43.906  6749  6813 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 19:02:43.906  6749  6813 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 19:02:43.906  6749  6813 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 19:02:43.906  6749  6813 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36684af4 added. We now have 1 listener(s)
08-26 19:02:43.909  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 19:02:43.911  6749  6813 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-26 19:02:43.912  6749  6813 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:02:43.913  6749  6813 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:02:43.913  6749  6813 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:02:43.919  6749  6813 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 19:02:43.919  6749  6813 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 19:02:43.919  6749  6813 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 19:02:43.919  6749  6813 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-26 19:02:43.919  6749  6813 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 19:02:43.919  6749  6813 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 19:02:43.919  6749  6813 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 19:02:43.919  6749  6813 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 19:02:43.919  6749  6813 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 19:02:43.919  6749  6813 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 19:02:43.919  6749  6813 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 19:02:43.919  6749  6813 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 19:02:43.919  6749  6813 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 19:02:43.919  6749  6813 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 19:02:43.919  6749  6813 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef05663 added. We now have 1 listener(s)
08-26 19:02:43.919  6749  6813 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:02:43.924  1034  1541 D WifiService: New client listening to asynchronous messages
,08-26 19:02:43.932  6749  6813 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:02:43.933  6749  6813 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 19:02:43.935  6749  6813 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 19:02:43.935  6749  6813 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 19:02:43.935  6749  6813 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 19:02:43.938  6749  6813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:02:43.938  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:02:43.939  6749  6813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-26 19:02:43.945  6749  6813 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 19:02:43.945  6749  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:43.945  6749  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:43.945  6749  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:02:43.945  6749  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:43.945  6749  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:43.945  6749  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:43.945  6749  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:43.945  6749  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:43.946  6749  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 19:02:43.946  6749  6813 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:02:43.947  6749  6813 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 19:02:43.947  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:43.949  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:43.957  6749  6749 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-26 19:02:43.957  6749  6749 I chromium: 
,08-26 19:02:43.975  6749  6749 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 19:02:43.994  6713  6713 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:02:43.994  6713  6713 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:02:44.121  6713  6713 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-26 19:02:44.132  1034  1978 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6826 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-26 19:02:44.204  6826  6826 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-26 19:02:44.217  6826  6826 I LockScreenSettings: New app installed broadcast received ..
,08-26 19:02:44.220  6826  6826 I LockScreenSettings: Number of installed packages  1
08-26 19:02:44.284  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
,08-26 19:02:44.370  1034  1896 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6845 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 19:02:44.372  1034  1896 I ActivityManager: Killing 6035:com.google.android.talk/u0a72 (adj 15): empty #17
08-26 19:02:44.496  1034  2057 W libprocessgroup: failed to open /acct/uid_10072/pid_6035/cgroup.procs: No such file or directory
,08-26 19:02:44.523   333   346 E GBMv2   : DFP En is all cleared set to be enabled
08-26 19:02:44.523   333   346 E GBMv2   : Set value is all cleared set the max
08-26 19:02:44.523   333   346 I GBMv2   : DFP Enabled. Ignore VFP set
08-26 19:02:44.604  6749  6816 W jxcore-log: Initializing JXcore engine
08-26 19:02:44.604  6749  6816 W jxcore-log: JXcore engine is ready
,08-26 19:02:44.633  1034  1969 I art     : Explicit concurrent mark sweep GC freed 27087(1341KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.481ms total 114.347ms
,08-26 19:02:44.654  6816  6816 W Thread-802: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7478]" dev="sockfs" ino=7478 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-26 19:02:44.654  6816  6816 W Thread-802: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-26 19:02:44.654  6816  6816 W Thread-802: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9911]" dev="sockfs" ino=9911 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-26 19:02:44.654  6816  6816 W Thread-802: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-26 19:02:44.654  6816  6816 W Thread-802: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32314]" dev="sockfs" ino=32314 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-26 19:02:44.669  6749  6816 W jxcore-log: Starting JXcore engine
,08-26 19:02:44.681  6845  6845 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-26 19:02:44.682  6845  6845 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-26 19:02:44.685  5685  5685 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-26 19:02:44.705  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,08-26 19:02:44.735  1034  1969 I ActivityManager: Killing 6249:com.google.android.gm/u0a64 (adj 15): empty #17
,08-26 19:02:44.792  6749  6816 W jxcore-log: Platform android
08-26 19:02:44.792  6749  6816 W jxcore-log: 
08-26 19:02:44.793  6749  6816 W jxcore-log: Process ARCH arm
08-26 19:02:44.793  6749  6816 W jxcore-log: 
,08-26 19:02:44.817  1034  2013 W libprocessgroup: failed to open /acct/uid_10064/pid_6249/cgroup.procs: No such file or directory
,08-26 19:02:45.179  6749  6816 I jxcore-log: JXcore Cordova bridge is ready!
08-26 19:02:45.179  6749  6816 I jxcore-log: 
08-26 19:02:45.180  6749  6816 W jxcore-log: JXcore engine is started
,08-26 19:02:45.195  6749  6813 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 19:02:45.203  6749  6749 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 19:02:48.067  6713  6713 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
08-26 19:02:48.073  1034  1978 I ActivityManager: Killing 5815:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-26 19:02:48.099  5790  5790 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-26 19:02:48.100  5790  5790 W System.err: android.os.DeadObjectException
08-26 19:02:48.100  5790  5790 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 19:02:48.100  5790  5790 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 19:02:48.100  5790  5790 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,08-26 19:02:48.100  5790  5790 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 19:02:48.100  5790  5790 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 19:02:48.100  5790  5790 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 19:02:48.100  5790  5790 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-26 19:02:48.100  5790  5790 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 19:02:48.100  5790  5790 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 19:02:48.100  5790  5790 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 19:02:48.100  5790  5790 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:48.100  5790  5790 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:02:48.100  5790  5790 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 19:02:48.100  5790  5790 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 19:02:48.101  5790  5790 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 19:02:48.101  5790  5790 W System.err: android.os.DeadObjectException
08-26 19:02:48.101  5790  5790 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 19:02:48.101  5790  5790 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 19:02:48.101  5790  5790 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 19:02:48.101  5790  5790 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 19:02:48.101  5790  5790 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 19:02:48.101  5790  5790 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 19:02:48.101  5790  5790 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 19:02:48.101  5790  5790 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 19:02:48.102  5790  5790 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 19:02:48.102  5790  5790 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 19:02:48.102  5790  5790 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:48.102  5790  5790 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:02:48.102  5790  5790 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 19:02:48.102  5790  5790 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 19:02:48.102  5790  5790 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 19:02:48.102  5790  5790 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-26 19:02:48.337  1034  1600 W libprocessgroup: failed to open /acct/uid_1000/pid_5815/cgroup.procs: No such file or directory
08-26 19:02:48.337  1034  1600 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-26 19:02:48.340  5790  5790 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 19:02:48.340  5790  5790 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 19:02:48.379  1034  1576 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6879 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 19:02:48.381  5790  5790 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 19:02:48.441  6879  6879 D UEI.SmartControl: Quickset Services start...
08-26 19:02:48.443  6879  6879 I UEI.SmartControl: Manufacture = LGE
08-26 19:02:48.443  6879  6879 D UEI.SmartControl: Id = LGNevo
08-26 19:02:48.444  6879  6879 D UEI.SmartControl: File observer start...
,08-26 19:02:48.445  6879  6879 E UEI.SmartControl: IR Port is disabled: false
08-26 19:02:48.445  6879  6879 D UEI.SmartControl: Starting file observer...
08-26 19:02:48.446  6879  6879 D UEI.SmartControl: Extracting JNI libs...
08-26 19:02:48.446  6879  6879 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 19:02:48.522  6879  6879 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-26 19:02:48.522  6879  6879 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 19:02:48.522  6879  6879 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 19:02:48.556  6879  6879 I UEI.SmartControl: --- Selecting new region: 6
08-26 19:02:48.558  6879  6879 I UEI.SmartControl: Model = LG-D855
08-26 19:02:48.560  6879  6879 D UEI.SmartControl: QS Service created
,08-26 19:02:48.576  6879  6879 I UEI.SmartControl: Service initServices...
08-26 19:02:48.581  6879  6879 D UEI.SmartControl: QS start get config
,08-26 19:02:48.678  6879  6879 D UEI.SmartControl: Loading JNI Libs...
,08-26 19:02:49.011  6879  6879 I UEI.SmartControl: Supports setup maps: true
,08-26 19:02:49.019  6879  6879 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 19:02:49.019  6879  6879 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-26 19:02:49.019  6879  6879 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 19:02:49.019  6879  6879 I UEI.SmartControl: ### init IR Blaster...
08-26 19:02:49.029  6879  6879 D serial_port: Configuring serial port
08-26 19:02:49.033  6879  6879 E UEI.SmartControl: UEIBLaster setting for 616
08-26 19:02:49.034  6879  6879 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 19:02:49.034  6879  6879 I UEI.SmartControl: configuring settings for MAXQ616
08-26 19:02:49.034  6879  6879 I UEI.SmartControl: Get version...
,08-26 19:02:49.055  6879  6906 D UEI.SmartControl: serial port data available: 21
08-26 19:02:49.061  6713  6817 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-26 19:02:49.082  6879  6879 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 19:02:49.082  6879  6879 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 19:02:49.082  6879  6879 I UEI.SmartControl: QS saving settings...
08-26 19:02:49.083  6879  6879 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 19:02:49.100  6879  6906 D UEI.SmartControl: serial port data available: 4
,08-26 19:02:49.106  2797  2797 I MusicWidget: mDelayedStopHandler : unbind
08-26 19:02:49.110  2130  2130 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-26 19:02:49.110  2130  2130 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-26 19:02:49.111  2130  2130 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-26 19:02:49.114  2130  2130 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-26 19:02:49.114  2130  2130 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
,08-26 19:02:49.115  2130  2130 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-26 19:02:49.120  2130  2130 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-26 19:02:49.120  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-26 19:02:49.122  1034  1969 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3159b6e2com.lge.music.MediaPlaybackService$5@2db7ea73
08-26 19:02:49.123  2130  2130 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-26 19:02:49.124  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 19:02:49.125  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 19:02:49.126  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-26 19:02:49.137  2130  2130 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@34cd0439
08-26 19:02:49.137  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 19:02:49.138  2130  2130 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-26 19:02:49.138  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-26 19:02:49.141  2130  2130 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-26 19:02:49.141  2130  2130 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-26 19:02:49.141  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 19:02:49.144  6879  6879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 19:02:49.145  6879  6910 I UEI.SmartControl: Device manager: loading config....
08-26 19:02:49.145  6879  6910 D UEI.SmartControl: ----------- loading internal config...
08-26 19:02:49.149  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 19:02:49.151  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-26 19:02:49.153  6879  6879 E UEI.SmartControl: Services init done
08-26 19:02:49.153  6879  6879 D UEI.SmartControl: QS Service init finished
08-26 19:02:49.154  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 19:02:49.155  6879  6879 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 19:02:49.155  6879  6879 D UEI.SmartControl: QS Service version code: 201091
,08-26 19:02:49.156  2130  2130 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 19:02:49.157  6879  6879 D UEI.SmartControl: Service requested: Control
08-26 19:02:49.157  2130  2130 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-26 19:02:49.159  2130  2130 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-26 19:02:49.159  2130  2130 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
,08-26 19:02:49.159  2130  2130 V MediaPlayer[Native]: reset
08-26 19:02:49.165  6879  6910 E UEI.SmartControl: Loading SETTINGS...
,08-26 19:02:49.170  6879  6879 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 19:02:49.174  2130  2130 V MediaPlayer[Native]: setListener
08-26 19:02:49.174  2130  2130 V MediaPlayer[Native]: disconnect
08-26 19:02:49.174  2130  2130 V MediaPlayer[Native]: destructor
08-26 19:02:49.185  1034  2057 I ActivityManager: Killing 5790:com.lge.qremote/u0a112 (adj 15): empty #17
,08-26 19:02:49.188   318  1394 V AudioFlinger: releasing 18 from 2130 for -1
08-26 19:02:49.188   318  1394 V AudioFlinger:  decremented refcount to 0
08-26 19:02:49.188   318  1394 V AudioFlinger: purging stale effects
08-26 19:02:49.190  2130  2130 V MediaPlayer[Native]: disconnect
08-26 19:02:49.192  6879  6910 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 19:02:49.203  2130  2130 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,08-26 19:02:49.206  2130  2130 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-26 19:02:49.206  2130  2130 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-26 19:02:49.208  2130  2130 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-26 19:02:49.208  2130  2130 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-26 19:02:49.208  2130  2130 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-26 19:02:49.209  2130  2130 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 145755440
08-26 19:02:49.209  2130  2130 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 145755440
08-26 19:02:49.218  2130  2130 I SmartShareClient: [SmartShareManagerClient] terminate service: 2130/MediaPlaybackService/967587559
08-26 19:02:49.222  2130  2130 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-26 19:02:49.222  2130  2130 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@3a1a6da9
,08-26 19:02:49.225  6879  6909 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 19:02:49.225  6879  6909 D UEI.SmartControl: -----service ready thread exits
08-26 19:02:49.407  6879  6879 D UEI.SmartControl: Internal service binding...
,08-26 19:02:49.408  1034  1600 W libprocessgroup: failed to open /acct/uid_10112/pid_5790/cgroup.procs: No such file or directory
08-26 19:02:49.414  2130  2130 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-26 19:02:49.415  2130  2130 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-26 19:02:49.418  2130  2130 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-26 19:02:49.419  2130  2130 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-26 19:02:49.428  1034  1933 I ActivityManager: Killing 5735:com.android.calendar/u0a13 (adj 15): empty #17
,08-26 19:02:49.435  2130  2130 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29983
08-26 19:02:49.586  1034  1978 W libprocessgroup: failed to open /acct/uid_10013/pid_5735/cgroup.procs: No such file or directory
,08-26 19:02:50.737  1818  6541 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-26 19:02:50.747   313  6930 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-26 19:02:50.747   313  6930 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-26 19:02:50.747   313  6930 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-26 19:02:50.964  1818  1818 I ConfigFetchService: fetch service done; releasing wakelock
,08-26 19:02:50.965  1818  1818 I ConfigFetchService: stopping self
,08-26 19:02:50.976  2188  2188 I ConfigService: onDestroy
,08-26 19:02:54.136  6879  6911 D UEI.SmartControl: Internal timer expired: 1
,08-26 19:02:54.136  6879  6911 D UEI.SmartControl: unbind internal service
,08-26 19:02:54.149  6879  6879 D UEI.SmartControl: Service.onUnbind: IControl
08-26 19:02:54.149  6879  6879 D UEI.SmartControl: Service.onDestroy
08-26 19:02:54.150  6879  6879 D UEI.SmartControl: Lock is in USE false
08-26 19:02:54.150  6879  6879 D UEI.SmartControl: unbind internal service
08-26 19:02:54.150  6879  6879 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@34cd0439
08-26 19:02:54.151  6879  6879 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
,08-26 19:02:54.151  6879  6879 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-26 19:02:54.151  6879  6879 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-26 19:02:54.152  6879  6879 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-26 19:02:54.152  6879  6879 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-26 19:02:54.152  6879  6879 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-26 19:02:54.152  6879  6879 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
,08-26 19:02:54.152  6879  6879 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-26 19:02:54.152  6879  6879 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:54.152  6879  6879 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 19:02:54.152  6879  6879 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 19:02:54.152  6879  6879 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:54.152  6879  6879 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:02:54.153  6879  6879 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 19:02:54.153  6879  6879 W System.err: 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 19:02:54.153  6879  6879 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@34cd0439
08-26 19:02:54.157  6879  6879 D serial_port: close(fd = 25)
08-26 19:02:54.160  6879  6879 I UEI.SmartControl: Serial port is closed.
08-26 19:02:54.160  6879  6879 I UEI.SmartControl: Serial port is closed.
08-26 19:02:54.160  6879  6879 D UEI.SmartControl: Blaster closed
08-26 19:02:54.160  6879  6879 D UEI.SmartControl: Shut down QS...
08-26 19:02:54.160  6879  6879 D UEI.SmartControl: Stopping QS lib
08-26 19:02:54.161  6879  6879 D UEI.SmartControl: QS lib stop result = true
08-26 19:02:54.161  6879  6879 D UEI.SmartControl: Stopped QS lib
,08-26 19:02:54.161  6879  6879 D UEI.SmartControl: Stopped file observer...
08-26 19:02:54.161  6879  6879 D UEI.SmartControl: QS shutdown complete
,08-26 19:02:55.841  1034  1092 I ActivityManager: Waited long enough for: ServiceRecord{2405ad1c u0 com.google.android.gms/.wearable.service.WearableService}
,08-26 19:02:55.845  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 19:02:55.845  6749  6816 I jxcore-log: 
,08-26 19:02:55.848  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 19:02:55.848  6749  6816 I jxcore-log: 
,08-26 19:02:55.852  6749  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:55.852  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:55.852  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:02:55.852  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:55.852  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:55.852  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:55.852  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:55.852  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:55.854  6749  6816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:55.857  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 19:02:55.857  6749  6816 I jxcore-log: 
08-26 19:02:55.859  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 19:02:55.859  6749  6816 I jxcore-log: 
,08-26 19:02:56.368  6749  6816 D executeNativeTests: Running unit tests
,08-26 19:02:56.449  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 19:02:56.449  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 added. We now have 2 listener(s)
,08-26 19:02:56.450  1034  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 19:02:56.451  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-26 19:02:56.451  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:02:56.451  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:02:56.451  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:02:56.451  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad added. We now have 2 listener(s)
08-26 19:02:56.451  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:02:56.452  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:02:56.453  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:02:56.456  6749  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:56.456  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.456  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:02:56.456  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:56.456  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:56.456  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:56.456  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:56.456  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:56.457  6749  6816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:56.457  6749  6816 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:02:56.458  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 19:02:56.459  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:56.461  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 19:02:56.462  6749  6816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:02:56.462  6749  6816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:02:56.463  6749  6816 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-26 19:02:56.464  6749  6816 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 19:02:56.464  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:02:56.464  6749  6816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 19:02:56.464  6749  6816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:02:56.464  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.466  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:02:56.466  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 19:02:56.467  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.467  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 19:02:56.467  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:02:56.467  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:02:56.468  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 removed from the list
08-26 19:02:56.468  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.468  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad removed from the list
08-26 19:02:56.468  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.468  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:56.469  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.469  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.469  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.469  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.470  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.470  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.472  6749  6816 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 19:02:56.472  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.472  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.472  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.473  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.473  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.473  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.473  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.473  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.473  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
,08-26 19:02:56.473  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.473  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.473  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.473  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.473  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.474  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.474  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.474  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.474  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910],
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 19:02:56.479  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 19:02:56.480  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 19:02:56.480  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 19:02:56.480  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 19:02:56.480  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 19:02:56.480  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 19:02:56.480  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-26 19:02:56.480  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 19:02:56.480  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 19:02:56.480  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.480  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.480  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.480  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.480  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.480  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.481  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.481  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.481  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.481  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.481  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.481  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.481  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.481  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.482  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.482  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 19:02:56.482  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.482  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.482  6749  6816 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 19:02:56.484  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:02:56.490  6749  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:56.490  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.490  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:02:56.490  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:56.490  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:56.490  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:56.490  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:56.490  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:56.492  6749  6816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:56.492  6749  6816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:02:56.492  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:02:56.493  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:02:56.493  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:02:56.493  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:02:56.493  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:02:56.493  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:56.495  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:56.496  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 19:02:56.497  1034  2057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 19:02:56.500  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 19:02:56.504  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 19:02:56.505  6749  6816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 19:02:56.505  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:02:56.506  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:02:56.507  6749  6816 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 19:02:56.507  6749  6816 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 19:02:56.509  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.509  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.509  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.510  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.510  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.510  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:02:56.510  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.510  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.510  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.510  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.510  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.510  6749  6816 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 19:02:56.512  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:02:56.513  6749  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:56.513  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.513  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:02:56.513  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:56.513  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:56.513  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:56.513  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:56.513  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:56.514  6749  6816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:56.514  6749  6816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:02:56.515  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:56.516  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:56.516  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:02:56.517  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:02:56.517  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:02:56.517  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:02:56.517  6749  6816 I org.thaliproject.,p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:02:56.519  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:02:56.520  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:02:56.520  6749  6816 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 19:02:56.521  6749  6816 I io.jxcore.node.ConnectionHelper: start: OK
08-26 19:02:56.522  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.522  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.522  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.522  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.522  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.522  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:02:56.522  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.522  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.522  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.522  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.522  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.523  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.523  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.523  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.523  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.524  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:02:56.524  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:56.524  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.524  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.525  6749  6816 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 19:02:56.526  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:02:56.528  6749  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:56.528  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.528  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:02:56.528  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:56.528  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:56.528  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:56.528  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:56.528  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:56.529  6749  6816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:56.530  6749  6816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:02:56.530  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:02:56.530  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:02:56.530  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:02:56.530  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:02:56.530  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:02:56.531  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:56.536  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:56.537  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:02:56.537  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:02:56.538  6749  6816 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 19:02:56.538  6749  6816 I io.jxcore.node.ConnectionHelper: start: OK
08-26 19:02:56.538  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.538  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.538  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.539  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.539  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.539  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.539  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.539  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.540  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:02:56.540  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.540  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.540  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.540  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.540  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.540  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.540  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.540  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.540  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.541  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:02:56.541  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:56.541  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.541  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.541  6749  6816 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 19:02:56.541  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.541  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.541  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.542  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.542  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.542  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.542  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.542  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.542  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.542  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.542  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.542  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.542  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.542  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.543  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.543  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.543  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:02:56.543  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:56.543  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.543  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.544  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 19:02:56.544  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.544  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.544  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.544  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.544  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.544  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.544  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.544  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.544  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.544  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.544  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.544  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.544  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.544  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.545  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.545  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.546  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:02:56.546  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:56.546  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.546  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.546  6749  6816 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 19:02:56.546  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.546  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.546  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.547  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.547  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.547  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.547  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.547  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.547  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.547  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.547  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.547  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.547  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.547  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.548  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.548  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.548  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:02:56.548  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 19:02:56.548  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.548  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.549  6749  6816 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 19:02:56.549  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.549  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.549  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.549  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.549  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.549  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.549  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.549  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.549  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.549  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.549  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.549  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.549  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.549  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.550  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.550  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.550  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:02:56.550  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:56.550  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.550  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.551  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 19:02:56.551  6749  6816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:02:56.551  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:02:56.551  6749  6816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:02:56.551  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 19:02:56.551  6749  6816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:02:56.551  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.551  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.551  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.551  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.551  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.551  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.552  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.552  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.552  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.552  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.552  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.552  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.552  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.552  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.552  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.552  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.553  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:02:56.553  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:56.553  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.553  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.553  6749  6816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:02:56.553  6749  6816 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 19:02:56.553  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 19:02:56.555  6749  6816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:02:56.555  6749  6816 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 19:02:56.555  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 19:02:56.555  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 19:02:56.555  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 19:02:56.555  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 19:02:56.555  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 19:02:56.555  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 19:02:56.555  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 19:02:56.555  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 19:02:56.555  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 19:02:56.556  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 19:02:56.556  6749  6816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 19:02:56.556  6749  6816 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:02:56.556  6749  6816 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 19:02:56.556  6749  6816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:02:56.556  6749  6816 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:02:56.556  6749  6816 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 19:02:56.556  6749  6816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:02:56.556  6749  6816 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:02:56.556  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 19:02:56.558  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 19:02:56.559  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 19:02:56.559  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 19:02:56.560  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 19:02:56.560  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 19:02:56.560  6749  6816 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 19:02:56.560  6749  6816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:02:56.560  6749  6816 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 19:02:56.560  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.560  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.560  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.560  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.561  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.561  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.561  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 19:02:56.561  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.561  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.561  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.561  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.561  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.561  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.561  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.561  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.562  6749  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 866)
08-26 19:02:56.565  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.565  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.566  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:02:56.566  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:56.566  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.566  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.567  6749  6816 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 19:02:56.567  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.567  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.567  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.567  6749  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 866
08-26 19:02:56.568  6749  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 866)
08-26 19:02:56.568  6749  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 866)
08-26 19:02:56.568  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.568  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.568  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.568  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.568  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.568  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.568  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.568  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.568  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.568  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.568  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.569  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.569  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.569  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:02:56.569  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:56.569  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.569  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.570  6749  6816 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 19:02:56.571  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.571  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.571  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.575  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.575  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.575  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.575  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.575  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.575  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.575  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.575  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.575  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.575  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.575  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.576  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.576  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.576  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:02:56.576  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:56.576  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.576  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.585  6749  6816 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 19:02:56.585  6749  6816 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 19:02:56.585  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:02:56.585  6749  6816 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 19:02:56.586  6749  6816 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 19:02:56.586  6749  6816 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 19:02:56.586  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:02:56.586  6749  6816 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 19:02:56.586  6749  6816 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 19:02:56.586  6749  6816 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 19:02:56.586  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:02:56.586  6749  6816 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 19:02:56.586  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.586  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.586  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.586  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.586  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.586  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.587  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.587  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.587  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.587  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.587  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.587  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.587  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.587  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.587  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.587  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.588  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:02:56.588  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:56.588  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.588  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.588  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.588  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.588  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.588  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.588  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:02:56.588  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.588  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.588  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.588  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.588  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.589  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.589  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.589  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.589  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.589  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.589  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.589  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.589  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.589  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.589  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.589  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.589  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.589  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.589  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.589  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.589  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.589  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.589  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.589  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.590  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.590  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.590  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:02:56.590  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:56.591  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.591  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.592  6749  6816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 19:02:56.592  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:02:56.595  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 19:02:56.596  6749  6816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 19:02:56.596  6749  6816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 19:02:56.596  6749  6749 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 19:02:56.596  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 19:02:56.596  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 19:02:56.597  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.597  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 19:02:56.597  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 19:02:56.597  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 19:02:56.597  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.597  6749  6816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 19:02:56.598  1034  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:02:56.600  6749  6749 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 19:02:56.600  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.600  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.600  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:02:56.600  6749  6816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:02:56.600  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:02:56.601  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:02:56.601  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:02:56.601  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:56.601  6749  6816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:02:56.601  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.601  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.602  6749  6816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:02:56.602  6749  6937 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:02:56.602  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.602  6749  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:02:56.602  6749  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:02:56.603  6749  6749 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:02:56.603  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.603  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.603  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.603  4337  4353 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-26 19:02:56.603  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.603  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.603  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.603  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.603  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.603  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.604  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.604  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.604  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.604  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.604  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.604  6749  6937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 19:02:56.604  6749  6937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 19:02:56.604  6749  6937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 19:02:56.605  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.605  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.605  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.605  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.605  6749  6749 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 19:02:56.608  6749  6816 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 19:02:56.609  6749  6816 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 19:02:56.609  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:02:56.611  6749  6816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:02:56.611  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.611  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.611  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.611  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.611  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.611  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.611  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.611  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.611  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.612  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.612  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.612  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.612  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.612  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.612  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.612  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.613  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.613  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.614  1034  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:02:56.614  1034  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:02:56.618  1034  2057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:02:56.618  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.618  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.618  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.619  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.619  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.619  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.619  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.619  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.619  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.619  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.619  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.619  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.619  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.619  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.620  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.620  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.620  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.620  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.621  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:56.621  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:56.621  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:56.621  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:56.621  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.621  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.621  6749  6816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd47cc4 not in the list
08-26 19:02:56.621  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.621  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.621  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:56.621  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.622  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.622  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:56.622  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:56.622  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:56.622  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:56.622  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:56.622  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81507ad not in the list
08-26 19:02:56.624  6749  6816 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 19:02:56.624  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:02:56.624  6749  6816 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 19:02:56.624  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:02:56.624  6749  6816 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 19:02:56.624  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:02:56.626  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 19:02:56.626  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 19:02:56.627  6749  6816 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 19:02:56.627  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-26 19:02:56.627  6749  6816 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 19:02:56.627  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 19:02:56.627  6749  6816 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 19:02:56.628  6749  6816 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 19:02:56.628  6749  6816 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 19:02:56.628  6749  6816 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 19:02:56.629  6749  6816 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 19:02:56.629  6749  6816 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 19:02:56.629  6749  6816 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 19:02:56.629  6749  6816 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 19:02:56.631  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:02:56.631  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35d1343a added. We now have 2 listener(s)
08-26 19:02:56.631  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:02:56.635  6749  6816 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 19:02:56.636  1034  1933 D WifiServiceImplEx: setWifiEnabled: true pid=6749, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 19:02:56.636  1034  1933 D WifiService: setWifiEnabled: true pid=6749, uid=10118
08-26 19:02:56.636  1034  1933 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 19:02:56.637  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:02:56.637  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6d918eb added. We now have 3 listener(s)
08-26 19:02:56.637  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:02:56.641  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:02:56.641  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c96648 added. We now have 4 listener(s)
08-26 19:02:56.641  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:02:56.644  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:02:56.644  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@169aace1 added. We now have 5 listener(s)
08-26 19:02:56.644  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:02:56.646  6749  6931 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-26 19:02:56.646  6749  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 866)
08-26 19:02:56.647  1034  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6749, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 19:02:56.647  1034  1051 D WifiService: setWifiEnabled: false pid=6749, uid=10118
08-26 19:02:56.647  1034  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 19:02:56.670  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 19:02:56.670  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 19:02:56.670  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 19:02:56.671  1034  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:02:56.671  1034  1466 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 19:02:56.672  1034  1051 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@131f80ed mBinding = false
08-26 19:02:56.672  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 19:02:56.672  1034  1466 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 19:02:56.673  1034  1466 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 19:02:56.673  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 19:02:56.673  1034  1466 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 19:02:56.673  1034  1466 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:02:56.674  1034  1466 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 19:02:56.674  1034  1466 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 19:02:56.674  1034  1466 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 19:02:56.686  1034  1466 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 19:02:56.686  1034  1419 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.686  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.687  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 19:02:56.687  2716  2716 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-26 19:02:56.687  1034  1466 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 19:02:56.687  1034  1466 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 19:02:56.688  1034  1466 D WifiNative-wlan0: SET ps 1: returned true
08-26 19:02:56.689  1034  2870 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.692   313   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:02:56.696  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 19:02:56.697  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 19:02:56.697  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 19:02:56.705  1034  1096 D BluetoothManagerService: Message: 2
,08-26 19:02:56.708  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:02:56.710  1034  1096 D BluetoothManagerService: Sending off request.
08-26 19:02:56.712  4337  6940 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 19:02:56.712  4337  4410 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 19:02:56.712  4337  4410 D BluetoothAdapterProperties: Setting state to 13
08-26 19:02:56.712  4337  4410 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 19:02:56.713  4337  4410 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 19:02:56.713  4337  4410 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 19:02:56.714  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.714  6749  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:56.714  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.714  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:02:56.714  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:56.714  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:56.714  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:56.714  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:56.714  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:56.719  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.719  6749  6816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:56.719  6749  6816 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:02:56.722  4337  4413 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:02:56.724  1034  1096 D BluetoothManagerService: Message: 60
08-26 19:02:56.724  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 19:02:56.724  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 19:02:56.730  4337  4410 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-26 19:02:56.731  4337  4410 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 19:02:56.733  4337  4731 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:02:56.733  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 19:02:56.733  4337  4522 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 19:02:56.734  4337  4788 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:02:56.734  4337  4730 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 19:02:56.734  4337  4730 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:02:56.734  4337  4730 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 19:02:56.734  4337  4730 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 19:02:56.734  4337  4730 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 19:02:56.734  4337  4730 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 19:02:56.734  4337  4730 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 19:02:56.734  4337  4730 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 19:02:56.734  4337  4789 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:02:56.735  4337  4792 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:02:56.745  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:02:56.745  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:02:56.745  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-26 19:02:56.749  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:02:56.749  4337  4522 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:02:56.749  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:02:56.749  4337  4522 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:02:56.749  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:02:56.749  4337  4522 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:02:56.750  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 19:02:56.750  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 19:02:56.750  4337  4522 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 19:02:56.759  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.759  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:56.759  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.759  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:02:56.759  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:56.759  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:56.759  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:56.759  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:56.759  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:56.759  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.759  6749  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:02:56.762  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:56.764  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 19:02:56.765  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.765  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:56.765  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.765  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:02:56.765  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:56.765  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:56.765  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:56.765  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:56.765  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:56.765  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-26 19:02:56.765  1034  1942 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-26 19:02:56.766  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.766  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.766  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 19:02:56.766  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.766  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-26 19:02:56.768  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.768  6749  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:02:56.771  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.772  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:56.772  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.772  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:02:56.772  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:56.772  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:56.772  6749  6749 V io.jxcore.node.Connectivit,yMonitor:     - BSSID name: null
08-26 19:02:56.772  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:02:56.772  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:56.775  1034  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6945 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-26 19:02:56.780  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:56.781  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 19:02:56.782  4337  4337 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:56.783  4337  4337 D BluetoothMapService: STATE_TURNING_OFF
08-26 19:02:56.783  4337  4337 V BtOppService: Receiver DISABLED_ACTION 
08-26 19:02:56.783  4337  4337 V BluetoothMapService: Handler(): got msg=4
08-26 19:02:56.783  4337  4337 D BluetoothMapService: MAP Service closeService in
08-26 19:02:56.783  4337  4337 D BluetoothMapMasInstance: MAP Service shutdown
08-26 19:02:56.783  4337  4337 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 19:02:56.783  4337  4337 V BluetoothMapService: MAP Service closeService out
08-26 19:02:56.784  4337  4337 I BtOppRfcommListener: stopping Accept Thread
08-26 19:02:56.784  4337  4337 V BtOppRfcommListener: close mBtServerSocket
08-26 19:02:56.784  4337  4337 V BtOppRfcommListener: waiting for thread to terminate
08-26 19:02:56.784  4337  4788 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 19:02:56.787  4337  4337 V BtOppRfcommListener: done waiting for thread to terminate
08-26 19:02:56.803  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.803  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:56.803  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.803  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:02:56.803  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:56.803  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:56.803  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:56.803  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:02:56.803  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:56.806  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:56.827  1034  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6966 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 19:02:56.831   313  6978 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 19:02:56.831  4337  4337 V BtOppService: onDestroy
08-26 19:02:56.832  1034  1094 D DSQN    : Dns fail occured do internet check.
08-26 19:02:56.832  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-26 19:02:56.832  1034  1034 D DSQN    : try Internet connection check
08-26 19:02:56.833  1034  1544 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 19:02:56.833  1034  1544 D DSQN    : disableDataServiceNotify
08-26 19:02:56.833  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 19:02:56.833  1034  1544 D DSQN    : stop dsqn bin
08-26 19:02:56.835  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:02:56.835  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:02:56.835  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:02:56.836  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-26 19:02:56.837  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 19:02:56.837  1034  1419 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.837  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.837  1034  1419 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@814c423
08-26 19:02:56.838  1034  1034 D WifiHS20: hidePasspointNotification off =false
,08-26 19:02:56.840  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:02:56.840  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:02:56.840  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:02:56.840  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 19:02:56.840  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-26 19:02:56.840  1034  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.843  1034  1558 D RttService: EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.843  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:02:56.843  1034  1419 D LGWifiP2pService: P2pDisablingState
,08-26 19:02:56.843  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:02:56.843  1034  1419 D LGWifiP2pService: P2pDisablingState{ when=-6ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.844  1034  1419 D LGWifiP2pService: p2p socket connection lost
08-26 19:02:56.844  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:02:56.844  1034  1419 D LGWifiP2pService: P2pDisabledState
08-26 19:02:56.846  4337  4337 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 19:02:56.847  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 19:02:56.847  1943  1943 D WfdsService: WifiP2pState is changed : false
08-26 19:02:56.847  1943  2348 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 19:02:56.847  1943  2348 D WfdsService: Set the WFDS Monitor: false
08-26 19:02:56.848   313  6989 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 19:02:56.848  1943  2348 D WfdsMonitor: WFDS Monitor is stopped
08-26 19:02:56.848  1943  2348 D WfdsService: STATE : WfdsDisabledState - enter
08-26 19:02:56.848  1943  2753 D CtrlSupplicant: Received on exit socket, terminate
08-26 19:02:56.848  1943  2753 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 19:02:56.848  1943  2753 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 19:02:56.849  1943  2753 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 19:02:56.849  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 19:02:56.849  1034  6981 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-26 19:02:56.849  1034  6980 D DSQN    : ThreadInternetCheck internet check NOK 
08-26 19:02:56.850  1034  6980 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
08-26 19:02:56.850  1943  2350 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 19:02:56.850  1034  6980 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
08-26 19:02:56.851  1034  1544 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 19:02:56.851  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:02:56.851  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:02:56.851  1034  1544 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:02:56.851  1034  1544 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 19:02:56.852  1604  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 19:02:56.852  1034  1034 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
08-26 19:02:56.852  1034  1544 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidt,h>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 19:02:56.852  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.852  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.852  1034  2869 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 19:02:56.852  1943  2348 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 19:02:56.854  1034  1466 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 19:02:56.854  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:02:56.855  1034  1466 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:02:56.857  1034  1466 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:02:56.857  1943  1959 D WifiServiceExtension: isInternetCheckAvailable return false
08-26 19:02:56.858  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:02:56.858  1034  1466 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:02:56.859  1034  1466 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:02:56.859  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:02:56.860  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:02:56.860  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:02:56.860  1034  1466 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:02:56.860  1034  1466 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 19:02:56.861  1034  1544 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 19:02:56.861  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:02:56.861  1034  1466 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 19:02:56.861  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 19:02:56.861  1034  1419 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.861  1034  1419 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.861  1034  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:02:56.861  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 19:02:56.861  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 19:02:56.861  2716  2716 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 19:02:56.862  1034  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:02:56.862  1034  1544 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:02:56.862  1034  1544 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:02:56.862  1034  1466 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 19:02:56.862  1034  1466 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 19:02:56.862  1034  1544 D NetworkManagementService: Removing idletimer
08-26 19:02:56.862  1034  1466 D WifiNative-wlan0: SET ps 1: returned true
08-26 19:02:56.863  1034  1544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:02:56.863   313   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:02:56.863  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:02:56.863  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 19:02:56.863  1034  1544 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 19:02:56.864  1034  1466 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 19:02:56.864  1034  1405 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 19:02:56.864  1034  1466 D WifiNative-p2p0: TERMINATE: returned true
08-26 19:02:56.865  1034  1466 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:02:56.865  1034  1466 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:02:56.865  1034  1466 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 19:02:56.865  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
,08-26 19:02:56.867  1034  1405 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 19:02:56.867  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 19:02:56.867  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 19:02:56.867  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 19:02:56.867  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 19:02:56.867  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 19:02:56.867  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 19:02:56.867  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 19:02:56.868  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 19:02:56.869  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:02:56.869  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:02:56.869  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:02:56.875  1034  1466 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:02:56.875  1034  1466 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:02:56.875  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 19:02:56.877  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 19:02:56.877  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:02:56.877  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,08-26 19:02:56.879  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.880  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:56.880  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.880  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:02:56.880  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:02:56.880  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:56.880  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:56.880  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:02:56.880  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:02:56.880  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.880  6749  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:02:56.883  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.883  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:56.883  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.883  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:02:56.883  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:02:56.883  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:56.883  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:56.883  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:02:56.883  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:02:56.884  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.884  6749  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:02:56.902  1034  2870 D DhcpStateMachine: StoppedState
08-26 19:02:56.902  1034  2870 D DhcpStateMachine: StoppedState{ when=-40ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.903  1034  1466 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 19:02:56.903  1034  1466 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 19:02:56.905  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 19:02:56.906  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:02:56.907  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:02:56.920  6966  6966 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:02:56.920  6966  6966 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-26 19:02:56.920  6966  6966 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 19:02:56.921  6966  6966 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-26 19:02:56.922  6966  6966 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 19:02:56.922  6966  6966 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 19:02:56.926  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 19:02:56.927  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:02:56.927  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:02:56.927  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 19:02:56.927  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:02:56.928  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:02:56.943  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:02:56.946  2716  2716 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 19:02:56.946  2716  2716 I wpa_supplicant: monitor socket send errors count : 1
08-26 19:02:56.947  2716  2716 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-2\x00 that cannot receive messages
08-26 19:02:56.948  1034  2749 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 19:02:56.948  1034  2749 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 19:02:56.960  6945  6945 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 19:02:56.960  6945  6945 W LG Account v2.2: No ProfileInfo entries
08-26 19:02:56.960  6945  6945 I LG Account v2.2: isEnabled: false
08-26 19:02:56.960  6945  6945 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 19:02:56.960  6945  6945 I Feature : [Lifetracker]Country: EU
08-26 19:02:56.960  6945  6945 I Feature : [Lifetracker]Operator: OPEN
08-26 19:02:56.960  6945  6945 I Feature : [Lifetracker]Ranking support: false
08-26 19:02:56.960  6945  6945 I Feature : [Lifetracker]Comfort support: false
08-26 19:02:56.960  6945  6945 I Feature : [Lifetracker]Accessory: true
08-26 19:02:56.960  6945  6945 I Feature : [Lifetracker]Health device: true
08-26 19:02:56.961  6945  6945 I Feature : [Lifetracker]Extra Pedometer: false
08-26 19:02:56.961  6945  6945 I Feature : [Lifetracker]Blood glucose device: false
08-26 19:02:56.961  6945  6945 I Feature : [Lifetracker]Device Number: 3
,08-26 19:02:56.968  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:02:56.985  2716  2716 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 19:02:56.986  1034  2749 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 19:02:56.986  1034  2749 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 19:02:56.986  1034  2749 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 19:02:56.986  1034  2749 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 19:02:56.987  2716  2716 W wpa_supplicant: USIM:  scard_deinit function
08-26 19:02:56.987  1034  2749 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:02:56.987  1034  2749 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:02:56.987  1034  1466 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=120317
08-26 19:02:56.988  1034  1096 D Tethering: InitialState.processMessage what=4
08-26 19:02:56.988  1034  1466 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=120319
08-26 19:02:56.989  1034  1466 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=120320  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 19:02:56.990  1034  1466 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=120321  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 19:02:57.009  1034  1978 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6994 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 19:02:57.010  1034  1978 I ActivityManager: Killing 6307:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-26 19:02:57.058  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 19:02:57.060  1034  1466 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:02:57.060  1034  1466 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:02:57.067  2716  2716 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 19:02:57.068  1034  2749 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,08-26 19:02:57.068  1034  2749 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 19:02:57.069  1034  2749 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 19:02:57.071  1034  1466 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-26 19:02:57.075  1034  2013 W libprocessgroup: failed to open /acct/uid_10014/pid_6307/cgroup.procs: No such file or directory
08-26 19:02:57.102  6749  6749 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:02:57.142  6994  6994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-26 19:02:57.155  6994  6994 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 19:02:57.156  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 19:02:57.158  1034  2013 I ActivityManager: Killing 6394:com.android.defcontainer/u0a4 (adj 15): empty #17
08-26 19:02:57.169  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 19:02:57.190  1034  1466 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 19:02:57.191  1034  1466 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:02:57.191  1034  1466 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:02:57.191  1034  1466 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 19:02:57.191  1034  1050 W libprocessgroup: failed to open /acct/uid_10004/pid_6394/cgroup.procs: No such file or directory
08-26 19:02:57.202  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-26 19:02:57.202  1943  2348 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-26 19:02:57.202  1943  2348 D WfdsService: Set the WFDS Monitor: false
08-26 19:02:57.202  1943  2348 D WfdsMonitor: WFDS Monitor is stopped
08-26 19:02:57.202  4337  4337 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-26 19:02:57.202  4337  4337 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:57.202  4337  4337 V BluetoothPbapReceiver: ***********state = 13
08-26 19:02:57.205  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:02:57.205  4337  4337 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 19:02:57.205  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 19:02:57.208  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 19:02:57.208  1034  1531 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
,08-26 19:02:57.208  1034  1531 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 19:02:57.208  2508  2508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:02:57.213  4337  4337 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:57.213  4337  4337 V BluetoothPbapService: state: 13
08-26 19:02:57.213  4337  4337 V BluetoothPbapService: Pbap Service closeService in
,08-26 19:02:57.213  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 19:02:57.216  4337  4337 V BluetoothPbapService: successfully stopped pbap service
08-26 19:02:57.216  4337  4337 V BluetoothPbapService: Pbap Service closeService out
08-26 19:02:57.217  4337  4337 V BluetoothPbapService: Pbap Service onDestroy
08-26 19:02:57.217  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:57.217  4337  4337 V BluetoothPbapService: Pbap Service closeService in
08-26 19:02:57.217  4337  4337 V BluetoothPbapService: Pbap Service closeService out
08-26 19:02:57.217  4337  4337 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 19:02:57.218  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 19:02:57.218  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:57.253  6966  6966 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 19:02:57.253  6966  6966 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 19:02:57.262  1034  1379 V AlarmManager: RTC_WAKEUP set : Alarm{528be9c type 0 when 1472230977256 com.android.vending} when 1472230977256
,08-26 19:02:57.265  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:02:57.287  1034  1096 D BluetoothManagerService: Message: 20
,08-26 19:02:57.288  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@af41c7a:true
08-26 19:02:57.300  1034  1096 D BluetoothManagerService: Message: 30
,08-26 19:02:57.306  1034  1096 D BluetoothManagerService: Message: 30
08-26 19:02:57.309  6966  6966 D LocalBluetoothProfileManager: Adding local MAP profile
08-26 19:02:57.311  6966  6966 D BluetoothMap: Create BluetoothMap proxy object
08-26 19:02:57.312  1034  1096 D BluetoothManagerService: Message: 30
,08-26 19:02:57.316  1034  1096 D BluetoothManagerService: Message: 30
08-26 19:02:57.318  6966  6966 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-26 19:02:57.320  6966  6966 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-26 19:02:57.334  1034  1907 V SIM_STK : Menu title from STK is T-Mobile
08-26 19:02:57.335  6966  6966 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-26 19:02:57.338  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-26 19:02:57.349  6966  6966 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:02:57.363  6966  6966 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 19:02:57.367  6966  6966 D BluetoothInputDevice: Proxy object connected
08-26 19:02:57.369  6966  6966 D HidProfile: Bluetooth service connected
08-26 19:02:57.370  6966  6966 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 19:02:57.370  6966  6966 D PanProfile: Bluetooth service connected
08-26 19:02:57.371  6966  6966 D BluetoothMap: Proxy object connected
08-26 19:02:57.372  6966  6966 D MapProfile: Bluetooth service connected
08-26 19:02:57.372  6966  6966 D BluetoothMap: getConnectedDevices()
08-26 19:02:57.373  6966  6966 D BluetoothMap: Bluetooth is Not enabled
08-26 19:02:57.373  6966  6966 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 19:02:57.375  6966  6966 D BluetoothPermissionRequest: onReceive
,08-26 19:02:57.377  6966  6966 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 19:02:57.386  4337  4337 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-26 19:02:57.386  4337  4337 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 19:02:57.387  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 19:02:57.388  4337  4337 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-26 19:02:57.460  1034  1051 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7022 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-26 19:02:57.464  1034  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{16b3f9cd type 2 when 120732 com.google.android.gms} when 120732
08-26 19:02:57.465  4337  4337 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:57.465  4337  4337 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 19:02:57.467  4337  4337 V BluetoothFtpService: Ftp Service onStartCommand
08-26 19:02:57.467  4337  4337 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:57.468  4337  4337 V BluetoothFtpService: Ftp Service closeService
08-26 19:02:57.468  4337  4337 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 19:02:57.469  4337  4337 V BluetoothFtpService: successfully stopped ftp service
08-26 19:02:57.470  4337  4337 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:02:57.470  4337  4337 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:02:57.470  4337  4337 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:02:57.470  4337  4337 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:57.470  4337  4337 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 19:02:57.470  4337  4337 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 19:02:57.473  4337  4337 V BluetoothFtpService: Ftp Service onDestroy
08-26 19:02:57.473  4337  4337 V BluetoothFtpService: Ftp Service closeService
,08-26 19:02:57.516  1034  1907 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7039 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 19:02:57.519  4337  4337 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:57.519  4337  4337 V BluetoothSapService: state: 13
08-26 19:02:57.519  4337  4337 V BluetoothSapService: Stopping SAP server process
08-26 19:02:57.520  4337  4337 V BluetoothSapService: Sap Service closeSapService in
08-26 19:02:57.520  4337  4337 V BluetoothSapService: Close listen Socket : 
08-26 19:02:57.520  4337  4337 V BluetoothSapService: Close rfcomm Socket : 
08-26 19:02:57.521  4337  4337 V BluetoothSapService: Close sapd  Socket : 
08-26 19:02:57.528  4337  4337 V BluetoothSapService: Sap Service closeSapService out
,08-26 19:02:57.529  4337  4337 V BluetoothSapService: Sap Service onDestroy
08-26 19:02:57.529  4337  4337 V BluetoothSapService: Sap Service closeSapService in
08-26 19:02:57.529  4337  4337 V BluetoothSapService: Close listen Socket : 
08-26 19:02:57.529  4337  4337 V BluetoothSapService: Close rfcomm Socket : 
08-26 19:02:57.529  4337  4337 V BluetoothSapService: Close sapd  Socket : 
08-26 19:02:57.530  4337  4337 V BluetoothSapService: Sap Service closeSapService out
08-26 19:02:57.549  7022  7022 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 19:02:57.570  7039  7039 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 19:02:57.579  7022  7022 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-26 19:02:57.584  1034  1576 I ActivityManager: Killing 6549:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-26 19:02:57.590  6675  6675 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
08-26 19:02:57.607  7022  7022 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-26 19:02:57.608  7022  7022 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 19:02:57.608  7022  7022 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 19:02:57.608  7022  7022 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 19:02:57.608  7022  7022 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-26 19:02:57.610  7022  7022 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 19:02:57.614  7022  7022 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-26 19:02:57.632  1034  1942 W libprocessgroup: failed to open /acct/uid_10008/pid_6549/cgroup.procs: No such file or directory
,08-26 19:02:57.635  1034  1576 I ActivityManager: Killing 6592:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-26 19:02:57.639  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:02:57.643  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:02:57.677  1034  1051 W libprocessgroup: failed to open /acct/uid_10011/pid_6592/cgroup.procs: No such file or directory
,08-26 19:02:57.681  7022  7022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 19:02:57.686  7022  7022 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 19:02:57.686  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:02:57.691  7022  7022 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-26 19:02:57.693  6994  6994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 19:02:57.693  6994  6994 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 19:02:57.693  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:02:57.699  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:02:57.708  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:02:57.722  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 19:02:57.723  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:02:57.727  7022  7022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 19:02:57.734  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:02:57.741  6994  6994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 19:02:57.742  6994  6994 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 19:02:57.742  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:02:57.748  4337  4522 W bt-btif : ag scb idx 1 not allocated
08-26 19:02:57.748  4337  4413 D bt_hci_bdroid: cleanup
08-26 19:02:57.748  4337  4522 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:02:57.749  4337  4524 I bt_lpm  : LPM is already off!!!
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:02:57.749  4337  4694 I bt_userial_mct: exiting userial_read_thread
08-26 19:02:57.749  4337  4694 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:02:57.749  4337  4522 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:02:57.750  4337  4522 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 19:02:57.750  4337  4413 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 19:02:57.750  4337  4524 I bt_vendor: hw_epilog_process
08-26 19:02:57.751  4337  4413 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 19:02:57.751  4337  4413 D bt_userial_mct: userial_close
08-26 19:02:57.751  4337  4413 E bt_userial_mct: pthread_join() FAILED result:3
08-26 19:02:57.751  4337  4413 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 19:02:57.753  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:02:57.766  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:02:57.780  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:02:57.781  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:02:57.784  7022  7022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 19:02:57.851  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,08-26 19:02:57.863  1034  1051 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7064 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-26 19:02:57.875  4337  4413 D bt_hci_bdroid: set_power 0
,08-26 19:02:57.875  4337  4413 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 19:02:57.875  4337  4413 I bt_vendor: bluetooth satus is on
08-26 19:02:57.875  4337  4413 I bt_vendor: bt-vendor : resetting BT status
08-26 19:02:57.875  4337  4413 I bt_vendor: Starting hciattach daemon
08-26 19:02:57.875  4337  4413 I bt_vendor: try to set false
08-26 19:02:57.877  4337  4413 I bt_vendor: Starting hciattach daemon
,08-26 19:02:57.877  4337  4413 I bt_vendor: try to set false
08-26 19:02:57.877  4337  4413 I bt_vendor: cleanup
08-26 19:02:57.878  4337  4522 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 19:02:57.879  4337  4413 I GKI_LINUX: GKI_exit_task 0 done
08-26 19:02:57.879  4337  4413 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 19:02:57.880  4337  4410 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 19:02:57.884  4337  4337 D HeadsetService: Received stop request...Stopping profile...
08-26 19:02:57.885  4337  4337 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 19:02:57.885  4337  4337 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:02:57.885  4337  4337 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e39d32
08-26 19:02:57.885  4337  4454 D HeadsetStateMachine: Exit Disconnected: -1
08-26 19:02:57.887  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 19:02:57.887  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 19:02:57.887  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 19:02:57.887  1034  1034 D BluetoothHeadset: Proxy object disconnected
,08-26 19:02:57.891  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 19:02:57.892   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 480us total 37.907ms
08-26 19:02:57.893  4337  4337 D A2dpService: Received stop request...Stopping profile...
08-26 19:02:57.894  4337  4493 D A2dpStateMachine: Exit Disconnected: -1
08-26 19:02:57.895  4337  4410 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 19:02:57.895  4337  4337 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 19:02:57.897  4337  4337 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 19:02:57.897  4337  4337 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:02:57.897  4337  4337 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e39d32
08-26 19:02:57.897  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-26 19:02:57.897  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 19:02:57.898  4337  4337 D HidService: Received stop request...Stopping profile...
08-26 19:02:57.898  4337  4337 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e39d32
08-26 19:02:57.899  6966  6966 D BluetoothInputDevice: Proxy object disconnected
08-26 19:02:57.900  6966  6966 D HidProfile: Bluetooth service disconnected
08-26 19:02:57.901  4337  4337 D HealthService: Received stop request...Stopping profile...
08-26 19:02:57.901  4337  4337 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e39d32
08-26 19:02:57.902  4337  4337 D HeadsetStateMachine: Unbinding service...
08-26 19:02:57.904  4337  4337 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 19:02:57.904  4337  4337 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 19:02:57.904  4337  4337 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 19:02:57.904  4337  4337 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 19:02:57.904  4337  4337 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 19:02:57.904  4337  4337 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 19:02:57.904  4337  4337 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 19:02:57.907  4337  4337 D PanService: Received stop request...Stopping profile...
08-26 19:02:57.907  4337  4337 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e39d32
08-26 19:02:57.909  4337  4337 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 19:02:57.909  4337  4337 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 19:02:57.910  4337  4337 D BtGatt.GattService: stop()
08-26 19:02:57.910  4337  4337 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 19:02:57.911  4337  4337 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e39d32
08-26 19:02:57.912  4337  4337 D BluetoothMapService: Received stop request...Stopping profile...
08-26 19:02:57.912  4337  4337 D BluetoothMapService: stop()
08-26 19:02:57.912  4337  4337 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 19:02:57.912  4337  4337 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 19:02:57.913   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 20.357ms
08-26 19:02:57.913  4337  4337 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34e39d32
08-26 19:02:57.915  4337  4337 I BluetoothA2dpServiceJni: cleanupNative
08-26 19:02:57.915  4337  4494 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 19:02:57.915  6966  6966 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 19:02:57.915  6966  6966 D PanProfile: Bluetooth service disconnected
08-26 19:02:57.915  4337  4337 I GKI_LINUX: GKI_exit_task 2 done
08-26 19:02:57.916  4337  4337 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 19:02:57.916  6966  6966 D BluetoothMap: Proxy object disconnected
08-26 19:02:57.916  6966  6966 D MapProfile: Bluetooth service disconnected
08-26 19:02:57.916  4337  4337 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 19:02:57.916  4337  4337 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 19:02:57.916  4337  4337 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 19:02:57.917  4337  4337 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 19:02:57.917  4337  4337 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 19:02:57.917  4337  4337 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 19:02:57.917  4337  4337 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 19:02:57.918  4337  4337 V BluetoothMapService: Handler(): got msg=4
08-26 19:02:57.918  4337  4337 D BluetoothMapService: MAP Service closeService in
08-26 19:02:57.918  4337  4337 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 19:02:57.918  4337  4337 V BluetoothMapService: MAP Service closeService out
08-26 19:02:57.919  4337  4410 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 19:02:57.919  4337  4410 D BluetoothAdapterProperties: Setting state to 10
08-26 19:02:57.919  4337  4410 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 19:02:57.919  4337  4337 D BluetoothMapService: cleanup()
08-26 19:02:57.919  4337  4337 D BluetoothMapService: MAP Service closeService in
08-26 19:02:57.919  4337  4337 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 19:02:57.919  4337  4337 V BluetoothMapService: MAP Service closeService out
,08-26 19:02:57.921  1034  1096 D BluetoothManagerService: Message: 60
08-26 19:02:57.921  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 19:02:57.921  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-26 19:02:57.923  6966  6987 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 19:02:57.923  4337  4410 I BluetoothAdapterState: Entering OffState
08-26 19:02:57.925  1853  4461 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:02:57.929  6966  6991 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 19:02:57.929  6966  6987 D BluetoothPan: onBluetoothStateChange on: false
08-26 19:02:57.930  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 19:02:57.930  1853  2723 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:02:57.931  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:02:57.932  6966  6991 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 19:02:57.932  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:02:57.933  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 19:02:57.933  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-26 19:02:57.934   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 20.203ms
08-26 19:02:57.937  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 19:02:57.937  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 19:02:57.937  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@131f80ed mBinding = false
08-26 19:02:57.937  1034  1096 D BluetoothManagerService: Sending unbind request.
08-26 19:02:57.938  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 19:02:57.942  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:57.943  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:57.943  1943  2127 D LGBluetoothAPIService: Message: 2
08-26 19:02:57.943  1943  2127 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@6a89e4d mBinding = false
08-26 19:02:57.943  1943  2127 D LGBluetoothAPIService: Sending unbind request.
08-26 19:02:57.944  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:57.946  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 19:02:57.947  6966  6966 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 19:02:57.948  6966  6966 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 19:02:57.948  6966  6966 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 19:02:57.950  4337  4413 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 19:02:57.950  4337  4337 I GKI_LINUX: GKI_exit_task 1 done
08-26 19:02:57.951  4337  4337 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 19:02:57.951  1604  1604 D BluetoothAdapter: 455772426: getState() :  mService = null. Returning STATE_OFF
08-26 19:02:57.951  1604  1604 D BluetoothAdapter: 455772426: getState() :  mService = null. Returning STATE_OFF
08-26 19:02:57.951  4337  4337 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 19:02:57.951  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 19:02:57.951  4337  4337 I art     : --- WEIRD: removing null entry 246
08-26 19:02:57.951  4337  4337 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-26 19:02:57.951  4337  4337 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 19:02:57.954  4337  4337 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 19:02:57.956  4337  4337 I art     : System.exit called, status: 0
08-26 19:02:57.956  4337  4337 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 19:02:57.959  6966  6966 D DockEventReceiver: finishStartingService: stopping service
08-26 19:02:57.975   318  2153 V AudioFlinger: 4337 died, releasing its sessions
08-26 19:02:57.975   318  2153 V AudioFlinger:  pid 1853 @ 0
,08-26 19:02:57.975   318  2153 V AudioFlinger:  pid 3201 @ 1
08-26 19:02:57.975   318  2153 V AudioFlinger:  pid 3201 @ 2
08-26 19:02:57.976  6966  6966 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 19:02:57.995  1034  1969 I ActivityManager: Process com.android.bluetooth (pid 4337) has died
,08-26 19:02:57.995  1034  1969 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-26 19:02:58.000  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 19:02:58.017  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 19:02:58.021  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 19:02:58.028  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:02:58.028  6966  6966 D BluetoothPermissionRequest: onReceive
,08-26 19:02:58.031  6966  6966 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 19:02:58.032  6966  6966 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 19:02:58.033  7064  7091 W FormManager: Network not available. Please check & try again.
08-26 19:02:58.033  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 19:02:58.097  1034  1600 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7093 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 19:02:58.121  7064  7092 V FormManager: Network unavailable.
,08-26 19:02:58.125  7064  7092 V FormManager: Network unavailable.
,08-26 19:02:58.127  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 19:02:58.127  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 19:02:58.127  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 19:02:58.128  6966  6966 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 19:02:58.128  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 19:02:58.137  6966  6966 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-26 19:02:58.137  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 19:02:58.137  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 19:02:58.137  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 19:02:58.137  6966  6966 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 19:02:58.137  6966  6966 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 19:02:58.141  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 19:02:58.141  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:02:58.143  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:02:58.145  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:02:58.150  1034  1576 I ActivityManager: Killing 6098:com.android.contacts/u0a19 (adj 15): empty #17
,08-26 19:02:58.156  4795  7114 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 19:02:58.158  4795  7114 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 19:02:58.159  4795  7112 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 19:02:58.187  1034  1908 W libprocessgroup: failed to open /acct/uid_10019/pid_6098/cgroup.procs: No such file or directory
,08-26 19:02:58.218  6994  6994 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-26 19:02:58.220  6994  6994 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 19:02:58.220  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:02:58.226  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 19:02:58.226  7064  7116 W FormManager: Network not available. Please check & try again.
08-26 19:02:58.230  7064  7117 V FormManager: Network unavailable.
,08-26 19:02:58.234  7064  7117 V FormManager: Network unavailable.
08-26 19:02:58.235  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:02:58.236  7093  7093 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 19:02:58.236  7093  7093 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 19:02:58.237  7093  7093 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-26 19:02:58.237  7093  7093 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 19:02:58.261  7093  7093 D BluetoothAdapterApp: Loading JNI Library
08-26 19:02:58.265   313  7121 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 19:02:58.265  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-26 19:02:58.268  7022  7022 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 19:02:58.270  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 19:02:58.270  7022  7022 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-26 19:02:58.296  7093  7093 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1df550b Instance Count = 1
08-26 19:02:58.298  4975  7118 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-26 19:02:58.302  7093  7093 D BluetoothAdapterApp: onCreate
08-26 19:02:58.313  7022  7022 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:02:58.314  7022  7022 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:02:58.336  7093  7093 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 19:02:58.336  7093  7093 D ProfileConfigQcom: Adding HeadsetService
08-26 19:02:58.337  7093  7093 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 19:02:58.337  7022  7022 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-26 19:02:58.337  7093  7093 D ProfileConfigQcom: Adding A2dpService
08-26 19:02:58.337  7093  7093 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 19:02:58.337  7093  7093 D ProfileConfigQcom: Adding HidService
08-26 19:02:58.338  7093  7093 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 19:02:58.338  7022  7022 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 19:02:58.338  7022  7022 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-26 19:02:58.338  7022  7022 V SoundPool: doLoad: loading sample sampleID=1
08-26 19:02:58.338  7093  7093 D ProfileConfigQcom: Adding HealthService
08-26 19:02:58.338  7093  7093 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 19:02:58.338  7022  7022 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 19:02:58.339  7093  7093 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 19:02:58.340  7022  7129 V SoundPool: Start decode
08-26 19:02:58.340  7022  7129 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 19:02:58.341   318  1394 V MediaPlayerService: decode(23, 10857164, 17813)
08-26 19:02:58.341   318  1394 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 19:02:58.341   318  1394 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 19:02:58.341   318  1394 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 19:02:58.341   318  1394 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 19:02:58.341   318  1394 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 19:02:58.341   318  1394 V MediaPlayerService: player type = 3
08-26 19:02:58.341   318  1394 V AwesomePlayer: AwesomePlayer create()
08-26 19:02:58.342   318  1394 V AwesomePlayer: reset_l() 
08-26 19:02:58.342   318  1394 V AwesomePlayer: cancelPlayerEvents
08-26 19:02:58.342   318  1394 V AwesomePlayer: setAudioSink() 
08-26 19:02:58.342   318  1394 V AwesomePlayer: reset_l() 
08-26 19:02:58.342   318  1394 V AudioCache: notify(0xb54744c0, 8, 0, 0)
08-26 19:02:58.342   318  1394 V AudioCache: ignored
08-26 19:02:58.342   318  1394 V AwesomePlayer: cancelPlayerEvents
08-26 19:02:58.342   318  1394 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 19:02:58.342  7093  7093 D ProfileConfigQcom: Adding PanService
08-26 19:02:58.342   318  1394 V AwesomePlayer: setDataSource_l dataSource
08-26 19:02:58.342   318  1394 V LGParserOSAL: SniffLGParser start
08-26 19:02:58.342   318  1394 V LGParserOSAL: MainType:5, SubType=0
08-26 19:02:58.342   318  1394 V LGParserOSAL: #### check Mime : application/ogg
08-26 19:02:58.342   318  1394 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 19:02:58.342   318  1394 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 19:02:58.342  7093  7093 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 19:02:58.342  7022  7022 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-26 19:02:58.342  7093  7093 D ProfileConfigQcom: Adding GattService
08-26 19:02:58.342  7093  7093 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 19:02:58.343  7093  7093 D ProfileConfigQcom: Adding BluetoothMapService
08-26 19:02:58.343  7093  7093 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 19:02:58.345  7093  7093 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 19:02:58.346  6879  6879 D UEI.SmartControl: QS Service created
08-26 19:02:58.348  7022  7022 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 19:02:58.348  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 19:02:58.358  6966  6966 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-26 19:02:58.360  7093  7093 V LGMDMManagerInternal: Create singleton instance
08-26 19:02:58.362  7022  7022 V LGMDMManager: Create singleton instance
08-26 19:02:58.367  6879  6879 I UEI.SmartControl: Service initServices...
,08-26 19:02:58.368  6879  6879 D UEI.SmartControl: QS start get config
08-26 19:02:58.379   318  1394 V LGParserOSAL: supported mime: application/ogg
08-26 19:02:58.379   318  1394 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 19:02:58.379   318  1394 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 19:02:58.379   318  1394 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 19:02:58.379   318  1394 V AwesomePlayer: AudioTrack Setting
08-26 19:02:58.379   318  1394 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 19:02:58.379   318  1394 V AwesomePlayer: setAudioSource() 
08-26 19:02:58.379   318  1394 V MediaPlayerService: prepare
08-26 19:02:58.379   318  1394 V AwesomePlayer: prepareAsync_l() 
08-26 19:02:58.379   318  1394 V MediaPlayerService: wait for prepare
08-26 19:02:58.379   318  7130 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 19:02:58.379   318  7130 V AwesomePlayer: initAudioDecoder() 
08-26 19:02:58.379   318  7130 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 19:02:58.379   318  7130 V AudioSystem: isOffloadSupported()
08-26 19:02:58.379   318  7130 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 19:02:58.379   318  7130 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 19:02:58.379   318  7130 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 19:02:58.379   318  7130 V AwesomePlayer: getUseOffload() = 0 
08-26 19:02:58.379   318  7130 V OMXCodec: OMXCodec::Create
08-26 19:02:58.379   318  7130 V OMXCodec: findMatchingCodecs()
08-26 19:02:58.379   318  7130 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 19:02:58.379   318  7130 V OMXCodec: matchingCodecs.size()=1
08-26 19:02:58.379   318  7130 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-26 19:02:58.380   318  7130 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 19:02:58.380   318  7130 V LGCodecAdapter: LG Codec Adapter start
08-26 19:02:58.380   318  7130 V OMXCodec: OMXCodec Createtor
08-26 19:02:58.380   318  7130 V OMXCodec: setComponentRole
,08-26 19:02:58.380   318  7130 V OMXCodec: configureCodec protected=0
08-26 19:02:58.380   318  7130 V LGCodecAdapter: called getLGCodecSpecificData
08-26 19:02:58.380   318  7130 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 19:02:58.380   318  7130 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 19:02:58.380   318  7130 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 19:02:58.380   318  7130 V LGCodecOSAL: Not support LGCodec
08-26 19:02:58.381   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 19:02:58.381   318  7130 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 19:02:58.381   318  7130 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 19:02:58.381   318  7130 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 19:02:58.381   318  7130 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 19:02:58.381   318  7130 V AudioSystem: isOffloadSupported()
08-26 19:02:58.381   318  7130 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 19:02:58.381   318  7130 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 19:02:58.381   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 19:02:58.381   318  7130 V OMXCodec: init()
08-26 19:02:58.381   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 19:02:58.381   318  7130 V OMXCodec: allocateBuffers
08-26 19:02:58.381   318  7130 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 19:02:58.381   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 19:02:58.381   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-26 19:02:58.381   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-26 19:02:58.381   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-26 19:02:58.381   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-26 19:02:58.381   318  7130 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 19:02:58.381   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 19:02:58.381   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-26 19:02:58.381   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-26 19:02:58.381   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-26 19:02:58.381   318  7130 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-26 19:02:58.381   318  7130 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 19:02:58.381   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 19:02:58.381   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 19:02:58.382   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 19:02:58.382   318  7130 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 19:02:58.382   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 19:02:58.382   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 19:02:58.382   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-26 19:02:58.382   318  7130 V OMXCodec: init() mAsyncCompletion wait free! 
08-26 19:02:58.382   318  7130 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 19:02:58.382   318  7130 V AudioCache: notify(0xb54744c0, 5, 0,, 0)
08-26 19:02:58.382   318  7130 V AudioCache: ignored
08-26 19:02:58.382   318  7130 V AudioCache: notify(0xb54744c0, 1, 0, 0)
08-26 19:02:58.382   318  7130 V AudioCache: prepared
08-26 19:02:58.382   318  1394 V AudioCache: wait - success
08-26 19:02:58.382   318  1394 V MediaPlayerService: start
08-26 19:02:58.382   318  1394 V AwesomePlayer: play_l() 
08-26 19:02:58.382   318  1394 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 19:02:58.382   318  1394 V AwesomePlayer: createAudioPlayer_l
08-26 19:02:58.382   318  1394 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 19:02:58.382   318  1394 V AwesomePlayer: startAudioPlayer_l() 
08-26 19:02:58.382   318  1394 D AudioPlayer: start of Playback, useOffload 0
,08-26 19:02:58.382   318  1394 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 19:02:58.382   318  1394 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
,08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-26 19:02:58.384   318  7132 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-26 19:02:58.384   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434240 on output port
08-26 19:02:58.385   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 19:02:58.385   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 19:02:58.385   318  1394 V AudioCache: open(48000, 2, 0x0, 1, 4)
,08-26 19:02:58.386   318  1394 V AudioCache: notify(0xb54744c0, 6, 0, 0)
08-26 19:02:58.386   318  1394 V AudioCache: ignored
08-26 19:02:58.386   318  1394 V MediaPlayerService: wait for playback complete
08-26 19:02:58.386   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.386   318  7133 V AudioCache: memcpy(0xaf006000, 0xb16dd000, 4096)
08-26 19:02:58.387   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.387   318  7133 V AudioCache: memcpy(0xaf007000, 0xb16dd000, 4096)
08-26 19:02:58.387   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.387   318  7133 V AudioCache: memcpy(0xaf008000, 0xb16dd000, 4096)
08-26 19:02:58.388   318  7133 V AudioCache: write(0xb16dd000, 4096)
,08-26 19:02:58.388   318  7133 V AudioCache: memcpy(0xaf009000, 0xb16dd000, 4096)
08-26 19:02:58.388   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.388   318  7133 V AudioCache: memcpy(0xaf00a000, 0xb16dd000, 4096)
08-26 19:02:58.388   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.388   318  7133 V AudioCache: memcpy(0xaf00b000, 0xb16dd000, 4096)
08-26 19:02:58.389   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.389   318  7133 V AudioCache: memcpy(0xaf00c000, 0xb16dd000, 4096)
08-26 19:02:58.390   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.390   318  7133 V AudioCache: memcpy(0xaf00d000, 0xb16dd000, 4096)
08-26 19:02:58.390   318  7133 V AudioCache: write(0xb16dd000, 4096)
,08-26 19:02:58.390   318  7133 V AudioCache: memcpy(0xaf00e000, 0xb16dd000, 4096)
08-26 19:02:58.390   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.390   318  7133 V AudioCache: memcpy(0xaf00f000, 0xb16dd000, 4096)
08-26 19:02:58.390   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.390   318  7133 V AudioCache: memcpy(0xaf010000, 0xb16dd000, 4096)
,08-26 19:02:58.391   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.391   318  7133 V AudioCache: memcpy(0xaf011000, 0xb16dd000, 4096)
08-26 19:02:58.391   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.391   318  7133 V AudioCache: memcpy(0xaf012000, 0xb16dd000, 4096)
08-26 19:02:58.391   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.391   318  7133 V AudioCache: memcpy(0xaf013000, 0xb16dd000, 4096)
08-26 19:02:58.392   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.392   318  7133 V AudioCache: memcpy(0xaf014000, 0xb16dd000, 4096)
08-26 19:02:58.392   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.392   318  7133 V AudioCache: memcpy(0xaf015000, 0xb16dd000, 4096)
08-26 19:02:58.393   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.393   318  7133 V AudioCache: memcpy(0xaf016000, 0xb16dd000, 4096)
08-26 19:02:58.393   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.393   318  7133 V AudioCache: memcpy(0xaf017000, 0xb16dd000, 4096)
08-26 19:02:58.394   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.394   318  7133 V AudioCache: memcpy(0xaf018000, 0xb16dd000, 4096)
08-26 19:02:58.394   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.394   318  7133 V AudioCache: memcpy(0xaf019000, 0xb16dd000, 4096)
08-26 19:02:58.394   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.394   318  7133 V AudioCache: memcpy(0xaf01a000, 0xb16dd000, 4096)
08-26 19:02:58.395   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.395   318  7133 V AudioCache: memcpy(0xaf01b000, 0xb16dd000, 4096)
08-26 19:02:58.395   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.396   318  7133 V AudioCache: memcpy(0xaf01c000, 0xb16dd000, 4096)
08-26 19:02:58.396   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.396   318  7133 V AudioCache: memcpy(0xaf01d000, 0xb16dd000, 4096)
08-26 19:02:58.396   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.396   318  7133 V AudioCache: memcpy(0xaf01e000, 0xb16dd000, 4096)
08-26 19:02:58.397   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.397   318  7133 V AudioCache: memcpy(0xaf01f000, 0xb16dd000, 4096)
08-26 19:02:58.397   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.397   318  7133 V AudioCache: memcpy(0xaf020000, 0xb16dd000, 4096)
08-26 19:02:58.398   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.398   318  7133 V AudioCache: memcpy(0xaf021000, 0xb16dd000, 4096)
08-26 19:02:58.398   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.398   318  7133 V AudioCache: memcpy(0xaf022000, 0xb16dd000, 4096)
08-26 19:02:58.398   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.399   318  7133 V AudioCache: memcpy(0xaf023000, 0xb16dd000, 4096)
08-26 19:02:58.399   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.399   318  7133 V AudioCache: memcpy(0xaf024000, 0xb16dd000, 4096)
08-26 19:02:58.399   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.399   318  7133 V AudioCache: memcpy(0xaf025000, 0xb16dd000, 4096)
08-26 19:02:58.400   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.400   318  7133 V AudioCache: memcpy(0xaf026000, 0xb16dd000, 4096)
08-26 19:02:58.400   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.400   318  7133 V AudioCache: memcpy(0xaf027000, 0xb16dd000, 4096)
08-26 19:02:58.401   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.401   318  7133 V AudioCache: memcpy(0xaf028000, 0xb16dd000, 4096)
08-26 19:02:58.401   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.401   318  7133 V AudioCache: memcpy(0xaf029000, 0xb16dd000, 4096)
08-26 19:02:58.401   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.401   318  7133 V AudioCache: memcpy(0xaf02a000, 0xb16dd000, 4096)
08-26 19:02:58.402   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.402   318  7133 V AudioCache: mem,cpy(0xaf02b000, 0xb16dd000, 4096)
08-26 19:02:58.402   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.402   318  7133 V AudioCache: memcpy(0xaf02c000, 0xb16dd000, 4096)
08-26 19:02:58.403   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.403   318  7133 V AudioCache: memcpy(0xaf02d000, 0xb16dd000, 4096)
08-26 19:02:58.403   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.403   318  7133 V AudioCache: memcpy(0xaf02e000, 0xb16dd000, 4096)
08-26 19:02:58.403   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.403   318  7133 V AudioCache: memcpy(0xaf02f000, 0xb16dd000, 4096)
08-26 19:02:58.404   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.404   318  7133 V AudioCache: memcpy(0xaf030000, 0xb16dd000, 4096)
08-26 19:02:58.404   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.404   318  7133 V AudioCache: memcpy(0xaf031000, 0xb16dd000, 4096)
08-26 19:02:58.405   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.405   318  7133 V AudioCache: memcpy(0xaf032000, 0xb16dd000, 4096)
08-26 19:02:58.405   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.405   318  7133 V AudioCache: memcpy(0xaf033000, 0xb16dd000, 4096)
,08-26 19:02:58.405   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.406   318  7133 V AudioCache: memcpy(0xaf034000, 0xb16dd000, 4096)
,08-26 19:02:58.406   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.406   318  7133 V AudioCache: memcpy(0xaf035000, 0xb16dd000, 4096)
08-26 19:02:58.406   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.406   318  7133 V AudioCache: memcpy(0xaf036000, 0xb16dd000, 4096)
08-26 19:02:58.407   318  7133 V AudioCache: write(0xb16dd000, 4096)
08-26 19:02:58.407   318  7133 V AudioCache: memcpy(0xaf037000, 0xb16dd000, 4096)
08-26 19:02:58.407   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-26 19:02:58.407   318  7133 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 19:02:58.407   318  7133 V AwesomePlayer: postAudioEOS() 
08-26 19:02:58.407   318  7133 V AudioCache: write(0xb16dd000, 280)
08-26 19:02:58.407   318  7133 V AudioCache: memcpy(0xaf038000, 0xb16dd000, 280)
08-26 19:02:58.415   318  7130 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 19:02:58.415   318  7130 V AwesomePlayer: onStreamDone
08-26 19:02:58.415   318  7130 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 19:02:58.415   318  7130 V AudioCache: notify(0xb54744c0, 2, 0, 0)
08-26 19:02:58.415   318  7130 V AudioCache: playback complete
08-26 19:02:58.415   318  7130 V AwesomePlayer: pause_l() 
08-26 19:02:58.415   318  7130 V AudioCache: notify(0xb54744c0, 7, 0, 0)
08-26 19:02:58.415   318  7130 V AudioCache: ignored
08-26 19:02:58.415   318  7130 V AwesomePlayer: cancelPlayerEvents
08-26 19:02:58.415   318  1394 V AudioCache: wait - success
08-26 19:02:58.415   318  1394 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 19:02:58.415   318  7130 D AudioPlayer: Pause Playback at 1068125
08-26 19:02:58.415   318  1394 V AwesomePlayer: reset_l() 
08-26 19:02:58.415   318  1394 V AudioCache: notify(0xb54744c0, 8, 0, 0)
08-26 19:02:58.415   318  1394 V AudioCache: ignored
08-26 19:02:58.415   318  1394 V AwesomePlayer: cancelPlayerEvents
08-26 19:02:58.416   318  1394 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-26 19:02:58.416   318  1394 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 19:02:58.416   318  1394 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 19:02:58.416   318  1394 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 19:02:58.416   318  1394 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434240 on port 1
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
08-26 19:02:58.416   31,8  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 1
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-26 19:02:58.416   318  1394 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 19:02:58.416   318  1394 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 19:02:58.416   318  7132 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 19:02:58.416   318  1394 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 19:02:58.416   318  1394 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 19:02:58.416   318  1394 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 19:02:58.417   318  1394 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-26 19:02:58.417   318  1394 D AudioPlayer: AudioPlayer releasing audio source
08-26 19:02:58.417   318  1394 D AudioPlayer: AudioPlayer done releasing audio source
08-26 19:02:58.417   318  1394 V AwesomePlayer: reset_l() 
08-26 19:02:58.417   318  1394 V AwesomePlayer: cancelPlayerEvents
08-26 19:02:58.417   318  1394 V AwesomePlayer: ~AwesomePlayer call
08-26 19:02:58.418   318  1394 V AwesomePlayer: reset_l() 
08-26 19:02:58.418   318  1394 V AwesomePlayer: cancelPlayerEvents
08-26 19:02:58.418  7022  7129 V SoundPool: close(31)
08-26 19:02:58.418  7022  7129 V SoundPool: pointer = 0xa001b000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 19:02:58.423  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 19:02:58.423  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-26 19:02:58.429  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5235
08-26 19:02:58.440  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:02:58.445  7093  7093 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:02:58.445  7093  7093 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:02:58.446  7093  7093 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:02:58.448  7093  7093 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:58.448  7093  7093 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 19:02:58.453  7039  7039 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-26 19:02:58.658  6879  6879 I UEI.SmartControl: Supports setup maps: true
,08-26 19:02:58.660  6879  6879 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 19:02:58.660  6879  6879 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 19:02:58.660  6879  6879 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 19:02:58.660  6879  6879 I UEI.SmartControl: ### init IR Blaster...
08-26 19:02:58.663  6879  6879 D serial_port: Configuring serial port
08-26 19:02:58.663  6879  6879 E UEI.SmartControl: UEIBLaster setting for 616
08-26 19:02:58.663  6879  6879 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 19:02:58.663  6879  6879 I UEI.SmartControl: configuring settings for MAXQ616
08-26 19:02:58.663  6879  6879 I UEI.SmartControl: Get version...
08-26 19:02:58.682  6879  7137 D UEI.SmartControl: serial port data available: 21
,08-26 19:02:58.709  6879  6879 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 19:02:58.709  6879  6879 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-26 19:02:58.709  6879  6879 I UEI.SmartControl: QS saving settings...
,08-26 19:02:58.711  6879  6879 D UEI.SmartControl: IR Blaster version: 25672567
08-26 19:02:58.728  6879  7137 D UEI.SmartControl: serial port data available: 4
,08-26 19:02:58.759  6879  6879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 19:02:58.767  6879  7146 I UEI.SmartControl: Device manager: loading config....
08-26 19:02:58.767  6879  7146 D UEI.SmartControl: ----------- loading internal config...
08-26 19:02:58.770  6879  6879 E UEI.SmartControl: Services init done
08-26 19:02:58.770  6879  6879 D UEI.SmartControl: QS Service init finished
08-26 19:02:58.771  6879  6879 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 19:02:58.772  6879  6879 D UEI.SmartControl: QS Service version code: 201091
08-26 19:02:58.772  6879  6879 D UEI.SmartControl: Service requested: Control
08-26 19:02:58.775  6879  7146 E UEI.SmartControl: Loading SETTINGS...
08-26 19:02:58.777  6879  6879 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-26 19:02:58.780  6879  6879 D UEI.SmartControl: Internal service binding...
,08-26 19:02:58.782  7022  7022 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 19:02:58.783  6879  6895 I UEI.SmartControl: ------ IControl API: 11
08-26 19:02:58.783  6879  6895 D UEI.SmartControl: File observer start...
08-26 19:02:58.784  6879  7146 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 19:02:58.784  6879  6895 E UEI.SmartControl: IR Port is disabled: false
08-26 19:02:58.784  6879  6895 D UEI.SmartControl: Starting file observer...
08-26 19:02:58.786  6879  6895 I UEI.SmartControl: Registering callback...
,08-26 19:02:58.786  6879  6894 I UEI.SmartControl: ------ IControl API: 19
08-26 19:02:58.787  6879  6894 I UEI.SmartControl: Registering Services Ready callback...
08-26 19:02:58.809  6879  7145 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 19:02:58.810  6879  7145 D UEI.SmartControl: -----service ready thread exits
08-26 19:02:58.810  7022  7038 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 19:02:58.811  7022  7127 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 19:02:58.811  7022  7127 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 19:02:58.812  7022  7022 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 19:02:58.813  7022  7022 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,08-26 19:02:58.814  6879  6895 I UEI.SmartControl: ------ IControl API: 8
08-26 19:02:58.819  7022  7022 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 19:02:58.820  7022  7022 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 19:02:58.821  7022  7022 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 19:02:58.822  7022  7022 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-26 19:02:58.823  7022  7022 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 19:02:58.824  7022  7022 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-26 19:02:58.828  7022  7022 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-26 19:02:58.831  7022  7022 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 19:02:58.832  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 19:02:58.833  7022  7022 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 19:02:58.834  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 19:02:58.835  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 19:02:58.837  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-26 19:02:58.838  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-26 19:02:58.840  7022  7022 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472230978839]
,08-26 19:02:58.848  7022  7022 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-26 19:02:58.851  1034  1933 I ActivityManager: Killing 6650:com.android.gallery3d/u0a27 (adj 15): empty #17
08-26 19:02:58.870  7022  7148 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-26 19:02:59.013  1034  1933 I ActivityManager: Killing 6619:com.lge.email/u0a23 (adj 15): empty #18
,08-26 19:02:59.110  1034  1942 W libprocessgroup: failed to open /acct/uid_10027/pid_6650/cgroup.procs: No such file or directory
,08-26 19:02:59.119  1034  2013 W libprocessgroup: failed to open /acct/uid_10023/pid_6619/cgroup.procs: No such file or directory
08-26 19:02:59.136  7022  7022 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-26 19:02:59.138  7022  7022 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-26 19:02:59.139  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-26 19:02:59.140  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-26 19:02:59.140  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-26 19:02:59.141  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-26 19:02:59.142  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-26 19:02:59.160  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-26 19:02:59.447  2130  2130 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19973
,08-26 19:02:59.539  1034  1379 V AlarmManager: ELAPSED_WAKEUP set : Alarm{22185183 type 2 when 122855 com.google.android.gms} when 122855
,08-26 19:02:59.723  1034  1734 D WifiServiceImplEx: setWifiEnabled: true pid=6749, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-26 19:02:59.732  1034  1734 D WifiService: setWifiEnabled: true pid=6749, uid=10118
08-26 19:02:59.732  1034  1734 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 19:02:59.755  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-26 19:02:59.755  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-26 19:02:59.755  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-26 19:02:59.757  1034  1466 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-26 19:02:59.757  1034  1466 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-26 19:02:59.759  1034  1466 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-26 19:02:59.760  1034  1466 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-26 19:02:59.760  1034  1466 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin],
08-26 19:02:59.760  1034  1466 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 19:02:59.760  1034  1466 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 19:02:59.760  1034  1466 E WifiHW  : unknown target_country: EU , set to default
08-26 19:02:59.760  1034  1466 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 19:02:59.760  1034  1466 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 19:02:59.760  1034  1466 I WifiUtil: gEnableBmps=1
08-26 19:02:59.865  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:02:59.889  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-26 19:02:59.895  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:59.902  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:59.911  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:02:59.915  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-26 19:02:59.920  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 19:02:59.924  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:59.928  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:59.930  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 19:02:59.933  6509  6536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 19:02:59.949  5844  5844 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 19:02:59.957  5844  5844 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 19:02:59.986  2188  2188 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:03:00.037  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:00.040  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 19:03:00.040  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 19:03:00.040  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-26 19:03:00.041  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
08-26 19:03:00.044  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 19:03:00.044  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-26 19:03:00.045  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-26 19:03:00.046  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 19:03:00.062  1034  1896 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7186 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-26 19:03:00.065  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 19:03:00.065  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 19:03:00.137  7186  7186 I AppUp4:AppBoxCP: onCreate
,08-26 19:03:00.138  7186  7186 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-26 19:03:00.149  7186  7186 I AppUp4:DB:  setFingerPrint start
,08-26 19:03:00.150  7186  7186 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-26 19:03:00.159  7186  7186 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-26 19:03:00.159  7186  7186 I AppUp4:DB:  SDK version = 21
08-26 19:03:00.159  7186  7186 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-26 19:03:00.161  7186  7186 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-26 19:03:00.162  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 19:03:00.163  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:00.165  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 19:03:00.165  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 19:03:00.173  7186  7186 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 19:03:00.228  7186  7186 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:03:00.228  7186  7186 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:03:00.246  7186  7186 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@20b3913d
08-26 19:03:00.246  7186  7186 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 19:03:00.246  7186  7186 D AppUp4:CustFacade: isPhone : true
08-26 19:03:00.247  7186  7186 D AppUp4:CustModeStarterReceiver: begin check event
08-26 19:03:00.247  7186  7186 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-26 19:03:00.248  7186  7186 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-26 19:03:00.249  7186  7206 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-26 19:03:00.249  7186  7206 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-26 19:03:00.250  7186  7206 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-26 19:03:00.252  1034  2032 I ActivityManager: Killing 6713:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-26 19:03:00.309  1034  1933 W libprocessgroup: failed to open /acct/uid_10061/pid_6713/cgroup.procs: No such file or directory
,08-26 19:03:00.311  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:00.312  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:03:00.316  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:03:00.320  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:03:00.327  4795  7215 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 19:03:00.334  4795  7218 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:00.334  4795  7218 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 19:03:00.414  1034  1908 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7220 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-26 19:03:00.433   313   894 D SoftapController: Softap fwReload - Ok
,08-26 19:03:00.436  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:03:00.436  1034  1096 D Tethering: InitialState.processMessage what=4
08-26 19:03:00.435  1034  1466 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (669ms)
08-26 19:03:00.437  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:03:00.438   313   894 D CommandListener: Setting iface cfg
08-26 19:03:00.438   313   894 D CommandListener: Trying to bring down wlan0
08-26 19:03:00.438   313   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:03:00.441  1034  1466 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-26 19:03:00.444  7231  7231 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:00.444  7231  7231 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 19:03:00.475  7231  7231 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 19:03:00.515  7220  7220 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 19:03:00.516  7220  7220 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 19:03:00.518  7220  7220 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 19:03:00.518  7220  7220 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 19:03:00.520  7231  7231 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 19:03:00.521  7231  7231 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-26 19:03:00.541  1034  1466 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:03:00.541  1034  1466 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:03:00.541  1034  1466 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 19:03:00.542  1034  1466 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 19:03:00.542  1034  1466 D WifiMonitor: connecting to supplicant
08-26 19:03:00.544  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-26 19:03:00.545  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:00.546  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 19:03:00.547  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:00.548  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:00.614  7220  7220 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-26 19:03:00.632  7231  7231 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 19:03:00.642  7220  7220 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-26 19:03:00.686  7220  7220 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 19:03:00.726  7220  7220 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:03:00.726  7220  7220 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:03:00.741  7231  7231 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-26 19:03:00.750  7231  7231 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-26 19:03:00.750  7231  7231 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-26 19:03:00.752  1034  1466 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 19:03:00.752  1034  1466 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 19:03:00.753  1034  7247 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-26 19:03:00.753  1034  7247 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 19:03:00.753  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 19:03:00.753  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,08-26 19:03:00.753  1034  1466 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 19:03:00.753  1034  7247 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 19:03:00.753  1034  7247 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 19:03:00.753  1034  1466 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 19:03:00.754  1034  1466 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:00.754  1034  1466 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:00.755  1034  1466 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-26 19:03:00.755  1034  1466 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:00.756  1034  1466 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 19:03:00.756  1034  1466 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 19:03:00.756  1034  1466 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 19:03:00.756  1034  1466 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 19:03:00.756  1034  1466 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-26 19:03:00.757  1034  1466 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:03:00.757  1034  1466 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:03:00.757  1034  1466 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 19:03:00.757  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:00.757  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:00.758  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:00.758  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:00.758  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:03:00.759  1034  1466 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 19:03:00.759  1034  1466 D WifiNative-wlan0: SET update_config 1: returned true
08-26 19:03:00.759  1034  1466 D WifiConfigStore: Loading config and enabling all networks 
08-26 19:03:00.759  1034  1466 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 19:03:00.760  1034  1466 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 19:03:00.761  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:00.763  1943  1943 D WfdService: Waiting for WifiP2p enabling
08-26 19:03:00.767  1034  1466 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-26 19:03:00.767  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:00.768  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:00.768  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:00.768  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:00.768  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:00.768  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:00.768  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:00.768  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:00.768  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:00.768  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:00.768  6749  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:00.770  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:00.770  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:00.770  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:00.770  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:00.770  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:00.770  6749  6749 V io.jxcor,e.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:00.770  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:00.770  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:00.770  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:00.770  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:00.770  6749  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:00.775  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 19:03:00.775  1034  1531 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 19:03:00.777  1034  1466 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 19:03:00.778  1034  1466 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 19:03:00.779  1034  1466 D WifiStateMachine: enableVerboseLogging : level 2
08-26 19:03:00.779  1034  1466 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 19:03:00.780  1034  1466 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 19:03:00.780  1034  1466 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 19:03:00.781  1034  1466 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 19:03:00.781  1034  1466 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 19:03:00.781  1034  1466 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 19:03:00.781  1034  1466 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 19:03:00.782  1034  1466 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 19:03:00.782  1034  1466 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 19:03:00.782  1034  1466 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 19:03:00.782  1034  1466 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 19:03:00.782  1034  1466 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 19:03:00.782  1034  1466 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 19:03:00.783  1034  1466 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-26 19:03:00.784  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-26 19:03:00.784  1943  2348 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 19:03:00.784  1943  2348 D WfdsService: Set the WFDS Monitor: true
08-26 19:03:00.784  1943  2348 D WfdsMonitor: WfdsMonitorThread create
08-26 19:03:00.785  1943  2348 D WfdsMonitor: WFDS Monitor is created and started
08-26 19:03:00.785  1943  2348 D WfdsService: WiFi: Supplicant connection re-established
08-26 19:03:00.785  1034  1466 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 19:03:00.785  1034  1466 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 19:03:00.786  1034  1466 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 19:03:00.786  1034  1466 D WifiNative-HAL: Setting external_sim to 1
08-26 19:03:00.786  1034  1466 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 19:03:00.786  1943  7248 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 19:03:00.786  1034  1466 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 19:03:00.786  1034  1466 I WifiNative-HAL: startHal
08-26 19:03:00.786  1034  1466 D wifi    : setting scan oui 0xaf6d1160
08-26 19:03:00.787  1943  7248 E CtrlSupplicant: Succeed to open control connection
08-26 19:03:00.787  1943  7248 E CtrlSupplicant: Succeed to open monitor connection
08-26 19:03:00.787  1034  1466 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 19:03:00.787  1034  1466 I WifiNative-HAL: startHal
08-26 19:03:00.787  1034  1466 D wifi    : setting scan oui 0xaf6d1160
08-26 19:03:00.787  1943  7248 D WfdsMonitor: Supplicant connection established
08-26 19:03:00.787  1034  1466 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 19:03:00.788  1943  2348 D WfdsService: Connected to the supplicant for wfds
08-26 19:03:00.788  1034  1466 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 19:03:00.788  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 19:03:00.788  7231  7231 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 19:03:00.789  1034  1466 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 19:03:00.789  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 19:03:00.789  7231  7231 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 19:03:00.789  1034  1466 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 19:03:00.789  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 19:03:00.789  7231  7231 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 19:03:00.790  1034  1466 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 19:03:00.790  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 19:03:00.790  7231  7231 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 19:03:00.791  1034  1466 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 19:03:00.791  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 19:03:00.791  7231  7231 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 19:03:00.791  1034  1466 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 19:03:00.791  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 19:03:00.791  7231  7231 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 19:03:00.792  1034  1466 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 19:03:00.792  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 19:03:00.792  7231  7231 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 19:03:00.792  1034  1466 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 19:03:00.793  1034  1466 E WifiNative: : [124,123,277 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 19:03:00.793  1034  1466 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 19:03:00.794  1034  1466 D W,ifiNative-wlan0: RECONNECT: returned true
08-26 19:03:00.794  1034  1466 D WifiNative-wlan0: doString: [STATUS]
08-26 19:03:00.794  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 19:03:00.794  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 19:03:00.795  1034  1466 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 19:03:00.795  1034  1466 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 19:03:00.796  1034  1466 D WifiNative-wlan0: SET ps 1: returned true
,08-26 19:03:00.796  1034  1419 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.797   313   894 D CommandListener: Setting iface cfg
08-26 19:03:00.798   313   894 D CommandListener: Trying to bring up p2p0
,08-26 19:03:00.798  1034  1419 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 19:03:00.798  1034  1419 D LGWifiP2pService: P2pEnablingState
08-26 19:03:00.798  1034  1419 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.798  1034  1419 D LGWifiP2pService: P2p socket connection successful
08-26 19:03:00.798  1034  1419 D LGWifiP2pService: P2pEnabledState
08-26 19:03:00.798  1034  1419 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 19:03:00.799  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 19:03:00.799  1943  1943 D WfdsService: WifiP2pState is changed : true
08-26 19:03:00.799  1034  1419 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 19:03:00.799  1943  2348 D WfdsService: Receive the WFDS_ENABLE Method
08-26 19:03:00.799  1943  2348 D WfdsService: Set the WFDS Monitor: true
08-26 19:03:00.799  1943  2348 D WfdsService: Connected to the supplicant for wfds
08-26 19:03:00.800  1943  2348 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 19:03:00.800  7231  7231 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 19:03:00.800  1034  1419 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 19:03:00.800  1034  1419 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 19:03:00.801  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 19:03:00.801  1943  1943 D WfdsService: isConnected: false
08-26 19:03:00.801  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 19:03:00.801  1034  1466 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 19:03:00.801  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-26 19:03:00.801  1034  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.801  1034  1557 I WifiNative-HAL: startHal
08-26 19:03:00.802  1034  1466 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 19:03:00.802  1034  1466 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 19:03:00.802  1034  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.803  1034  1466 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 19:03:00.803  1034  1466 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 19:03:00.803  1034  1466 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 19:03:00.804  1034  1466 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 19:03:00.804  1034  1466 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 19:03:00.804  1943  2348 D WfdsService: selectPreferredScanChannel [36]
08-26 19:03:00.804  7231  7231 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 19:03:00.804  1943  2348 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 19:03:00.804  1034  1419 D WifiNative-p2p0: SET device_name G3: returned true
08-26 19:03:00.804  1034  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf6d1160
08-26 19:03:00.804  1034  1557 D wifi    : failed to get capabilities : -3
08-26 19:03:00.805  1034  1557 E WifiScanningService: could not get scan capabilities
08-26 19:03:00.805  1034  1419 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 19:03:00.805  1034  1466 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 19:03:00.805  1034  1419 D LGWifiP2pService: before postfix = G3
08-26 19:03:00.805  1034  1419 D WifiServerServiceExt: postfix byte check : 2
08-26 19:03:00.805  1034  1419 D LGWifiP2pService: after postfix = G3
08-26 19:03:00.805  1034  1419 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 19:03:00.805  1034  1419 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 19:03:00.805  1034  1419 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 19:03:00.805  1034  1,466 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 19:03:00.805  1034  1419 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 19:03:00.805  1034  1419 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 19:03:00.806  1034  1466 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 19:03:00.806  1034  1466 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 19:03:00.806  7231  7231 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 19:03:00.806  1034  1419 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 19:03:00.806  1034  1419 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 19:03:00.806  1034  1419 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 19:03:00.806  1034  1419 D WifiNative-HAL: p2pGetDeviceAddress
08-26 19:03:00.807  1034  1419 D WifiNative-HAL: p2pGetDeviceAddress returning 
,08-26 19:03:00.808  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged,
08-26 19:03:00.808  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,08-26 19:03:00.808  1943  1943 D WfdsService: Update P2p Interface State: 3
08-26 19:03:00.808  1034  1419 D LGWifiP2pService: DeviceAddress: 
08-26 19:03:00.808  1034  1419 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 19:03:00.809  1034  1419 D WifiNative-p2p0: P2P_FLUSH: returned false
08-26 19:03:00.809  1034  1419 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 19:03:00.809  1034  1419 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 19:03:00.809  1034  1419 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 19:03:00.810  1034  1466 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
,08-26 19:03:00.810  1034  1466 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 19:03:00.811  1034  1466 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 19:03:00.811  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 19:03:00.811  1034  1419 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 19:03:00.811  1034  1419 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 19:03:00.811  7231  7231 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 19:03:00.812  7231  7231 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:03:00.812  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 19:03:00.812  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-26 19:03:00.812  1034  7247 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:03:00.812  1034  7247 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:03:00.812  7231  7231 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 19:03:00.813  7231  7231 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:00.813  1943  7248 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:00.813  1034  7247 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:00.813  1034  7247 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-26 19:03:00.813  1034  7247 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:00.813  1034  7247 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:00.813  1034  1466 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 19:03:00.813  7231  7231 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:00.813  1943  7248 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:00.813  1034  7247 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:00.813  1034  7247 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:00.813  1034  7247 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-26 19:03:00.813  1034  7247 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:00.814  1034  1466 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 19:03:00.814  1034  1466 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 19:03:00.815  1034  1466 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 19:03:00.815  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 19:03:00.815  7231  7231 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 19:03:00.815  7231  7231 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 19:03:00.816  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
,08-26 19:03:00.816  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 19:03:00.816  1034  7247 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 19:03:00.816  1034  7247 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 19:03:00.817  1034  1466 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 19:03:00.817  1034  1466 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 19:03:00.818  1034  1466 D WifiNative-wlan0: BSS_FLUSH 0: returned true
,08-26 19:03:00.818  1034  1466 D WifiNative-wlan0: doBoolean: SCAN
08-26 19:03:00.826  1034  1419 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 19:03:00.826  1034  1419 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 19:03:00.826  1034  1419 D LGWifiP2pService: InactiveState
08-26 19:03:00.827  1034  1466 D WifiNative-wlan0: SCAN: returned false
08-26 19:03:00.827  1034  1419 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.827  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.827  1034  1419 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-26 19:03:00.827  1034  1466 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=124158  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 19:03:00.827  7231  7231 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 19:03:00.828  7231  7231 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-26 19:03:00.828  1034  7247 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-26 19:03:00.828  1034  7247 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:03:00.828  1034  7247 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:03:00.828  1034  7247 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:03:00.828  7231  7231 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 19:03:00.828  1943  7248 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 19:03:00.828  7231  7231 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:00.829  7231  7231 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:00.829  1943  7248 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:00.829  1943  7248 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:00.829  1034  7247 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:00.829  1034  7247 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:00.830  1034  7247 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:00.830  1034  7247 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:00.830  1034  7247 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:00.830  1034  7247 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:00.830  1034  7247 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:00.830  1034  7247 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:00.830  1034  1419 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 19:03:00.830  1034  1419 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.830  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.830  1034  1419 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.830  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.830  1034  1419 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.830  1034  1419 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.830  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.830  1034  1419 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.831  1034  1419 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.831  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.831  1034  1419 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.831  1943  2348 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 19:03:00.831  1034  1419 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.831  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=4 t,arget=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.831  1034  1419 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.831  1034  1034 E WifiServerServiceExt: No p2p device connected
08-26 19:03:00.834  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:00.834  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:00.834  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 19:03:00.834  1034  1466 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=124165  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 19:03:00.835  1034  1466 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:03:00.835  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:00.835  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:00.835  1034  1466 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:03:00.836  1034  1466 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:03:00.836  1034  1466 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:03:00.836  1034  1466 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:03:00.837  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:03:00.837  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 19:03:00.838  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming,
08-26 19:03:00.877  7220  7220 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 19:03:00.923  7220  7220 I HubEmail: JNI_OnLoad()
08-26 19:03:00.923  7220  7220 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 19:03:00.923  7220  7220 I HubEmail: registerNatives()
08-26 19:03:00.923  7220  7220 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 19:03:00.923  7220  7220 I HubEmail: registerNativeMethods()
08-26 19:03:00.923  7220  7220 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 19:03:00.923  7220  7220 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-26 19:03:00.928  3201  3201 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 19:03:00.928  3201  3201 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:00.928  3201  3201 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 19:03:00.933  7064  7253 W FormManager: Network not available. Please check & try again.
08-26 19:03:01.000  1034  1969 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7256 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-26 19:03:01.007  7220  7255 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.008  7064  7254 V FormManager: Network unavailable.
08-26 19:03:01.011  7064  7254 V FormManager: Network unavailable.
08-26 19:03:01.017  1034  1600 I ActivityManager: Killing 6826:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-26 19:03:01.056  1034  2057 W libprocessgroup: failed to open /acct/uid_10080/pid_6826/cgroup.procs: No such file or directory
,08-26 19:03:01.120  7256  7256 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:03:01.120  7256  7256 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:03:01.123  7256  7256 D PhoneMonitor: Register our PhoneStateListener
,08-26 19:03:01.139  7256  7256 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-26 19:03:01.141  7256  7256 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 19:03:01.155  7256  7256 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-26 19:03:01.157  7256  7256 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-26 19:03:01.158  7256  7256 D TelephonyAutoProfiling: [parse] Load xml
,08-26 19:03:01.168  7256  7256 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-26 19:03:01.168  7256  7256 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-26 19:03:01.168  7256  7256 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-26 19:03:01.169  7256  7256 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-26 19:03:01.169  7256  7256 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-26 19:03:01.169  7256  7256 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-26 19:03:01.169  7256  7256 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-26 19:03:01.169  7256  7256 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-26 19:03:01.169  7256  7256 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-26 19:03:01.169  7256  7256 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
,08-26 19:03:01.169  7256  7256 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-26 19:03:01.169  7256  7256 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-26 19:03:01.169  7256  7256 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-26 19:03:01.169  7256  7256 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-26 19:03:01.170  7256  7256 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-26 19:03:01.170  7256  7256 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-26 19:03:01.170  7256  7256 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-26 19:03:01.174  7256  7256 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-26 19:03:01.212  1034  1978 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7275 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:03:01.214  1034  1978 I ActivityManager: Killing 6220:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-26 19:03:01.318  1034  1969 W libprocessgroup: failed to open /acct/uid_10097/pid_6220/cgroup.procs: No such file or directory
,08-26 19:03:01.381  7231  7231 E wpa_supplicant: USIM:  scard_init function
08-26 19:03:01.381  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-26 19:03:01.382  1034  7247 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 19:03:01.382  7231  7231 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 19:03:01.382  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 19:03:01.382  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-26 19:03:01.382  1034  7247 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 19:03:01.383  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 19:03:01.383  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-26 19:03:01.387  1034  1466 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 19:03:01.388  1034  1466 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 19:03:01.389  1034  1466 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 19:03:01.391  1034  1466 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 19:03:01.391  1034  1466 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 19:03:01.398  1034  1466 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=124728  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 19:03:01.401  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 19:03:01.401  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:01.406  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.406  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.406  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 19:03:01.407  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:01.415  1034  1466 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=124745  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 19:03:01.417  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.417  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.417  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 19:03:01.418  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:03:01.418  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-26 19:03:01.432  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:01.432  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 19:03:01.435  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:01.520  7231  7231 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 19:03:01.523  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 19:03:01.523  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 19:03:01.524  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 19:03:01.524  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 19:03:01.524  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:03:01.525  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:03:01.527  1034  1466 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=124857  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 19:03:01.529  1034  1466 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=124859  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 19:03:01.530  1034  1466 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124861
08-26 19:03:01.531  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:03:01.531  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:03:01.531  1034  1466 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124862
08-26 19:03:01.532  7231  7231 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 19:03:01.532  7231  7231 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 19:03:01.532  1034  1466 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124863
08-26 19:03:01.534  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124864
08-26 19:03:01.535  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 19:03:01.535  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 19:03:01.535  1034  7247 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 19:03:01.535  1034  1466 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=124865
08-26 19:03:01.536  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 19:03:01.536  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 19:03:01.536  1034  7247 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 19:03:01.536  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:03:01.536  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:03:01.536  1034  1466 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=124867  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-26 19:03:01.573  1034  1969 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7293 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-26 19:03:01.575  1034  1969 I ActivityManager: Killing 6845:com.lge.eula/1000 (adj 15): empty #17
08-26 19:03:01.616  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 19:03:01.619  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:01.619  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:01.619  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.619  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.619  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 19:03:01.620  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:01.624  1034  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_6845/cgroup.procs: No such file or directory
08-26 19:03:01.625  1034  1466 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=124955  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 19:03:01.628  1034  1466 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=124958  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-26 19:03:01.629  1034  1466 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=124959  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 19:03:01.629  1034  1466 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=124960
08-26 19:03:01.630  1034  1466 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=124960
08-26 19:03:01.630  1034  1466 D WifiNative-wlan0: doString: [STATUS]
08-26 19:03:01.631  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:03:01.631  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-26 19:03:01.631  1034  1466 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 19:03:01.633  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.633  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.633  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 19:03:01.633  1034  1466 I WifiServiceExtension: setVHTCapabilityType  : false
08-26 19:03:01.633  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:03:01.633  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 19:03:01.639  1034  1466 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 19:03:01.639  1034  1466 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-26 19:03:01.641  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:01.641  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:01.643  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:03:01.647  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.647  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.647  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 19:03:01.648  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 19:03:01.648  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:01.649  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:01.656  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.656  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:03:01.656  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-26 19:03:01.657  1034  1466 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 19:03:01.657  1034  1466 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:03:01.657  1034  1544 D ConnectivityService: Got NetworkAgent Messenger
08-26 19:03:01.657  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 19:03:01.657  1034  1544 D ConnectivityService: NetworkAgent connected
08-26 19:03:01.657  1034  1466 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 19:03:01.658  1034  1466 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 19:03:01.658  1034  1466 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 19:03:01.665  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:01.665  1034  1466 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 19:03:01.665  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:01.665  1034  1466 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:03:01.665  1034  1466 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 19:03:01.666  1034  1466 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 19:03:01.666  1034  1466 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 19:03:01.666  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:01.671  1034  1466 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-26 19:03:01.673   313   894 D CommandListener: Setting iface cfg
08-26 19:03:01.741  1034  1942 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7312 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:03:01.744  1034  1942 I ActivityManager: Killing 5685:com.lge.bnr/1000 (adj 15): empty #17
,08-26 19:03:01.803  1034  1466 E WifiStateMachine: Start Dhcp Watchdog 2
,08-26 19:03:01.803  1034  1978 W libprocessgroup: failed to open /acct/uid_1000/pid_5685/cgroup.procs: No such file or directory
08-26 19:03:01.803  1034  7311 D DhcpStateMachine: StoppedState
,08-26 19:03:01.803  1034  7311 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:01.803  1034  7311 D DhcpStateMachine: WaitBeforeStartState
08-26 19:03:01.803  1034  1466 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=125134  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:03:01.804  1034  1466 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=125134  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:03:01.804  1034  1466 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=125135  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-26 19:03:01.805  1034  1466 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:01.805  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:01.806  1034  1466 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:01.806  1034  1466 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:01.807  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:01.807  1034  1466 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:01.810  1034  1466 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=125141  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:03:01.811  1034  1466 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=125141  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:03:01.812  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:03:01.812  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 19:03:01.812  1034  1466 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=125142  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:03:01.813  1034  1466 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:77931] from screen [on:0 period:-942800715] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 19:03:01.814  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-942800714] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 19:03:01.814  1034  1466 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-26 19:03:01.819  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:01.819  1034  1544 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-26 19:03:01.820  1034  1466 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:01.820  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:01.821  1034  1466 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:01.821  1034  1466 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:01.822  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:01.822  1034  1466 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:01.822  1034  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 19:03:01.823  1034  1466 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=109,0,0
08-26 19:03:01.823  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=109,0,0
08-26 19:03:01.823  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 19:03:01.824  7231  7231 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 19:03:01.824  1034  1466 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 19:03:01.824  1034  1466 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 19:03:01.825  1034  1466 D WifiNative-wlan0: SET ps 0: returned true
08-26 19:03:01.825  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 19:03:01.825  7231  7231 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 19:03:01.825  1034  1466 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 19:03:01.825  1034  1466 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 19:03:01.826  1034  1466 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 19:03:01.826  1034  1419 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@311c60f9 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:01.826  1034  1466 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 19:03:01.826  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@311c60f9 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:01.826  1034  7311 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:03:01.826  1034  7311 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 19:03:01.827   313   894 D CommandListener: Setting iface cfg
08-26 19:03:01.827   313   894 D CommandListener: Trying to bring up wlan0
08-26 19:03:01.829  1034  1466 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 19:03:01.830  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-26 19:03:01.830  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 19:03:01.831  7312  7312 I art     : Almond Protected OAT
08-26 19:03:01.832  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:03:01.832  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 19:03:01.832  1034  1466 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:01.833  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:01.833  1034  1466 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:01.833  1034  1466 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:01.834  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:01.834  1034  1466 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:01.835  1034  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-26 19:03:01.835  1034  1466 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 19:03:01.836  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 19:03:01.836  1034  1419 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:01.836  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:01.836  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 19:03:01.836  7231  7231 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 19:03:01.837  1034  1466 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 19:03:01.837  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 19:03:01.837  7231  7231 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,08-26 19:03:01.837  1034  1466 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 19:03:01.837  1034  1466 D WifiNative-wlan0: doBoolean: SET ps 1
,08-26 19:03:01.843  1034  1419 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:01.843  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:01.843  1034  1419 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:01.854  1034  1466 D WifiNative-wlan0: SET ps 1: returned true
,08-26 19:03:01.854  1034  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 19:03:01.856  1034  1466 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 19:03:01.856  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 19:03:01.856  1034  1466 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 19:03:01.857  1034  1544 D ConnectivityService: ignoring duplicate network state non-change
08-26 19:03:01.860  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:01.860  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:01.862  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:01.866  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.866  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.866  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-26 19:03:01.869  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 19:03:01.869  1034  1544 D ConnectivityService: Adding iface wlan0 to network 101
08-26 19:03:01.874  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.875  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.875  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 19:03:01.877  1034  1466 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 19:03:01.878  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 19:03:01.881  7312  7312 D WeatherApplication: removeAccount
08-26 19:03:01.882  7312  7312 D WeatherApplication: Account.length = 0
08-26 19:03:01.883  7312  7312 E WeatherApplication: OPERATOR:OPEN
08-26 19:03:01.883  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 19:03:01.884  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:01.884  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 19:03:01.887  7312  7312 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:3:1
08-26 19:03:01.888  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:01.890  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.890  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.890  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 19:03:01.891  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 19:03:01.893  7312  7312 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 19:03:01.893  7312  7312 D Weather.Utils: 2 : All the weather widget is gone.
08-26 19:03:01.893  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:01.893  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 19:03:01.893  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:01.895  7312  7312 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 19:03:01.897  7312  7312 D WeatherAncestor: connectivity changed - connection : true
08-26 19:03:01.897  7312  7312 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-26 19:03:01.900  1034  1544 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 19:03:01.900  1034  1544 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-26 19:03:01.900  1034  1466 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 19:03:01.901  1034  1544 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-26 19:03:01.901  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 19:03:01.902  1034  1466 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 19:03:01.902   313   894 E Netd    : netlink response contains error (File exists)
08-26 19:03:01.902  1034  1466 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 19:03:01.903  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 19:03:01.903  1034  1544 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-26 19:03:01.903  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.903  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:01.903  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 19:03:01.903  1034  1544 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 19:03:01.903  1034  1544 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-26 19:03:01.903  1034  1544 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-26 19:03:01.904  1034  1466 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 19:03:01.904  1034  1544 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 19:03:01.904  1034  1544 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 19:03:01.904  1034  1544 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-26 19:03:01.904  1034  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 19:03:01.904  1034  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:03:01.904  1034  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:01.904  1034  7310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:01.904  1034  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 19:03:01.904  1034  7310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 19:03:01.904  1034  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:01.904  1034  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 19:03:01.904  1034  7310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:01.905  1034  1544 D ConnectivityService: currentScore = 0, newScore = 20
08-26 19:03:01.905  1034  1544 D ConnectivityService:    accepting network in place of null
,08-26 19:03:01.905  1034  1544 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:01.905  1034  7310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 19:03:01.906  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:01.906  1034  1544 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 19:03:01.906  1034  1544 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 19:03:01.906  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 19:03:01.906  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 19:03:01.907  1034  1466 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:01.907  1034  1466 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:03:01.908   313  7333 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 19:03:01.912  1034  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:01.912  1034  1544 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 19:03:01.912  1034  1544 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 19:03:01.912  1034  1544 D ConnectivityService: validation of new default Network = false
,08-26 19:03:01.913  1034  1544 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 19:03:01.913  1034  1544 D DSQN    : enableDataServiceNotify 
08-26 19:03:01.913  1034  1544 D DSQN    : start dsqn bin
08-26 19:03:01.913  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:01.913  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 19:03:01.914  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:01.914  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 19:03:01.914  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 19:03:01.914  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 19:03:01.914  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 19:03:01.917  1034  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 19:03:01.917  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:01.917  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:01.918  1034  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:01.914  7334  7334 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:01.919  1604  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 19:03:01.914  7334  7334 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:01.920  7312  7312 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 19:03:01.920  7312  7312 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 19:03:01.920  7312  7312 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-26 19:03:01.932  7334  7334 E DSQN    : DSQN ssw
08-26 19:03:01.938  7312  7312 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 19:03:01.938  7312  7312 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:3:1
,08-26 19:03:01.939  1034  1405 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-26 19:03:01.988  1034  1576 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7339 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 19:03:01.991  1818  7338 I CheckinService: active receiver: enabled
08-26 19:03:01.992  1034  1576 I ActivityManager: Killing 2130:com.lge.music/u0a34 (adj 15): empty #17
08-26 19:03:01.997   313  7333 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-26 19:03:02.004  1818  7338 I CheckinService: Preparing to send checkin request
08-26 19:03:02.004  1818  7338 I EventLogService: Accumulating logs since 1472230899870
08-26 19:03:02.009   318  2153 V AudioFlinger: 2130 died, releasing its sessions
08-26 19:03:02.009   318  2153 V AudioFlinger:  pid 1853 @ 0
08-26 19:03:02.009   318  2153 V AudioFlinger:  pid 3201 @ 1
08-26 19:03:02.009   318  2153 V AudioFlinger:  pid 3201 @ 2
08-26 19:03:02.028  1034  7311 D DhcpStateMachine: DHCPV4 request on wlan0
,08-26 19:03:02.030  1034  7311 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 19:03:02.030  1034  7311 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-26 19:03:02.030   313  7333 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-26 19:03:02.024  7357  7357 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:02.024  7357  7357 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:02.040  7357  7357 I dhcpcd  : version 5.5.6 starting
,08-26 19:03:02.042  7357  7357 E dhcpcd  : get_duid: m
08-26 19:03:02.042  7357  7357 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 19:03:02.042  7357  7357 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 19:03:02.046  1034  1600 W libprocessgroup: failed to open /acct/uid_10034/pid_2130/cgroup.procs: No such file or directory
08-26 19:03:02.054  1818  7338 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-26 19:03:02.060   313   893 D LGDataListener: argv[0]=dsqncommand
08-26 19:03:02.060   313   893 D LGDataListener: argv[1]=wlan0
08-26 19:03:02.060   313   893 D LGDataListener: argv[2]=1
08-26 19:03:02.060   313   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 19:03:02.060  1034  1094 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 19:03:02.060  1034  1094 D DSQN    : start to monitor internet connection
08-26 19:03:02.069  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 19:03:02.070  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:03:02.071  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:03:02.093  1034  7310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 17:03:02 GMT], X-Android-Received-Millis=[1472230982093], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472230982059]}
08-26 19:03:02.093  1034  7310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 19:03:02.093  1034  7310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 19:03:02.093  1034  1544 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-26 19:03:02.093  1034  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 19:03:02.093  1034  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:03:02.093  1034  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:02.093  1034  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 19:03:02.093  1034  1544 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-26 19:03:02.094  1034  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 19:03:02.094  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:02.094  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:02.094  1034  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:02.094  1034  1544 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:02.094  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 19:03:02.095  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:02.095  1604  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 19:03:02.095  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 19:03:02.096  1034  1466 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:02.096  1034  1466 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 19:03:02.113  7357  7357 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 19:03:02.113  7357  7357 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 19:03:02.113  7357  7357 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 19:03:02.113  7357  7357 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 19:03:02.113  7357  7357 D dhcpcd  : wlan0: sending REQUEST (xid 0x87602d01), next in 4.50 seconds
,08-26 19:03:02.117  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 19:03:02.118  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:02.118  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:02.159  7357  7357 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 19:03:02.160   278   351 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 19:03:02.160   278   351 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 19:03:02.160   278   351 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 19:03:02.160  7339  7367 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 19:03:02.162   278   351 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 19:03:02.162   278   351 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 19:03:02.162   278   351 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 19:03:02.162  7339  7367 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-26 19:03:02.170   278   351 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 19:03:02.170   278   351 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 19:03:02.170   278   351 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 19:03:02.170  7339  7369 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-26 19:03:02.174   278   351 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 19:03:02.174   278   351 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 19:03:02.174   278   351 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 19:03:02.176  7339  7369 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-26 19:03:02.207  7357  7357 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 19:03:02.207  7357  7357 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-26 19:03:02.207  7357  7357 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 19:03:02.207  7357  7357 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 19:03:02.208  7357  7357 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 19:03:02.208  7357  7357 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 19:03:02.208  7357  7357 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 19:03:02.208  7357  7357 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-26 19:03:02.224  1034  1907 I art     : Explicit concurrent mark sweep GC freed 107269(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/64MB, paused 1.502ms total 103.724ms
,08-26 19:03:02.287  1034  1933 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7383 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-26 19:03:02.343  7383  7383 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-26 19:03:02.343  7383  7383 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 19:03:02.369  7383  7383 I MultiDex: VM with version 2.1.0 has multidex support
08-26 19:03:02.369  7383  7383 I MultiDex: install
,08-26 19:03:02.370  7383  7383 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 19:03:02.378  7383  7383 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-26 19:03:02.388  7339  7339 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-26 19:03:02.404  7339  7339 I LibraryLoader: Loading: webviewchromium
,08-26 19:03:02.409  7339  7339 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 5748-5754)
,08-26 19:03:02.409  7339  7339 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 19:03:02.415  7339  7339 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2fc0cc5c}
08-26 19:03:02.417  7339  7339 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 19:03:02.417  7339  7339 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 19:03:02.429  7339  7339 I BrowserStartupController: Initializing chromium process, renderers=0
,08-26 19:03:02.430  7339  7339 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 19:03:02.433  1034  7311 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-26 19:03:02.433  1034  7311 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 19:03:02.434  1034  7311 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 19:03:02.434  1034  7311 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 19:03:02.434  1034  7311 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 19:03:02.434  1034  7311 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 19:03:02.434  1034  7311 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 19:03:02.434  1034  7311 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 19:03:02.434  1034  7311 D DhcpStateMachine: RunningState
08-26 19:03:02.447   318   318 V AudioPolicyService: registerClient() client 0xb57efc60, uid 10093
,08-26 19:03:02.448  7339  7429 W AudioManagerAndroid: Requires BLUETOOTH permission
08-26 19:03:02.449  7339  7339 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 19:03:02.451  7339  7339 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-26 19:03:02.451  7339  7339 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-26 19:03:02.464  7339  7339 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 19:03:02.464  7339  7339 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 19:03:02.464  7339  7339 I Adreno-EGL: Build Date: 12/12/14 금
08-26 19:03:02.464  7339  7339 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 19:03:02.464  7339  7339 I Adreno-EGL: Remote Branch: 
08-26 19:03:02.464  7339  7339 I Adreno-EGL: Local Patches: 
08-26 19:03:02.464  7339  7339 I Adreno-EGL: Reconstruct Branch: 
,08-26 19:03:02.522  7339  7339 I NSApplication: Starting up...
,08-26 19:03:02.575  1034  1050 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7442 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-26 19:03:02.577  1034  1050 I ActivityManager: Killing 6675:com.android.vending/u0a44 (adj 15): empty #17
,08-26 19:03:02.639  1034  1969 W libprocessgroup: failed to open /acct/uid_10044/pid_6675/cgroup.procs: No such file or directory
,08-26 19:03:02.671  7442  7442 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 19:03:02.728  7459  7459 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 19:03:02.764  1034  1576 D WifiServiceImplEx: setWifiEnabled: false pid=6749, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 19:03:02.764  1034  1576 D WifiService: setWifiEnabled: false pid=6749, uid=10118
08-26 19:03:02.764  1034  1576 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 19:03:02.784  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 19:03:02.784  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 19:03:02.784  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 19:03:02.784  1034  1466 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 19:03:02.785  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 19:03:02.786  1034  1466 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 19:03:02.787  1034  1466 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 19:03:02.787  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 19:03:02.788  1034  1466 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 19:03:02.788  1034  1466 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:03:02.788  1034  1466 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 19:03:02.788  1034  1466 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 19:03:02.788  1034  1466 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 19:03:02.796  7459  7459 I dex2oat : dex2oat took 67.932ms (threads: 4)
,08-26 19:03:02.803  1034  1466 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 19:03:02.803  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 19:03:02.803  7231  7231 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 19:03:02.803  1034  1419 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:02.803  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:02.804  1034  1466 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 19:03:02.804  1034  1466 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 19:03:02.804  1034  1466 D WifiNative-wlan0: SET ps 1: returned true
08-26 19:03:02.805  1034  7311 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:02.805   313   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:03:02.810  7383  7403 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 19:03:02.810  7383  7403 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 19:03:02.810  7383  7403 I Adreno-EGL: Build Date: 12/12/14 금
08-26 19:03:02.810  7383  7403 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 19:03:02.810  7383  7403 I Adreno-EGL: Remote Branch: 
08-26 19:03:02.810  7383  7403 I Adreno-EGL: Local Patches: 
08-26 19:03:02.810  7383  7403 I Adreno-EGL: Reconstruct Branch: 
,08-26 19:03:02.835  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 19:03:02.835  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-26 19:03:02.837  1034  1466 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:02.837  1034  1419 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:02.837  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:02.837  1034  1419 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@814c423
08-26 19:03:02.837  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:02.837  1034  1419 D LGWifiP2pService: P2pDisablingState
08-26 19:03:02.837  1034  1419 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:02.837  1034  1419 D LGWifiP2pService: p2p socket connection lost
08-26 19:03:02.837  1034  1419 D LGWifiP2pService: P2pDisabledState
08-26 19:03:02.838  1034  1466 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:02.838  1034  1466 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:02.839  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 19:03:02.839  1034  1466 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:02.839  1034  1466 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 19:03:02.840  1034  1466 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 19:03:02.840  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 19:03:02.840  1034  1419 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:02.840  1034  1419 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:02.840  7231  7231 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 19:03:02.841  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 19:03:02.845  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:02.845  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:02.845  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:03:02.846  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 19:03:02.847  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:02.847  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:02.847  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:02.848  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 19:03:02.849  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:02.849  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:02.849  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:03:02.849  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:02.849  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:02.849  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 19:03:02.849  1034  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:02.849  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:02.849  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-26 19:03:02.850  1034  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:02.851  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 19:03:02.851  1943  1943 D WfdsService: WifiP2pState is changed : false
08-26 19:03:02.855  1943  2348 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 19:03:02.855  1943  2348 D WfdsService: Set the WFDS Monitor: false
08-26 19:03:02.856  1034  1466 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 19:03:02.856  1034  1466 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 19:03:02.856  1943  2348 D WfdsMonitor: WFDS Monitor is stopped
08-26 19:03:02.856  1943  2348 D WfdsService: STATE : WfdsDisabledState - enter
,08-26 19:03:02.857  1943  7248 D CtrlSupplicant: Received on exit socket, terminate
08-26 19:03:02.857  1943  7248 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
,08-26 19:03:02.857  1943  7248 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 19:03:02.857  1943  7248 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 19:03:02.857  1034  1466 D WifiNative-wlan0: SET ps 1: returned true
08-26 19:03:02.858  1943  2350 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 19:03:02.859  1943  2348 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 19:03:02.897   313   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:03:02.897  1034  1544 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 19:03:02.897  1034  1544 D DSQN    : disableDataServiceNotify
08-26 19:03:02.897  1034  1544 D DSQN    : stop dsqn bin
,08-26 19:03:02.900  1034  1466 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 19:03:02.901  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-26 19:03:02.901  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:02.901  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 19:03:02.902  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:02.903  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:02.903  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:02.903  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:03:02.903  1034  1466 D WifiNative-p2p0: TERMINATE: returned true
08-26 19:03:02.903  1034  1466 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:03:02.903  1034  1466 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:03:02.903  1034  1466 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 19:03:02.906  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 19:03:02.906  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 19:03:02.906  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:03:02.906  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 19:03:02.907  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:02.907  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:02.907  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:02.907  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:02.907  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:02.907  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:02.907  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:02.907  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:02.907  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:03:02.908  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:02.908  6749  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:02.908  1034  1544 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-26 19:03:02.908  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:02.908  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:02.908  1034  1544 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:02.908  1034  1544 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 19:03:02.908  1034  7310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:03:02.908  1034  7310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:02.908  1034  7310 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 19:03:02.908  1034  1544 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 19:03:02.908  1034  1544 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 19:03:02.909  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 19:03:02.909  1034  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:02.909  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 19:03:02.910  1034  1405 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 19:03:02.910  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 19:03:02.911  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 19:03:02.911  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 19:03:02.911  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 19:03:02.912  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:02.912  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:02.912  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:02.912  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:02.912  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:02.912  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:02.912  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:02.912  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:02.912  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:03:02.912  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:02.913  6749  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:02.913  1604  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 19:03:02.914  1034  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:02.914  1034  1544 ,D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:02.914  1034  1544 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:02.914  1034  1544 D NetworkManagementService: Removing idletimer
08-26 19:03:02.914  1034  1544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:02.914  1034  1544 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 19:03:02.914  1034  1466 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:02.914  1034  1466 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:03:02.914  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:02.915  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 19:03:02.915  1034  1405 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 19:03:02.915  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 19:03:02.915  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 19:03:02.916  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 19:03:02.916  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 19:03:02.917  1034  1544 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-26 19:03:02.920  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:03:02.959  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 19:03:02.960  6509  6536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 19:03:02.972  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 19:03:02.972  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:02.973  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:02.974  2188  2188 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:02.984  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 19:03:02.984  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:02.984  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 19:03:02.984  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-26 19:03:02.988  7186  7186 I AppUp4:CustModeStarterReceiver: onReceive
08-26 19:03:02.989  7186  7186 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@20b3913d
08-26 19:03:02.989  7186  7186 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 19:03:02.989  7186  7186 D AppUp4:CustFacade: isPhone : true
08-26 19:03:02.990  7186  7186 D AppUp4:CustModeStarterReceiver: begin check event
08-26 19:03:02.991  7186  7186 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 19:03:02.992  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:02.993  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:03:02.994  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:03:02.995  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:03:03.002  7220  7220 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 19:03:03.004  4795  7478 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 19:03:03.004  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 19:03:03.006  4795  7479 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:03.006  4795  7479 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 19:03:03.006  7231  7231 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 19:03:03.006  7231  7231 I wpa_supplicant: monitor socket send errors count : 1
,08-26 19:03:03.006  7231  7231 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-4\x00 that cannot receive messages
08-26 19:03:03.006  1034  7247 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 19:03:03.006  1034  7247 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 19:03:03.007  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:03.008  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:03.017  3201  3201 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 19:03:03.017  3201  3201 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:03.017  3201  3201 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 19:03:03.019  7256  7256 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 19:03:03.019  7256  7256 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 19:03:03.022  1034  7311 D DhcpStateMachine: StoppedState
08-26 19:03:03.022  1034  7311 D DhcpStateMachine: StoppedState{ when=-165ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:03.023  7220  7480 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:03.024  1034  1466 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 19:03:03.024  1034  1466 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 19:03:03.028  7231  7231 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 19:03:03.028  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 19:03:03.028  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 19:03:03.028  1034  7247 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 19:03:03.028  1034  7247 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 19:03:03.029  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:03:03.029  7231  7231 W wpa_supplicant: USIM:  scard_deinit function
,08-26 19:03:03.029  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:03:03.029  1034  1096 D Tethering: InitialState.processMessage what=4
08-26 19:03:03.029  1034  1466 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=126360
08-26 19:03:03.030  1034  1466 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=126360
08-26 19:03:03.030  1034  1466 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=126360  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 19:03:03.030  1034  1466 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=126361  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 19:03:03.033  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:03:03.034  1034  1466 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:03.034  7064  7484 W FormManager: Network not available. Please check & try again.
08-26 19:03:03.034  1034  1466 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:03.038  7064  7485 V FormManager: Network unavailable.
08-26 19:03:03.038  7312  7312 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:3:3
08-26 19:03:03.041  7064  7485 V FormManager: Network unavailable.
08-26 19:03:03.041  7312  7312 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 19:03:03.041  7312  7312 D Weather.Utils: 2 : All the weather widget is gone.
08-26 19:03:03.041  7312  7312 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-26 19:03:03.041  7312  7312 D WeatherAncestor: connectivity changed - connection : true
08-26 19:03:03.041  7312  7312 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@257b5a83
08-26 19:03:03.042  7312  7312 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 19:03:03.042  7312  7312 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 19:03:03.042  7312  7312 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 19:03:03.042  7312  7312 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 19:03:03.042  7312  7312 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:3:3
08-26 19:03:03.061  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 19:03:03.061  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 19:03:03.061  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 19:03:03.061  6966  6966 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-26 19:03:03.063  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 19:03:03.063  6966  6966 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 19:03:03.063  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 19:03:03.063  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 19:03:03.063  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 19:03:03.063  6966  6966 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 19:03:03.063  6966  6966 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 19:03:03.069  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:03:03.077  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:03:03.080  7064  7491 W FormManager: Network not available. Please check & try again.
08-26 19:03:03.082  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:03.084  7064  7492 V FormManager: Network unavailable.
08-26 19:03:03.088  7064  7492 V FormManager: Network unavailable.
,08-26 19:03:03.100  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 19:03:03.103  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 19:03:03.104  7064  7494 W FormManager: Network not available. Please check & try again.
08-26 19:03:03.108  7064  7495 V FormManager: Network unavailable.
08-26 19:03:03.109  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:03.116  7064  7495 V FormManager: Network unavailable.
,08-26 19:03:03.120  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 19:03:03.120  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:03:03.122  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:03:03.123  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:03:03.128  4795  7496 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 19:03:03.128  4795  7497 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 19:03:03.128  4795  7497 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 19:03:03.154  1034  1933 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7498 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 19:03:03.156  7231  7231 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 19:03:03.161  1034  7247 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 19:03:03.161  1034  7247 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 19:03:03.161  1034  7247 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 19:03:03.162  1034  1466 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-26 19:03:03.163  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-26 19:03:03.163  1943  2348 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 19:03:03.163  1943  2348 D WfdsService: Set the WFDS Monitor: false
08-26 19:03:03.163  1034  1466 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 19:03:03.163  1943  2348 D WfdsMonitor: WFDS Monitor is stopped
08-26 19:03:03.163  1034  1466 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:03:03.163  1034  1466 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:03:03.163  1034  1466 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 19:03:03.165  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 19:03:03.166  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 19:03:03.166  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:03.166  1034  1531 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 19:03:03.166  1034  1531 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 19:03:03.167  2508  2508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:03:03.168  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:03.168  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:03.168  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:03.168  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:03.168  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:03.168  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:03.168  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:03.168  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:03.168  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:03.169   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 13.135ms
08-26 19:03:03.169  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:03.169  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:03.169  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:03.169  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:03.169  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:03.169  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:03.169  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:03.169  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:03.169  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:03.178   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 9.077ms
08-26 19:03:03.188   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 8.781ms
,08-26 19:03:03.210  7383  7403 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:03:03.210  7383  7403 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:03:03.226  7383  7403 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 19:03:03.226  7383  7403 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 19:03:03.226  7383  7403 I Adreno-EGL: Build Date: 12/12/14 금
08-26 19:03:03.226  7383  7403 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 19:03:03.226  7383  7403 I Adreno-EGL: Remote Branch: 
08-26 19:03:03.226  7383  7403 I Adreno-EGL: Local Patches: 
08-26 19:03:03.226  7383  7403 I Adreno-EGL: Reconstruct Branch: 
,08-26 19:03:03.247  7498  7498 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 19:03:03.248  7498  7498 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 19:03:03.253  7498  7498 V [BNRBootReceiver]: Boot Receiver Return
08-26 19:03:03.254  7498  7498 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 19:03:03.256  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:03:03.261  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:03.266  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:03.274  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:03.274  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:03:03.275  7022  7022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 19:03:03.277  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 19:03:03.279  6966  6966 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 19:03:03.282  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:03.288  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:03.295  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:03.301  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:03.302  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:03:03.305  7022  7022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 19:03:03.306  7383  7403 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 19:03:03.306  7383  7403 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 19:03:03.306  7383  7403 I Adreno-EGL: Build Date: 12/12/14 금
08-26 19:03:03.306  7383  7403 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 19:03:03.306  7383  7403 I Adreno-EGL: Remote Branch: 
08-26 19:03:03.306  7383  7403 I Adreno-EGL: Local Patches: 
08-26 19:03:03.306  7383  7403 I Adreno-EGL: Reconstruct Branch: 
08-26 19:03:03.308  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:03.314  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:03.319  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:03.325  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 19:03:03.326  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:03.326  7022  7022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 19:03:03.331  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:03:03.338  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:03.344  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:03.350  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:03.350  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:03.350  7022  7022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 19:03:03.354  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:03.362  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:03.368  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:03.374  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:03.374  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:03:03.375  7022  7022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:03:03.379  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:03:03.387  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:03.393  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 19:03:03.401  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:03.401  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:03.401  7022  7022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 19:03:03.406   313  7517 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 19:03:03.407  1034  1094 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 19:03:03.407  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:03.407  1818  7338 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-26 19:03:03.415  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:03.419  1818  7338 I CheckinService: active receiver: disabled
08-26 19:03:03.422  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 19:03:03.437  1034  1379 D PowerManagerServiceEx: acquireWakeLockInternal: lock=53567817, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,08-26 19:03:03.441  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:03.441  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:03.441  7022  7022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:03:03.453  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:03:03.465  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:03.472  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 19:03:03.481  2583  2583 D [Concierge]Service: onStartCommand(). Type : 9
,08-26 19:03:03.491  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:03.491  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:03:03.497  7022  7022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:03:03.507  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:03:03.523  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:03.534  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:03.542  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 19:03:03.542  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:03.544  7022  7022 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:03:03.549  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:03.553  6994  6994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 19:03:03.563  1034  1541 D WifiService: New client listening to asynchronous messages
08-26 19:03:03.564  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:03:03.569  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:03.579  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:03.587  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:03.588  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:03:03.590  7022  7022 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 19:03:03.593  7022  7022 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 19:03:03.594  7022  7022 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 19:03:03.602  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:03:03.611  6994  6994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 19:03:03.614  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 19:03:03.626  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:03.640  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:03.653  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:03.654  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:03:03.657  7022  7022 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 19:03:03.659  7022  7022 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 19:03:03.660  7022  7022 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 19:03:03.666  1034  1907 I ActivityManager: Killing 6945:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-26 19:03:03.727  1034  1969 W libprocessgroup: failed to open /acct/uid_10037/pid_6945/cgroup.procs: No such file or directory
,08-26 19:03:03.735  2188  2188 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-26 19:03:03.749  2188  2188 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-26 19:03:03.751  2188  2188 D c       : Getting all permits...
08-26 19:03:03.752  2188  2188 D a       : Opening database...
08-26 19:03:03.757  6879  7147 D UEI.SmartControl: Internal timer expired: 2
08-26 19:03:03.757  6879  7147 D UEI.SmartControl: unbind internal service
08-26 19:03:03.760  2188  2188 D a       : Opening database auth.proximity.permit_store...
08-26 19:03:03.762  2188  2188 D a       : Closing database...
08-26 19:03:03.777  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:03:03.782  6994  6994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-26 19:03:03.782  6994  6994 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 19:03:03.782  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:03:03.787  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:03.794  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:03.805  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:03.806  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:03:03.811  7022  7022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 19:03:03.817  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:03.823  6994  6994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 19:03:03.823  6994  6994 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-26 19:03:03.823  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 19:03:03.828  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 19:03:03.835  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:03.844  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 19:03:03.849  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:03.852  7022  7022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 19:03:03.857  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:03.868  6994  6994 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 19:03:03.868  6994  6994 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 19:03:03.868  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 19:03:03.873  6879  7141 D serial_port: close(fd = 24)
08-26 19:03:03.877  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 19:03:03.878  6879  7141 I UEI.SmartControl: Serial port is closed.
,08-26 19:03:03.884  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:03.892  7022  7022 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:03.893  7022  7022 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:03.895  7022  7022 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 19:03:03.903  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:03:03.909  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:03:03.915  7064  7526 W FormManager: Network not available. Please check & try again.
08-26 19:03:03.919  7064  7527 V FormManager: Network unavailable.
08-26 19:03:03.919  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:03.927  7064  7527 V FormManager: Network unavailable.
,08-26 19:03:03.944  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 19:03:03.945  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:03:03.950  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:03:03.954  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:03:03.963  4795  7528 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 19:03:03.970  4795  7529 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 19:03:03.971  4795  7529 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 19:03:03.978  6994  6994 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 19:03:03.978  6994  6994 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 19:03:03.978  6994  6994 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 19:03:03.983  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 19:03:03.987  7064  7531 W FormManager: Network not available. Please check & try again.
08-26 19:03:03.989  7064  7532 V FormManager: Network unavailable.
08-26 19:03:03.991  7064  7532 V FormManager: Network unavailable.
08-26 19:03:03.991  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 19:03:04.009  7022  7022 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-26 19:03:04.010  7022  7022 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5235
,08-26 19:03:04.010  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=53567817 [*alarm*], flags=0x0
,08-26 19:03:04.016  2188  2188 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-26 19:03:04.828  1034  1466 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-942797704] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 19:03:04.844  1034  1466 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:20] from screen [on:0 period:-942797684] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 19:03:04.914  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:03:04.929  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-26 19:03:04.934  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:04.938  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:04.943  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:04.946  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-26 19:03:04.950  6509  6536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 19:03:04.958  5844  5844 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 19:03:04.981  2188  2188 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:03:05.001  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 19:03:05.001  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:05.001  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 19:03:05.001  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-26 19:03:05.006  7186  7186 I AppUp4:CustModeStarterReceiver: onReceive
08-26 19:03:05.010  7186  7186 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@20b3913d
08-26 19:03:05.010  7186  7186 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 19:03:05.010  7186  7186 D AppUp4:CustFacade: isPhone : true
08-26 19:03:05.010  7186  7186 D AppUp4:CustModeStarterReceiver: begin check event
08-26 19:03:05.010  7186  7186 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 19:03:05.015  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:05.015  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:03:05.017  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 19:03:05.022  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:03:05.030  7220  7220 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 19:03:05.061  3201  3201 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 19:03:05.061  3201  3201 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:05.062  3201  3201 I LgeMiscReceiver: networkInfo.isConnected() = true
08-26 19:03:05.062  3201  3201 D PhoneState: setPdpRejectCasuse : false
,08-26 19:03:05.074  7256  7256 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 19:03:05.075  7256  7256 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 19:03:05.075  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 19:03:05.080  4795  7541 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 19:03:05.087  7220  7540 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:05.093  7064  7559 W FormManager: Network not available. Please check & try again.
,08-26 19:03:05.096  4795  7555 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:05.096  4795  7555 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 19:03:05.099  7312  7312 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:3:5
08-26 19:03:05.101  7312  7312 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 19:03:05.101  7312  7312 D Weather.Utils: 2 : All the weather widget is gone.
08-26 19:03:05.101  7312  7312 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 19:03:05.101  7312  7312 D WeatherAncestor: connectivity changed - connection : true
08-26 19:03:05.101  7312  7312 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@257b5a83
08-26 19:03:05.102  7312  7312 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 19:03:05.102  7312  7312 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 19:03:05.102  7312  7312 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 19:03:05.102  7312  7312 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 19:03:05.103  7312  7312 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:3:5
08-26 19:03:05.115  7064  7560 V FormManager: Network unavailable.
,08-26 19:03:05.121  7064  7560 V FormManager: Network unavailable.
,08-26 19:03:05.786  1034  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 19:03:05.787  1034  2013 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 19:03:05.819  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 19:03:05.819  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 19:03:05.819  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 19:03:05.820  1034  1096 D BluetoothManagerService: Message: 1
08-26 19:03:05.820  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-26 19:03:05.845  1034  1096 D BluetoothManagerService: Message: 20
08-26 19:03:05.845  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f48a5f:true
,08-26 19:03:05.849  7093  7093 D BluetoothAdapterState: make
08-26 19:03:05.854  7093  7093 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 19:03:05.854  7093  7093 I bluedroid-qcom: init
08-26 19:03:05.856  7093  7572 I BluetoothAdapterState: Entering OffState
08-26 19:03:05.856  7093  7093 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 19:03:05.856  7093  7093 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 19:03:05.856  7093  7093 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 19:03:05.856  7093  7093 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 19:03:05.857  7093  7093 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 19:03:05.858  7093  7093 I bluedroid-qcom: get_profile_interface socket
08-26 19:03:05.858  7093  7093 I bluedroid-qcom: get_profile_interface map_client
,08-26 19:03:05.862  7093  7576 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 19:03:05.866  7093  7576 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 19:03:05.864  7575  7575 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:05.864  7575  7575 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:05.878  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 19:03:05.878  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-26 19:03:05.881  1034  1096 D BluetoothManagerService: Message: 40
08-26 19:03:05.881  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 19:03:05.883  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 19:03:05.883  7093  7109 I bluedroid-qcom: config_hci_snoop_log
08-26 19:03:05.884  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 19:03:05.884  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 19:03:05.885  7575  7575 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 19:03:05.885  7575  7575 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 19:03:05.885  7575  7575 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-26 19:03:05.890  7575  7575 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-26 19:03:05.896  7093  7572 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 19:03:05.898  7093  7576 D BluetoothAdapterProperties: Name is: G3
08-26 19:03:05.898  7093  7572 D BluetoothAdapterProperties: Setting state to 11
08-26 19:03:05.899  7575  7575 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 19:03:05.899  7575  7575 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-26 19:03:05.900  7093  7572 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 19:03:05.901  1034  1096 D BluetoothManagerService: Message: 60
08-26 19:03:05.901  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 19:03:05.901  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 19:03:05.903  7093  7572 I LGBluetoothServiceJni: classInitNative: succeeds
,08-26 19:03:05.910  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:05.912  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 19:03:05.913  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:05.915  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:05.917  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:05.919  6966  6966 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-26 19:03:05.923  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:05.938  7093  7093 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 19:03:05.940  7093  7093 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:05.941  7093  7093 V BluetoothPbapReceiver: ***********state = 11
,08-26 19:03:05.949  1034  1096 D Tethering: MasterInitialState.processMessage what=3
08-26 19:03:05.953  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:05.957  1034  1096 D Tethering: MasterInitialState.processMessage what=3
,08-26 19:03:05.959  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:05.961  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:05.964  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:05.965  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:05.968  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 19:03:05.970  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:03:05.972  6509  6536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 19:03:05.974  1034  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:05.974  7093  7572 D BluetoothBondStateMachine: make
08-26 19:03:05.977  7093  7572 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:05.977  7093  7572 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 19:03:05.977  7093  7572 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:05.977  7093  7572 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 19:03:05.978  7093  7572 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 19:03:05.978  7093  7592 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 19:03:05.979  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:05.979  1034  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:05.981  5844  5844 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 19:03:05.981  7093  7572 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 19:03:06.028  1034  2032 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7594 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-26 19:03:06.035  7093  7572 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:03:06.036  5844  5844 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 19:03:06.037  7093  7093 D HeadsetService: Received start request. Starting profile...
08-26 19:03:06.038  7093  7093 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 19:03:06.038  7093  7093 D LGBluetoothHfpAdapter: Version 1.6
,08-26 19:03:06.042  7093  7093 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 19:03:06.043  7093  7093 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 19:03:06.043  7093  7093 D HeadsetStateMachine: make
08-26 19:03:06.044  7093  7572 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:03:06.050  7093  7572 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:03:06.059  7093  7572 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 19:03:06.066  7093  7572 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:03:06.072  2188  2188 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:03:06.075  7093  7572 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:03:06.078  7093  7093 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:03:06.078  7093  7093 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:03:06.091  7093  7093 D HeadsetStateMachine: max_hf_connections = 1
08-26 19:03:06.091  7093  7093 I bluedroid-qcom: get_profile_interface handsfree
08-26 19:03:06.092  7093  7572 V LGMDMManager: Create singleton instance
08-26 19:03:06.093  7093  7093 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 19:03:06.093  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 19:03:06.093  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:06.093   318  1394 V AudioPolicyService: registerClient() client 0xb558a420, uid 1002
08-26 19:03:06.094  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 19:03:06.094   318  2153 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 19:03:06.094   318  2153 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 19:03:06.094  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 19:03:06.094   318  2153 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 19:03:06.095  7093  7572 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 19:03:06.095  7093  7093 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 19:03:06.095   318   318 V AudioFlinger: registerClient() client 0xb55818b0, pid 7093
08-26 19:03:06.096  7186  7186 I AppUp4:CustModeStarterReceiver: onReceive
08-26 19:03:06.096   318  1388 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:03:06.096   318  1388 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:03:06.096  1034  1908 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:03:06.096  1034  1908 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:03:06.096  1604  2076 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:03:06.096  1604  2076 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:03:06.096  7093  7109 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:03:06.096  7093  7109 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 19:03:06.096  3201  3217 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:03:06.096  3201  3217 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:03:06.097   318  1389 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:03:06.097   318  1389 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:03:06.097  7093  7111 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:03:06.097  1034  1933 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:03:06.097  1034  1933 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:03:06.097  1853  1869 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:03:06.097  7093  7111 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 19:03:06.097  1853  1869 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:03:06.097  1604  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:03:06.097  1604  1624 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:03:06.097  1853  1869 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:03:06.097  1853  1869 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:03:06.097  3201  3216 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:03:06.097  3201  3216 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:03:06.097  7093  7093 V ToneGenerator: Create Track: 0xb4928a80
08-26 19:03:06.097  7093  7093 V AudioTrack: set(): streamType 8, sampleRate 0, format ,0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 19:03:06.097  7093  7093 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 19:03:06.098   318  1394 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 19:03:06.098   318  1394 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 19:03:06.098   318  1394 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 19:03:06.098   318  1394 V AudioPolicyManagerEx: getOutput() returns output 2
,08-26 19:03:06.101   318  2153 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 19:03:06.101   318   318 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 19:03:06.101   318   318 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 19:03:06.101   318   318 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 19:03:06.101   318   318 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 19:03:06.102  7093  7093 V AudioSystem: getLatency() output 2, latency 50
08-26 19:03:06.102  7093  7093 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 19:03:06.102  7093  7093 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 19:03:06.102   318  2152 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 19:03:06.102   318  2152 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
,08-26 19:03:06.102   318  2152 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 19:03:06.102   318  2152 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 19:03:06.102   318  2152 V AudioFlinger: createTrack() lSessionId: 22
08-26 19:03:06.103  7093  7093 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 19:03:06.104   318  2152 V AudioFlinger: acquiring 22 from 7093, for 7093
08-26 19:03:06.104   318  2152 V AudioFlinger:  added new entry for 22
08-26 19:03:06.106  7093  7093 V ToneGenerator: ToneGenerator INIT OK, time: 129451
08-26 19:03:06.106  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:06.107  7093  7605 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 19:03:06.107  7093  7605 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 19:03:06.107  7093  7605 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 19:03:06.107  7093  7605 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 19:03:06.108   318  1393 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7093
08-26 19:03:06.108   318  1393 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 19:03:06.108   318  1393 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 19:03:06.108   318  1393 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 19:03:06.108   318  1393 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 19:03:06.108   318  1393 V voice   : voice_set_parameters: exit with code(0)
08-26 19:03:06.108   318  1393 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 19:03:06.108   318  1393 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 19:03:06.108  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:06.108   318  1393 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 19:03:06.108   318  1393 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 19:03:06.108   318  1393 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 19:03:06.108   318  1393 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 19:03:06.109  7093  7605 V ToneGenerator: ToneGenerator destructor
08-26 19:03:06.109  7093  7605 V ToneGenerator: stopTone
08-26 19:03:06.109  7093  7605 V ToneGenerator: Delete Track: 0xb4928a80
08-26 19:03:06.109  7186  7186 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@20b3913d
08-26 19:03:06.109  7186  7186 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 19:03:06.109  7186  7186 D AppUp4:CustFacade: isPhone : true
08-26 19:03:06.110  7186  7186 D AppUp4:CustModeStarterReceiver: begin check event
08-26 19:03:06.110  7093  7093 D A2dpService: Received start request. Starting profile...
08-26 19:03:06.110  7186  7186 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-26 19:03:06.110  7093  7093 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 19:03:06.111  7093  7093 V Avrcp   : make
08-26 19:03:06.112  7093  7093 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 19:03:06.112  7093  7093 I bluedroid-qcom: get_profile_interface avrcp
08-26 19:03:06.113  7093  7605 V AudioTrack: ~AudioTrack, releasing session id from 7093 on behalf of 7093
08-26 19:03:06.113   318  1394 V AudioFlinger: releasing 22 from 7093 for 7093
08-26 19:03:06.113   318  1394 V AudioFlinger:  decremented refcount to 0
08-26 19:03:06.113   318  1394 V AudioFlinger: purging stale effects
08-26 19:03:06.113   318  1394 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 19:03:06.113   318  1394 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 19:03:06.113   318  1256 V AudioPolicyService: AudioCommandThread() waking up
08-26 19:03:06.113   318  1256 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 19:03:06.113   318  1256 V AudioPolicyManager: releaseOutput() 2
08-26 19:03:06.113   318  1256 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 19:03:06.113   318  1394 V AudioFlinger: PlaybackThread::Track destructor
08-26 19:03:06.113   318  1394 V AudioFlinger: removeClient_l() pid 7093, calling pid 318
08-26 19:03:06.113  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:06.114  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:03:06.115  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:03:06.117  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:03:06.121  7093  7093 V AudioManager: registerRemoteController: size of Media player list: 0
,08-26 19:03:06.123  7093  7093 E AudioManager: No RCC entry present to update
08-26 19:03:06.123  7093  7093 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 19:03:06.124  7220  7220 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 19:03:06.126  7093  7093 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 19:03:06.127  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 19:03:06.127  7093  7093 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 19:03:06.127  4795  7616 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 19:03:06.133  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-26 19:03:06.137  4795  7617 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:06.138  4795  7617 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 19:03:06.190  7594  7594 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 19:03:06.190  7220  7619 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:06.190  7594  7594 W LG Account v2.2: No ProfileInfo entries
08-26 19:03:06.191  7594  7594 I LG Account v2.2: isEnabled: false
08-26 19:03:06.191  7594  7594 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 19:03:06.191  7594  7594 I Feature : [Lifetracker]Country: EU
08-26 19:03:06.191  7594  7594 I Feature : [Lifetracker]Operator: OPEN
08-26 19:03:06.192  7594  7594 I Feature : [Lifetracker]Ranking support: false
08-26 19:03:06.192  7594  7594 I Feature : [Lifetracker]Comfort support: false
08-26 19:03:06.192  7594  7594 I Feature : [Lifetracker]Accessory: true
08-26 19:03:06.192  7594  7594 I Feature : [Lifetracker]Health device: true
08-26 19:03:06.192  7594  7594 I Feature : [Lifetracker]Extra Pedometer: false
08-26 19:03:06.193  7594  7594 I Feature : [Lifetracker]Blood glucose device: false
08-26 19:03:06.193  7594  7594 I Feature : [Lifetracker]Device Number: 3
,08-26 19:03:06.200  7064  7621 W FormManager: Network not available. Please check & try again.
08-26 19:03:06.207  3201  3201 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 19:03:06.207  3201  3201 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:06.207  3201  3201 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 19:03:06.214  7064  7622 V FormManager: Network unavailable.
08-26 19:03:06.216  7256  7256 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 19:03:06.217  6966  6966 D BluetoothPermissionRequest: onReceive
08-26 19:03:06.217  7256  7256 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 19:03:06.232  7064  7622 V FormManager: Network unavailable.
08-26 19:03:06.234  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 19:03:06.239  1034  1734 V SIM_STK : Menu title from STK is T-Mobile
,08-26 19:03:06.239  1034  1734 V SIM_STK : Menu title from STK is T-Mobile
08-26 19:03:06.251  7312  7312 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:3:6
,08-26 19:03:06.253  7312  7312 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 19:03:06.253  7312  7312 D Weather.Utils: 2 : All the weather widget is gone.
08-26 19:03:06.254  7312  7312 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 19:03:06.255  7312  7312 D WeatherAncestor: connectivity changed - connection : true
08-26 19:03:06.255  7312  7312 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@257b5a83
08-26 19:03:06.257  7312  7312 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 19:03:06.257  7312  7312 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 19:03:06.257  7312  7312 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 19:03:06.257  7312  7312 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 19:03:06.257  7312  7312 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:3:6
08-26 19:03:06.289  6509  6509 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-26 19:03:06.292  6509  6536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 19:03:06.299  1034  1933 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 19:03:06.305  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-26 19:03:06.310  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-26 19:03:06.310  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 19:03:06.310  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 19:03:06.311  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 19:03:06.311  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 19:03:06.311  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 19:03:06.311  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 19:03:06.311  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 19:03:06.311  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 19:03:06.311  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 19:03:06.311  7093  7093 I BluetoothA2dpServiceJni: classInitNative
08-26 19:03:06.312  7093  7093 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 19:03:06.312  7093  7093 D A2dpStateMachine: make
08-26 19:03:06.313  2188  2188 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:06.313  7093  7093 I bluedroid-qcom: get_profile_interface a2dp
08-26 19:03:06.313  7093  7627 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 19:03:06.316  7093  7093 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 19:03:06.316  7093  7093 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 19:03:06.317  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:06.318  7093  7093 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 19:03:06.320  7093  7093 D HidService: Received start request. Starting profile...
08-26 19:03:06.320  7093  7093 I bluedroid-qcom: get_profile_interface hidhost
08-26 19:03:06.320  7093  7626 D A2dpStateMachine: Enter Disconnected: -2
08-26 19:03:06.320  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:06.320  7093  7093 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 19:03:06.322  7093  7093 D HealthService: Received start request. Starting profile...
08-26 19:03:06.323  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 19:03:06.323  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:06.323  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 19:03:06.323  7186  7186 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 19:03:06.324  7186  7186 I AppUp4:CustModeStarterReceiver: onReceive
08-26 19:03:06.324  7093  7093 I bluedroid-qcom: get_profile_interface health
08-26 19:03:06.325  7093  7093 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 19:03:06.325  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:06.326  7093  7093 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 19:03:06.327  7186  7186 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@20b3913d
08-26 19:03:06.327  7186  7186 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 19:03:06.327  7186  7186 D AppUp4:CustFacade: isPhone : true
08-26 19:03:06.327  7186  7186 D AppUp4:CustModeStarterReceiver: begin check event
08-26 19:03:06.327  7093  7093 D PanService: Received start request. Starting profile...
08-26 19:03:06.327  7093  7093 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 19:03:06.327  7093  7093 I bluedroid-qcom: get_profile_interface pan
08-26 19:03:06.327  7186  7186 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 19:03:06.333  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:06.333  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:03:06.334  7093  7093 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 19:03:06.334  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:06.335  7093  7093 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-26 19:03:06.336  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:03:06.339  7093  7093 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 19:03:06.340  7093  7093 D BtGatt.GattService: Received start request. Starting profile...
08-26 19:03:06.340  7093  7093 D BtGatt.GattService: start()
08-26 19:03:06.340  7093  7093 I bluedroid-qcom: get_profile_interface gatt
08-26 19:03:06.340  7093  7093 D BtGatt.AdvertiseManager: advertise manager created
08-26 19:03:06.340  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:03:06.348  7220  7220 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 19:03:06.348  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
,08-26 19:03:06.350  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:06.351  7093  7093 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 19:03:06.352  7093  7093 V BluetoothMapService: BluetoothMapBinder()
08-26 19:03:06.352  4795  7633 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 19:03:06.352  7093  7093 D BluetoothMapService: Received start request. Starting profile...
08-26 19:03:06.352  7093  7093 D BluetoothMapService: start()
08-26 19:03:06.353  4795  7635 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:06.354  4795  7635 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 19:03:06.355  7093  7093 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 19:03:06.355  7093  7093 D BluetoothMapEmailAppObserver: createReceiver()
08-26 19:03:06.360  7093  7093 D BluetoothMapEmailAppObserver: initObservers()
08-26 19:03:06.360  7093  7093 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-26 19:03:06.367  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:06.368  7093  7093 D HeadsetStateMachine: Proxy object connected
08-26 19:03:06.368  7220  7636 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:06.369  7093  7093 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 19:03:06.369  7093  7093 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-26 19:03:06.373  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:03:06.373  7093  7605 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 19:03:06.373  7093  7605 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 19:03:06.374  7093  7605 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-26 19:03:06.376  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:03:06.379  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:03:06.381  7064  7638 W FormManager: Network not available. Please check & try again.
08-26 19:03:06.382  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:03:06.385  3201  3201 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 19:03:06.385  3201  3201 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:06.386  3201  3201 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 19:03:06.386  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:03:06.386  7093  7093 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 19:03:06.389  7093  7093 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 19:03:06.390  7064  7639 V FormManager: Network unavailable.
08-26 19:03:06.390  7093  7093 V BluetoothMapService: Handler(): got msg=1
08-26 19:03:06.391  7093  7572 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 19:03:06.391  7093  7572 I bluedroid-qcom: enable
08-26 19:03:06.391  7093  7572 I bt_hci_bdroid: init
08-26 19:03:06.392  7256  7256 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 19:03:06.393  7093  7572 I bt_vendor: bt-vendor : init
08-26 19:03:06.393  7093  7572 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 19:03:06.393  7256  7256 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 19:03:06.393  7093  7572 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 19:03:06.393  7093  7572 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 19:03:06.393  7093  7572 D bt_userial_mct: userial_init
08-26 19:03:06.393  7093  7641 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 19:03:06.393  7093  7572 D bt_hci_bdroid: set_power 1
08-26 19:03:06.393  7093  7572 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 19:03:06.393  7093  7572 I bt_vendor: Starting hciattach daemon
08-26 19:03:06.393  7093  7572 I bt_vendor: try to set true
08-26 19:03:06.394  7093  7641 I bt-btu  : btu_task pending for preload complete event
08-26 19:03:06.395  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:06.394  7644  7644 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:06.394  7644  7644 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:06.399  7093  7093 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:03:06.399  7093  7093 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:03:06.399  7093  7093 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:03:06.399  7093  7093 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:06.399  7093  7093 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 19:03:06.400  7064  7639 V FormManager: Network unavailable.
,08-26 19:03:06.405  7312  7312 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:3:6
08-26 19:03:06.408  7312  7312 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 19:03:06.408  7312  7312 D Weather.Utils: 2 : All the weather widget is gone.
08-26 19:03:06.409  7312  7312 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 19:03:06.409  7312  7312 D WeatherAncestor: connectivity changed - connection : true
08-26 19:03:06.409  7312  7312 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@257b5a83
08-26 19:03:06.409  7312  7312 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 19:03:06.409  7312  7312 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 19:03:06.409  7312  7312 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 19:03:06.409  7312  7312 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 19:03:06.410  7312  7312 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:3:6
08-26 19:03:06.422  7645  7645 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 19:03:06.498  7651  7651 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 19:03:06.525  7652  7652 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 19:03:06.562  7654  7654 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 19:03:06.576  7655  7655 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 19:03:06.590  7656  7656 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 19:03:06.602  7657  7657 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 19:03:06.628  7659  7659 I libmdmdetect: ESOC framework not supported
08-26 19:03:06.629  7659  7659 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 19:03:06.639  7659  7659 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-26 19:03:06.639  7659  7659 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 19:03:06.639  7659  7659 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 19:03:06.640  7659  7659 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 19:03:06.640  7659  7659 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 19:03:06.640  7659  7659 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 19:03:06.640  7659  7659 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 19:03:06.682  7659  7660 E QC-QMI  : qmi_client [7659] 14: failed to locate client data
,08-26 19:03:06.683   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-26 19:03:06.683   467   467 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-26 19:03:06.726  7664  7664 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 19:03:06.742  7665  7665 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 19:03:06.796  7093  7572 I bt_vendor: bluetooth satus is on
08-26 19:03:06.796  7093  7572 D bt_hci_bdroid: preload
,08-26 19:03:06.796  7093  7643 D bt_userial_mct: userial_open(port:0)
08-26 19:03:06.796  7093  7643 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-26 19:03:06.801  7093  7643 I bt_vendor: Done intiailizing UART
08-26 19:03:06.801  7093  7643 I bt_vendor: Done intiailizing UART
08-26 19:03:06.801  7093  7643 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 19:03:06.801  7093  7643 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 19:03:06.802  7093  7641 I bt-btu  : btu_task received preload complete event
08-26 19:03:06.802  7093  7667 D bt_userial_mct: Entering userial_read_thread()
08-26 19:03:06.802  7093  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 19:03:06.803  7093  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 19:03:06.805  7093  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-26 19:03:06.810  7093  7641 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 19:03:06.814  7093  7641 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 19:03:06.814  7093  7641 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 19:03:06.814  7093  7641 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 19:03:06.814  7093  7641 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 19:03:06.814  7093  7641 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 19:03:06.814  7093  7641 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-26 19:03:06.814  7093  7641 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 19:03:06.814  7093  7641 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-26 19:03:06.814  7093  7641 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 19:03:06.814  7093  7641 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 19:03:06.815  7093  7641 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 19:03:06.815  7093  7641 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 19:03:06.815  7093  7641 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 19:03:06.815  7093  7641 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-26 19:03:06.815  7093  7641 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 19:03:06.871  7093  7641 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-26 19:03:06.871  7093  7641 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0229061 
08-26 19:03:06.871  7093  7641 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0229061 
,08-26 19:03:06.888  7093  7576 E bt-btif : Calling BTA_HhEnable
08-26 19:03:06.888  7093  7576 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-26 19:03:06.888  7093  7576 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 19:03:06.889  7093  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-26 19:03:06.889  7093  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 19:03:06.889  7093  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 19:03:06.889  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 19:03:06.890  7093  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 19:03:06.890  7093  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 19:03:06.890  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 19:03:06.890  7093  7576 D BluetoothAdapterProperties: Name is: G3
08-26 19:03:06.891  7093  7576 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:03:06.892  7093  7576 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:03:06.892  7093  7576 D bt_hci_bdroid: postload
08-26 19:03:06.892  7093  7643 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:03:06.893  7093  7641 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 19:03:06.893  7093  7576 D bte_conf: Device ID record 1 : primary
08-26 19:03:06.893  7093  7576 D bte_conf:   vendorId            = 00c4
08-26 19:03:06.893  7093  7576 D bte_conf:   vendorIdSource      = 0001
08-26 19:03:06.893  7093  7576 D bte_conf:   product             = 13a1
08-26 19:03:06.893  7093  7576 D bte_conf:   version             = 1000
08-26 19:03:06.893  7093  7576 D bte_conf:   clientExecutableURL = 
08-26 19:03:06.893  7093  7576 D bte_conf:   serviceDescription  = 
08-26 19:03:06.894  7093  7643 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:03:06.893  7093  7576 D bte_conf:   documentationURL    = 
08-26 19:03:06.894  7093  7576 D bte_conf: bte_load_did_conf no section named DID2.
08-26 19:03:06.895  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:06.895  7093  7643 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:03:06.895  7093  7643 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:03:06.894  7669  7669 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:06.894  7669  7669 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:06.899  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:06.899  7093  7572 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 19:03:06.899  7093  7572 D BluetoothAdapterProperties: ScanMode =  20
08-26 19:03:06.899  7093  7572 D BluetoothAdapterProperties: State =  11
08-26 19:03:06.899  7093  7572 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 19:03:06.899  7093  7643 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:03:06.899  7093  7643 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:03:06.900  7093  7572 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 19:03:06.900  7093  7572 D BluetoothAdapterProperties: Setting state to 12
08-26 19:03:06.900  7093  7572 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 19:03:06.900  1034  1096 D BluetoothManagerService: Message: 60
08-26 19:03:06.900  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 19:03:06.900  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-26 19:03:06.900  7093  7576 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 19:03:06.901  7093  7576 D btif_config_util: btif_config_save_file(L188): in file name:/data,/misc/bluedroid/bt_config.new
08-26 19:03:06.903  7093  7667 E bt_mct  : hci lib postload completed
,08-26 19:03:06.907  7093  7572 I BluetoothAdapterState: Entering On State
08-26 19:03:06.908  6966  6991 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 19:03:06.911  7093  7641 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:03:06.911  7093  7641 W bt-smp  : Plain text(LSB ~ MSB) = 75 37 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:03:06.911  7093  7641 W bt-smp  : Encrypted text(LSB ~ MSB) = 44 3b b7 02 96 7a c8 2e d2 16 34 2e 7e 44 a1 cb 
08-26 19:03:06.912  7093  7572 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 19:03:06.912  7093  7572 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 19:03:06.912  7093  7572 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-26 19:03:06.912  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:03:06.913  7093  7641 W bt-btm  : Stopping oneshot timer
08-26 19:03:06.913  7093  7572 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 19:03:06.914  6966  6966 D BluetoothInputDevice: Proxy object connected
08-26 19:03:06.914  6966  6966 D HidProfile: Bluetooth service connected
08-26 19:03:06.918  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 19:03:06.920  6966  6991 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 19:03:06.927  6966  6991 D BluetoothPan: onBluetoothStateChange on: true
08-26 19:03:06.927  6966  6991 D BluetoothPan: onBluetoothStateChange call bindService
08-26 19:03:06.928  6966  6966 D BluetoothMap: Proxy object connected
08-26 19:03:06.928  6966  6966 D MapProfile: Bluetooth service connected
08-26 19:03:06.928  6966  6966 D BluetoothMap: getConnectedDevices()
08-26 19:03:06.931  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:03:06.934  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 19:03:06.935  7093  7641 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:03:06.935  7093  7641 W bt-smp  : Plain text(LSB ~ MSB) = 32 18 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:03:06.935  7093  7641 W bt-smp  : Encrypted text(LSB ~ MSB) = 26 50 b1 fc 8c 2b 71 f6 44 24 ba 48 b0 c1 9a 48 
08-26 19:03:06.935  7093  7641 W bt-btm  : Stopping oneshot timer
08-26 19:03:06.936  1034  1034 D BluetoothA2dp: Proxy object connected
08-26 19:03:06.938  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 19:03:06.940  1853  4461 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:03:06.942  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 19:03:06.943  6966  7673 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 19:03:06.945  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:03:06.946  1034  1034 D BluetoothHeadset: Proxy object connected
,08-26 19:03:06.948  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 19:03:06.949  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 19:03:06.949  7093  7641 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:03:06.949  7093  7641 W bt-smp  : Plain text(LSB ~ MSB) = 21 4a 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:03:06.949  7093  7641 W bt-smp  : Encrypted text(LSB ~ MSB) = b2 95 20 c6 3d f5 44 d3 ed 2b f4 16 97 6f 5e f9 
08-26 19:03:06.950  7093  7641 W bt-btm  : Stopping oneshot timer
08-26 19:03:06.951  7093  7672 V BluetoothMapService: getConnectedDevices()
08-26 19:03:06.952  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 19:03:06.955  7093  7572 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-26 19:03:06.955  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:06.955  1943  2127 D LGBluetoothAPIService: Message: 1
08-26 19:03:06.955  1943  2127 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 19:03:06.964  7093  7641 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:03:06.964  7093  7641 W bt-smp  : Plain text(LSB ~ MSB) = b0 a9 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:03:06.965  7093  7641 W bt-smp  : Encrypted text(LSB ~ MSB) = 51 ee 79 1b 3c de 69 54 1d 63 64 e7 c0 cf 34 36 
08-26 19:03:06.965  7093  7641 W bt-btm  : Stopping oneshot timer
08-26 19:03:06.966  6749  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-26 19:03:06.970  6966  6966 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 19:03:06.970  6966  6966 D PanProfile: Bluetooth service connected
08-26 19:03:06.980  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 19:03:06.980  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:06.980  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:06.980  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:06.980  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:06.980  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:06.980  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:06.980  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:06.980  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:06.980  1034  1096 D BluetoothManagerService: Message: 40
08-26 19:03:06.980  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-26 19:03:06.980  7093  7641 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:03:06.980  7093  7641 W bt-smp  : Plain text(LSB ~ MSB) = dd 49 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:03:06.980  7093  7641 W bt-smp  : Encrypted text(LSB ~ MSB) = 86 2c 8d 6b da b8 5c 81 29 c7 c8 aa a3 eb e2 d3 
08-26 19:03:06.980  7093  7641 W bt-btm  : Stopping oneshot timer
08-26 19:03:06.980  1943  2127 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-26 19:03:06.981  7093  7093 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:06.981  7093  7093 D BluetoothMapService: STATE_ON
08-26 19:03:06.983  6749  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:06.983  7093  7093 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 19:03:06.983  7093  7093 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 19:03:06.985  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 19:03:06.985  1943  2127 D LGBluetoothAPIService: Message: 100
08-26 19:03:06.985  1943  2127 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 19:03:06.988  7682  7682 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 19:03:06.989  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:06.989  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:06.989  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:06.989  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:06.989  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:06.989  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:06.989  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:06.989  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:06.989  7093  7576 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:03:06.990  7093  7576 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 19:03:06.991  6966  6966 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 19:03:06.992  6749  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:06.993  1034  1096 D BluetoothManagerService: Message: 30
08-26 19:03:06.997  6966  6966 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-26 19:03:06.999  1034  1096 D BluetoothManagerService: Message: 30
,08-26 19:03:07.003  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:07.003  7093  7093 V BluetoothPbapService: Pbap Service onCreate
08-26 19:03:07.003  7093  7093 V BluetoothPbapService: Starting PBAP service
08-26 19:03:07.004  7093  7093 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 19:03:07.004  6966  6966 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 19:03:07.004  7093  7093 V BluetoothPbapService: Pbap Service onBind
08-26 19:03:07.006  7093  7093 V BluetoothMapService: Handler(): got msg=1
08-26 19:03:07.006  7093  7093 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 19:03:07.006  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 19:03:07.007  7093  7093 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:07.007  7093  7093 V BluetoothPbapService: state: 12
08-26 19:03:07.007  7093  7093 V BluetoothPbapService: Handler(): got msg=1
08-26 19:03:07.008  7093  7093 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 19:03:07.009  7093  7683 D BluetoothMapMasInstance: MAS initSocket()
08-26 19:03:07.010  7093  7683 D BluetoothMapMasInstance:   masId = 00
08-26 19:03:07.010  7093  7683 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 19:03:07.010  7093  7683 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 19:03:07.010  7093  7683 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 19:03:07.010  7093  7684 V BluetoothPbapService: Pbap Service initSocket
08-26 19:03:07.111  1034  1734 I art     : Explicit concurrent mark sweep GC freed 93911(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.853ms total 102.350ms
,08-26 19:03:07.112  6966  6966 D BluetoothA2dp: Proxy object connected
,08-26 19:03:07.112  1034  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:07.113  6966  6966 D A2dpProfile: Bluetooth service connected
08-26 19:03:07.115  7093  7683 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:03:07.118  7093  7093 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 19:03:07.118  7093  7093 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:07.118  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:07.118  7093  7093 V BluetoothPbapReceiver: ***********state = 12
08-26 19:03:07.119  7093  7684 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:03:07.119  7093  7684 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 19:03:07.120  7093  7684 V BluetoothPbapService: Succeed to create listening socket 
08-26 19:03:07.120  7093  7684 V BluetoothPbapService: Accepting socket connection...
08-26 19:03:07.120  7093  7683 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 19:03:07.120  7093  7576 D BluetoothAdapterProperties: Scan Mode:21
08-26 19:03:07.121  7093  7683 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 19:03:07.121  7093  7683 D BluetoothMapMasInstance: Accepting socket connection...
08-26 19:03:07.121  7093  7576 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 19:03:07.121  6966  6966 D BluetoothHeadset: Proxy object connected
08-26 19:03:07.122  6966  6966 D HeadsetProfile: Bluetooth service connected
08-26 19:03:07.123  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:07.124  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:07.127  6966  6966 D BluetoothPbap: Proxy object connected
08-26 19:03:07.128  6966  6966 D PbapServerProfile: Bluetooth service connected
08-26 19:03:07.130  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 19:03:07.131  2188  2188 D c       : Getting all permits...
08-26 19:03:07.131  2188  2188 D a       : Opening database...
08-26 19:03:07.134  6966  6966 D DockEventReceiver: finishStartingService: stopping service
08-26 19:03:07.135  2188  2188 D a       : Opening database auth.proximity.permit_store...
08-26 19:03:07.136  2188  2188 D a       : Closing database...
08-26 19:03:07.160  6966  6966 D BluetoothPermissionRequest: onReceive
,08-26 19:03:07.162  6966  6966 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 19:03:07.164  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 19:03:07.167  7093  7093 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 19:03:07.170  7093  7093 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 19:03:07.178  7093  7093 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-26 19:03:07.186  7339  7370 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-26 19:03:07.200  7093  7093 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 19:03:07.201  7093  7093 V BtOppService: onCreate
,08-26 19:03:07.205  7093  7093 V BluetoothOppNotification: send message
08-26 19:03:07.209  7093  7093 V BtOppService: Starting RfcommListener
08-26 19:03:07.213  7093  7093 D BluetoothOppPreference: Dumping Names:  
,08-26 19:03:07.213  7093  7093 D BluetoothOppPreference: {}
08-26 19:03:07.213  7093  7093 D BluetoothOppPreference: Dumping Channels:  
08-26 19:03:07.213  7093  7093 D BluetoothOppPreference: {}
08-26 19:03:07.214  7093  7093 V BtOppService: onStartCommand
08-26 19:03:07.216  7093  7694 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 19:03:07.220  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:07.220  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 19:03:07.223  7093  7093 V BluetoothOppNotification: new notify threadi!
08-26 19:03:07.224  7093  7093 V BluetoothOppNotification: send delay message
08-26 19:03:07.225  7093  7093 V BtOppService: start RfcommListener
08-26 19:03:07.225  7093  7691 V BtOppService: Deleted complete outbound shares, number =  0
,08-26 19:03:07.225  7093  7695 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 19:03:07.226  7093  7694 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 19:03:07.229  7093  7691 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 19:03:07.229  7093  7691 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 19:03:07.229  7093  7093 V BtOppService: RfcommListener started
08-26 19:03:07.231  7093  7696 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 19:03:07.231  7093  7691 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30d1a8bc on behalf of 
08-26 19:03:07.233  7093  7695 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28165045 on behalf of 
08-26 19:03:07.233  7093  7694 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3853639a on behalf of 
08-26 19:03:07.233  1034  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:07.234  7093  7695 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 19:03:07.235  7093  7694 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 19:03:07.235  7093  7694 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 19:03:07.236  7093  7695 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 19:03:07.236  7093  7694 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6f684cb on behalf of 
08-26 19:03:07.236  7093  7696 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:03:07.237  7093  7696 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-26 19:03:07.237  7093  7696 V BtOppRfcommListener: Started RFCOMM listener....
08-26 19:03:07.238  7093  7696 I BtOppRfcommListener: Accept thread started.
08-26 19:03:07.238  7093  7696 V BtOppRfcommListener: Accepting connection...
,08-26 19:03:07.239  7093  7694 V BluetoothOppNotification: update too frequent, put in queue
08-26 19:03:07.240  7093  7695 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@136e94a8 on behalf of 
08-26 19:03:07.241  7093  7694 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 19:03:07.241  7093  7695 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 19:03:07.243  7093  7695 V BluetoothOppNotification: outbound notification was removed.
08-26 19:03:07.243  7093  7695 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 19:03:07.245  7093  7695 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1950abc1 on behalf of 
08-26 19:03:07.246  7093  7695 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 19:03:07.247  7093  7695 V BluetoothOppNotification: inbound notification was removed.
08-26 19:03:07.247  7093  7695 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 19:03:07.248  7093  7695 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33f41f66 on behalf of 
08-26 19:03:07.250  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:07.250  7093  7093 V BluetoothFtpService: Ftp Service onCreate
08-26 19:03:07.250  7093  7093 I BluetoothFtpService: Ftp Service onCreate
08-26 19:03:07.251  7093  7093 V BluetoothFtpService: Ftp Service onStartCommand
08-26 19:03:07.251  7093  7093 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:07.251  7093  7093 V BluetoothFtpService: Starting Listening on sockets
08-26 19:03:07.251  7093  7093 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:03:07.251  7093  7093 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:03:07.252  7093  7093 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:03:07.252  7093  7093 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:07.252  7093  7093 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 19:03:07.252  7093  7093 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 19:03:07.254  7093  7093 V BtOppService: ContentObserver received notification
08-26 19:03:07.254  7093  7093 V BtOppService: ContentObserver received notification
08-26 19:03:07.254  7093  7093 V BluetoothFtpService: Handler(): got msg=1
08-26 19:03:07.255  7093  7093 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 19:03:07.255  7093  7093 V BluetoothFtpService: Ftp Service initSocket
08-26 19:03:07.258  7093  7697 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 19:03:07.258  7093  7697 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 19:03:07.260  7093  7697 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@286c5354 on behalf of 
08-26 19:03:07.260  7093  7697 V BluetoothOppNotification: update too frequent, put in queue
08-26 19:03:07.262  1034  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:07.262  7093  7697 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 19:03:07.263  7093  7093 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:03:07.264  7093  7093 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
,08-26 19:03:07.264  7093  7093 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 19:03:07.266  7093  7698 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-26 19:03:07.285  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:07.285  7093  7093 V BluetoothSapService: Sap Service onCreate
,08-26 19:03:07.287  7093  7093 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:07.288  7093  7093 V BluetoothSapService: state: 12
08-26 19:03:07.288  7093  7093 V BluetoothSapService: Starting SAP server process
,08-26 19:03:07.289  7093  7093 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 19:03:07.284  7699  7699 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:07.291  7093  7700 V BluetoothSapService: Sap Service initRfcommSocket
08-26 19:03:07.284  7699  7699 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:07.292  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:07.293  7093  7700 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:03:07.294  7093  7700 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-26 19:03:07.294  7093  7700 V BluetoothSapService: Succeed to create listening socket 
08-26 19:03:07.294  7093  7700 V BluetoothSapService: Accepting socket connection...
08-26 19:03:07.302  7699  7699 V BT_SAP  : Event pipe created
08-26 19:03:07.303  7699  7699 V BT_SAP  : create_server_socket qcom.sap.server
08-26 19:03:07.303  7699  7699 V BT_SAP  : created socket fd 6
,08-26 19:03:07.842  1034  1419 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:03:07.842  1034  1419 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:03:07.908  1034  1466 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 19:03:07.910  1034  1466 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 19:03:07.983  1034  1978 I ActivityManager: Killing 7498:com.lge.bnr/1000 (adj 15): empty #17
,08-26 19:03:08.018  1034  1907 W libprocessgroup: failed to open /acct/uid_1000/pid_7498/cgroup.procs: No such file or directory
,08-26 19:03:08.226  7093  7093 V BluetoothOppNotification: new notify threadi!
,08-26 19:03:08.227  7093  7093 V BluetoothOppNotification: send delay message
,08-26 19:03:08.240  7093  7710 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 19:03:08.243  7093  7710 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ee550c0 on behalf of 
,08-26 19:03:08.249  7093  7710 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 19:03:08.251  7093  7710 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 19:03:08.252  7093  7710 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2abe11f9 on behalf of 
08-26 19:03:08.253  7093  7710 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 19:03:08.254  7093  7710 V BluetoothOppNotification: outbound notification was removed.
08-26 19:03:08.254  7093  7710 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 19:03:08.256  7093  7710 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bfdb53e on behalf of 
08-26 19:03:08.256  7093  7710 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 19:03:08.258  7093  7710 V BluetoothOppNotification: inbound notification was removed.
08-26 19:03:08.258  7093  7710 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 19:03:08.259  7093  7710 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4333f9f on behalf of 
,08-26 19:03:08.402  1034  1978 I ActivityManager: Killing 6994:com.lge.sync/1000 (adj 15): empty #17
,08-26 19:03:08.427  1034  1541 D WifiService: Client connection lost with reason: 4
,08-26 19:03:08.437  1034  1907 W libprocessgroup: failed to open /acct/uid_1000/pid_6994/cgroup.procs: No such file or directory
,08-26 19:03:08.838  1034  1734 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 19:03:08.839  1034  1734 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@28b3451b mBinding = false
,08-26 19:03:08.869  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 19:03:08.870  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 19:03:08.870  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-26 19:03:08.873  1034  1096 D BluetoothManagerService: Message: 2
08-26 19:03:08.874  1034  1096 D BluetoothManagerService: Sending off request.
08-26 19:03:08.875  7093  7111 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 19:03:08.876  7093  7572 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 19:03:08.876  7093  7572 D BluetoothAdapterProperties: Setting state to 13
08-26 19:03:08.876  7093  7572 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 19:03:08.877  7093  7572 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 19:03:08.877  7093  7572 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 19:03:08.879  7093  7576 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:03:08.880  7093  7572 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 19:03:08.882  7093  7684 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 19:03:08.886  7093  7572 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 19:03:08.888  7093  7683 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 19:03:08.888  7093  7683 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:03:08.888  7093  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 19:03:08.888  7093  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 19:03:08.888  7093  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 19:03:08.888  7093  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 19:03:08.888  7093  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 19:03:08.888  7093  7683 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 19:03:08.889  7093  7696 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:03:08.889  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 19:03:08.889  7093  7641 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 19:03:08.891  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:03:08.891  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:03:08.891  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:03:08.891  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:03:08.891  7093  7641 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:03:08.891  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:03:08.891  7093  7641 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:03:08.891  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:03:08.891  7093  7641 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:03:08.891  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 19:03:08.891  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 19:03:08.891  7093  7641 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 19:03:08.901  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:08.901  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:08.901  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:08.901  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:08.901  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:08.901  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:08.901  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:08.901  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:08.901  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:08.907  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:08.907  6749  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:08.912  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:08.913  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:08.913  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:08.913  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:08.913  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:08.913  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:08.913  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:08.913  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:08.913  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:08.913  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:08.913  6749  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:08.917  1034  1096 D BluetoothManagerService: Message: 60
08-26 19:03:08.917  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 19:03:08.917  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 19:03:08.920  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:08.921  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 19:03:08.926  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:08.930  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:08.933  7093  7093 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:08.933  7093  7093 D BluetoothMapService: STATE_TURNING_OFF
08-26 19:03:08.933  7093  7093 V BluetoothMapService: Handler(): got msg=4
08-26 19:03:08.933  7093  7093 D BluetoothMapService: MAP Service closeService in
08-26 19:03:08.934  7093  7093 D BluetoothMapMasInstance: MAP Service shutdown
08-26 19:03:08.934  7093  7093 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 19:03:08.934  7093  7093 V BluetoothMapService: MAP Service closeService out
08-26 19:03:08.936  7093  7093 V BtOppService: Receiver DISABLED_ACTION 
08-26 19:03:08.937  7093  7093 I BtOppRfcommListener: stopping Accept Thread
08-26 19:03:08.937  7093  7093 V BtOppRfcommListener: close mBtServerSocket
08-26 19:03:08.937  7093  7696 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 19:03:08.938  7093  7093 V BtOppRfcommListener: waiting for thread to terminate
08-26 19:03:08.938  7093  7093 V BtOppRfcommListener: done waiting for thread to terminate
,08-26 19:03:08.946  7093  7698 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:03:08.950  7093  7700 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 19:03:08.953  6966  6966 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-26 19:03:08.954  7093  7093 V BtOppService: onDestroy
08-26 19:03:08.956  7093  7093 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 19:03:08.957  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 19:03:08.962  7093  7093 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 19:03:08.962  7093  7093 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:08.962  7093  7093 V BluetoothPbapReceiver: ***********state = 13
,08-26 19:03:08.966  7093  7093 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 19:03:08.968  7093  7093 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:08.968  7093  7093 V BluetoothPbapService: state: 13
08-26 19:03:08.969  7093  7093 V BluetoothPbapService: Pbap Service closeService in
08-26 19:03:08.971  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 19:03:08.972  7093  7093 V BluetoothPbapService: successfully stopped pbap service
08-26 19:03:08.972  7093  7093 V BluetoothPbapService: Pbap Service closeService out
08-26 19:03:08.976  7093  7093 V BluetoothPbapService: Pbap Service onDestroy
08-26 19:03:08.976  7093  7093 V BluetoothPbapService: Pbap Service closeService in
08-26 19:03:08.976  7093  7093 V BluetoothPbapService: Pbap Service closeService out
08-26 19:03:08.976  7093  7093 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-26 19:03:08.993  6966  6966 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:03:09.000  6966  6966 D BluetoothPbap: Proxy object disconnected
08-26 19:03:09.000  6966  6966 D PbapServerProfile: Bluetooth service disconnected
08-26 19:03:09.017  6966  6966 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 19:03:09.024  6966  6966 D BluetoothPermissionRequest: onReceive
,08-26 19:03:09.025  6966  6966 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 19:03:09.033  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 19:03:09.040  7093  7093 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 19:03:09.040  7093  7093 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 19:03:09.040  7093  7093 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-26 19:03:09.046  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:09.046  7093  7093 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 19:03:09.047  7093  7093 V BluetoothFtpService: Ftp Service onStartCommand
08-26 19:03:09.047  7093  7093 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:09.048  7093  7093 V BluetoothFtpService: Ftp Service closeService
08-26 19:03:09.048  7093  7093 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 19:03:09.050  7093  7093 V BluetoothFtpService: successfully stopped ftp service
08-26 19:03:09.051  7093  7093 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:03:09.051  7093  7093 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:03:09.051  7093  7093 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:03:09.051  7093  7093 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:09.051  7093  7093 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 19:03:09.051  7093  7093 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 19:03:09.053  7093  7093 V BluetoothFtpService: Ftp Service onDestroy
,08-26 19:03:09.053  7093  7093 V BluetoothFtpService: Ftp Service closeService
08-26 19:03:09.054  7093  7093 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:09.054  7093  7093 V BluetoothSapService: state: 13
08-26 19:03:09.054  7093  7093 V BluetoothSapService: Stopping SAP server process
08-26 19:03:09.055  7093  7093 V BluetoothSapService: Sap Service closeSapService in
08-26 19:03:09.055  7093  7093 V BluetoothSapService: Close listen Socket : 
08-26 19:03:09.055  7093  7093 V BluetoothSapService: Close rfcomm Socket : 
08-26 19:03:09.055  7093  7093 V BluetoothSapService: Close sapd  Socket : 
08-26 19:03:09.059  7093  7093 V BluetoothSapService: Sap Service closeSapService out
08-26 19:03:09.060  7093  7093 V BluetoothSapService: Sap Service onDestroy
08-26 19:03:09.060  7093  7093 V BluetoothSapService: Sap Service closeSapService in
08-26 19:03:09.060  7093  7093 V BluetoothSapService: Close listen Socket : 
08-26 19:03:09.060  7093  7093 V BluetoothSapService: Close rfcomm Socket : 
08-26 19:03:09.060  7093  7093 V BluetoothSapService: Close sapd  Socket : 
,08-26 19:03:09.060  7093  7093 V BluetoothSapService: Sap Service closeSapService out
,08-26 19:03:09.814  7093  7576 D bt_hci_bdroid: cleanup
,08-26 19:03:09.822  7093  7643 I bt_lpm  : LPM is already off!!!
08-26 19:03:09.823  7093  7641 W bt-btif : ag scb idx 1 not allocated
08-26 19:03:09.823  7093  7641 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 19:03:09.823  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:03:09.823  7093  7641 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:03:09.823  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:03:09.823  7093  7641 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:03:09.823  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:03:09.824  7093  7641 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:03:09.824  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:03:09.824  7093  7641 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:03:09.824  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:03:09.824  7093  7641 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:03:09.824  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:03:09.824  7093  7641 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:03:09.824  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:03:09.824  7093  7641 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:03:09.824  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:03:09.824  7093  7641 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:03:09.824  7093  7641 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:03:09.824  7093  7641 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:03:09.824  7093  7641 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 19:03:09.828  7093  7667 I bt_userial_mct: exiting userial_read_thread
08-26 19:03:09.828  7093  7667 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 19:03:09.828  7093  7576 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 19:03:09.828  7093  7643 I bt_vendor: hw_epilog_process
08-26 19:03:09.829  7093  7576 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 19:03:09.829  7093  7576 D bt_userial_mct: userial_close
08-26 19:03:09.829  7093  7576 E bt_userial_mct: pthread_join() FAILED result:3
08-26 19:03:09.829  7093  7576 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 19:03:09.836  7093  7576 D bt_hci_bdroid: set_power 0
08-26 19:03:09.836  7093  7576 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 19:03:09.836  7093  7576 I bt_vendor: bluetooth satus is on
08-26 19:03:09.836  7093  7576 I bt_vendor: bt-vendor : resetting BT status
08-26 19:03:09.836  7093  7576 I bt_vendor: Starting hciattach daemon
08-26 19:03:09.836  7093  7576 I bt_vendor: try to set false
,08-26 19:03:09.842  7093  7576 I bt_vendor: Starting hciattach daemon
08-26 19:03:09.842  7093  7576 I bt_vendor: try to set false
08-26 19:03:09.844  7093  7576 I bt_vendor: cleanup
08-26 19:03:09.844  7093  7641 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 19:03:09.845  7093  7576 I GKI_LINUX: GKI_exit_task 0 done
08-26 19:03:09.845  7093  7576 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 19:03:09.847  7093  7572 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 19:03:09.851  7093  7093 D HeadsetService: Received stop request...Stopping profile...
,08-26 19:03:09.857  7093  7093 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 19:03:09.857  7093  7093 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:03:09.857  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:09.857  7093  7605 D HeadsetStateMachine: Exit Disconnected: -1
08-26 19:03:09.862  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 19:03:09.862  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 19:03:09.862  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 19:03:09.863  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-26 19:03:09.863  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-26 19:03:09.868  7093  7572 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 19:03:09.869  7093  7093 D A2dpService: Received stop request...Stopping profile...
08-26 19:03:09.870  7093  7626 D A2dpStateMachine: Exit Disconnected: -1
08-26 19:03:09.871  7093  7093 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 19:03:09.873  7093  7093 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 19:03:09.873  7093  7093 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:03:09.873  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:09.875  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-26 19:03:09.875  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 19:03:09.878  7093  7093 D HidService: Received stop request...Stopping profile...
08-26 19:03:09.878  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:09.880  7093  7093 D HealthService: Received stop request...Stopping profile...
08-26 19:03:09.881  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:09.884  7093  7093 D PanService: Received stop request...Stopping profile...
08-26 19:03:09.884  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:09.886  7093  7093 D HeadsetStateMachine: Unbinding service...
08-26 19:03:09.887  7093  7093 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 19:03:09.887  7093  7093 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 19:03:09.887  7093  7093 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 19:03:09.887  7093  7093 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 19:03:09.887  7093  7093 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 19:03:09.887  7093  7093 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:03:09.887  7093  7093 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 19:03:09.887  7093  7093 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 19:03:09.891  7093  7093 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 19:03:09.891  7093  7093 D BtGatt.GattService: stop()
08-26 19:03:09.891  7093  7093 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 19:03:09.892  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:09.895  7093  7093 D BluetoothMapService: Received stop request...Stopping profile...
08-26 19:03:09.895  7093  7093 D BluetoothMapService: stop()
08-26 19:03:09.896  7093  7093 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 19:03:09.896  7093  7093 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 19:03:09.896  7093  7093 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:09.898  7093  7093 I BluetoothA2dpServiceJni: cleanupNative
08-26 19:03:09.898  7093  7627 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 19:03:09.898  7093  7093 I GKI_LINUX: GKI_exit_task 2 done
08-26 19:03:09.898  7093  7093 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 19:03:09.899  7093  7093 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 19:03:09.899  7093  7093 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 19:03:09.899  7093  7093 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 19:03:09.900  7093  7093 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 19:03:09.900  7093  7093 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 19:03:09.900  7093  7093 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 19:03:09.900  7093  7093 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 19:03:09.904  7093  7093 V BluetoothMapService: Handler(): got msg=4
08-26 19:03:09.904  7093  7093 D BluetoothMapService: MAP Service closeService in
08-26 19:03:09.904  7093  7093 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 19:03:09.904  7093  7093 V BluetoothMapService: MAP Service closeService out
08-26 19:03:09.906  7093  7572 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 19:03:09.906  7093  7572 D BluetoothAdapterProperties: Setting state to 10
08-26 19:03:09.906  7093  7572 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 19:03:09.907  1034  1096 D BluetoothManagerService: Message: 60
08-26 19:03:09.907  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 19:03:09.907  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-26 19:03:09.907  7093  7572 I BluetoothAdapterState: Entering OffState
08-26 19:03:09.908  6966  7673 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 19:03:09.909  7093  7093 D BluetoothMapService: cleanup()
08-26 19:03:09.909  7093  7093 D BluetoothMapService: MAP Service closeService in
08-26 19:03:09.909  7093  7093 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 19:03:09.909  7093  7093 V BluetoothMapService: MAP Service closeService out
08-26 19:03:09.912  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 19:03:09.917  6966  7673 D BluetoothMap: onBluetoothStateChange: up=false
08-26 19:03:09.918  6966  7673 D BluetoothPan: onBluetoothStateChange on: false
08-26 19:03:09.920  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 19:03:09.921  6966  6987 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:03:09.921  1853  2480 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:03:09.922  1853  2723 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:03:09.922  6966  6991 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 19:03:09.923  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:03:09.923  6966  7673 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 19:03:09.924  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 19:03:09.924  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-26 19:03:09.928  1034  1096 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 19:03:09.928  1034  1096 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 19:03:09.928  1034  1096 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@28b3451b mBinding = false
08-26 19:03:09.930  1034  1096 D BluetoothManagerService: Sending unbind request.
08-26 19:03:09.934  7093  7576 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 19:03:09.934  7093  7093 I GKI_LINUX: GKI_exit_task 1 done
08-26 19:03:09.935  7093  7093 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 19:03:09.935  7093  7093 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 19:03:09.935  7093  7093 I art     : --- WEIRD: removing null entry 248
08-26 19:03:09.935  7093  7093 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-26 19:03:09.935  7093  7093 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 19:03:09.936  7093  7093 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-26 19:03:09.940  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-26 19:03:09.943  7093  7093 I art     : System.exit called, status: 0
08-26 19:03:09.943  7093  7093 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 19:03:09.964  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:09.968  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 19:03:09.968  1943  2127 D LGBluetoothAPIService: Message: 2
08-26 19:03:09.968  1943  2127 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@32950d02 mBinding = false
08-26 19:03:09.968  1943  2127 D LGBluetoothAPIService: Sending unbind request.
08-26 19:03:09.970  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:09.970  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:09.979  6966  6966 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 19:03:09.979  6966  6966 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-26 19:03:09.985   318  1393 V AudioFlinger: 7093 died, releasing its sessions
08-26 19:03:09.986   318  1393 V AudioFlinger:  pid 1853 @ 0
08-26 19:03:09.986   318  1393 V AudioFlinger:  pid 3201 @ 1
08-26 19:03:09.986   318  1393 V AudioFlinger:  pid 3201 @ 2
08-26 19:03:09.987  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 19:03:09.988  1604  1604 D BluetoothAdapter: 455772426: getState() :  mService = null. Returning STATE_OFF
08-26 19:03:09.988  1604  1604 D BluetoothAdapter: 455772426: getState() :  mService = null. Returning STATE_OFF
08-26 19:03:09.997  1034  1600 I ActivityManager: Process com.android.bluetooth (pid 7093) has died
08-26 19:03:09.997  1034  1600 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-26 19:03:10.006  6966  6966 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 19:03:10.057  1034  2013 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7741 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 19:03:10.070  6966  6966 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:03:10.136  7741  7741 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 19:03:10.137  7741  7741 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 19:03:10.137  7741  7741 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-26 19:03:10.138  7741  7741 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 19:03:10.159  7741  7741 D BluetoothAdapterApp: Loading JNI Library
,08-26 19:03:10.195  7741  7741 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1df550b Instance Count = 1
,08-26 19:03:10.202  7741  7741 D BluetoothAdapterApp: onCreate
08-26 19:03:10.226  7741  7741 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 19:03:10.226  7741  7741 D ProfileConfigQcom: Adding HeadsetService
08-26 19:03:10.226  7741  7741 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 19:03:10.226  7741  7741 D ProfileConfigQcom: Adding A2dpService
,08-26 19:03:10.226  7741  7741 D ProfileConfigQcom: [BTUI] HidService is supported
,08-26 19:03:10.227  7741  7741 D ProfileConfigQcom: Adding HidService
08-26 19:03:10.227  7741  7741 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 19:03:10.227  7741  7741 D ProfileConfigQcom: Adding HealthService
08-26 19:03:10.227  7741  7741 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 19:03:10.228  7741  7741 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 19:03:10.228  7741  7741 D ProfileConfigQcom: Adding PanService
08-26 19:03:10.229  7741  7741 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 19:03:10.229  7741  7741 D ProfileConfigQcom: Adding GattService
08-26 19:03:10.229  7741  7741 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 19:03:10.229  7741  7741 D ProfileConfigQcom: Adding BluetoothMapService
08-26 19:03:10.230  7741  7741 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 19:03:10.230  7741  7741 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 19:03:10.232  7741  7741 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:10.232  7741  7741 V BluetoothPbapReceiver: ***********state = 10
08-26 19:03:10.234  7741  7741 V LGMDMManagerInternal: Create singleton instance
08-26 19:03:10.300  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:03:10.313  6966  6966 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 19:03:10.316  6966  6966 D BluetoothPermissionRequest: onReceive
08-26 19:03:10.318  6966  6966 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 19:03:10.318  6966  6966 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-26 19:03:10.321  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 19:03:10.329  7741  7741 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 19:03:10.334  7741  7741 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:10.338  7741  7741 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:03:10.338  7741  7741 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:03:10.338  7741  7741 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:03:10.339  7741  7741 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:10.339  7741  7741 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 19:03:10.343  7039  7039 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-26 19:03:10.345  1034  1908 I ActivityManager: Killing 6879:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-26 19:03:10.363  7022  7022 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-26 19:03:10.364  7022  7022 W System.err: android.os.DeadObjectException
08-26 19:03:10.364  7022  7022 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 19:03:10.364  7022  7022 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 19:03:10.365  7022  7022 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 19:03:10.365  7022  7022 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 19:03:10.365  7022  7022 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 19:03:10.366  7022  7022 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 19:03:10.366  7022  7022 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 19:03:10.366  7022  7022 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 19:03:10.366  7022  7022 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 19:03:10.366  7022  7022 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 19:03:10.366  7022  7022 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:10.366  7022  7022 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:10.367  7022  7022 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 19:03:10.367  7022  7022 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 19:03:10.368  7022  7022 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 19:03:10.369  7022  7022 W System.err: android.os.DeadObjectException
08-26 19:03:10.373  7022  7022 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 19:03:10.373  7022  7022 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 19:03:10.373  7022  7022 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 19:03:10.373  7022  7022 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 19:03:10.374  7022  7022 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 19:03:10.374  7022  7022 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 19:03:10.374  7022  7022 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 19:03:10.374  7022  7022 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 19:03:10.374  7022  7022 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 19:03:10.374  7022  7022 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 19:03:10.374  7022  7022 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:10.374  7022  7022 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:10.375  7022  7022 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 19:03:10.375  7022  7022 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 19:03:10.375  7022  7022 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 19:03:10.376  7022  7022 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-26 19:03:10.454  1034  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_6879/cgroup.procs: No such file or directory
,08-26 19:03:10.455  1034  2032 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-26 19:03:10.468  7022  7022 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,08-26 19:03:10.468  7022  7022 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-26 19:03:10.535  1034  1942 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7787 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 19:03:10.536  7022  7022 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 19:03:10.622  7787  7787 D UEI.SmartControl: Quickset Services start...
08-26 19:03:10.624  7787  7787 I UEI.SmartControl: Manufacture = LGE
08-26 19:03:10.625  7787  7787 D UEI.SmartControl: Id = LGNevo
,08-26 19:03:10.629  7787  7787 D UEI.SmartControl: File observer start...
,08-26 19:03:10.629  7787  7787 E UEI.SmartControl: IR Port is disabled: false
08-26 19:03:10.630  7787  7787 D UEI.SmartControl: Starting file observer...
08-26 19:03:10.630  7787  7787 D UEI.SmartControl: Extracting JNI libs...
08-26 19:03:10.630  7787  7787 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 19:03:10.718  7787  7787 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-26 19:03:10.718  7787  7787 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 19:03:10.718  7787  7787 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 19:03:10.759  7787  7787 I UEI.SmartControl: --- Selecting new region: 6
,08-26 19:03:10.761  7787  7787 I UEI.SmartControl: Model = LG-D855
08-26 19:03:10.763  7787  7787 D UEI.SmartControl: QS Service created
,08-26 19:03:10.784  7787  7787 I UEI.SmartControl: Service initServices...
,08-26 19:03:10.792  7787  7787 D UEI.SmartControl: QS start get config
,08-26 19:03:10.853  7787  7787 D UEI.SmartControl: Loading JNI Libs...
,08-26 19:03:11.239  7787  7787 I UEI.SmartControl: Supports setup maps: true
,08-26 19:03:11.244  7787  7787 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 19:03:11.245  7787  7787 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-26 19:03:11.248  7787  7787 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-26 19:03:11.249  7787  7787 I UEI.SmartControl: ### init IR Blaster...
08-26 19:03:11.255  7787  7787 D serial_port: Configuring serial port
08-26 19:03:11.260  7787  7787 E UEI.SmartControl: UEIBLaster setting for 616
08-26 19:03:11.260  7787  7787 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 19:03:11.261  7787  7787 I UEI.SmartControl: configuring settings for MAXQ616
08-26 19:03:11.261  7787  7787 I UEI.SmartControl: Get version...
08-26 19:03:11.279  7787  7805 D UEI.SmartControl: serial port data available: 21
,08-26 19:03:11.311  7787  7787 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-26 19:03:11.311  7787  7787 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 19:03:11.311  7787  7787 I UEI.SmartControl: QS saving settings...
,08-26 19:03:11.313  7787  7787 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 19:03:11.339  7787  7805 D UEI.SmartControl: serial port data available: 4
,08-26 19:03:11.378  7787  7787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 19:03:11.387  7787  7808 I UEI.SmartControl: Device manager: loading config....
,08-26 19:03:11.388  7787  7808 D UEI.SmartControl: ----------- loading internal config...
08-26 19:03:11.401  7787  7787 E UEI.SmartControl: Services init done
08-26 19:03:11.401  7787  7787 D UEI.SmartControl: QS Service init finished
,08-26 19:03:11.407  7787  7787 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 19:03:11.407  7787  7787 D UEI.SmartControl: QS Service version code: 201091
08-26 19:03:11.408  7787  7787 D UEI.SmartControl: Service requested: Control
08-26 19:03:11.412  7787  7808 E UEI.SmartControl: Loading SETTINGS...
08-26 19:03:11.414  7787  7787 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 19:03:11.418  1034  1576 I ActivityManager: Killing 7022:com.lge.qremote/u0a112 (adj 15): empty #17
,08-26 19:03:11.439  7787  7808 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 19:03:11.464  7787  7807 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 19:03:11.464  7787  7807 D UEI.SmartControl: -----service ready thread exits
,08-26 19:03:11.476  1034  1969 W libprocessgroup: failed to open /acct/uid_10112/pid_7022/cgroup.procs: No such file or directory
08-26 19:03:11.481  7787  7787 D UEI.SmartControl: Internal service binding...
,08-26 19:03:11.955  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:03:11.956  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:03:12.081  1034  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 19:03:12.090  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
08-26 19:03:12.171  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 19:03:12.188  1034  1034 D administrator: Handling package changes for user 0
08-26 19:03:12.191  1034  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7824 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-26 19:03:12.198  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-26 19:03:12.199  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-26 19:03:12.216  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 19:03:12.252  7824  7824 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 19:03:12.313  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-26 19:03:12.313  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 19:03:12.333  7824  7824 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 19:03:12.333  7824  7824 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:03:12.359  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 19:03:12.364  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-26 19:03:12.371  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-26 19:03:12.372  2508  2508 V GmsNetworkLocationProvi: DISABLE
08-26 19:03:12.400  1034  1091 D LocationProviderProxy: applying state to connected service
,08-26 19:03:12.402  2508  2508 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-26 19:03:12.466  7824  7855 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-26 19:03:12.466  7824  7855 I Babel   : MmsConfig.loadMmsSettings
08-26 19:03:12.474  7824  7855 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-26 19:03:12.474  7824  7855 I Babel   : MmsConfig.loadFromDatabase
,08-26 19:03:12.499  7824  7855 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-26 19:03:12.499  7824  7855 I Babel   : MmsConfig.loadFromResources
08-26 19:03:12.501  7824  7855 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-26 19:03:12.502  7824  7855 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-26 19:03:12.528  7824  7824 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:12.528  7824  7854 W AudioCapabilities: Unsupported mime audio/evrc
08-26 19:03:12.530  7824  7854 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 19:03:12.532  7824  7854 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:03:12.545  7824  7854 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-26 19:03:12.548  7824  7854 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 19:03:12.549  7824  7854 W AudioCapabilities: Unsupported mime audio/evrc
08-26 19:03:12.559  1818  7858 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-26 19:03:12.559  1818  7858 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-26 19:03:12.565  7186  7186 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 19:03:12.577  7824  7854 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-26 19:03:12.579  7186  7186 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@20b3913d
08-26 19:03:12.579  7186  7186 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 19:03:12.579  7186  7186 D AppUp4:CustFacade: isPhone : true
08-26 19:03:12.580  7186  7186 D AppUp4:CustModeStarterReceiver: begin check event
08-26 19:03:12.580  7186  7186 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-26 19:03:12.582  1818  5257 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-26 19:03:12.592  7824  7854 W VideoCapabilities: Unsupported mime video/divx
08-26 19:03:12.596  7824  7854 W VideoCapabilities: Unsupported mime video/divx311
,08-26 19:03:12.600  7824  7854 W VideoCapabilities: Unsupported mime video/divx4
08-26 19:03:12.608  7824  7854 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 19:03:12.626  7824  7854 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 19:03:12.634  1034  1050 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7861 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-26 19:03:12.638  7824  7854 W AudioCapabilities: Unsupported mime audio/eac3
08-26 19:03:12.638  1034  1576 I ActivityManager: Killing 7220:com.lge.email/u0a23 (adj 15): empty #17
08-26 19:03:12.639  7824  7854 W AudioCapabilities: Unsupported mime audio/ac3
08-26 19:03:12.639  7824  7854 W AudioCapabilities: Unsupported mime audio/g726
,08-26 19:03:12.641  7824  7854 W AudioCapabilities: Unsupported mime audio/wma-voice
08-26 19:03:12.641  7824  7854 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-26 19:03:12.642  7824  7854 W AudioCapabilities: Unsupported mime audio/adpcm
08-26 19:03:12.654  7824  7854 W VideoCapabilities: Unsupported mime video/theora
,08-26 19:03:12.658  7824  7854 W VideoCapabilities: Unsupported mime video/mjpg
08-26 19:03:12.737  1034  1600 W libprocessgroup: failed to open /acct/uid_10023/pid_7220/cgroup.procs: No such file or directory
,08-26 19:03:12.780  7861  7861 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:03:12.781  7861  7861 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 19:03:12.781  7861  7861 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 19:03:12.783  7861  7861 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-26 19:03:12.784  7861  7861 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 19:03:12.886  7861  7861 I SystemConfig: BUILD Country: EU
08-26 19:03:12.887  7861  7861 I SystemConfig: BUILD Operator: OPEN
,08-26 19:03:12.943  1034  2013 I ActivityManager: Killing 7064:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-26 19:03:13.164  1034  2013 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7884 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-26 19:03:13.169  1034  1576 W libprocessgroup: failed to open /acct/uid_10026/pid_7064/cgroup.procs: No such file or directory
08-26 19:03:13.180  7861  7879 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-26 19:03:13.180  7861  7879 I SystemConfig: existFile = false
08-26 19:03:13.180  7861  7879 I SystemConfig: canReadFile = false
,08-26 19:03:13.180  7861  7879 I SystemConfig: systemFeature RCS result false
08-26 19:03:13.181  7861  7879 D SystemConfig: refreshRcsSupport() :false
,08-26 19:03:13.233  7884  7884 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 19:03:13.233  7884  7884 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 19:03:13.233  7884  7884 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 19:03:13.234  7884  7884 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 19:03:13.333  7884  7884 I AppConfig: Total System Memory = 2995761152
,08-26 19:03:13.344  7884  7884 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-26 19:03:13.430  1034  1896 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7903 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:03:13.431  1034  1896 I ActivityManager: Killing 6509:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-26 19:03:13.517  1034  1734 W libprocessgroup: failed to open /acct/uid_1000/pid_6509/cgroup.procs: No such file or directory
,08-26 19:03:13.687  7903  7903 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-26 19:03:13.791  7903  7903 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:03:13.791  7903  7903 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:03:13.850  7903  7903 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-26 19:03:13.871  7903  7903 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 19:03:13.872  7903  7903 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 19:03:13.908  7903  7903 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 19:03:13.908  7903  7903 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-26 19:03:13.930  1034  1933 I ActivityManager: Killing 7256:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-26 19:03:13.962  1034  1969 W libprocessgroup: failed to open /acct/uid_10046/pid_7256/cgroup.procs: No such file or directory
,08-26 19:03:13.976  3359  3374 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-26 19:03:13.978  3359  3374 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@368d1cb6 on behalf of 7903
,08-26 19:03:13.981  5086  7943 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-26 19:03:14.025  1034  2032 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7944 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-26 19:03:14.050  7903  7903 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-26 19:03:14.082  7903  7903 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-26 19:03:14.132  7944  7944 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-26 19:03:14.160  7944  7944 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-26 19:03:14.160  7944  7944 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-26 19:03:14.160  7944  7944 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-26 19:03:14.160  7944  7944 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,08-26 19:03:14.160  7944  7944 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-26 19:03:14.160  7944  7944 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-26 19:03:14.190  1034  1734 I ActivityManager: Killing 7275:com.android.chrome/u0a57 (adj 15): empty #17
,08-26 19:03:14.219  1034  1942 W libprocessgroup: failed to open /acct/uid_10057/pid_7275/cgroup.procs: No such file or directory
,08-26 19:03:14.370  1034  1933 V SIM_STK : Menu title from STK is T-Mobile
,08-26 19:03:14.409  5086  7943 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 427 ms] updated apps [took 427 ms] 
,08-26 19:03:14.969  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:03:14.969  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dae58c7 added. We now have 6 listener(s)
,08-26 19:03:14.969  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:03:14.984  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:14.984  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23329ef4 added. We now have 7 listener(s)
08-26 19:03:14.984  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:14.988  6749  6816 I System.out: IsBluetoothEnabled
08-26 19:03:14.989  1034  2057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:14.989  1034  2057 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-26 19:03:14.990  1034  1096 D BluetoothManagerService: Message: 2
,08-26 19:03:14.995  6749  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:14.996  1034  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:14.996  1034  2013 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 19:03:15.011  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 19:03:15.011  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 19:03:15.011  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 19:03:15.012  1034  1096 D BluetoothManagerService: Message: 1
08-26 19:03:15.012  1034  1096 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-26 19:03:15.040  1034  1096 D BluetoothManagerService: Message: 20
08-26 19:03:15.041  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f76bd76:true
,08-26 19:03:15.045  7741  7741 D BluetoothAdapterState: make
08-26 19:03:15.050  7741  7741 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 19:03:15.050  7741  7741 I bluedroid-qcom: init
08-26 19:03:15.051  7741  7980 I BluetoothAdapterState: Entering OffState
08-26 19:03:15.051  7741  7741 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 19:03:15.052  7741  7741 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 19:03:15.052  7741  7741 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 19:03:15.052  7741  7741 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 19:03:15.052  7741  7741 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 19:03:15.054  7741  7741 I bluedroid-qcom: get_profile_interface socket
08-26 19:03:15.054  7741  7741 I bluedroid-qcom: get_profile_interface map_client
,08-26 19:03:15.058  7741  7984 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 19:03:15.054  7983  7983 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:15.062  7741  7984 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 19:03:15.054  7983  7983 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:15.071  7983  7983 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 19:03:15.071  7983  7983 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 19:03:15.071  7983  7983 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-26 19:03:15.075  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 19:03:15.076  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 19:03:15.082  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 19:03:15.082  1034  1096 D BluetoothManagerService: Message: 40
08-26 19:03:15.082  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 19:03:15.083  7741  7766 I bluedroid-qcom: config_hci_snoop_log
,08-26 19:03:15.087  7983  7983 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 19:03:15.091  1034  1096 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 19:03:15.091  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 19:03:15.093  7741  7984 D BluetoothAdapterProperties: Name is: G3
08-26 19:03:15.097  7741  7980 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 19:03:15.098  7741  7980 D BluetoothAdapterProperties: Setting state to 11
08-26 19:03:15.098  7741  7980 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-26 19:03:15.101  1034  1096 D BluetoothManagerService: Message: 60
08-26 19:03:15.101  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 19:03:15.101  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 19:03:15.107  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:15.108  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 19:03:15.111  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:15.114  7983  7983 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
,08-26 19:03:15.114  7983  7983 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-26 19:03:15.119  6966  6966 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-26 19:03:15.124  7741  7741 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 19:03:15.124  7741  7741 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:15.124  7741  7741 V BluetoothPbapReceiver: ***********state = 11
,08-26 19:03:15.143  7741  7980 I LGBluetoothServiceJni: classInitNative: succeeds
08-26 19:03:15.144  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 19:03:15.161  6966  6966 D BluetoothPermissionRequest: onReceive
,08-26 19:03:15.162  7741  7980 D BluetoothBondStateMachine: make
08-26 19:03:15.168  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 19:03:15.171  7741  7980 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:15.171  7741  7980 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 19:03:15.171  7741  7980 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:15.171  7741  7980 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 19:03:15.173  7741  7980 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 19:03:15.174  7741  8000 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 19:03:15.179  7741  7741 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:15.180  7741  7980 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:03:15.181  7741  7741 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:03:15.181  7741  7741 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:03:15.181  7741  7741 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:03:15.181  7741  7741 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:15.182  7741  7741 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 19:03:15.188  7741  7980 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:03:15.190  7741  7741 D HeadsetService: Received start request. Starting profile...
,08-26 19:03:15.191  7741  7741 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 19:03:15.191  7741  7741 D LGBluetoothHfpAdapter: Version 1.6
08-26 19:03:15.195  7741  7741 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 19:03:15.196  7741  7741 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 19:03:15.196  7741  7741 D HeadsetStateMachine: make
08-26 19:03:15.198  7741  7980 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:03:15.204  7741  7980 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 19:03:15.211  7741  7980 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:03:15.218  7741  7980 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:03:15.224  7741  7980 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 19:03:15.237  7741  7741 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:03:15.237  7741  7741 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:03:15.240  7741  7980 V LGMDMManager: Create singleton instance
08-26 19:03:15.241  7741  7741 D HeadsetStateMachine: max_hf_connections = 1
08-26 19:03:15.241  7741  7741 I bluedroid-qcom: get_profile_interface handsfree
08-26 19:03:15.242  7741  7980 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 19:03:15.243  7741  7741 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 19:03:15.244   318   318 V AudioPolicyService: registerClient() client 0xb54f4180, uid 1002
08-26 19:03:15.244   318  1394 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 19:03:15.244   318  1394 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 19:03:15.244   318  1394 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 19:03:15.244  7741  7741 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 19:03:15.245   318  2153 V AudioFlinger: registerClient() client 0xb57c8f58, pid 7741
08-26 19:03:15.245   318  1388 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:03:15.245   318  1388 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:03:15.245  1604  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:03:15.245  1604  1624 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:03:15.245  1853  2480 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:03:15.245  1853  2480 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:03:15.246  7741  7741 V ToneGenerator: Create Track: 0xb4928a80
08-26 19:03:15.246  3201  3217 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:03:15.246  7741  7741 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 19:03:15.246  7741  7741 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 19:03:15.246  3201  3217 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:03:15.246  7741  7766 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:03:15.246  7741  7766 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 19:03:15.246   318  1393 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 19:03:15.246   318  1393 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 19:03:15.246   318  1393 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 19:03:15.246   318  1393 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 19:03:15.246  1034  2032 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:03:15.246  1034  2032 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:03:15.246   318  1389 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:03:15.246   318  1389 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:03:15.246  1604  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:03:15.246  1604  1622 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:03:15.246  1034  1050 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:03:15.247  1034  1050 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:03:15.247  1853  2723 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:03:15.247  1853  2723 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:03:15.247   318   318 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 19:03:15.247  7741  7766 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:03:15.247  7741  7766 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount, 960 latency 80
08-26 19:03:15.247   318  1394 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 19:03:15.247   318  1394 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 19:03:15.247   318  1394 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 19:03:15.247   318  1394 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 19:03:15.247  7741  7741 V AudioSystem: getLatency() output 2, latency 50
08-26 19:03:15.247  7741  7741 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 19:03:15.247  7741  7741 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 19:03:15.248   318  2153 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 19:03:15.248   318  2153 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 19:03:15.248   318  2153 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 19:03:15.248   318  2153 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 19:03:15.248   318  2153 V AudioFlinger: createTrack() lSessionId: 23
08-26 19:03:15.248  7741  7741 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 19:03:15.248  3201  3216 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:03:15.249  3201  3216 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:03:15.249   318  2153 V AudioFlinger: acquiring 23 from 7741, for 7741
08-26 19:03:15.249   318  2153 V AudioFlinger:  added new entry for 23
08-26 19:03:15.249  7741  7741 V ToneGenerator: ToneGenerator INIT OK, time: 138594
08-26 19:03:15.249  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:15.250  7741  8003 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 19:03:15.250  7741  8003 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 19:03:15.250  7741  8003 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 19:03:15.250  7741  8003 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 19:03:15.251   318  2152 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7741
08-26 19:03:15.251   318  2152 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 19:03:15.251   318  2152 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 19:03:15.251   318  2152 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 19:03:15.251   318  2152 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 19:03:15.251   318  2152 V voice   : voice_set_parameters: exit with code(0)
08-26 19:03:15.251   318  2152 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
,08-26 19:03:15.251   318  2152 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 19:03:15.252   318  2152 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 19:03:15.252   318  2152 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 19:03:15.252   318  2152 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 19:03:15.252   318  2152 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 19:03:15.252  7741  8003 V ToneGenerator: ToneGenerator destructor
08-26 19:03:15.252  7741  8003 V ToneGenerator: stopTone
08-26 19:03:15.252  7741  8003 V ToneGenerator: Delete Track: 0xb4928a80
,08-26 19:03:15.252  7741  8003 V AudioTrack: ~AudioTrack, releasing session id from 7741 on behalf of 7741
08-26 19:03:15.253   318  1393 V AudioFlinger: releasing 23 from 7741 for 7741
08-26 19:03:15.253   318  1393 V AudioFlinger:  decremented refcount to 0
08-26 19:03:15.253  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:15.253   318  1393 V AudioFlinger: purging stale effects
08-26 19:03:15.253   318  1393 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 19:03:15.253   318  1393 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 19:03:15.253   318  1393 V AudioFlinger: PlaybackThread::Track destructor
08-26 19:03:15.253   318  1393 V AudioFlinger: removeClient_l() pid 7741, calling pid 318
08-26 19:03:15.253   318  1256 V AudioPolicyService: AudioCommandThread() waking up
08-26 19:03:15.253   318  1256 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 19:03:15.253   318  1256 V AudioPolicyManager: releaseOutput() 2
08-26 19:03:15.253   318  1256 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 19:03:15.254  7741  7741 D A2dpService: Received start request. Starting profile...
08-26 19:03:15.255  7741  7741 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 19:03:15.256  7741  7741 V Avrcp   : make
08-26 19:03:15.257  7741  7741 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 19:03:15.257  7741  7741 I bluedroid-qcom: get_profile_interface avrcp
08-26 19:03:15.264  7741  7741 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 19:03:15.266  7741  7741 E AudioManager: No RCC entry present to update
08-26 19:03:15.266  7741  7741 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 19:03:15.269  7741  7741 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 19:03:15.269  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 19:03:15.269  7741  7741 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 19:03:15.274  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 19:03:15.410  1034  1978 V SIM_STK : Menu title from STK is T-Mobile
,08-26 19:03:15.410  1034  1978 V SIM_STK : Menu title from STK is T-Mobile
,08-26 19:03:15.487  1034  1734 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 19:03:15.493  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 19:03:15.497  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 19:03:15.497  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 19:03:15.497  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 19:03:15.497  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 19:03:15.497  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 19:03:15.497  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 19:03:15.497  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 19:03:15.497  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 19:03:15.497  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 19:03:15.498  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 19:03:15.498  7741  7741 I BluetoothA2dpServiceJni: classInitNative
08-26 19:03:15.498  7741  7741 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 19:03:15.498  7741  7741 D A2dpStateMachine: make
08-26 19:03:15.501  7741  7741 I bluedroid-qcom: get_profile_interface a2dp
08-26 19:03:15.501  7741  8011 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-26 19:03:15.503  7741  7741 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 19:03:15.503  7741  7741 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 19:03:15.504  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:15.505  7741  7741 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 19:03:15.506  7741  7741 D HidService: Received start request. Starting profile...
,08-26 19:03:15.506  7741  7741 I bluedroid-qcom: get_profile_interface hidhost
08-26 19:03:15.506  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:15.506  7741  8010 D A2dpStateMachine: Enter Disconnected: -2
08-26 19:03:15.507  7741  7741 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 19:03:15.508  7741  7741 D HealthService: Received start request. Starting profile...
08-26 19:03:15.511  7741  7741 I bluedroid-qcom: get_profile_interface health
08-26 19:03:15.511  7741  7741 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 19:03:15.512  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:15.512  7741  7741 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 19:03:15.513  7741  7741 D PanService: Received start request. Starting profile...
08-26 19:03:15.513  7741  7741 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 19:03:15.513  7741  7741 I bluedroid-qcom: get_profile_interface pan
08-26 19:03:15.520  7741  7741 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 19:03:15.521  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
,08-26 19:03:15.521  7741  7741 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 19:03:15.525  7741  7741 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 19:03:15.525  7741  7741 D BtGatt.GattService: Received start request. Starting profile...
08-26 19:03:15.525  7741  7741 D BtGatt.GattService: start()
08-26 19:03:15.525  7741  7741 I bluedroid-qcom: get_profile_interface gatt
08-26 19:03:15.526  7741  7741 D BtGatt.AdvertiseManager: advertise manager created
08-26 19:03:15.537  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
,08-26 19:03:15.538  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:15.538  7741  7741 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 19:03:15.539  7741  7741 V BluetoothMapService: BluetoothMapBinder()
08-26 19:03:15.539  7741  7741 D BluetoothMapService: Received start request. Starting profile...
08-26 19:03:15.539  7741  7741 D BluetoothMapService: start()
08-26 19:03:15.542  7741  7741 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 19:03:15.542  7741  7741 D BluetoothMapEmailAppObserver: createReceiver()
08-26 19:03:15.543  7741  7741 D BluetoothMapEmailAppObserver: initObservers()
08-26 19:03:15.543  7741  7741 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 19:03:15.548  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:15.549  7741  7741 D HeadsetStateMachine: Proxy object connected
08-26 19:03:15.549  7741  7741 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 19:03:15.549  7741  7741 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-26 19:03:15.554  7741  7741 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:03:15.554  7741  8003 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 19:03:15.554  7741  8003 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 19:03:15.555  7741  8003 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-26 19:03:15.558  7741  7741 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:03:15.560  7741  7741 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:03:15.563  7741  7741 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:03:15.563  7741  7741 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 19:03:15.566  7741  7741 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:03:15.568  7741  7741 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 19:03:15.568  7741  7741 V BluetoothMapService: Handler(): got msg=1
08-26 19:03:15.568  7741  7980 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 19:03:15.568  7741  7980 I bluedroid-qcom: enable
08-26 19:03:15.569  7741  8018 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 19:03:15.569  7741  8018 I bt-btu  : btu_task pending for preload complete event
08-26 19:03:15.569  7741  7980 I bt_hci_bdroid: init
,08-26 19:03:15.570  7741  7980 I bt_vendor: bt-vendor : init
08-26 19:03:15.570  7741  7980 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 19:03:15.570  7741  7980 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 19:03:15.570  7741  7980 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 19:03:15.570  7741  7980 D bt_userial_mct: userial_init
08-26 19:03:15.571  7741  7980 D bt_hci_bdroid: set_power 1
08-26 19:03:15.571  7741  7980 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 19:03:15.571  7741  7980 I bt_vendor: Starting hciattach daemon
08-26 19:03:15.571  7741  7980 I bt_vendor: try to set true
08-26 19:03:15.564  8021  8021 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:15.564  8021  8021 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:15.604  8022  8022 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 19:03:15.687  8029  8029 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 19:03:15.704  8030  8030 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 19:03:15.745  8032  8032 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 19:03:15.758  8033  8033 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 19:03:15.771  8034  8034 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 19:03:15.785  8035  8035 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 19:03:15.811  8037  8037 I libmdmdetect: ESOC framework not supported
,08-26 19:03:15.812  8037  8037 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 19:03:15.822  8037  8037 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-26 19:03:15.822  8037  8037 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 19:03:15.822  8037  8037 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 19:03:15.822  8037  8037 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 19:03:15.822  8037  8037 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 19:03:15.822  8037  8037 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 19:03:15.822  8037  8037 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 19:03:15.861  8037  8038 E QC-QMI  : qmi_client [8037] 15: failed to locate client data
08-26 19:03:15.862   467   467 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-26 19:03:15.862   467   467 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-26 19:03:15.917  8039  8039 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 19:03:15.940  8040  8040 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 19:03:15.977  7741  7980 I bt_vendor: bluetooth satus is on
,08-26 19:03:15.977  7741  7980 D bt_hci_bdroid: preload
08-26 19:03:15.977  7741  8020 D bt_userial_mct: userial_open(port:0)
,08-26 19:03:15.977  7741  8020 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 19:03:15.981  7741  8020 I bt_vendor: Done intiailizing UART
,08-26 19:03:15.984  7741  8020 I bt_vendor: Done intiailizing UART
08-26 19:03:15.984  7741  8020 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 19:03:15.984  7741  8020 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 19:03:15.984  7741  8018 I bt-btu  : btu_task received preload complete event
08-26 19:03:15.984  7741  8042 D bt_userial_mct: Entering userial_read_thread()
08-26 19:03:15.985  7741  8018 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 19:03:15.985  7741  8018 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 19:03:15.987  7741  8018 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 19:03:15.991  7741  8018 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 19:03:16.084  7741  8018 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-26 19:03:16.085  7741  8018 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0229061 
08-26 19:03:16.085  7741  8018 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0229061 
,08-26 19:03:16.123  7741  7984 E bt-btif : Calling BTA_HhEnable
,08-26 19:03:16.123  7741  7984 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-26 19:03:16.123  7741  7984 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 19:03:16.128  7741  8018 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-26 19:03:16.128  7741  8018 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 19:03:16.128  7741  8018 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 19:03:16.128  7741  8018 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 19:03:16.128  7741  8018 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 19:03:16.129  7741  7984 D BluetoothAdapterProperties: Name is: G3
08-26 19:03:16.131  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 19:03:16.131  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 19:03:16.132  7741  7984 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:03:16.132  7741  7984 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:03:16.133  7741  7984 D bt_hci_bdroid: postload
08-26 19:03:16.133  7741  8020 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:03:16.134  7741  7984 D bte_conf: Device ID record 1 : primary
08-26 19:03:16.134  7741  7984 D bte_conf:   vendorId            = 00c4
08-26 19:03:16.134  7741  7984 D bte_conf:   vendorIdSource      = 0001
08-26 19:03:16.134  7741  7984 D bte_conf:   product             = 13a1
08-26 19:03:16.134  7741  7984 D bte_conf:   version             = 1000
08-26 19:03:16.134  7741  7984 D bte_conf:   clientExecutableURL = 
08-26 19:03:16.134  7741  7984 D bte_conf:   serviceDescription  = 
08-26 19:03:16.134  7741  7984 D bte_conf:   documentationURL    = 
08-26 19:03:16.134  7741  7984 D bte_conf: bte_load_did_conf no section named DID2.
08-26 19:03:16.134  7741  8018 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 19:03:16.139  7741  7980 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 19:03:16.139  7741  7980 D BluetoothAdapterProperties: ScanMode =  20
08-26 19:03:16.139  7741  7980 D BluetoothAdapterProperties: State =  11
,08-26 19:03:16.139  7741  7980 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 19:03:16.139  7741  7980 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 19:03:16.139  7741  7980 D BluetoothAdapterProperties: Setting state to 12,
08-26 19:03:16.139  7741  7980 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 19:03:16.146  7741  7984 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 19:03:16.144  8050  8050 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:16.148  1034  1096 D BluetoothManagerService: Message: 60
08-26 19:03:16.148  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 19:03:16.148  1034  1096 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-26 19:03:16.149  7741  8020 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:03:16.149  7741  7984 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 19:03:16.144  8050  8050 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:16.155  7741  8020 D bt_hci_bdroid: Used up Tx Cmd credits
,08-26 19:03:16.160  7741  8020 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:03:16.169  7741  8042 E bt_mct  : hci lib postload completed
,08-26 19:03:16.177  7741  8018 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:03:16.177  7741  8018 W bt-smp  : Plain text(LSB ~ MSB) = a1 8c 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:03:16.177  7741  8018 W bt-smp  : Encrypted text(LSB ~ MSB) = d0 b1 27 39 41 3b 69 f4 5a d4 22 21 15 5d 67 a8 
08-26 19:03:16.178  7741  8018 W bt-btm  : Stopping oneshot timer
08-26 19:03:16.191  7741  7984 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:03:16.191  7741  7984 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-26 19:03:16.200  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:16.200  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:16.200  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:16.200  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:16.200  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:16.200  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:16.200  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:16.200  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:16.201  7741  7980 I BluetoothAdapterState: Entering On State
08-26 19:03:16.203  7741  8018 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:03:16.203  7741  8018 W bt-smp  : Plain text(LSB ~ MSB) = d1 34 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:03:16.203  7741  8018 W bt-smp  : Encrypted text(LSB ~ MSB) = 02 f0 bf a8 3f b3 97 bd 2b e5 e0 49 9b 6b 78 f5 
,08-26 19:03:16.205  7741  8018 W bt-btm  : Stopping oneshot timer
08-26 19:03:16.210  6749  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:16.224  7741  7980 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 19:03:16.224  7741  7980 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 19:03:16.224  7741  7980 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-26 19:03:16.227  7741  7980 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 19:03:16.228  6966  6987 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 19:03:16.251  7741  7980 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-26 19:03:16.253  7741  8018 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:03:16.253  7741  8018 W bt-smp  : Plain text(LSB ~ MSB) = f9 08 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:03:16.253  7741  8018 W bt-smp  : Encrypted text(LSB ~ MSB) = 6d dd ef 61 d3 c9 45 05 e3 4d 17 9d aa 7b 45 17 
08-26 19:03:16.254  7741  8018 W bt-btm  : Stopping oneshot timer
08-26 19:03:16.264  8055  8055 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-26 19:03:16.280  7741  8018 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:03:16.280  7741  8018 W bt-smp  : Plain text(LSB ~ MSB) = 5b f9 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:03:16.280  7741  8018 W bt-smp  : Encrypted text(LSB ~ MSB) = 5e 37 54 2f 47 04 9d 98 ff 71 b5 69 71 2c 76 34 
08-26 19:03:16.281  7741  8018 W bt-btm  : Stopping oneshot timer
,08-26 19:03:16.300  7741  8018 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:03:16.300  7741  8018 W bt-smp  : Plain text(LSB ~ MSB) = fc 49 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:03:16.300  7741  8018 W bt-smp  : Encrypted text(LSB ~ MSB) = e5 5a 4b 07 6a 0e 2d 53 e2 bc 25 65 1f 4b 77 3d 
08-26 19:03:16.300  7741  8018 W bt-btm  : Stopping oneshot timer
,08-26 19:03:16.381  7787  7809 D UEI.SmartControl: Internal timer expired: 1
08-26 19:03:16.382  7787  7809 D UEI.SmartControl: unbind internal service
,08-26 19:03:16.425  1034  1096 I art     : Explicit concurrent mark sweep GC freed 26644(1315KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.882ms total 155.413ms
,08-26 19:03:16.431  6966  6966 D BluetoothInputDevice: Proxy object connected
08-26 19:03:16.431  6966  6966 D HidProfile: Bluetooth service connected
,08-26 19:03:16.432  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:03:16.433  7787  7787 D UEI.SmartControl: Service.onUnbind: IControl
,08-26 19:03:16.435  7787  7787 D UEI.SmartControl: Service.onDestroy
08-26 19:03:16.435  7787  7787 D UEI.SmartControl: Lock is in USE false
08-26 19:03:16.435  7787  7787 D UEI.SmartControl: unbind internal service
08-26 19:03:16.436  7787  7787 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@34cd0439
08-26 19:03:16.436  7787  7787 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
,08-26 19:03:16.436  7787  7787 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-26 19:03:16.436  7787  7787 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-26 19:03:16.437  7787  7787 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-26 19:03:16.437  7787  7787 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-26 19:03:16.437  7787  7787 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
,08-26 19:03:16.437  7787  7787 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-26 19:03:16.437  7787  7787 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-26 19:03:16.437  7787  7787 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:16.437  7787  7787 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 19:03:16.437  7787  7787 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 19:03:16.437  7787  7787 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-26 19:03:16.437  7787  7787 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:16.437  7787  7787 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 19:03:16.437  7787  7787 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 19:03:16.437  7787  7787 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@34cd0439
08-26 19:03:16.440  7787  7787 D serial_port: close(fd = 25)
,08-26 19:03:16.448  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 19:03:16.449  6966  6987 D BluetoothMap: onBluetoothStateChange: up=true
08-26 19:03:16.452  6966  6966 D BluetoothMap: Proxy object connected
08-26 19:03:16.452  6966  6966 D MapProfile: Bluetooth service connected
08-26 19:03:16.452  6966  6966 D BluetoothMap: getConnectedDevices()
08-26 19:03:16.452  7787  7787 I UEI.SmartControl: Serial port is closed.
08-26 19:03:16.452  7787  7787 I UEI.SmartControl: Serial port is closed.
08-26 19:03:16.452  7787  7787 D UEI.SmartControl: Blaster closed
08-26 19:03:16.452  6966  6987 D BluetoothPan: onBluetoothStateChange on: true
08-26 19:03:16.452  6966  6987 D BluetoothPan: onBluetoothStateChange call bindService
08-26 19:03:16.452  7787  7787 D UEI.SmartControl: Shut down QS...
08-26 19:03:16.453  7787  7787 D UEI.SmartControl: Stopping QS lib
08-26 19:03:16.454  7787  7787 D UEI.SmartControl: QS lib stop result = true
08-26 19:03:16.454  7787  7787 D UEI.SmartControl: Stopped QS lib
08-26 19:03:16.455  7787  7787 D UEI.SmartControl: Stopped file observer...
08-26 19:03:16.455  7787  7787 D UEI.SmartControl: QS shutdown complete
,08-26 19:03:16.462  7741  7765 V BluetoothMapService: getConnectedDevices()
08-26 19:03:16.463  1034  1096 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:03:16.463  6966  6966 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 19:03:16.464  6966  6966 D PanProfile: Bluetooth service connected
08-26 19:03:16.465  6966  6991 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:03:16.469  1034  1034 D BluetoothA2dp: Proxy object connected
,08-26 19:03:16.470  6966  6966 D BluetoothHeadset: Proxy object connected
08-26 19:03:16.470  6966  6966 D HeadsetProfile: Bluetooth service connected
08-26 19:03:16.470  1853  2480 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 19:03:16.474  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 19:03:16.474  1853  4461 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:03:16.475  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 19:03:16.476  6966  6991 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 19:03:16.477  1034  1096 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:03:16.478  1034  1034 D BluetoothHeadset: Proxy object connected
08-26 19:03:16.479  6966  6987 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:03:16.481  1034  1096 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 19:03:16.481  1034  1096 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 19:03:16.482  6966  6966 D BluetoothA2dp: Proxy object connected
08-26 19:03:16.482  6966  6966 D A2dpProfile: Bluetooth service connected
,08-26 19:03:16.484  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 19:03:16.485  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:16.485  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 19:03:16.486  1943  2127 D LGBluetoothAPIService: Message: 1
08-26 19:03:16.486  1943  2127 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 19:03:16.488  1034  1096 D BluetoothManagerService: Message: 40
08-26 19:03:16.488  1034  1096 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 19:03:16.491  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:16.491  1943  2127 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-26 19:03:16.492  7741  7741 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:16.492  7741  7741 D BluetoothMapService: STATE_ON
08-26 19:03:16.494  7741  7741 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 19:03:16.494  7741  7741 D LGBluetoothAPIServer: [BTUI] onBind()
,08-26 19:03:16.495  7741  7741 V BluetoothMapService: Handler(): got msg=1
08-26 19:03:16.497  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 19:03:16.497  1943  2127 D LGBluetoothAPIService: Message: 100
08-26 19:03:16.497  1943  2127 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 19:03:16.499  7741  7741 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 19:03:16.499  6966  6966 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 19:03:16.501  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 19:03:16.501  7741  8069 D BluetoothMapMasInstance: MAS initSocket()
08-26 19:03:16.501  7741  8069 D BluetoothMapMasInstance:   masId = 00
08-26 19:03:16.501  7741  8069 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 19:03:16.501  7741  8069 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 19:03:16.501  7741  8069 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 19:03:16.504  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:16.509  7741  8069 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:03:16.510  6966  6966 D DockEventReceiver: finishStartingService: stopping service
08-26 19:03:16.511  7741  8069 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 19:03:16.512  7741  8069 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 19:03:16.512  7741  8069 D BluetoothMapMasInstance: Accepting socket connection...
08-26 19:03:16.515  7741  7984 D BluetoothAdapterProperties: Scan Mode:21
08-26 19:03:16.516  7741  7984 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 19:03:16.518  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:16.518  7741  7741 V BluetoothPbapService: Pbap Service onCreate
08-26 19:03:16.518  7741  7741 V BluetoothPbapService: Starting PBAP service
08-26 19:03:16.520  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:16.521  7741  7741 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 19:03:16.521  7741  7741 V BluetoothPbapService: Pbap Service onBind
,08-26 19:03:16.523  7741  7741 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:16.524  6966  6966 D BluetoothPbap: Proxy object connected
08-26 19:03:16.524  6966  6966 D PbapServerProfile: Bluetooth service connected
08-26 19:03:16.524  7741  7741 V BluetoothPbapService: state: 12
08-26 19:03:16.524  7741  7741 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 19:03:16.524  7741  7741 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:16.525  7741  7741 V BluetoothPbapReceiver: ***********state = 12
08-26 19:03:16.526  7741  7741 V BluetoothPbapService: Handler(): got msg=1
08-26 19:03:16.526  7741  7741 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 19:03:16.528  2188  2188 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 19:03:16.528  7741  8071 V BluetoothPbapService: Pbap Service initSocket
08-26 19:03:16.528  2188  2188 D c       : Getting all permits...
08-26 19:03:16.528  2188  2188 D a       : Opening database...
08-26 19:03:16.528  1034  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:16.529  7741  8071 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:03:16.531  7741  8071 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 19:03:16.531  7741  8071 V BluetoothPbapService: Succeed to create listening socket 
08-26 19:03:16.531  7741  8071 V BluetoothPbapService: Accepting socket connection...
08-26 19:03:16.532  2188  2188 D a       : Opening database auth.proximity.permit_store...
,08-26 19:03:16.533  2188  2188 D a       : Closing database...
08-26 19:03:16.553  6966  6966 D BluetoothPermissionRequest: onReceive
,08-26 19:03:16.557  6966  6966 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 19:03:16.559  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 19:03:16.563  7741  7741 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 19:03:16.564  7741  7741 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-26 19:03:16.573  7741  7741 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-26 19:03:16.604  7741  7741 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 19:03:16.605  7741  7741 V BtOppService: onCreate
,08-26 19:03:16.610  7741  7741 V BluetoothOppNotification: send message
08-26 19:03:16.614  7741  7741 V BtOppService: Starting RfcommListener
08-26 19:03:16.623  7741  7741 D BluetoothOppPreference: Dumping Names:  
08-26 19:03:16.623  7741  7741 D BluetoothOppPreference: {}
08-26 19:03:16.623  7741  7741 D BluetoothOppPreference: Dumping Channels:  
,08-26 19:03:16.623  7741  7741 D BluetoothOppPreference: {}
08-26 19:03:16.626  7741  7741 V BtOppService: onStartCommand
08-26 19:03:16.630  7741  7741 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:16.630  7741  7741 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 19:03:16.632  7741  8083 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 19:03:16.635  7741  7741 V BluetoothOppNotification: new notify threadi!
,08-26 19:03:16.638  7741  7741 V BluetoothOppNotification: send delay message
08-26 19:03:16.640  7741  7741 V BtOppService: start RfcommListener
08-26 19:03:16.645  7741  8083 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 19:03:16.646  7741  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 19:03:16.646  7741  7741 V BtOppService: RfcommListener started
08-26 19:03:16.648  7741  8080 V BtOppService: Deleted complete outbound shares, number =  0
,08-26 19:03:16.656  7741  8085 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 19:03:16.657  1034  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:16.661  7741  8085 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:03:16.662  7741  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30d1a8bc on behalf of 
08-26 19:03:16.663  7741  8080 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 19:03:16.663  7741  8084 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 19:03:16.664  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:16.664  7741  8080 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 19:03:16.664  7741  7741 V BluetoothFtpService: Ftp Service onCreate
08-26 19:03:16.664  7741  7741 I BluetoothFtpService: Ftp Service onCreate
08-26 19:03:16.664  7741  7741 V BluetoothFtpService: Ftp Service onStartCommand
08-26 19:03:16.664  7741  7741 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:16.664  7741  8083 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3853639a on behalf of 
08-26 19:03:16.664  7741  7741 V BluetoothFtpService: Starting Listening on sockets
08-26 19:03:16.665  7741  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 19:03:16.665  7741  7741 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:03:16.665  7741  7741 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:03:16.665  7741  7741 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:03:16.665  7741  7741 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:16.665  7741  7741 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 19:03:16.665  7741  7741 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 19:03:16.666  7741  8080 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6f684cb on behalf of 
08-26 19:03:16.667  7741  8085 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-26 19:03:16.667  7741  8085 V BtOppRfcommListener: Started RFCOMM listener....
08-26 19:03:16.667  7741  8085 I BtOppRfcommListener: Accept thread started.
08-26 19:03:16.668  7741  8085 V BtOppRfcommListener: Accepting connection...
08-26 19:03:16.668  7741  7741 V BtOppService: ContentObserver received notification
08-26 19:03:16.668  7741  7741 V BtOppService: ContentObserver received notification
08-26 19:03:16.668  7741  7741 V BluetoothFtpService: Handler(): got msg=1
08-26 19:03:16.669  7741  7741 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 19:03:16.669  7741  7741 V BluetoothFtpService: Ftp Service initSocket
08-26 19:03:16.675  1034  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:16.676  7741  7741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:03:16.677  7741  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@136e94a8 on behalf of 
08-26 19:03:16.678  7741  8084 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 19:03:16.679  7741  7741 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-26 19:03:16.679  7741  7741 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 19:03:16.681  7741  8086 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-26 19:03:16.682  7741  8083 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 19:03:16.682  7741  8083 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 19:03:16.684  7741  8083 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1950abc1 on behalf of 
08-26 19:03:16.685  7741  8083 V BluetoothOppNotification: update too frequent, put in queue
08-26 19:03:16.686  7741  8083 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 19:03:16.687  7741  8084 V BluetoothOppNotification: outbound notification was removed.
,08-26 19:03:16.687  7741  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 19:03:16.690  7741  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33f41f66 on behalf of 
08-26 19:03:16.692  7741  8084 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 19:03:16.695  7741  8084 V BluetoothOppNotification: inbound notification was removed.
08-26 19:03:16.696  7741  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 19:03:16.699  7741  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f66a2a7 on behalf of 
,08-26 19:03:16.700  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@257b5a83
08-26 19:03:16.701  7741  7741 V BluetoothSapService: Sap Service onCreate
08-26 19:03:16.703  7741  7741 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:16.703  7741  7741 V BluetoothSapService: state: 12
08-26 19:03:16.704  7741  7741 V BluetoothSapService: Starting SAP server process
08-26 19:03:16.706  7741  7741 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 19:03:16.704  8087  8087 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:16.709  7741  8088 V BluetoothSapService: Sap Service initRfcommSocket
08-26 19:03:16.710  1034  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:16.712  7741  8088 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:03:16.704  8087  8087 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 19:03:16.715  7741  8088 V BluetoothSapService: Succeed to create listening socket 
08-26 19:03:16.715  7741  8088 V BluetoothSapService: Accepting socket connection...
08-26 19:03:16.720  8087  8087 V BT_SAP  : Event pipe created
,08-26 19:03:16.721  8087  8087 V BT_SAP  : create_server_socket qcom.sap.server
08-26 19:03:16.721  8087  8087 V BT_SAP  : created socket fd 6
08-26 19:03:17.039  6749  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:17.039  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:17.039  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:17.039  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:17.039  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:17.039  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:17.039  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:17.039  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:17.043  6749  6816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:17.046  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:17.046  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@db4361d added. We now have 8 listener(s)
08-26 19:03:17.047  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:17.050  1034  2013 D WifiServiceImplEx: setWifiEnabled: false pid=6749, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 19:03:17.051  1034  2013 D WifiService: setWifiEnabled: false pid=6749, uid=10118
08-26 19:03:17.051  1034  2013 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 19:03:17.063  6749  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:17.068  1034  2032 D WifiServiceImplEx: setWifiEnabled: true pid=6749, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 19:03:17.068  1034  2032 D WifiService: setWifiEnabled: true pid=6749, uid=10118
08-26 19:03:17.068  1034  2032 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 19:03:17.099  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 19:03:17.099  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 19:03:17.100  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 19:03:17.103  1034  1466 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-26 19:03:17.103  1034  1466 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-26 19:03:17.110  1034  1466 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-26 19:03:17.110  1034  1466 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 19:03:17.110  1034  1466 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 19:03:17.110  1034  1466 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 19:03:17.110  1034  1466 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 19:03:17.110  1034  1466 E WifiHW  : unknown target_country: EU , set to default
08-26 19:03:17.110  1034  1466 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 19:03:17.110  1034  1466 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 19:03:17.110  1034  1466 I WifiUtil: gEnableBmps=1
,08-26 19:03:17.640  7741  7741 V BluetoothOppNotification: new notify threadi!
,08-26 19:03:17.640  7741  7741 V BluetoothOppNotification: send delay message
,08-26 19:03:17.652  7741  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 19:03:17.675  7741  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38d0c243 on behalf of 
,08-26 19:03:17.678  7741  8108 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 19:03:17.679  7741  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 19:03:17.681  7741  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ee550c0 on behalf of 
08-26 19:03:17.681  7741  8108 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 19:03:17.683  7741  8108 V BluetoothOppNotification: outbound notification was removed.
08-26 19:03:17.683  7741  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 19:03:17.684  7741  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2abe11f9 on behalf of 
08-26 19:03:17.684  7741  8108 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 19:03:17.686  7741  8108 V BluetoothOppNotification: inbound notification was removed.
08-26 19:03:17.686  7741  8108 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 19:03:17.687  7741  8108 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bfdb53e on behalf of 
,08-26 19:03:17.810   313   894 D SoftapController: Softap fwReload - Ok
,08-26 19:03:17.915  1034  1466 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (795ms)
,08-26 19:03:17.921   313   894 D CommandListener: Setting iface cfg
08-26 19:03:17.922   313   894 D CommandListener: Trying to bring down wlan0
08-26 19:03:17.923   313   894 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:03:17.927  1034  1466 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-26 19:03:17.929  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 19:03:17.924  8126  8126 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 19:03:17.936  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 19:03:17.936  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 19:03:17.936  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 19:03:17.936  6966  6966 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 19:03:17.937  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 19:03:17.938  6966  6966 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 19:03:17.938  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 19:03:17.938  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 19:03:17.938  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 19:03:17.938  6966  6966 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 19:03:17.938  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-26 19:03:17.938  6966  6966 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 19:03:17.942  1034  1096 D Tethering: InitialState.processMessage what=4
08-26 19:03:17.943  1034  1096 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:03:17.924  8126  8126 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 19:03:17.948  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 19:03:17.948  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 19:03:17.948  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 19:03:17.948  6966  6966 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 19:03:17.949  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 19:03:17.950  6966  6966 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 19:03:17.950  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 19:03:17.950  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 19:03:17.950  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 19:03:17.950  6966  6966 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 19:03:17.950  6966  6966 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 19:03:17.956  8126  8126 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 19:03:17.989  8126  8126 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 19:03:17.989  8126  8126 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-26 19:03:18.028  1034  1466 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:03:18.028  1034  1466 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:03:18.028  1034  1466 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 19:03:18.029  1034  1466 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 19:03:18.029  1034  1466 D WifiMonitor: connecting to supplicant
08-26 19:03:18.030  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:18.030  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 19:03:18.033  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:18.072  1034  1092 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8127 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-26 19:03:18.073  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-26 19:03:18.108  8126  8126 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 19:03:18.138  8126  8126 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-26 19:03:18.145  1034  1466 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 19:03:18.145  8126  8126 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-26 19:03:18.145  1034  1466 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 19:03:18.146  1034  1466 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 19:03:18.146  1034  1466 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 19:03:18.147  1034  8145 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-26 19:03:18.147  1034  8145 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 19:03:18.147  1034  1466 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:18.147  1034  1466 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:18.148  1034  1466 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:18.148  1034  1466 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:18.149  1034  1466 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 19:03:18.149  1034  1466 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 19:03:18.149  1034  1466 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 19:03:18.149  1034  1466 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 19:03:18.149  1034  1466 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 19:03:18.150  1034  1466 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:03:18.150  1034  1466 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:03:18.150  1034  1466 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 19:03:18.150  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:18.151  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:18.151  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:18.151  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:18.151  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:03:18.152  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:18.152  1943  1943 D WfdService: Waiting for WifiP2p enabling
,08-26 19:03:18.154  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 19:03:18.154  1034  1531 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 19:03:18.155  1034  1466 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 19:03:18.157  1034  8145 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 19:03:18.158  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 19:03:18.158  8126  8126 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-26 19:03:18.158  1034  8145 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 19:03:18.158  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 19:03:18.158  1034  8145 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 19:03:18.158  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:18.158  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:18.158  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:18.158  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:18.158  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:18.158  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:18.158  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:18.158  6749  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:18.158  1034  8145 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 19:03:18.160  6749  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:18.161  1034  1466 D WifiNative-wlan0: SET update_config 1: returned true
08-26 19:03:18.161  1034  1466 D WifiConfigStore: Loading config and enabling all networks 
08-26 19:03:18.161  1034  1466 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 19:03:18.162  1034  1466 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 19:03:18.168  1034  1466 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-26 19:03:18.177  1034  1466 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 19:03:18.177  1034  1466 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 19:03:18.209  1034  1969 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8151 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 19:03:18.217  1034  1466 D WifiStateMachine: enableVerboseLogging : level 2
08-26 19:03:18.217  1034  1466 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 19:03:18.217  1034  1466 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 19:03:18.217  1034  1466 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 19:03:18.218  1034  1466 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 19:03:18.218  1034  1466 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 19:03:18.218  1034  1466 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 19:03:18.218  1034  1466 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 19:03:18.219  1034  1466 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 19:03:18.219  1034  1466 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 19:03:18.219  1034  1466 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 19:03:18.219  1034  1466 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 19:03:18.219  1034  1466 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 19:03:18.219  1034  1466 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 19:03:18.220  1034  1466 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 19:03:18.220  8127  8149 W FormManager: Network not available. Please check & try again.
08-26 19:03:18.220  1034  1466 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 19:03:18.220  1034  1466 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 19:03:18.221  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-26 19:03:18.221  1943  2348 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 19:03:18.221  1943  2348 D WfdsService: Set the WFDS Monitor: true
08-26 19:03:18.221  1943  2348 D WfdsMonitor: WfdsMonitorThread create
08-26 19:03:18.221  1034  1466 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 19:03:18.221  1034  1466 D WifiNative-HAL: Setting external_sim to 1
08-26 19:03:18.221  1034  1466 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 19:03:18.221  1943  2348 D WfdsMonitor: WFDS Monitor is created and started
08-26 19:03:18.221  1943  2348 D WfdsService: WiFi: Supplicant connection re-established
08-26 19:03:18.221  1034  1466 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 19:03:18.221  1034  1466 I WifiNative-HAL: startHal
08-26 19:03:18.221  1034  1466 D wifi    : setting scan oui 0xaf6d1160
08-26 19:03:18.222  1034  1466 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 19:03:18.222  1034  1466 I WifiNative-HAL: startHal
08-26 19:03:18.222  1034  1466 D wifi    : setting scan oui 0xaf6d1160
08-26 19:03:18.222  1034  1466 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 19:03:18.222  1034  1466 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 19:03:18.222  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
,08-26 19:03:18.223  8126  8126 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 19:03:18.223  1034  1466 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 19:03:18.223  7824  7824 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:18.223  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 19:03:18.223  8126  8126 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 19:03:18.224  1943  8166 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 19:03:18.224  1943  8166 E CtrlSupplicant: Succeed to open control connection
08-26 19:03:18.224  1943  8166 E CtrlSupplicant: Succeed to open monitor connection
08-26 19:03:18.225  1943  8166 D WfdsMonitor: Supplicant connection established
08-26 19:03:18.225  1943  2348 D WfdsService: Connected to the supplicant for wfds
08-26 19:03:18.225  1034  1466 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 19:03:18.225  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 19:03:18.225  8126  8126 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 19:03:18.226  1034  1466 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 19:03:18.226  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 19:03:18.226  8126  8126 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 19:03:18.226  1034  1466 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 19:03:18.226  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 19:03:18.226  8126  8126 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 19:03:18.226  1034  1466 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 19:03:18.226  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 19:03:18.227  8126  8126 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 19:03:18.227  1034  1466 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 19:03:18.227  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 19:03:18.227  8126  8126 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 19:03:18.227  1034  1466 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 19:03:18.228  1034  1466 E WifiNative: : [141,558,429 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 19:03:18.228  1034  1466 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 19:03:18.229  1034  1466 D WifiNative-wlan0: RECONNECT: returned true
08-26 19:03:18.229  1034  1466 D WifiNative-wlan0: doString: [STATUS]
08-26 19:03:18.229  8127  8150 V FormManager: Network unavailable.
08-26 19:03:18.229  1034  8145 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 19:03:18.229  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 19:03:18.229  1034  1466 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 19:03:18.229  1034  1466 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 19:03:18.230  1034  1466 D WifiNative-wlan0: SET ps 1: returned true
08-26 19:03:18.230  1034  1419 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.231   313   894 D CommandListener: Setting iface cfg
08-26 19:03:18.231   313   894 D CommandListener: Trying to bring up p2p0
08-26 19:03:18.232  1034  1419 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 19:03:18.232  1034  1419 D LGWifiP2pService: P2pEnablingState
08-26 19:03:18.232  1034  1419 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachi,ne$SmHandler }
08-26 19:03:18.232  1034  1419 D LGWifiP2pService: P2p socket connection successful
08-26 19:03:18.232  1034  1419 D LGWifiP2pService: P2pEnabledState
08-26 19:03:18.232  1034  1419 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 19:03:18.233  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 19:03:18.233  1943  1943 D WfdsService: WifiP2pState is changed : true
08-26 19:03:18.233  1034  1419 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 19:03:18.233  1943  2348 D WfdsService: Receive the WFDS_ENABLE Method
08-26 19:03:18.233  1943  2348 D WfdsService: Set the WFDS Monitor: true
08-26 19:03:18.233  1943  2348 D WfdsService: Connected to the supplicant for wfds
08-26 19:03:18.233  1943  2348 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 19:03:18.233  8126  8126 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 19:03:18.233  1943  2348 D WfdsService: selectPreferredScanChannel [36]
08-26 19:03:18.233  1943  2348 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 19:03:18.234  1034  1419 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 19:03:18.234  1034  1419 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 19:03:18.235  1034  1419 D WifiNative-p2p0: SET device_name G3: returned true
08-26 19:03:18.235  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 19:03:18.235  1943  1943 D WfdsService: isConnected: false
08-26 19:03:18.236  1034  1419 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 19:03:18.236  1034  1419 D LGWifiP2pService: before postfix = G3
08-26 19:03:18.236  1034  1419 D WifiServerServiceExt: postfix byte check : 2
08-26 19:03:18.236  1034  1419 D LGWifiP2pService: after postfix = G3
08-26 19:03:18.236  1034  1419 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 19:03:18.236  1034  1419 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 19:03:18.236  1034  1419 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 19:03:18.237  1034  1419 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 19:03:18.237  1034  1419 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 19:03:18.237  1034  1419 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 19:03:18.237  1034  1419 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 19:03:18.237  1034  1419 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 19:03:18.237  1034  1419 D WifiNative-HAL: p2pGetDeviceAddress
08-26 19:03:18.238  1034  1419 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,08-26 19:03:18.238  1034  1419 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 19:03:18.238  1034  1419 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 19:03:18.238  1034  1419 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 19:03:18.238  1034  1419 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 19:03:18.239  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 19:03:18.239  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 19:03:18.239  1943  1943 D WfdsService: Update P2p Interface State: 3
08-26 19:03:18.239  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
,08-26 19:03:18.239  1034  1466 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 19:03:18.239  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-26 19:03:18.240  1034  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.240  1034  1557 I WifiNative-HAL: startHal
08-26 19:03:18.240  1034  1466 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 19:03:18.240  1034  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.240  1034  1466 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 19:03:18.241  1034  1466 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 19:03:18.241  1034  1466 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 19:03:18.241  1034  1466 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 19:03:18.242  1034  1466 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 19:03:18.242  1034  1466 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 19:03:18.242  8126  8126 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 19:03:18.242  1034  1419 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 19:03:18.242  1034  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf6d1160
08-26 19:03:18.242  1034  1557 D wifi    : failed to get capabilities : -3
08-26 19:03:18.242  1034  1419 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 19:03:18.243  1034  1557 E WifiScanningService: could not get scan capabilities
08-26 19:03:18.243  1034  1466 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 19:03:18.243  1034  1419 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 19:03:18.243  1034  1419 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 19:03:18.243  1034  1466 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 19:03:18.243  1034  1466 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 19:03:18.243  1034  1466 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 19:03:18.245  8127  8150 V FormManager: Network unavailable.
,08-26 19:03:18.260  8126  8126 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 19:03:18.261  1034  1419 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 19:03:18.261  1034  1419 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 19:03:18.261  1034  1466 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=141591  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 19:03:18.261  1034  1419 D LGWifiP2pService: InactiveState
08-26 19:03:18.261  1034  1419 D LGWifiP2pService: InactiveState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.261  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.261  1034  1419 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 19:03:18.262  1034  1466 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=141592  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 19:03:18.262  8126  8126 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 19:03:18.262  1034  1466 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 19:03:18.262  1034  1466 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 19:03:18.262  8126  8126 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:03:18.262  1034  1466 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 19:03:18.263  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 19:03:18.263  8126  8126 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 19:03:18.263  8126  8126 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-26 19:03:18.263  1034  1419 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 19:03:18.263  1034  1419 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.263  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:18.263  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.263  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:18.263  1034  1419 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.263  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 19:03:18.263  1034  1419 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.263  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.264  1034  1419 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.264  8126  8126 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:18.264  1034  1419 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.264  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.264  1034  1419 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.264  1034  1419 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.264  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.264  1034  1419 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.265  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:18.265  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:18.265  1034  8145 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 19:03:18.265  1034  8145 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:03:18.265  1034  8145 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:03:18.265  1034  8145 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:03:18.265  1034  1034 E WifiServerServiceExt: No p2p device connected
08-26 19:03:18.265  1034  8145 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:18.265  1943  8166 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 19:03:18.265  1943  8166 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:18.265  1943  8166 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:18.265  1034  8145 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:18.265  1034  8145 E WifiMonitor: handleEvent 1,4  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:18.265  1034  8145 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:18.266  1034  8145 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:18.266  1034  8145 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:18.266  1034  8145 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:18.266  1034  8145 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:18.266  1943  2348 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 19:03:18.266  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:18.266  8126  8126 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 19:03:18.267  8126  8126 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:03:18.267  8126  8126 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 19:03:18.267  8126  8126 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:18.267  1943  8166 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:18.268  1034  1466 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 19:03:18.268  8126  8126 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:18.268  1943  8166 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:18.268  1034  1419 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.268  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.268  1034  1466 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 19:03:18.268  1034  8145 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 19:03:18.268  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:03:18.268  1034  8145 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:03:18.268  1034  8145 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:03:18.268  1034  8145 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:18.269  1034  8145 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:18.269  1034  8145 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:18.269  1034  8145 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:18.269  1034  1466 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 19:03:18.269  1034  8145 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:03:18.269  1034  8145 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:18.269  1034  8145 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:18.269  1034  8145 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:03:18.269  1034  1466 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 19:03:18.269  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 19:03:18.269  8126  8126 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 19:03:18.269  8126  8126 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 19:03:18.269  1034  8145 D WifiMon,itor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 19:03:18.269  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 19:03:18.270  1034  8145 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 19:03:18.270  1034  8145 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 19:03:18.270  1034  1466 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 19:03:18.270  1034  1466 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 19:03:18.271  1034  1466 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 19:03:18.271  1034  1466 D WifiNative-wlan0: doBoolean: SCAN
08-26 19:03:18.271  1034  1466 D WifiNative-wlan0: SCAN: returned false
08-26 19:03:18.271  1034  1466 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=141602  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 19:03:18.273  1034  1466 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=141603  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 19:03:18.273  1034  1466 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:03:18.274  1034  1466 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:03:18.274  1034  1466 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:03:18.274  1034  1466 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:03:18.277  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:18.277  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:18.277  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 19:03:18.278  1034  1466 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:03:18.280  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:03:18.280  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 19:03:18.286  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:18.286  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:18.287  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:18.294  8151  8151 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:03:18.296  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:03:18.300  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:18.301  1034  2057 I ActivityManager: Killing 7293:com.lge.drmservice/u0a62 (adj 15): empty #17
08-26 19:03:18.326  1034  2013 W libprocessgroup: failed to open /acct/uid_10062/pid_7293/cgroup.procs: No such file or directory
,08-26 19:03:18.346  8151  8151 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 19:03:18.351  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 19:03:18.362  8127  8173 W FormManager: Network not available. Please check & try again.
,08-26 19:03:18.368  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:18.369  8127  8174 V FormManager: Network unavailable.
08-26 19:03:18.386  8127  8174 V FormManager: Network unavailable.
,08-26 19:03:18.393  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 19:03:18.394  4795  4795 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:03:18.399  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:03:18.404  4795  4795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:03:18.418  4795  8175 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 19:03:18.426  4795  8176 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 19:03:18.426  4795  8176 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 19:03:18.470  1034  1942 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8177 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 19:03:18.497   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 515us total 23.343ms
,08-26 19:03:18.519   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 427us total 21.080ms
,08-26 19:03:18.540   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 416us total 20.177ms
,08-26 19:03:18.572  8177  8177 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 19:03:18.572  8177  8177 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 19:03:18.580  8177  8177 V [BNRBootReceiver]: Boot Receiver Return
08-26 19:03:18.580  8177  8177 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 19:03:18.630  1034  1907 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8195 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 19:03:18.631  1034  1907 I ActivityManager: Killing 7312:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-26 19:03:18.737  1034  1908 W libprocessgroup: failed to open /acct/uid_10085/pid_7312/cgroup.procs: No such file or directory
,08-26 19:03:18.774  8195  8195 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 19:03:18.800  8195  8195 D PluginManager: init()
,08-26 19:03:18.881  8126  8126 E wpa_supplicant: USIM:  scard_init function
08-26 19:03:18.882  8126  8126 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 19:03:18.882  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 19:03:18.883  1034  8145 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 19:03:18.883  1034  8145 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 19:03:18.883  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-26 19:03:18.883  1034  8145 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 19:03:18.886  1034  1466 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 19:03:18.887  1034  1466 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 19:03:18.888  1034  1466 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 19:03:18.888  1034  8145 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 19:03:18.888  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-26 19:03:18.889  1034  1466 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 19:03:18.889  1034  1466 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 19:03:18.907  1034  1466 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=142238  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 19:03:18.910  1034  1466 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=142241  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 19:03:18.911  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:18.911  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:18.912  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:18.912  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:18.912  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 19:03:18.912  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:18.914  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:03:18.914  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-26 19:03:18.998  8126  8126 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-26 19:03:18.998  1034  8145 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 19:03:18.998  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 19:03:18.999  1034  8145 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 19:03:18.999  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 19:03:19.000  1034  8145 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:03:19.000  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-26 19:03:19.002  1034  1466 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=142332  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 19:03:19.004  1034  1466 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=142334  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 19:03:19.006  1034  1466 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142336
08-26 19:03:19.008  1034  1466 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142338
08-26 19:03:19.008  1034  1466 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142339
08-26 19:03:19.010  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142340
08-26 19:03:19.010  1034  1466 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=142341
08-26 19:03:19.011  1034  1466 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=142341  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 19:03:19.013  1034  1466 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=142343  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 19:03:19.014  1034  1466 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:19.015  1034  1466 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:19.016  1034  1466 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:19.016  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:19.017  1034  1466 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:03:19.019  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:19.019  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:19.020  1034  8145 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:03:19.020  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:19.020  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:03:19.020  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:19.021  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 19:03:19.021  8126  8126 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 19:03:19.022  1034  8145 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 19:03:19.022  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 19:03:19.022  1034  8145 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 19:03:19.022  8126  8126 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 19:03:19.022  1034  1096 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 19:03:19.025  1034  8145 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 19:03:19.025  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 19:03:19.025  1034  8145 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 19:03:19.026  1034  8145 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:03:19.026  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:03:19.026  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:19.030  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:19.030  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:19.030  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 19:03:19.030  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:03:19.030  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 19:03:19.031  1034  1466 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=142362  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 19:03:19.032  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:03:19.032  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 19:03:19.032  1034  1466 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=142362  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 19:03:19.033  1034  1466 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=142363
08-26 19:03:19.033  1034  1466 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=142364
08-26 19:03:19.034  1034  1466 D WifiNative-wlan0: doString: [STATUS]
08-26 19:03:19.035  1034  8145 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:03:19.035  1034  8145 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-26 19:03:19.035  1034  1466 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-26 19:03:19.037  1034  1466 I WifiServiceExtension: setVHTCapabilityType  : false
08-26 19:03:19.046  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:19.046  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:19.047  1034  1466 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 19:03:19.047  1034  1466 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-26 19:03:19.048  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:03:19.051  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:19.051  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:19.051  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 19:03:19.058  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:19.058  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:03:19.058  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 19:03:19.061  1034  1466 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 19:03:19.061  1034  1544 D ConnectivityService: Got NetworkAgent Messenger
08-26 19:03:19.061  1034  1466 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:03:19.061  1034  1466 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 19:03:19.061  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 19:03:19.061  1034  1544 D ConnectivityService: NetworkAgent connected
08-26 19:03:19.061  1034  1466 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 19:03:19.061  1034  1466 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-26 19:03:19.068  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:19.068  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:19.069  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:19.070  1034  1466 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 19:03:19.070  1034  1466 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:03:19.070  1034  1466 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 19:03:19.070  1034  1466 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 19:03:19.070  1034  1466 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 19:03:19.071  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:19.071  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:19.072  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:19.077  1034  1466 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-26 19:03:19.079   313   894 D CommandListener: Setting iface cfg
08-26 19:03:19.082  1034  1466 E WifiStateMachine: Start Dhcp Watchdog 3
08-26 19:03:19.082  1034  8213 D DhcpStateMachine: StoppedState
08-26 19:03:19.082  1034  8213 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:19.082  1034  8213 D DhcpStateMachine: WaitBeforeStartState
08-26 19:03:19.083  1034  1466 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=142413  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-26 19:03:19.083  1034  1466 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=142413  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:03:19.084  1034  1466 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=142414  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:03:19.084  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:03:19.084  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 19:03:19.085  1034  1466 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=142415  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:03:19.085  1034  1466 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=142416  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:03:19.086  1034  1466 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=142416  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:03:19.087  1034  1466 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14242] from screen [on:0 period:-942783441] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 19:03:19.088  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-942783440] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 19:03:19.088  1034  1466 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 19:03:19.092  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:19.092  1034  1544 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-26 19:03:19.093  1034  1466 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 19:03:19.094  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 19:03:19.095  1034  1466 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:19.095  1034  1466 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:19.096  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 19:03:19.096  1034  1466 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:03:19.096  1034  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 19:03:19.097  1034  1466 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=117,0,0
08-26 19:03:19.097  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=117,0,0
08-26 19:03:19.097  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 19:03:19.097  8126  8126 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 19:03:19.098  1034  1466 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 19:03:19.098  1034  1466 D WifiNative-wlan0: doBoolean: SET ps 0
,08-26 19:03:19.098  1034  1466 D WifiNative-wlan0: SET ps 0: returned true
08-26 19:03:19.098  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 19:03:19.098  8126  8126 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 19:03:19.099  1034  1466 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 19:03:19.099  1034  1419 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@9c8ce2a target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:19.099  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@9c8ce2a target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:19.099  1034  1466 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 19:03:19.099  1034  8213 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:19.099  1034  1466 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 19:03:19.099  1034  8213 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 19:03:19.100  1034  1466 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 19:03:19.101   313   894 D CommandListener: Setting iface cfg
08-26 19:03:19.102   313   894 D CommandListener: Trying to bring up wlan0
08-26 19:03:19.102  1034  1466 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 19:03:19.103  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:03:19.103  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 19:03:19.104  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:03:19.104  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 19:03:19.105  1034  1466 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-26 19:03:19.105  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-26 19:03:19.105  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 19:03:19.106  8126  8126 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 19:03:19.106  1034  1419 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:19.106  1034  1419 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:19.106  1034  1466 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 19:03:19.106  1034  1466 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 19:03:19.106  8126  8126 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 19:03:19.107  1034  1466 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 19:03:19.107  1034  1466 D WifiNative-wlan0: doBoolean: SET ps 1
,08-26 19:03:19.112  6749  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-26 19:03:19.112  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:19.112  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:19.112  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:19.112  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:19.112  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:19.112  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:19.112  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:19.114  6749  6816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:19.120  6749  6816 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 19:03:19.120  6749  6816 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 19:03:19.124  6749  6816 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@175aa7d7 Bundle[{}]
08-26 19:03:19.125  6749  6816 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 19:03:19.125  6749  6816 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-26 19:03:19.126  6749  6816 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 19:03:19.126  1034  1466 D WifiNative-wlan0: SET ps 1: returned true
08-26 19:03:19.126  1034  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 19:03:19.126  6749  6816 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 19:03:19.127  1034  1466 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 19:03:19.127  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:03:19.127  6749  6816 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-26 19:03:19.127  1034  1466 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:03:19.128  1034  1466 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:03:19.128  6749  6816 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 19:03:19.128  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:03:19.128  1034  1466 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:03:19.129  1034  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 19:03:19.129  1034  1466 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 19:03:19.130  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 19:03:19.130  1034  1466 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 19:03:19.130  1034  1544 D ConnectivityService: ignoring duplicate network state non-change
08-26 19:03:19.132  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:19.132  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:19.135  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:19.135  1034  1544 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 19:03:19.136  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:19.136  1034  1544 D ConnectivityService: Adding iface wlan0 to network 102
08-26 19:03:19.136  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:19.136  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-26 19:03:19.139  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:19.139  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:19.139  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 19:03:19.143  1034  1466 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 19:03:19.144  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 19:03:19.147  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 19:03:19.148  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:19.148  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:19.148  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 19:03:19.149  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-26 19:03:19.154  1034  1544 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 19:03:19.154  1034  1544 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-26 19:03:19.155  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:19.155  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:03:19.155  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 19:03:19.155  1034  1544 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-26 19:03:19.156   313   894 E Netd    : netlink response contains error (File exists)
08-26 19:03:19.156  6749  6816 I System.out: Running OutgoingSocketThread
08-26 19:03:19.156  1034  1544 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-26 19:03:19.157  1034  1544 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 19:03:19.157  1034  1544 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-26 19:03:19.157  1034  1544 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-26 19:03:19.157  1034  1544 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 19:03:19.157  1034  1544 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 19:03:19.158  1034  1544 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-26 19:03:19.158  1034  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 19:03:19.158  1034  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:03:19.158  1034  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:19.158  6749  8216 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 896)
08-26 19:03:19.158  1034  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 19:03:19.158  1034  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:19.158  1034  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 19:03:19.158  1034  1544 D ConnectivityService: currentScore = 0, newScore = 20
08-26 19:03:19.158  1034  1544 D ConnectivityService:    accepting network in place of null
08-26 19:03:19.158  1034  1544 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:19.158  1034  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:19.158  1034  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 19:03:19.158  1034  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:19.158  1034  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 19:03:19.159  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:19.159  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:03:19.159  1034  1466 D WIFI    : new score 20, for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:19.159  1034  1466 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:03:19.160  1034  1544 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 19:03:19.161  1034  1544 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-26 19:03:19.161  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 19:03:19.161  6749  8216 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38459
08-26 19:03:19.161  6749  8216 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-26 19:03:19.161   313  8218 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 19:03:19.163  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:19.163  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 19:03:19.165  1034  1544 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:03:19.165  1034  1544 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 19:03:19.165  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:19.165  1034  1544 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 19:03:19.167  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 19:03:19.167  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 19:03:19.167  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 19:03:19.167  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 19:03:19.167  1034  1544 D ConnectivityService: validation of new default Network = false
08-26 19:03:19.167  1034  1544 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 19:03:19.167  1034  1544 D DSQN    : enableDataServiceNotify 
08-26 19:03:19.167  1034  1544 D DSQN    : start dsqn bin
08-26 19:03:19.168  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:19.169  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 19:03:19.169  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:19.172  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:19.172  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 19:03:19.172  1034  1405 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-26 19:03:19.172  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:03:19.179  1034  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 19:03:19.179  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:19.179  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:19.179  1034  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:19.179  1604  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 19:03:19.174  8219  8219 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:19.174  8219  8219 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:19.185  8219  8219 E DSQN    : DSQN ssw
08-26 19:03:19.200  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 19:03:19.201  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:19.201  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:19.223   313  8218 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-26 19:03:19.259   313  8218 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-26 19:03:19.291   313   893 D LGDataListener: argv[0]=dsqncommand
,08-26 19:03:19.291   313   893 D LGDataListener: argv[1]=wlan0
08-26 19:03:19.291   313   893 D LGDataListener: argv[2]=1
08-26 19:03:19.291   313   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 19:03:19.293  1034  1094 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 19:03:19.293  1034  1094 D DSQN    : start to monitor internet connection
,08-26 19:03:19.302  1034  8213 D DhcpStateMachine: DHCPV4 request on wlan0
08-26 19:03:19.302  1034  8213 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 19:03:19.302  1034  8213 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-26 19:03:19.304  8225  8225 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:19.304  8225  8225 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:03:19.306  8195  8195 W ExternalStrings: load override strings
08-26 19:03:19.306  8195  8195 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 19:03:19.306  8195  8195 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 19:03:19.312  8195  8195 D StatusProvider: onCreate
,08-26 19:03:19.324  1034  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 17:03:19 GMT], X-Android-Received-Millis=[1472230999324], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472230999290]}
08-26 19:03:19.325  1034  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 19:03:19.325  1034  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 19:03:19.326  1034  1544 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-26 19:03:19.326  8225  8225 I dhcpcd  : version 5.5.6 starting
08-26 19:03:19.326  1034  1544 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 19:03:19.326  1034  1544 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:03:19.326  1034  1544 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:19.326  1034  1544 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 19:03:19.326  1034  1544 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-26 19:03:19.327  1034  1544 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 19:03:19.327  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:19.327  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:19.327  1034  1544 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:19.327  1034  1544 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:19.328  1034  1544 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 19:03:19.329  1034  1466 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:19.329  1034  1466 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:03:19.329  1604  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 19:03:19.330  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:19.330  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 19:03:19.330  8225  8225 E dhcpcd  : get_duid: m
08-26 19:03:19.330  8225  8225 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 19:03:19.330  8225  8225 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 19:03:19.351  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 19:03:19.352  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:03:19.353  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:03:19.388  8195  8195 V Signer  : override build config not found
08-26 19:03:19.388  8195  8195 D Signer  : value of property debug is false
,08-26 19:03:19.418  8225  8225 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-26 19:03:19.418  8225  8225 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 19:03:19.418  8225  8225 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 19:03:19.419  8225  8225 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 19:03:19.419  8225  8225 D dhcpcd  : wlan0: sending REQUEST (xid 0xd5d06eee), next in 4.25 seconds
,08-26 19:03:19.440  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-26 19:03:19.440  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,08-26 19:03:19.440  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-26 19:03:19.441  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-26 19:03:19.441  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-26 19:03:19.441  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-26 19:03:19.441  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-26 19:03:19.442  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-26 19:03:19.442  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-26 19:03:19.442  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-26 19:03:19.442  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-26 19:03:19.443  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-26 19:03:19.443  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-26 19:03:19.457  8195  8195 V LGMDMManager: Create singleton instance
,08-26 19:03:19.510  8225  8225 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 19:03:19.513  8195  8195 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-26 19:03:19.525  8225  8225 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 19:03:19.525  8225  8225 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-26 19:03:19.526  8225  8225 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 19:03:19.526  8225  8225 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 19:03:19.526  8225  8225 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 19:03:19.527  8225  8225 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 19:03:19.527  8225  8225 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-26 19:03:19.528  8225  8225 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 19:03:19.620  8195  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:03:19.621  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:03:19.636  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:19.642  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:19.682  1034  1942 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8253 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-26 19:03:19.683  1034  1942 I ActivityManager: Killing 7339:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-26 19:03:19.810  8195  8238 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 19:03:19.905  1034  8213 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-26 19:03:19.908  1034  8213 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 19:03:19.908  1034  8213 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 19:03:19.909  1034  1734 W libprocessgroup: failed to open /acct/uid_10093/pid_7339/cgroup.procs: No such file or directory
08-26 19:03:19.912  1034  8213 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 19:03:19.912  1034  8213 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 19:03:19.912  1034  8213 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 19:03:19.912  1034  8213 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 19:03:19.912  1034  8213 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 19:03:19.913  1034  8213 D DhcpStateMachine: RunningState
,08-26 19:03:19.941  8253  8253 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 19:03:19.970  8253  8253 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-26 19:03:20.004  8253  8253 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-26 19:03:20.004  8253  8253 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 19:03:20.006  8253  8253 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 19:03:20.006  8253  8253 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 19:03:20.007  8253  8253 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-26 19:03:20.008  8253  8253 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 19:03:20.013  8253  8253 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 19:03:20.020  8253  8253 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 19:03:20.022  8253  8253 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:20.031  8195  8238 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:03:20.032  8195  8238 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:03:20.038  8253  8253 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 19:03:20.041  8253  8253 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 19:03:20.042  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.042  8195  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:03:20.045  8253  8253 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 19:03:20.050  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:20.056  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:20.063  8253  8253 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:20.063  8253  8253 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:03:20.064  8253  8253 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 19:03:20.067  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 19:03:20.069  6966  6966 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 19:03:20.071  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.072  8195  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:03:20.077  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:20.084  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:20.090  8253  8253 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:20.091  8253  8253 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:03:20.091  8253  8253 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:03:20.095  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 19:03:20.095  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 19:03:20.095  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 19:03:20.095  6966  6966 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 19:03:20.095  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 19:03:20.096  6966  6966 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 19:03:20.096  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 19:03:20.096  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 19:03:20.096  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 19:03:20.096  6966  6966 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 19:03:20.096  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-26 19:03:20.096  6966  6966 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 19:03:20.100  8195  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:03:20.100  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.105  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:20.112  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:20.117  8253  8253 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 19:03:20.117  8253  8253 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:20.118  8253  8253 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:03:20.120  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.121  8195  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:03:20.127  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:20.133  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:20.139  8253  8253 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:20.139  8253  8253 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:20.139  8253  8253 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:03:20.142  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:03:20.145  8195  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:03:20.148  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 19:03:20.153  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:20.159  8253  8253 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 19:03:20.159  8253  8253 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:20.160  8253  8253 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:03:20.162  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.163  6749  6816 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 897)
08-26 19:03:20.163  8195  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:03:20.163  6749  6816 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 897)
08-26 19:03:20.167  6749  6816 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 902)
08-26 19:03:20.168  6749  6816 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 19:03:20.168  6749  6816 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 903)
08-26 19:03:20.169  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 19:03:20.171  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:20.171  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35a61092 added. We now have 2 listener(s)
08-26 19:03:20.172  1034  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 19:03:20.176  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:03:20.176  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:20.176  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:20.176  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:20.176  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13adba63 added. We now have 9 listener(s)
08-26 19:03:20.176  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:20.179  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:03:20.181  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:03:20.182  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:20.185  6749  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:03:20.185  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:20.185  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:20.185  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:20.185  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:20.185  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:20.185  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:03:20.185  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:03:20.189  8253  8253 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:20.189  6749  6816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:20.189  6749  6816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:03:20.189  8253  8253 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:20.190  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:20.190  8253  8253 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:03:20.190  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20e31719 added. We now have 3 listener(s)
08-26 19:03:20.190  8195  8238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-26 19:03:20.192  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:20.193  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:20.197  1034  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:20.201  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:03:20.201  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:20.201  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 19:03:20.201  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:20.201  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2810a3de added. We now have 10 listener(s)
08-26 19:03:20.201  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:20.201  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:03:20.202  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:20.202  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:03:20.202  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:20.202  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.202  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:03:20.202  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:20.202  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35a61092 removed from the list
08-26 19:03:20.202  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:20.202  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13adba63 removed from the list
08-26 19:03:20.202  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:03:20.202  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.202  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.203  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.203  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:20.203  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:20.203  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:20.204  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13adba63 not in the list
08-26 19:03:20.204  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.204  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.205  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:20.205  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:20.205  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:20.205  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2810a3de removed from the list
08-26 19:03:20.205  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:20.205  6749  6816 W org.thaliproject,.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.205  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.205  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:20.205  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20e31719 removed from the list
08-26 19:03:20.206  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:20.206  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cb799bf added. We now have 2 listener(s)
08-26 19:03:20.206  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:20.209  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:03:20.209  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:20.209  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:20.209  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:20.209  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33bed88c added. We now have 9 listener(s)
08-26 19:03:20.209  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:20.209  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:03:20.210  8195  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:03:20.211  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.213  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:03:20.216  6749  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:03:20.216  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:20.216  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:20.216  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:20.216  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:20.216  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:20.216  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:03:20.216  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:03:20.219  6749  6816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:20.219  6749  6816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:03:20.219  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:20.219  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bff1fea added. We now have 3 listener(s)
08-26 19:03:20.220  1034  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:20.222  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:20.225  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:03:20.225  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:20.225  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:20.225  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:20.226  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@205612db added. We now have 10 listener(s)
08-26 19:03:20.226  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:20.226  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:03:20.226  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:03:20.226  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:03:20.226  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:03:20.226  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:03:20.226  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:20.227  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:03:20.228  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 19:03:20.229  1034  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:20.234  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:20.243  8253  8253 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:20.243  8253  8253 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:20.243  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:03:20.245  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 19:03:20.247  8195  8238 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-26 19:03:20.251  8253  8253 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:03:20.258  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:03:20.258  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.259  8195  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 19:03:20.260  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:03:20.265  6749  6816 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 19:03:20.266  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:20.266  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:03:20.269  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:03:20.270  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:20.270  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:03:20.270  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 19:03:20.270  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:20.270  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.270  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:03:20.270  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:20.270  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cb799bf removed from the list
08-26 19:03:20.270  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:03:20.270  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33bed88c removed from the list
08-26 19:03:20.270  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:03:20.270  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.270  8195  8238 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-26 19:03:20.273  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.273  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.274  8195  8238 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 19:03:20.274  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:20.274  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:20.274  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:20.274  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33bed88c not in the list
08-26 19:03:20.274  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.274  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.275  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:20.275  8195  8238 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 19:03:20.276  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:03:20.276  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:03:20.276  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:20.276  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:20.276  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@205612db removed from the list
08-26 19:03:20.276  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:20.276  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.276  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.276  8195  8238 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-26 19:03:20.276  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:20.276  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bff1fea removed from the list
08-26 19:03:20.276  8195  8238 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers,: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-26 19:03:20.277  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:20.277  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ea750b6 added. We now have 2 listener(s)
08-26 19:03:20.277  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:20.280  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:03:20.280  8195  8238 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-26 19:03:20.280  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:20.280  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:20.280  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:20.280  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a9901b7 added. We now have 9 listener(s)
08-26 19:03:20.280  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:20.280  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:03:20.282  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 19:03:20.282  8195  8238 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-26 19:03:20.287  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:03:20.292  6749  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:03:20.292  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:20.292  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:20.292  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:20.292  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:20.292  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:20.292  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:03:20.292  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:03:20.293  8253  8253 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:20.294  8253  8253 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:20.294  8253  8253 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:03:20.294  6749  6816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:20.295  6749  6816 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:03:20.295  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:20.295  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b73e08d added. We now have 3 listener(s)
,08-26 19:03:20.297  1034  2057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:20.298  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.299  8195  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:03:20.300  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:20.302  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:03:20.302  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:20.302  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:20.302  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:20.303  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cfc242 added. We now have 10 listener(s)
08-26 19:03:20.303  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:20.303  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:03:20.303  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:03:20.304  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:03:20.304  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:03:20.304  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:03:20.304  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:03:20.306  8151  8151 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 19:03:20.307  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:20.308  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 19:03:20.308  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:20.313  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 19:03:20.314  8151  8151 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:03:20.314  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 19:03:20.317  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 19:03:20.317  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:03:20.318  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:03:20.320  6749  6816 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 19:03:20.320  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:03:20.321  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:20.321  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:03:20.321  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:20.321  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.321  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:03:20.321  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:20.321  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ea750b6 removed from the list
08-26 19:03:20.321  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:20.321  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a9901b7 removed from the list
08-26 19:03:20.321  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:03:20.321  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.322  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.322  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.323  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:20.323  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:20.323  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:20.323  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a9901b7 not in the list
08-26 19:03:20.323  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.323  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.324  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:20.325  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:20.325  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:03:20.325  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:03:20.325  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:20.325  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:20.325  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cfc242 removed from the list
08-26 19:03:20.325  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:20.325  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: rel,ease: The given listener does not exist in the list - probably already removed
08-26 19:03:20.325  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.325  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:20.326  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b73e08d removed from the list
08-26 19:03:20.326  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:20.326  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecaf889 added. We now have 2 listener(s)
08-26 19:03:20.327  1034  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:20.330  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:03:20.330  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:20.330  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:20.330  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:20.330  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@271bc08e added. We now have 9 listener(s)
08-26 19:03:20.330  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:20.331  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:03:20.335  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:03:20.337  8253  8253 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:20.337  8253  8253 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:20.338  8253  8253 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 19:03:20.339  8253  8253 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 19:03:20.339  6749  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:03:20.339  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:20.339  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:20.339  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:20.339  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:20.339  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:20.339  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:03:20.339  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:03:20.339  8253  8253 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 19:03:20.341  6749  6816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:20.341  6749  6816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:03:20.342  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:20.342  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ef7cbc added. We now have 3 listener(s)
08-26 19:03:20.344  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:20.344  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:03:20.344  8195  8240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:03:20.345  1034  1600 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:03:20.346  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:20.349  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:03:20.349  8151  8151 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 19:03:20.349  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:20.349  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:20.349  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:20.349  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34619445 added. We now have 10 listener(s)
08-26 19:03:20.350  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:20.350  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:03:20.350  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:03:20.350  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:03:20.350  8151  8151 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:03:20.350  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:03:20.350  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:03:20.353  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 19:03:20.356  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 19:03:20.357  1034  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 19:03:20.363  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:03:20.364  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 19:03:20.365  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 19:03:20.368  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:03:20.370  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:03:20.371  8253  8253 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:03:20.372  8253  8253 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:03:20.372  8253  8253 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 19:03:20.372  6749  6816 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 19:03:20.374  8253  8253 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 19:03:20.375  8253  8253 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 19:03:20.376  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:03:20.376  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:20.376  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:03:20.377  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:20.377  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.377  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:03:20.377  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:20.377  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecaf889 removed from the list
08-26 19:03:20.377  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:20.377  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@271bc08e removed from the list
08-26 19:03:20.377  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:03:20.377  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.379  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.379  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.379  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-26 19:03:20.380  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:20.380  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:20.380  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:20.380  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@271bc08e not in the list
08-26 19:03:20.380  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.380  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.381  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:20.382  6749  6816 D BluetoothLeScanner: could not find callback wrapper
08-26 19:03:20.382  6749  6816 D org.thalipro,ject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:03:20.382  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:20.382  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:20.382  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34619445 removed from the list
08-26 19:03:20.382  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:20.382  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.382  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.382  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:20.382  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ef7cbc removed from the list
08-26 19:03:20.383  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:20.383  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e95a8a8 added. We now have 2 listener(s)
08-26 19:03:20.383  1034  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 19:03:20.386  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:03:20.386  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:20.386  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:20.386  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:20.387  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@190c2fc1 added. We now have 9 listener(s)
08-26 19:03:20.387  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:20.387  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:03:20.389  8253  8253 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 19:03:20.390  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:03:20.391  8253  8253 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 19:03:20.392  8253  8253 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-26 19:03:20.394  6749  6816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:03:20.394  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:20.394  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:03:20.394  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:20.394  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:20.394  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:20.394  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:03:20.394  6749  6816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:03:20.396  6749  6816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:20.396  6749  6816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:03:20.396  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:20.396  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28b7c6a7 added. We now have 3 listener(s)
08-26 19:03:20.396  1034  1600 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 19:03:20.400  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:20.402  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:20.403  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:03:20.403  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:20.403  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:20.404  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:03:20.404  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f0a754 added. We now have 10 listener(s)
08-26 19:03:20.404  6749  6816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:20.404  6749  6816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:03:20.404  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:20.404  6749  6816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:03:20.405  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:20.405  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.405  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:03:20.405  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:20.405  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e95a8a8 removed from the list
08-26 19:03:20.405  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:20.405  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@190c2fc1 removed from the list
08-26 19:03:20.405  6749  6816 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:03:20.405  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.405  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.406  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.406  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:20.406  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:20.406  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:20.407  6749  6816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@190c2fc1 not in the list
08-26 19:03:20.407  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:20.407  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.407  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:20.407  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:20.408  6749  6816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:20.408  6749  6816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20f0a754 removed from the list
08-26 19:03:20.408  6749  6816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:20.408  6749  6816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - pro,bably already removed
08-26 19:03:20.408  6749  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:20.408  6749  6816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:20.408  6749  6816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28b7c6a7 removed from the list
08-26 19:03:20.410  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 19:03:20.410  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 19:03:20.410  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-26 19:03:20.411  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:03:20.411  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 19:03:20.411  6749  6816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:20.423  6749  8307 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 910, name: My test thread name)
08-26 19:03:20.423  6749  8307 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 910, thread name: My test thread name)
08-26 19:03:20.424  6749  8307 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 910, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 19:03:20.426  6749  8308 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 912, name: My test thread name)
08-26 19:03:20.427  6749  8308 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 912, thread name: My test thread name)
08-26 19:03:20.427  6749  8308 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 912, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 19:03:20.431  6749  6816 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 19:03:20.431  6749  6816 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 19:03:20.431  6749  6816 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 19:03:20.431  6749  6816 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 19:03:20.431  6749  6816 D com.test.thalitest.ThaliTestRunner: Total duration: 23985 ms
08-26 19:03:20.433  6749  6816 I jxcore-log: *Native tests were executed*
08-26 19:03:20.433  6749  6816 I jxcore-log: 
08-26 19:03:20.433  6749  6816 I jxcore-log: Total number of executed tests:  80
08-26 19:03:20.433  6749  6816 I jxcore-log: 
08-26 19:03:20.433  6749  6816 I jxcore-log: Number of passed tests:  80
08-26 19:03:20.433  6749  6816 I jxcore-log: 
08-26 19:03:20.434  6749  6816 I jxcore-log: Number of failed tests:  0
08-26 19:03:20.434  6749  6816 I jxcore-log: 
08-26 19:03:20.434  6749  6816 I jxcore-log: Number of ignored tests:  0
08-26 19:03:20.434  6749  6816 I jxcore-log: 
08-26 19:03:20.434  6749  6816 I jxcore-log: Total duration:  23985
08-26 19:03:20.434  6749  6816 I jxcore-log: 
08-26 19:03:20.435  6749  6816 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 19:03:20.435  6749  6816 I jxcore-log: 
08-26 19:03:20.440  8253  8253 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 19:03:20.441  8253  8253 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 19:03:20.442  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:20.442  6749  6816 I jxcore-log: 
08-26 19:03:20.447  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:20.447  6749  6816 I jxcore-log: 
08-26 19:03:20.447  8253  8253 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-26 19:03:20.448  8253  8253 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 19:03:20.448  8253  8253 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-26 19:03:20.448  8253  8253 V SoundPool: doLoad: loading sample sampleID=1
08-26 19:03:20.448  6749  6749 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 19:03:20.449  8253  8253 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 19:03:20.449  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:20.449  6749  6816 I jxcore-log: 
08-26 19:03:20.449  8253  8312 V SoundPool: Start decode
08-26 19:03:20.449  8253  8312 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 19:03:20.450  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:20.450  6749  6816 I jxcore-log: 
08-26 19:03:20.450   318  2152 V MediaPlayerService: decode(23, 10857164, 17813)
08-26 19:03:20.450   318  2152 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 19:03:20.450   318  2152 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 19:03:20.450   318  2152 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 19:03:20.450   318  2152 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 19:03:20.451   318  2152 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 19:03:20.451   318  2152 V MediaPlayerService: player type = 3
08-26 19:03:20.451   318  2152 V AwesomePlayer: AwesomePlayer create()
08-26 19:03:20.451   318  2152 V AwesomePlayer: reset_l() 
,08-26 19:03:20.451   318  2152 V AwesomePlayer: cancelPlayerEvents
08-26 19:03:20.451   318  2152 V AwesomePlayer: setAudioSink() 
08-26 19:03:20.451   318  2152 V AwesomePlayer: reset_l() 
08-26 19:03:20.451   318  2152 V AudioCache: notify(0xb0409880, 8, 0, 0)
08-26 19:03:20.451   318  2152 V AudioCache: ignored
08-26 19:03:20.451  7787  7787 D UEI.SmartControl: QS Service created
08-26 19:03:20.451   318  2152 V AwesomePlayer: cancelPlayerEvents
08-26 19:03:20.452  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:20.452  6749  6816 I jxcore-log: 
08-26 19:03:20.452   318  2152 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 19:03:20.452   318  2152 V AwesomePlayer: setDataSource_l dataSource
08-26 19:03:20.452   318  2152 V LGParserOSAL: SniffLGParser start
08-26 19:03:20.452   318  2152 V LGParserOSAL: MainType:5, SubType=0
08-26 19:03:20.452   318  2152 V LGParserOSAL: #### check Mime : application/ogg
08-26 19:03:20.452   318  2152 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 19:03:20.452   318  2152 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 19:03:20.454  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:03:20.454  6749  6816 I jxcore-log: 
08-26 19:03:20.458  8253  8253 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-26 19:03:20.459  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:20.459  6749  6816 I jxcore-log: 
08-26 19:03:20.461  8253  8253 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 19:03:20.461  8253  8253 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 19:03:20.462  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:03:20.462  6749  6816 I jxcore-log: 
08-26 19:03:20.464  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:20.464  6749  6816 I jxcore-log: 
08-26 19:03:20.466  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:20.466  6749  6816 I jxcore-log: 
08-26 19:03:20.467  7787  7787 I UEI.SmartControl: Service initServices...
,08-26 19:03:20.467  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:03:20.467  6749  6816 I jxcore-log: 
08-26 19:03:20.467  7787  7787 D UEI.SmartControl: QS start get config
08-26 19:03:20.469  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:03:20.469  6749  6816 I jxcore-log: 
08-26 19:03:20.471  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:03:20.471  6749  6816 I jxcore-log: 
08-26 19:03:20.472  8253  8253 V LGMDMManager: Create singleton instance
08-26 19:03:20.472  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:20.472  6749  6816 I jxcore-log: 
08-26 19:03:20.474  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:20.474  6749  6816 I jxcore-log: 
08-26 19:03:20.475  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:03:20.475  6749  6816 I jxcore-log: 
08-26 19:03:20.476  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:03:20.476  6749  6816 I jxcore-log: 
08-26 19:03:20.477  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:20.477  6749  6816 I jxcore-log: 
08-26 19:03:20.478  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:20.478  6749  6816 I jxcore-log: 
08-26 19:03:20.479  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:03:20.479  6749  6816 I jxcore-log: 
08-26 19:03:20.480  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:03:20.480  6749  6816 I jxcore-log: 
08-26 19:03:20.481  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:03:20.481  6749  6816 I jxcore-log: 
08-26 19:03:20.482  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:03:20.482  6749  6816 I jxcore-log: 
08-26 19:03:20.483  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:20.483  6749  6816 I jxcore-log: 
08-26 19:03:20.484  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:20.484  6749  6816 I jxcore-log: 
08-26 19:03:20.485  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:20.485  6749  6816 I jxcore-log: 
08-26 19:03:20.486  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:20.486  674,9  6816 I jxcore-log: 
08-26 19:03:20.486  6749  6816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:20.486  6749  6816 I jxcore-log: 
08-26 19:03:20.496   318  2152 V LGParserOSAL: supported mime: application/ogg
08-26 19:03:20.496   318  2152 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 19:03:20.496   318  2152 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 19:03:20.496   318  2152 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 19:03:20.496   318  2152 V AwesomePlayer: AudioTrack Setting
08-26 19:03:20.496   318  2152 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 19:03:20.496   318  2152 V AwesomePlayer: setAudioSource() 
08-26 19:03:20.496   318  2152 V MediaPlayerService: prepare
08-26 19:03:20.496   318  2152 V AwesomePlayer: prepareAsync_l() 
08-26 19:03:20.496   318  2152 V MediaPlayerService: wait for prepare
08-26 19:03:20.496   318  8313 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 19:03:20.496   318  8313 V AwesomePlayer: initAudioDecoder() 
,08-26 19:03:20.496   318  8313 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 19:03:20.496   318  8313 V AudioSystem: isOffloadSupported()
08-26 19:03:20.496   318  8313 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 19:03:20.496   318  8313 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 19:03:20.496   318  8313 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 19:03:20.497   318  8313 V AwesomePlayer: getUseOffload() = 0 
08-26 19:03:20.497   318  8313 V OMXCodec: OMXCodec::Create
08-26 19:03:20.497   318  8313 V OMXCodec: findMatchingCodecs()
08-26 19:03:20.497   318  8313 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 19:03:20.497   318  8313 V OMXCodec: matchingCodecs.size()=1
08-26 19:03:20.497   318  8313 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-26 19:03:20.498   318  8313 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 19:03:20.498   318  8313 V LGCodecAdapter: LG Codec Adapter start
08-26 19:03:20.498   318  8313 V OMXCodec: OMXCodec Createtor
08-26 19:03:20.498   318  8313 V OMXCodec: setComponentRole
08-26 19:03:20.498   318  8313 V OMXCodec: configureCodec protected=0
08-26 19:03:20.498   318  8313 V LGCodecAdapter: called getLGCodecSpecificData
08-26 19:03:20.498   318  8313 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 19:03:20.498   318  8313 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 19:03:20.498   318  8313 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 19:03:20.498   318  8313 V LGCodecOSAL: Not support LGCodec
08-26 19:03:20.499   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 19:03:20.499   318  8313 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 19:03:20.499   318  8313 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 19:03:20.499   318  8313 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 19:03:20.499   318  8313 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 19:03:20.499   318  8313 V AudioSystem: isOffloadSupported()
08-26 19:03:20.499   318  8313 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 19:03:20.499   318  8313 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 19:03:20.499   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 19:03:20.499   318  8313 V OMXCodec: init()
08-26 19:03:20.499   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 19:03:20.499   318  8313 V OMXCodec: allocateBuffers
08-26 19:03:20.499   318  8313 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 19:03:20.499   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 19:03:20.499   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
08-26 19:03:20.499   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-26 19:03:20.499   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-26 19:03:20.499   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-26 19:03:20.499   318  8313 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 19:03:20.499   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 bu,ffers of size 32768 on output port
08-26 19:03:20.500   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-26 19:03:20.500   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-26 19:03:20.500   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-26 19:03:20.500   318  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-26 19:03:20.500   318  8313 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 19:03:20.500   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 19:03:20.500   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 19:03:20.500   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 19:03:20.500   318  8313 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 19:03:20.500   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 19:03:20.500   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 19:03:20.500   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-26 19:03:20.501   318  8313 V OMXCodec: init() mAsyncCompletion wait free! 
08-26 19:03:20.501   318  8313 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 19:03:20.501   318  8313 V AudioCache: notify(0xb0409880, 5, 0, 0)
08-26 19:03:20.501   318  8313 V AudioCache: ignored
08-26 19:03:20.501   318  8313 V AudioCache: notify(0xb0409880, 1, 0, 0)
08-26 19:03:20.501   318  8313 V AudioCache: prepared
08-26 19:03:20.501   318  2152 V AudioCache: wait - success
08-26 19:03:20.501   318  2152 V MediaPlayerService: start
08-26 19:03:20.501   318  2152 V AwesomePlayer: play_l() 
08-26 19:03:20.501   318  2152 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 19:03:20.501   318  2152 V AwesomePlayer: createAudioPlayer_l
08-26 19:03:20.501   318  2152 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 19:03:20.501   318  2152 V AwesomePlayer: startAudioPlayer_l() 
08-26 19:03:20.501   318  2152 D AudioPlayer: start of Playback, useOffload 0
08-26 19:03:20.501   318  2152 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 19:03:20.501   318  2152 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 19:03:20.503   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 19:03:20.503   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 19:03:20.503   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 19:03:20.503   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 19:03:20.503   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 19:03:20.503   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] initOu,tputFormat()
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-26 19:03:20.504   318  8315 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c4b50 on output port
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 19:03:20.504   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 19:03:20.506   318  2152 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 19:03:20.507   318  2152 V AudioCache: notify(0xb0409880, 6, 0, 0)
08-26 19:03:20.507   318  2152 V AudioCache: ignored
08-26 19:03:20.507   318  2152 V MediaPlayerService: wait for playback complete
08-26 19:03:20.507   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.507   318  8316 V AudioCache: memcpy(0xaf006000, 0xb1785000, 4096)
08-26 19:03:20.509   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.509   318  8316 V AudioCache: memcpy(0xaf007000, 0xb1785000, 4096)
08-26 19:03:20.509   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.509   318  8316 V AudioCache: memcpy(0xaf008000, 0xb1785000, 4096)
08-26 19:03:20.510   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.511   318  8316 V AudioCache: memcpy(0xaf009000, 0xb1785000, 4096)
08-26 19:03:20.511   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.511   318  8316 V AudioCache: memcpy(0xaf00a000, 0xb1785000, 4096)
08-26 19:03:20.511   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.511   318  8316 V AudioCache: memcpy(0xaf00b000, 0xb1785000, 4096)
08-26 19:03:20.511   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.511   318  8316 V AudioCache: memcpy(0xaf00c000, 0xb1785000, 4096)
08-26 19:03:20.513   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.513   318  8316 V AudioCache: memcpy(0xaf00d000, 0xb1785000, 4096)
08-26 19:03:20.513   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.513   318  8316 V AudioCache: memcpy(0xaf00e000, 0xb1785000, 4096)
08-26 19:03:20.514   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.514   318  8316 V AudioCache: memcpy(0xaf00f000, 0xb1785000, 4096)
08-26 19:03:20.515   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.515   318  8316 V AudioCache: memcpy(0xaf010000, 0xb1785000, 4096)
08-26 19:03:20.515   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.515   318  8316 V AudioCache: memcpy(0xaf011000, 0xb1785000, 4096)
08-26 19:03:20.516   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.516   318  8316 V AudioCache: memcpy(0xaf012000, 0xb1785000, 4096)
08-26 19:03:20.517   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.517   318  8316 V AudioCache: memcpy(0xaf013000, 0xb1785000, 4096)
08-26 19:03:20.521   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.521   318  8316 V AudioCache: memcpy(0xaf014000, 0xb1785000, 4096)
08-26 19:03:20.522   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.522   318  8316 V AudioCache: memcpy(0xaf015000, 0xb1785000, 4096)
08-26 19:03:20.522   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.522   318  8316 V AudioCache: memcpy(0xaf016000, 0xb1785000, 4096)
08-26 19:03:20.523   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.523   318  8316 V AudioCache: memcpy(0xaf017000, 0xb1785000, 4096)
08-26 19:03:20.523   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.523   318  8316 V AudioCache: memcpy(0xaf018000, 0xb1785000, 4096)
08-26 19:03:20.524   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.524   318  8316 V AudioCache: memcpy(0xaf019000, 0xb1785000, 4096)
08-26 19:03:20.524   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.524   318  8316 V AudioCache: memcpy(0xaf01a000, 0xb1785000, 4096)
08-26 19:03:20.525   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.525   318  8316 V AudioCache: memcpy(0xaf01b000, 0xb1785000, 4096)
08-26 19:03:20.526   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.526   318  8316 V AudioCache: memcpy(0xaf01c000, 0xb1785000, 4096)
08-26 19:03:20.526   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.526   318  8316 V AudioCache: memcpy(0xaf01d000, 0xb1785000, 4096)
08-26 19:03:20.526   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.526   318  8316 V AudioCache: memcpy(0xaf01e000, 0xb1785000, 4096)
08-26 19:03:20.527   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.527   318  8316 V AudioCache: memcpy(0xaf01f000, 0xb1785000, 4096)
08-26 19:03:20.527   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.527   318  8316 V AudioCache: memcpy(0xaf020000, 0xb1785000, 4096)
08-26 19:03:20.528   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.528   318  8316 V AudioCache: memcpy(0xaf021000, 0xb1785000, 4096)
08-26 19:03:20.528   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.528   318  8316 V AudioCache: memcpy(0xaf022000, 0xb1785000, 4096)
08-26 19:03:20.529   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.529   318  8316 V AudioCache: memcpy(0xaf023000, 0xb1785000, 4096)
08-26 19:03:20.529   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.529   318  8316 V AudioCache: memcpy(0xaf024000, 0xb1785000, 4096)
08-26 19:03:20.530   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.530   318  8316 V AudioCache: memcpy(0xaf025000, 0xb1785000, 4096)
08-26 19:03:20.530   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.530   318  8316 V AudioCache: memcpy(0xaf026000, 0xb1785000, 4096)
08-26 19:03:20.531   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.531   318  8316 V AudioCache: memcpy(0xaf027000, 0xb1785000, 4096)
08-26 19:03:20.531   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.531   318  8316 V AudioCache: memcpy(0xaf028000, 0xb1785000, 4096)
08-26 19:03:20.531   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.531   318  8316 V AudioCache: memcpy(0xaf029000, 0xb1785000, 4096)
08-26 19:03:20.532   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.532   318  8316 V AudioCache: memcpy(0xaf02a000, 0xb1785000, 4096)
08-26 19:03:20.532   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.532   318  8316 V AudioCache: memcpy(0xaf02b000, 0xb1785000, 4096)
08-26 19:03:20.533   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.533   318  8316 V AudioCache: memcpy(0xaf02c000, 0xb1785000, 4096)
08-26 19:03:20.533   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.533   318  8316 V AudioCache: memcpy(0xaf02d000, 0xb1785000, 4096)
08-26 19:03:20.534   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.534   318  8316 V AudioCache: memcpy(0xaf02e000, 0xb1785000, 4096)
08-26 19:03:20.534   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.534   318  8316 V AudioCache: memcpy(0xaf02f000, 0xb1785000, 4096)
08-26 19:03:20.534   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.534   318  8316 V AudioCache: memcpy(0xaf030000, 0xb1785000, 4096)
08-26 19:03:20.535   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.535   318  8316 V AudioCache: memcpy(0xaf031000, 0xb1785000, 4096)
08-26 19:03:20.535   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.535   318  8316 V AudioCache: memcpy(0xaf032000, 0xb1785000, 4096)
08-26 19:03:20.536   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.536   318  8316 V AudioCache: memcpy(0xaf033000, 0xb1785000, 4096)
08-26 19:03:20.536   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.536   318  8316 V AudioCache: memcpy(0xaf034000, 0xb1785000, 4096)
08-26 19:03:20.537   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.537   318  8316 V AudioCache: memcpy(0xaf035000, 0xb1785000, 4096)
08-26 19:03:20.537   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.537   318  8316 V AudioCache: memcpy(0xaf036000, 0xb1785000, 4096)
08-26 19:03:20.537   318  8316 V AudioCache: write(0xb1785000, 4096)
08-26 19:03:20.538   318  8316 V AudioCache: memcpy(0xaf037000, 0xb1785000, 4096)
08-26 19:03:20.538   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-26 19:03:20.538   318  8316 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 19:03:20.538   318  8316 V AwesomePlayer: postAudioEOS() 
08-26 19:03:20.538   318  8316 V AudioCache: write(0xb1785000, 280)
08-26 19:03:20.538   318  8316 V AudioCache: memcpy(0xaf038000, 0xb1785000, 280)
08-26 19:03:20.545   318  8313 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 19:03:20.545   318  8313 V AwesomePlayer: onStreamDone
08-26 19:03:20.545   318  8313 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 19:03:20.545   318  8313 V AudioCache: notify(0xb0409880, 2, 0, 0)
08-26 19:03:20.545   318  8313 V AudioCache: playback complete
08-26 19:03:20.545   318  8313 V AwesomePlayer: pause_l() 
08-26 19:03:20.545   318  8313 V AudioCache: notify(0xb0409880, 7, 0, 0)
08-26 19:03:20.545   318  2152 V AudioCache: wait - success
08-26 19:03:20.545   318  8313 V AudioCache: ignored
08-26 19:03:20.545   318  8313 V AwesomePlayer: cancelPlayerEvents
08-26 19:03:20.545   318  2152 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 19:03:20.545   318  8313 D AudioPlayer: Pause Playback at 1068125
08-26 19:03:20.546   318  2152 V AwesomePlayer: reset_l() 
08-26 19:03:20.546   318  2152 V AudioCache: notify(0xb0409880, 8, 0, 0)
08-26 19:03:20.546   318  2152 V AudioCache: ignored
08-26 19:03:20.546   318  2152 V AwesomePlayer: cancelPlayerEvents
08-26 19:03:20.546   318  2152 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-26 19:03:20.546   318  2152 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 19:03:20.546   318  2152 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 19:03:20.546   318  2152 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 19:03:20.546   318  2152 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c4b50 on port 1
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-26 19:03:20.546   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 19:03:20.547   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-26 19:03:20.547   318  2152 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 19:03:20.547   318  2152 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 19:03:20.547   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 19:03:20.547   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 19:03:20.547   318  8315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 19:03:20.547   318  2152 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 19:03:20.547   318  2152 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 19:03:20.547   318  2152 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 19:03:20.547  8253  8253 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 19:03:20.547   318  2152 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-26 19:03:20.547   318  2152 D AudioPlayer: AudioPlayer releasing audio source
08-26 19:03:20.547   318  2152 D AudioPlayer: AudioPlayer done releasing audio source
08-26 19:03:20.548   318  2152 V AwesomePlayer: reset_l() 
08-26 19:03:20.548   318  2152 V AwesomePlayer: cancelPlayerEvents
08-26 19:03:20.548   318  2152 V AwesomePlayer: ~AwesomePlayer call
08-26 19:03:20.548   318  2152 V AwesomePlayer: reset_l() 
08-26 19:03:20.548   318  2152 V AwesomePlayer: cancelPlayerEvents
08-26 19:03:20.548  8253  8312 V SoundPool: close(31)
08-26 19:03:20.548  8253  8312 V SoundPool: pointer = 0xa001b000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 19:03:20.550  8253  8253 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-26 19:03:20.552  8253  8253 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6834
08-26 19:03:20.554  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:03:20.579  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.584  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.586  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.587  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.588  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.590  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.592  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.594  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:03:20.596  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:03:20.683  8317  8317 D AndroidRuntime: 
08-26 19:03:20.683  8317  8317 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 19:03:20.686  8317  8317 D AndroidRuntime: CheckJNI is OFF
,08-26 19:03:20.767  1034  1466 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:03:20.767  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:03:20.768  1034  1466 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:03:20.768  1034  1466 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:03:20.769  1034  1466 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:03:20.769  1034  1466 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 19:03:20.772  1034  1544 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
,08-26 19:03:20.772  1034  1544 D ConnectivityService: identical MTU - not setting
08-26 19:03:20.773  1034  1544 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 19:03:20.773  1034  1544 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 19:03:20.773  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:03:20.773  1034  1544 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:20.774  1034  1544 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:03:20.774  1604  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-26 19:03:20.914  7787  7787 I UEI.SmartControl: Supports setup maps: true
,08-26 19:03:20.920  7787  7787 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 19:03:20.920  7787  7787 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 19:03:20.920  7787  7787 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 19:03:20.920  7787  7787 I UEI.SmartControl: ### init IR Blaster...
08-26 19:03:20.924  7787  7787 D serial_port: Configuring serial port
08-26 19:03:20.925  7787  7787 E UEI.SmartControl: UEIBLaster setting for 616
08-26 19:03:20.925  7787  7787 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 19:03:20.925  7787  7787 I UEI.SmartControl: configuring settings for MAXQ616
08-26 19:03:20.925  7787  7787 I UEI.SmartControl: Get version...
08-26 19:03:20.944  7787  8330 D UEI.SmartControl: serial port data available: 21
,08-26 19:03:20.948  8317  8317 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-26 19:03:20.964  1034  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-26 19:03:20.965  1034  1092 I ActivityManager: Killing 6749:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-26 19:03:20.970  7787  7787 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-26 19:03:20.970  7787  7787 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 19:03:20.970  7787  7787 I UEI.SmartControl: QS saving settings...
08-26 19:03:20.971  7787  7787 D UEI.SmartControl: IR Blaster version: 25672567
08-26 19:03:20.987  7787  8330 D UEI.SmartControl: serial port data available: 4
,08-26 19:03:21.016  7787  8335 I UEI.SmartControl: Device manager: loading config....
,08-26 19:03:21.018  7787  7787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 19:03:21.019  7787  8335 D UEI.SmartControl: ----------- loading internal config...
08-26 19:03:21.022  7787  8335 E UEI.SmartControl: Loading SETTINGS...
08-26 19:03:21.025  7787  8335 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 19:03:21.031  1034  1734 I WindowState: WIN DEATH: Window{3dbae447 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 19:03:21.032  1034  1541 D WifiService: Client connection lost with reason: 4
,08-26 19:03:21.036  7787  8334 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 19:03:21.036  7787  8334 D UEI.SmartControl: -----service ready thread exits
08-26 19:03:21.036  1034  1734 D InputDispatcher: Window went away: Window{3dbae447 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 19:03:21.097  1034  1092 I ActivityManager:   Force finishing activity ActivityRecord{20d9b580 u0 com.test.thalitest/.MainActivity t6}
,08-26 19:03:21.142   333   344 E GBMv2   : DFP En is all cleared set to be enabled
08-26 19:03:21.144  1034  1050 W ActivityManager: Spurious death for ProcessRecord{2460893a 6749:com.test.thalitest/u0a118}, curProc for 6749: null
,08-26 19:03:21.146  1034  1117 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-26 19:03:21.147  1034  1117 I ActivityManager:   Force finishing activity ActivityRecord{20d9b580 u0 com.test.thalitest/.MainActivity t6 f}
08-26 19:03:21.147  1034  1117 W ActivityManager: Duplicate finish request for ActivityRecord{20d9b580 u0 com.test.thalitest/.MainActivity t6 f}
08-26 19:03:21.150  7787  7787 E UEI.SmartControl: Services init done
08-26 19:03:21.151  7787  7787 D UEI.SmartControl: QS Service init finished
08-26 19:03:21.152  7787  7787 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 19:03:21.152  7787  7787 D UEI.SmartControl: QS Service version code: 201091
08-26 19:03:21.152  7787  7787 D UEI.SmartControl: Service requested: Control
,08-26 19:03:21.178  7787  7787 D UEI.SmartControl: Internal service binding...
08-26 19:03:21.179  2033  2033 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-26 19:03:21.181  2033  2033 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-26 19:03:21.184  8253  8253 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-26 19:03:21.189  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-26 19:03:21.190  2033  2139 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-26 19:03:21.191  7787  7802 I UEI.SmartControl: ------ IControl API: 11
08-26 19:03:21.191  7787  7802 D UEI.SmartControl: File observer start...
08-26 19:03:21.191  7787  7802 E UEI.SmartControl: IR Port is disabled: false
08-26 19:03:21.191  7787  7802 D UEI.SmartControl: Starting file observer...
08-26 19:03:21.193  1943  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-26 19:03:21.195  1943  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{39edd249 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 19:03:21.197  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-26 19:03:21.199  1905  1905 D ActionManagerService: notifyUserLog: 1000003
08-26 19:03:21.200  3804  4944 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-26 19:03:21.200  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{dcaf74e co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 19:03:21.202  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-26 19:03:21.204  7787  7802 I UEI.SmartControl: Registering callback...
,08-26 19:03:21.206  2033  2033 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-26 19:03:21.206  2033  2033 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-26 19:03:21.208  2033  2033 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-26 19:03:21.210  5086  5086 I art     : Explicit concurrent mark sweep GC freed 8204(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 551us total 46.254ms
08-26 19:03:21.211  7787  7803 I UEI.SmartControl: ------ IControl API: 19
08-26 19:03:21.212  7787  7803 I UEI.SmartControl: Registering Services Ready callback...
08-26 19:03:21.212  7787  7803 I UEI.SmartControl: Notify client services are ready...
08-26 19:03:21.212  8253  8269 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 19:03:21.213  8253  8310 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 19:03:21.213  8253  8310 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 19:03:21.213  8253  8253 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 19:03:21.213  8253  8253 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-26 19:03:21.215  7787  7802 I UEI.SmartControl: ------ IControl API: 8
08-26 19:03:21.216  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-26 19:03:21.217  8253  8253 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 19:03:21.217  8253  8253 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 19:03:21.218  8253  8253 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 19:03:21.218  8253  8253 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-26 19:03:21.221  8253  8253 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 19:03:21.221  8253  8253 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-26 19:03:21.224  1034  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 19:03:21.225  3804  3804 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-26 19:03:21.227  1996  1996 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-26 19:03:21.227  7741  7741 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-26 19:03:21.227  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 19:03:21.230  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-26 19:03:21.234  2508  2685 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 19:03:21.234  1905  1905 D ActionManagerService: notifyUserLog: 1000004
08-26 19:03:21.235  3804  4944 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-26 19:03:21.236  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-26 19:03:21.291  1034  1034 D administrator: Handling package changes for user 0
,08-26 19:03:21.293  8253  8253 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-26 19:03:21.294  4975  4975 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-26 19:03:21.294  4975  4975 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-26 19:03:21.294  4975  4975 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-26 19:03:21.294  4975  4975 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-26 19:03:21.294  4975  4975 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 19:03:21.296  1604  1659 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 19:03:21.296  1604  1659 D KeyguardModel: createShortcutInfo...
08-26 19:03:21.297  4975  4975 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 19:03:21.297  4975  4975 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 19:03:21.297  4975  4975 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 19:03:21.297  8253  8253 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-26 19:03:21.298  3804  3819 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 19:03:21.300  4975  4975 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:21.300  4975  4975 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:21.300  4975  4975 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 19:03:21.300  4975  4975 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-26 19:03:21.303  1818  1818 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-26 19:03:21.303  1604  1659 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 19:03:21.303  1604  1659 D KeyguardModel: createShortcutInfo...
08-26 19:03:21.308  1604  1659 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 19:03:21.308  1604  1659 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:03:21.309  1604  1659 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 19:03:21.310  1604  1659 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 19:03:21.313  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-26 19:03:21.313  1604  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 19:03:21.314  1604  1659 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 19:03:21.318  1604  1659 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 19:03:21.318  1604  1659 D KeyguardModel: createShortcutInfo...
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262123
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , display: false
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , animation: false }
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262287
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , display: false
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , animation: false }
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , create_time: 1472216588858
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , display: false
08-26 19:03:21.328  2033  2033 I GBoardWebViewUtils: , animation: false }
,08-26 19:03:21.334  1604  1659 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 19:03:21.334  1604  1659 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 19:03:21.335  1604  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 19:03:21.335  1604  1659 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 19:03:21.340  1604  1659 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 19:03:21.340  1604  1659 D KeyguardModel: createShortcutInfo...
,08-26 19:03:21.346  2188  2188 I ConfigService: onCreate
08-26 19:03:21.346  2188  2188 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-26 19:03:21.347  1604  1659 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:03:21.347  1604  1659 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 19:03:21.347  1604  1659 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 19:03:21.348  1604  1659 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 19:03:21.352  1818  1818 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-26 19:03:21.354  2188  2188 I ConfigService: onBind returning update interface
,08-26 19:03:21.355  1604  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 19:03:21.358  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-26 19:03:21.359  1870  1870 D SplitUIService: removed split : 
08-26 19:03:21.363  2188  2188 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-26 19:03:21.363  2188  2188 I ConfigService: onBind returning config service
08-26 19:03:21.368  1604  1659 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 19:03:21.371  1034  1734 V SIM_STK : Menu title from STK is T-Mobile
08-26 19:03:21.371  1034  1734 V SIM_STK : Menu title from STK is T-Mobile
08-26 19:03:21.373  2033  8347 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-26 19:03:21.374  2188  2188 I ConfigService: onDestroy
08-26 19:03:21.376  1034  1576 V SIM_STK : Menu title from STK is T-Mobile
,08-26 19:03:21.379  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-26 19:03:21.385  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-26 19:03:21.385  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-26 19:03:21.385  1604  1659 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 19:03:21.385  1604  1659 D KeyguardModel: createShortcutInfo...
08-26 19:03:21.389  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-26 19:03:21.389  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 19:03:21.390  1604  1659 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 19:03:21.390  1604  1659 D KeyguardModel: createShortcutInfo...
08-26 19:03:21.411  1604  1659 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 19:03:21.411  1604  1659 D KeyguardModel: createShortcutInfo...
,08-26 19:03:21.423  1604  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 19:03:21.424  1604  1659 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 19:03:21.430  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-26 19:03:21.430  1870  1870 I SplitUIService: split app #11
08-26 19:03:21.432  1604  1659 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 19:03:21.432  1604  1659 D KeyguardModel: createShortcutInfo...
08-26 19:03:21.434  1604  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 19:03:21.434  1604  1659 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-26 19:03:21.435  1604  1659 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 19:03:21.435  1604  1659 D KeyguardModel: createShortcutInfo...
08-26 19:03:21.436  1604  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 19:03:21.436  1604  1659 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 19:03:21.439  1604  1659 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 19:03:21.439  1604  1659 D KeyguardModel: createShortcutInfo...
08-26 19:03:21.440  1818  8350 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-26 19:03:21.459  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-26 19:03:21.469  1034  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 19:03:21.470  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 19:03:21.470  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 19:03:21.470  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 19:03:21.470  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 19:03:21.470  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 19:03:21.470  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 19:03:21.470  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 19:03:21.470  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 19:03:21.470  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 19:03:21.470  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 19:03:21.470  7741  7741 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 19:03:21.472  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-26 19:03:21.472  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 19:03:21.475  7186  7186 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-26 19:03:21.507  1034  2013 I ActivityManager: Killing 7383:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-26 19:03:21.525  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-26 19:03:21.528  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 19:03:21.529  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-26 19:03:21.531  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-26 19:03:21.532  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-26 19:03:21.533  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-26 19:03:21.543  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-26 19:03:21.543  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 19:03:21.543  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 19:03:21.548  2033  2033 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-26 19:03:21.557  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-26 19:03:21.557  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 19:03:21.561  2033  2177 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-26 19:03:21.561  2033  2177 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-26 19:03:21.580  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-26 19:03:21.581  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 19:03:21.581  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 19:03:21.593  2033  2033 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-26 19:03:21.610  1034  1978 W libprocessgroup: failed to open /acct/uid_10005/pid_7383/cgroup.procs: No such file or directory
,08-26 19:03:21.612  1034  1051 V SIM_STK : Menu title from STK is T-Mobile
08-26 19:03:21.614  2583  2583 D [Concierge]Service: onStartCommand(). Type : 8
08-26 19:03:21.614  2583  2583 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-26 19:03:21.616  2583  2583 D [Concierge]Service: Update widget ID : 11
08-26 19:03:21.617  2033  2033 D [Concierge]WidgetView: change position of spinner
08-26 19:03:21.618  1034  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-26 19:03:21.618  2033  2033 I [Concierge]WidgetView: initWebView(). Time : 1472231001618
08-26 19:03:21.619  2583  2583 D [Concierge]Service: onStartCommand(). Type : 0
08-26 19:03:21.621  5883  8360 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-26 19:03:21.623  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{206fe368 u0 com.lge.launcher2/.Launcher t5} time:144968
,08-26 19:03:21.625  1818  8361 I PeopleContactsSync: CP2 sync disabled
08-26 19:03:21.628  1034  1117 I art     : Explicit concurrent mark sweep GC freed 83727(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.525ms total 322.797ms
08-26 19:03:21.628  1034  1047 I art     : WaitForGcToComplete blocked for 203.410ms for cause HeapTrim
08-26 19:03:21.634  1818  5257 I Icing   : doRemovePackageData com.test.thalitest
08-26 19:03:21.642  2334  8362 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 19:03:21.662  8317  8317 D AndroidRuntime: Shutting down VM
,08-26 19:03:21.668  1034  2013 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8363 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-26 19:03:21.679  2033  2033 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 834835176
08-26 19:03:21.680  2033  2033 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
,08-26 19:03:21.680  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 19:03:21.682  2033  2033 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@29cd5881
08-26 19:03:21.683  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-26 19:03:21.684  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 19:03:21.684  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 19:03:21.689  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-26 19:03:21.690  2033  2033 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-26 19:03:21.690  2033  2033 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 19:03:21.690  2033  2033 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472230885903, New one : 1472231001618
08-26 19:03:21.690  2033  2033 D [Concierge]WidgetView: Unregister all receivers
08-26 19:03:21.691  2033  2033 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-26 19:03:21.691  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 19:03:21.693  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-26 19:03:21.694  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-26 19:03:21.695  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-26 19:03:21.695  1818  8356 W GmsApplication: Using Auth Proxy for data requests.
08-26 19:03:21.696  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-26 19:03:21.697  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-26 19:03:21.700  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 19:03:21.701  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 19:03:21.726  2188  2317 I art     : Explicit concurrent mark sweep GC freed 6442(382KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 829us total 26.132ms
,08-26 19:03:21.729  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 19:03:21.732  1818  8356 W GmsApplication: Using Auth Proxy for data requests.
08-26 19:03:21.737  2033  2033 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-26 19:03:21.737  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-26 19:03:21.738  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 19:03:21.759  2033  2033 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1807e56d time:145104
,08-26 19:03:21.768  8363  8363 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:03:21.769  8363  8363 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 19:03:21.770  8363  8363 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 19:03:21.771  8363  8363 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 19:03:21.833  8363  8363 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-26 19:03:21.841  8363  8363 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-26 19:03:21.876  8363  8363 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 19:03:21.896  8363  8363 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 19:03:21.897  8363  8363 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:03:21.924  1034  1117 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8385 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-26 19:03:21.962  8363  8363 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-26 19:03:21.973  2033  2033 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-26 19:03:21.979  1034  1576 I ActivityManager: Killing 7824:com.google.android.talk/u0a72 (adj 15): empty #17
,08-26 19:03:21.983  1034  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-26 19:03:22.027  2033  2881 I GBoardtInterface: onReloaded()
,08-26 19:03:22.030  2033  2033 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-26 19:03:22.066  1034  2032 W libprocessgroup: failed to open /acct/uid_10072/pid_7824/cgroup.procs: No such file or directory
,08-26 19:03:22.069  3804  3819 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-26 19:03:22.070  1034  1576 I ActivityManager: Killing 7903:com.android.vending/u0a44 (adj 15): empty #17
08-26 19:03:22.094  1034  1466 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2437 sc=60 link=72 tx=58.5, 0.0, 0.0  rx=69.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-942780434] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 19:03:22.094  1034  1466 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2437 sc=60 link=72 tx=58.5, 0.0, 0.0  rx=69.5 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-942780434] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 19:03:22.094  1034  1466 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-26 19:03:22.103  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:03:22.109  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)

```
